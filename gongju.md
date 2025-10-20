# 独角鲸哪吒探针安装

```
cd /opt/nezha/agent
```

```
apk add tmux
```

```
tmux
```

```
./nezha-agent -c /opt/nezha/agent/config.yml
```

文章URL：https://blog.1314047.xyz/example-049

#  Debian 系统搭建 Hysteria2 (hy2) 节点

```
wget -N --no-check-certificate https://raw.githubusercontent.com/flame1ce/hysteria2-install/main/hysteria2-install-main/hy2/hysteria.sh && bash hysteria.sh
```

# Alpine 系统搭建 Hysteria2 (hy2) 节点

```
apk update && apk upgrade
```

```
wget -O hy2.sh https://raw.githubusercontent.com/zrlhk/alpine-hysteria2/main/hy2.sh  && sh hy2.sh
```

# IP 被墙时搭建 VMESS/VLESS 节点

```
curl -fsSL https://raw.githubusercontent.com/eooce/ssh_tool/main/ssh_tool.sh -o ssh_tool.sh && chmod +x ssh_tool.sh && ./ssh_tool.sh
```

文章URL：https://blog.1314047.xyz/example-042