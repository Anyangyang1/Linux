# Linux网络篇
```
  arp -a                               # 查看arp高速缓存
  sudo arp -d IP地址                    # 删除arp缓存
  sudo arp -s IP地址   MAC地址          # 增加arp缓存

  sudo tcpdump                          # 抓取数据包

  route                                 # 查看路由表

  netstat -nat                          # 查看连接状态

  iptables -L INPUT --line-numbers      # 查看防火墙的所有规则
  iptables -D INPUT 规则号              # 删除某一条规则
```

