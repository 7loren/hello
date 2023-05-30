# hello
Go



```bash
➜  hello git:(main) ✗ go mod init github.com/7loren/hello

go: creating new go.mod: module github.com/7loren/hello
go: to add module requirements and sums:
        go mod tidy


➜  hello git:(main) ✗ go mod tidy


```


```bash
➜  hello git:(main) git add .
➜  hello git:(main) ✗ git commit -m "feat: SayHi现在支持给指定人打招呼啦"
[main d1b47ac] feat: SayHi现在支持给指定人打招呼啦
 2 files changed, 5 insertions(+), 3 deletions(-)
➜  hello git:(main) git push
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (4/4), 580 bytes | 580.00 KiB/s, done.
Total 4 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/7loren/hello.git
   5c787f2..d1b47ac  main -> main

➜  hello git:(main) git tag -a v2.0.0 -m "release version v2.0.0"

➜  hello git:(main) git push origin v2.0.0
Enumerating objects: 1, done.
Counting objects: 100% (1/1), done.
Writing objects: 100% (1/1), 167 bytes | 167.00 KiB/s, done.
Total 1 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/7loren/hello.git
 * [new tag]         v2.0.0 -> v2.0.0
```



```bash
go get github.com/7loren/hello/v2@v2.0.0
```