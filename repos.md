# modID
```diff
diff --git a/LICENSE.md b/LICENSE.md
index d2fe92c..857a8ac 100644
--- a/LICENSE.md
+++ b/LICENSE.md
@@ -1,6 +1,6 @@
 # All Rights Reserved
 
-Copyright (c) 2026 [Request Timeout](https://github.com/RequestTimeout)
+Copyright (c) YEAR [Request Timeout](https://github.com/RequestTimeout)
 
 All rights reserved.
```
# .github
```diff
diff --git a/scripts/repo_count.py b/scripts/repo_count.py
index 1294a5e..fd47ea9 100644
--- a/scripts/repo_count.py
+++ b/scripts/repo_count.py
@@ -7,7 +7,7 @@
     "Accept": "application/vnd.github+json",
     "X-GitHub-Api-Version": "2022-11-28",
 }
-public, public = 0, 0
+public, private = 0, 0
 page = 1
 
 while True:
```
# localS
```diff
diff --git a/LICENSE.md b/LICENSE.md
index d2fe92c..857a8ac 100644
--- a/LICENSE.md
+++ b/LICENSE.md
@@ -1,6 +1,6 @@
 # All Rights Reserved
 
-Copyright (c) 2026 [Request Timeout](https://github.com/RequestTimeout)
+Copyright (c) YEAR [Request Timeout](https://github.com/RequestTimeout)
 
 All rights reserved.
```
# CurlS
```diff
diff --git a/HowTo.md b/HowTo.md
index 27cd68d..415ce8c 100644
--- a/HowTo.md
+++ b/HowTo.md
@@ -5,8 +5,7 @@
 > Some Features Might Not Work On MacOS or Linux.
 
 ### Installation
-Click here to [download CurlS.py](https://raw.githubusercontent.com/RequestTimeout/CurlS/main/src/CurlS.py), OR go to /RequestTimeout/CurlS/src/CurlS.py
-and download the file.
+Go to /RequestTimeout/CurlS/src/CurlS.py and download the file.
 
 ---
 Then drop the .py file somewhere accessible, like:
```
# RandG
```diff
diff --git a/LICENSE.md b/LICENSE.md
index d2fe92c..857a8ac 100644
--- a/LICENSE.md
+++ b/LICENSE.md
@@ -1,6 +1,6 @@
 # All Rights Reserved
 
-Copyright (c) 2026 [Request Timeout](https://github.com/RequestTimeout)
+Copyright (c) YEAR [Request Timeout](https://github.com/RequestTimeout)
 
 All rights reserved.
```
# Jsonify
```diff
diff --git a/LICENSE.md b/LICENSE.md
index d2fe92c..857a8ac 100644
--- a/LICENSE.md
+++ b/LICENSE.md
@@ -1,6 +1,6 @@
 # All Rights Reserved
 
-Copyright (c) 2026 [Request Timeout](https://github.com/RequestTimeout)
+Copyright (c) YEAR [Request Timeout](https://github.com/RequestTimeout)
 
 All rights reserved.
```
# FibF
```diff
diff --git a/LICENSE.md b/LICENSE.md
index d2fe92c..857a8ac 100644
--- a/LICENSE.md
+++ b/LICENSE.md
@@ -1,6 +1,6 @@
 # All Rights Reserved
 
-Copyright (c) 2026 [Request Timeout](https://github.com/RequestTimeout)
+Copyright (c) YEAR [Request Timeout](https://github.com/RequestTimeout)
 
 All rights reserved.
```
# RegexIt
```diff
diff --git a/LICENSE.md b/LICENSE.md
index d2fe92c..857a8ac 100644
--- a/LICENSE.md
+++ b/LICENSE.md
@@ -1,6 +1,6 @@
 # All Rights Reserved
 
-Copyright (c) 2026 [Request Timeout](https://github.com/RequestTimeout)
+Copyright (c) YEAR [Request Timeout](https://github.com/RequestTimeout)
 
 All rights reserved.
```
# Refs
```diff
diff --git a/LICENSE.md b/LICENSE.md
index d2fe92c..857a8ac 100644
--- a/LICENSE.md
+++ b/LICENSE.md
@@ -1,6 +1,6 @@
 # All Rights Reserved
 
-Copyright (c) 2026 [Request Timeout](https://github.com/RequestTimeout)
+Copyright (c) YEAR [Request Timeout](https://github.com/RequestTimeout)
 
 All rights reserved.
```
# RElog
```diff
diff --git a/LICENSE.md b/LICENSE.md
index d2fe92c..857a8ac 100644
--- a/LICENSE.md
+++ b/LICENSE.md
@@ -1,6 +1,6 @@
 # All Rights Reserved
 
-Copyright (c) 2026 [Request Timeout](https://github.com/RequestTimeout)
+Copyright (c) YEAR [Request Timeout](https://github.com/RequestTimeout)
 
 All rights reserved.
```
# requesttimeout.github.io
```diff
diff --git a/LICENSE.md b/LICENSE.md
index d2fe92c..857a8ac 100644
--- a/LICENSE.md
+++ b/LICENSE.md
@@ -1,6 +1,6 @@
 # All Rights Reserved
 
-Copyright (c) 2026 [Request Timeout](https://github.com/RequestTimeout)
+Copyright (c) YEAR [Request Timeout](https://github.com/RequestTimeout)
 
 All rights reserved.
```
# docs
```diff
diff --git a/repos.md b/repos.md
index 32d2b60..cd59e87 100644
--- a/repos.md
+++ b/repos.md
@@ -14,19 +14,19 @@ index d2fe92c..857a8ac 100644
 ```
 # .github
 ```diff
-diff --git a/.github/workflows/action.yml b/.github/workflows/action.yml
-index c853676..ee71c7a 100644
---- a/.github/workflows/action.yml
-+++ b/.github/workflows/action.yml
-@@ -26,5 +26,8 @@ jobs:
-           ADMIN_PAT: ${{ secrets.ADMIN_PAT }}
-         run: |
-           python scripts/check_repo.py
-+          echo "$(printf '=%.0s' {1..100})"
-           python scripts/repo_count.py
-+          echo "$(printf '=%.0s' {1..100})"
-           python scripts/diff.py
-+          echo "$(printf '=%.0s' {1..100})"
+diff --git a/scripts/repo_count.py b/scripts/repo_count.py
+index 1294a5e..fd47ea9 100644
+--- a/scripts/repo_count.py
++++ b/scripts/repo_count.py
+@@ -7,7 +7,7 @@
+     "Accept": "application/vnd.github+json",
+     "X-GitHub-Api-Version": "2022-11-28",
+ }
+-public, public = 0, 0
++public, private = 0, 0
+ page = 1
+ 
+ while True:
 ```
 # localS
 ```diff
@@ -173,15 +173,197 @@ index d2fe92c..857a8ac 100644
 ```
 # docs
 ```diff
-diff --git a/How our APIs work/README.md b/How our APIs work/README.md
-index b19448e..642d169 100644
---- a/How our APIs work/README.md	
-+++ b/How our APIs work/README.md	
-@@ -62,5 +62,5 @@ flowchart LR
- ```
- 
- [^1]: These APIs use a serverless architecture.
--[^2]: Incoming requests are routed to the API code hosted by Cloudflare, which generates the and returns the response.
-+[^2]: Incoming requests are routed to the API code hosted by Cloudflare, which generates and returns the response.
- [^3]: These are not all possible response codes. This list may be expanded in the future.
+diff --git a/repos.md b/repos.md
+new file mode 100644
+index 0000000..32d2b60
+--- /dev/null
++++ b/repos.md
+@@ -0,0 +1,187 @@
++# modID
++```diff
++diff --git a/LICENSE.md b/LICENSE.md
++index d2fe92c..857a8ac 100644
++--- a/LICENSE.md
+++++ b/LICENSE.md
++@@ -1,6 +1,6 @@
++ # All Rights Reserved
++ 
++-Copyright (c) 2026 [Request Timeout](https://github.com/RequestTimeout)
+++Copyright (c) YEAR [Request Timeout](https://github.com/RequestTimeout)
++ 
++ All rights reserved.
++```
++# .github
++```diff
++diff --git a/.github/workflows/action.yml b/.github/workflows/action.yml
++index c853676..ee71c7a 100644
++--- a/.github/workflows/action.yml
+++++ b/.github/workflows/action.yml
++@@ -26,5 +26,8 @@ jobs:
++           ADMIN_PAT: ${{ secrets.ADMIN_PAT }}
++         run: |
++           python scripts/check_repo.py
+++          echo "$(printf '=%.0s' {1..100})"
++           python scripts/repo_count.py
+++          echo "$(printf '=%.0s' {1..100})"
++           python scripts/diff.py
+++          echo "$(printf '=%.0s' {1..100})"
++```
++# localS
++```diff
++diff --git a/LICENSE.md b/LICENSE.md
++index d2fe92c..857a8ac 100644
++--- a/LICENSE.md
+++++ b/LICENSE.md
++@@ -1,6 +1,6 @@
++ # All Rights Reserved
++ 
++-Copyright (c) 2026 [Request Timeout](https://github.com/RequestTimeout)
+++Copyright (c) YEAR [Request Timeout](https://github.com/RequestTimeout)
++ 
++ All rights reserved.
++```
++# CurlS
++```diff
++diff --git a/HowTo.md b/HowTo.md
++index 27cd68d..415ce8c 100644
++--- a/HowTo.md
+++++ b/HowTo.md
++@@ -5,8 +5,7 @@
++ > Some Features Might Not Work On MacOS or Linux.
++ 
++ ### Installation
++-Click here to [download CurlS.py](https://raw.githubusercontent.com/RequestTimeout/CurlS/main/src/CurlS.py), OR go to /RequestTimeout/CurlS/src/CurlS.py
++-and download the file.
+++Go to /RequestTimeout/CurlS/src/CurlS.py and download the file.
++ 
++ ---
++ Then drop the .py file somewhere accessible, like:
++```
++# RandG
++```diff
++diff --git a/LICENSE.md b/LICENSE.md
++index d2fe92c..857a8ac 100644
++--- a/LICENSE.md
+++++ b/LICENSE.md
++@@ -1,6 +1,6 @@
++ # All Rights Reserved
++ 
++-Copyright (c) 2026 [Request Timeout](https://github.com/RequestTimeout)
+++Copyright (c) YEAR [Request Timeout](https://github.com/RequestTimeout)
++ 
++ All rights reserved.
++```
++# Jsonify
++```diff
++diff --git a/LICENSE.md b/LICENSE.md
++index d2fe92c..857a8ac 100644
++--- a/LICENSE.md
+++++ b/LICENSE.md
++@@ -1,6 +1,6 @@
++ # All Rights Reserved
++ 
++-Copyright (c) 2026 [Request Timeout](https://github.com/RequestTimeout)
+++Copyright (c) YEAR [Request Timeout](https://github.com/RequestTimeout)
++ 
++ All rights reserved.
++```
++# FibF
++```diff
++diff --git a/LICENSE.md b/LICENSE.md
++index d2fe92c..857a8ac 100644
++--- a/LICENSE.md
+++++ b/LICENSE.md
++@@ -1,6 +1,6 @@
++ # All Rights Reserved
++ 
++-Copyright (c) 2026 [Request Timeout](https://github.com/RequestTimeout)
+++Copyright (c) YEAR [Request Timeout](https://github.com/RequestTimeout)
++ 
++ All rights reserved.
++```
++# RegexIt
++```diff
++diff --git a/LICENSE.md b/LICENSE.md
++index d2fe92c..857a8ac 100644
++--- a/LICENSE.md
+++++ b/LICENSE.md
++@@ -1,6 +1,6 @@
++ # All Rights Reserved
++ 
++-Copyright (c) 2026 [Request Timeout](https://github.com/RequestTimeout)
+++Copyright (c) YEAR [Request Timeout](https://github.com/RequestTimeout)
++ 
++ All rights reserved.
++```
++# Refs
++```diff
++diff --git a/LICENSE.md b/LICENSE.md
++index d2fe92c..857a8ac 100644
++--- a/LICENSE.md
+++++ b/LICENSE.md
++@@ -1,6 +1,6 @@
++ # All Rights Reserved
++ 
++-Copyright (c) 2026 [Request Timeout](https://github.com/RequestTimeout)
+++Copyright (c) YEAR [Request Timeout](https://github.com/RequestTimeout)
++ 
++ All rights reserved.
++```
++# RElog
++```diff
++diff --git a/LICENSE.md b/LICENSE.md
++index d2fe92c..857a8ac 100644
++--- a/LICENSE.md
+++++ b/LICENSE.md
++@@ -1,6 +1,6 @@
++ # All Rights Reserved
++ 
++-Copyright (c) 2026 [Request Timeout](https://github.com/RequestTimeout)
+++Copyright (c) YEAR [Request Timeout](https://github.com/RequestTimeout)
++ 
++ All rights reserved.
++```
++# requesttimeout.github.io
++```diff
++diff --git a/LICENSE.md b/LICENSE.md
++index d2fe92c..857a8ac 100644
++--- a/LICENSE.md
+++++ b/LICENSE.md
++@@ -1,6 +1,6 @@
++ # All Rights Reserved
++ 
++-Copyright (c) 2026 [Request Timeout](https://github.com/RequestTimeout)
+++Copyright (c) YEAR [Request Timeout](https://github.com/RequestTimeout)
++ 
++ All rights reserved.
++```
++# hosting
++```diff
++diff --git a/LICENSE.md b/LICENSE.md
++index d2fe92c..857a8ac 100644
++--- a/LICENSE.md
+++++ b/LICENSE.md
++@@ -1,6 +1,6 @@
++ # All Rights Reserved
++ 
++-Copyright (c) 2026 [Request Timeout](https://github.com/RequestTimeout)
+++Copyright (c) YEAR [Request Timeout](https://github.com/RequestTimeout)
++ 
++ All rights reserved.
++```
++# docs
++```diff
++diff --git a/How our APIs work/README.md b/How our APIs work/README.md
++index b19448e..642d169 100644
++--- a/How our APIs work/README.md	
+++++ b/How our APIs work/README.md	
++@@ -62,5 +62,5 @@ flowchart LR
++ ```
++ 
++ [^1]: These APIs use a serverless architecture.
++-[^2]: Incoming requests are routed to the API code hosted by Cloudflare, which generates the and returns the response.
+++[^2]: Incoming requests are routed to the API code hosted by Cloudflare, which generates and returns the response.
++ [^3]: These are not all possible response codes. This list may be expanded in the future.
++```
 ```
```
