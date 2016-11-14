
# VPN分享计划 
### 一键部署，和别人共享你的资源。  
> 很多人都有国外的vps，一个月1TB的流量是用不完的。如果你愿意，可以和他人分享你的资源。

## [完整项目](http://www.wantjr.com "我的网站")

### 设计思路

| 用户类型 | 更换频率 | 流量限制                                  |  速度限制            | 共享性质          |
|---------|----------|---------- -------------------------------| ---------------------| -----------------|
| 普通用户 | 24小时   |  5 GB/天/端口  * 2端口                   |   1MB/s/所有端口     | 多人共享一个端口  |
| 登录用户 | 7天      |  30 GB/周/端口  * 3端口                  |   1MB/s/所有端口     | 多人共享一个端口  |
| 捐助用户 | 30天     |  2GB/月/端口  * 5端口                    |   1MB/s/端口         | 一人独享一个端口  |

以上大约700GB每个月。 剩余300GB应该足够自己的使用。



#### 普通用户
> 采用24小时的更换频率，使他经常访问网站来获取新的帐号密码，从而增加网站的流量。

#### 登录用户
> 和普通用户一样,频率改变,用户体验会更好

#### 捐助用户
> 独享一个帐号和端口。因此采用了流量限制。虽然是限制2GB每月，但是大部分的用户都只会使用1GB左右。所以成本还是很低的。


### 可能存在的问题    
一旦用户进行大量的下载，会严重影响他人的体验。待思考一个方案来处理这个问题。

-----------
# 教程还未完成，尽快完成更新



## 教程
#### 需要预装的应用
- python2.7
- tornado1.1 及以上 
- shadowsocks
- MySQL
- crontab


用法 :
` sudo /bin/bash build.sh `




