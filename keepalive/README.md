## Usage

##互相保活

```bash
dev.nix 第 16 行
services.docker.enable = true;
```


##安装保活脚本

```bash
curl -sSL https://raw.githubusercontent.com/whggo/idx-free/refs/heads/main/keepalive/install.sh | sh
```

##修改 app.js 环境变量
app.js 第 4-11 行


##设置开机自启

```
idx = "/home/user/WORKSPACE_NAME/app/idx-keepalive/startup.sh";
```
