# **后台维护**

以下内容仅为其他相关人员提供参考信息。若遇到任何后台服务的技术问题，请联系服务提供商进行解决。

## 1.后台服务状态

智能监控平台的后台由多个不同的服务组成，在服务器重启后会自动启动。这些服务由supervisord监控，以保证不间断的运行。下面的这些命令可以对这些服务进行操作：

查看服务状态

```bash
$ supervisorctl status

$ supervisorctl status <服务名>
```

启动单个服务

```bash
$ supervisorctl start <服务名>
```

停止单个服务

```bash
$ supervisorctl stop <服务名>
```
