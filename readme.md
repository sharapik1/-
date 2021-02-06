# Лабораторная работа
Первая команда: `git commit -m "initial project version"`
Вывела результат: 
```
[master (root-commit) 2b3b855] initial project version
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 readme.md
```

Вторая команда `git status`

```
On branch master
nothing to commit, working tree clean
```
Третья команда `git add README.` была использована для остлеживания файла README:
```
fatal: pathspec 'README' did not match any files
```
Четвертая команда `git status` 
``` 
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   readme.md
``` 
Пятая команда `git diff`
```
diff --git a/readme.md b/readme.md
index e69de29..1ccb449 100644
diff --git a/readme.md b/readme.md
index e69de29..1ccb449 100644
--- a/readme.md
+++ b/readme.md
@@ -0,0 +1,19 @@
+# Лабораторная работа
+Первая команда: `git commit -m "initial project version"`
+Вывела результат: 
+```
+[master (root-commit) 2b3b855] initial project version
+ 1 file changed, 0 insertions(+), 0 deletions(-)
+ create mode 100644 readme.md
+```
+
+Вторая команда `git status`
+
+```
+On branch master
+nothing to commit, working tree clean
+```
+Третья команда `git add README.` была использована для остлеживания файла README:
+fatal: pathspec 'README' did not match any files
+```
+Четвертая команда
\ No newline at end of file
(END)
``` 
