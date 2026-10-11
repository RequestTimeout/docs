# How our APIs work
## Base concept
**The base concept is:**
```mermaid
%%{init: {"theme": "base", "themeVariables": {
  "background": "#1f1f1f",
  "primaryColor": "#282828",
  "primaryTextColor": "#ffffff",
  "primaryBorderColor": "#00a315",
  "lineColor": "#a0a0a0",
  "secondaryColor": "#282828",
  "tertiaryColor": "#242424",
  "edgeLabelBackground": "#1f1f1f",
  "fontFamily": "JetBrains Mono, monospace",
  "fontSize": "14px"
}}}%%

flowchart LR
    A(["CLI App / Browser"]) -->|HTTP Request| B(["Cloudflare"])
    B -->|Forward| C(["API"])
    C -->|HTTP Response| B
    B -->|Return| A

    style A fill:#282828,stroke:#00a315,color:#ffffff,stroke-width:2px
    style B fill:#f38020,stroke:#ffb36b,color:#ffffff,stroke-width:3px
    style C fill:#282828,stroke:#00a315,color:#ffffff,stroke-width:2px

    linkStyle 0 stroke:#00d084,stroke-width:2px,color:#00d084
    linkStyle 1 stroke:#a0a0a0,stroke-width:2px,color:#ffffff
    linkStyle 2 stroke:#ffb36b,stroke-width:2px,color:#ffb36b
    linkStyle 3 stroke:#a0a0a0,stroke-width:2px,color:#ffffff
```
## Error handling
Common HTTP status codes returned by our APIs[^1]:

| Status | Meaning                                    |
|:------:|:-------------------------------------------|
|  200   | Request succeeded                          |
|  400   | Invalid request                            |
|  401   | Authentication required                    |
|  403   | Access denied                              |
|  404   | Not found                                  |
|  429   | Rate limited (for APIs needing protection) |
|  500   | Something went horribly wrong              |

```mermaid
flowchart LR
    A(["HTTP Request"]) --> B("Valid request?")
    B -->|Yes| C(["Process request"])
    B -->|No| D(["400 Bad Request"])
    C --> E("Success?")
    E -->|Yes| F(["Return response"])
    E -->|No| G(["Return error"])

    style A fill:#282828,stroke:#00a315,color:#fff
    style B fill:#282828,stroke:#f38020,color:#fff
    style C fill:#282828,stroke:#00a315,color:#fff
    style D fill:#9b2020,stroke:#ff5555,color:#fff
    style E fill:#282828,stroke:#f38020,color:#fff
    style F fill:#174d2b,stroke:#00d084,color:#fff
    style G fill:#9b2020,stroke:#ff5555,color:#fff
```

[^1]: These are not all possible response codes. This list may be expanded in the future.
