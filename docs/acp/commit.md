---
title: Creating a commit
---

Once we've added enough files to our changelist, we can solidify it and make a commit.
Commits need a "commit message", which is a short sentence describing our commit.

```
git commit -m "My first commit!
```
And Git will confirm it, giving us a commit ID and a quick overview of what changed:
```
[master (root-commit) 821a2a2] My first commit
 1 file changed, 1 insertion(+)
 create mode 100644 hello.txt
```

If we type `git show`, Git will show us a overview of our commit chain:
```
git show
```
```
commit 821a2a284b5c1bd23eafdae39a2b25d5f206cbc1 (HEAD -> master)
Author: Jackson C. Rakena <hello@jacksonrakena.com>
Date:   Fri May 7 11:55:53 2021 +1200

    My first commit

diff --git a/hello.txt b/hello.txt
new file mode 100644
index 0000000..666a5fb
--- /dev/null
+++ b/hello.txt
@@ -0,0 +1 @@
+🕋🕋🕋🕋🕋🕋🕋🕋🕋🕋🕋🕋🕋🕋🕋🕋🕋🕋🕋🕋🕋🕋🕋🕋🕋🕋🕋🕋🕋🕋🕋🕋🕋🕋🕋🕋🕋🕋🕋
🕋🕋🕋🕋🕋🕋🕋
```
