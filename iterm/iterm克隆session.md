# 配置ssh
`vi ~/.ssh/config` 输入如下内容
```sh
host *
ControlMaster auto
ControlPath ~/.ssh/master-%r@%h:%p
```
