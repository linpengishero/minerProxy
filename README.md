## Windows 直接下载运行 <a href="https://github.com/linpengishero/minerProxy/releases/download/minerproxy/minerProxy-windows.exe">Release</a></br>

---

### 查看运行情况
```bash
screen -r minerProxy-linux
```
### 退出查看运行情况 键盘键入
```
ctrl + a + d
```

---
## Linux手动安装
```bash
mkdir miner_proxy
cd miner_proxy
# x86服务器
wget https://github.com/linpengishero/minerProxy/releases/download/minerproxy/minerProxy-linux
chmod 777 minerProxy-linux
./minerProxy-linux
```

### 后台运行（注意后面的&）运行完再敲几下回车

```bash
nohup ./minerProxy-linux &
# 运行之后查看webtoken
tail -f nohup.out
```

### 后台运行时关闭

```bash
killall minerProxy-linux
```
### 后台运行时查看
```bash
tail -f nohup.out
```
## 重要说明

```bigquery
软件如果您开启了抽水则为0.5%的开发者费用,如果您不开启抽水,则没有开发者费用
