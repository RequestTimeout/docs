> [!IMPORTANT]
> Some repositories are excluded from this list

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
diff --git a/scripts/diff.py b/scripts/diff.py
index 0354589..335cb9b 100644
--- a/scripts/diff.py
+++ b/scripts/diff.py
@@ -35,6 +35,8 @@
         name = repo["name"]
         branch = repo["default_branch"]
 
+        if name in ["docs"]:
+            continue
         print(f"Fetching diff for repo: {name}...")
         diff_response = requests.get(
             f"https://api.github.com/repos/RequestTimeout/{name}/commits/{branch}",
@@ -52,8 +54,6 @@
         if not diff:
             continue
 
-        if name in ["docs"]:
-            continue
         print(f"Adding repo {name} to output...")
         output += f"# {name}\n```diff\n{diff}\n```\n"
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
diff --git a/services/index.html b/services/index.html
index 9a7f5e6..212a2c8 100644
--- a/services/index.html
+++ b/services/index.html
@@ -8,10 +8,6 @@
     name="description"
     content="RequestTimeout Services — developer services, APIs, and useful things made by RequestTimeout."
 >
-  <link rel="icon" href="/assets/images/icon%2032x32.svg" sizes="32x32">
-  <link rel="icon" href="/assets/images/icon%20512x512.svg" sizes="512x512">
-  <link rel="apple-touch-icon" href="/assets/images/icon%20512x512.svg">
-
   <style>
     :root {
       --bg: #0b0d11;
```
