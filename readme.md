## Golang程序中的版本信息管理

```
# 构建测试
$ make default
build the version
build done.

$ ./build/version.mac
Version(hard code): 0.1

$ ./build/version.mac version
Version: 0.0.1
GitBranch: master
CommitId: c1702a8
Build Date: 2020-06-27T13:32:42+0800
Go Version: go1.14
OS/Arch: darwin/amd64
```
