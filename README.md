# wessh
# 环境
linux(python2.7) windows(无) mac(无)

# 需要安装的依赖库
pip install tornado ; pip install paramiko;

# 如何使用
python ws_app.py
默认8011端口，vi ws_app.py以修改

浏览器访问http://ws_app服务器地址:端口号?h=192.168.113.128&p=22&u=root&passwd=admin

各参数说明：

h：要访问的服务器ip

p：要访问的服务器端口

u：以什么身份登录

passwd：登录密码

或者以iframe形式嵌入到应用中
