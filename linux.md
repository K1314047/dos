## 独角鲸哪吒探针安装

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

##  Debian 系统搭建 Hysteria2 (hy2) 节点

```
wget -N --no-check-certificate https://raw.githubusercontent.com/flame1ce/hysteria2-install/main/hysteria2-install-main/hy2/hysteria.sh && bash hysteria.sh
```

## Alpine 系统搭建 Hysteria2 (hy2) 节点

```
apk update && apk upgrade
```

```
wget -O hy2.sh https://raw.githubusercontent.com/zrlhk/alpine-hysteria2/main/hy2.sh  && sh hy2.sh
```

## IP 被墙时搭建 VMESS/VLESS 节点

```
curl -fsSL https://raw.githubusercontent.com/eooce/ssh_tool/main/ssh_tool.sh -o ssh_tool.sh && chmod +x ssh_tool.sh && ./ssh_tool.sh
```

文章URL：https://blog.1314047.xyz/example-042

## 哪吒被监控删除代码

```
systemctl disable --now nezha-agent
rm -rf /opt/nezha/agent
```

文章URL：https://www.nodeseek.com/post-93761-1

## Alpine一键安装Reality/Hysteria2

```
 wget -O LiteBox https://raw.githubusercontent.com/lite-vm/LiteBox/main/LiteBox && chmod +x LiteBox && ./LiteBox 
```

## Alpine一键安装3x-ui 最新版

```
 wget -O 3xui https://raw.githubusercontent.com/lite-vm/Alpine-3xui/main/3xui && chmod +x 3xui && ./3xui 
```

## 如何检测服务器的ip质量?

#### IP质量体检脚本

##### 默认双栈检测：

```
bash <(curl -Ls https://IP.Check.Place)
```

 只检测IPv4结果：

```
bash <(curl -Ls https://IP.Check.Place) -4
```

 只检测IPv6结果：

```
bash <(curl -Ls https://IP.Check.Place) -6
```

## 一键自动生成四种协议脚本

**一键自动生成四种协议脚本** **不需要安装任何面板** **支持Alpine Linux系统**

（VLESS-reality-verison、VMess-ws-tls(tunnel)、Hysteria2、Tuic）默认解锁GPT和奈飞

内存低于256的不建议安装4协议脚本 可能会出现内存不足导致断开的情况.

```
bash <(curl -Ls https://raw.githubusercontent.com/eooce/sing-box/main/sing-box.sh)
```

