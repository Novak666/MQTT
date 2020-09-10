# MQTT
基于MQTT协议的手套机远程信息管理系统（简介）

若干个提花手套机控制器、手套信息节点、无线收发通讯模块、手套机云平台和信
息访问终端；云平台包括MQTT代理服务器、后台管理和数据库；无线收发通讯模块
和信息访问终端通过MQTT协议连接手套机云平台，手套机云平台起到了数据中转和
云存储的作用；系统基于MQTT协议发布-订阅的模式，实现了生产数据从提花手套机
控制器上传至手套机云平台，进一步推送到信息访问终端；实现了控制指令从信息
访问终端推送到手套机云平台，进一步下发到手套信息节点，下发到提花手套机控
制器；实现了信息访问终端向手套机云平台查询任意历史数据；本系统是物联网技
术在工业领域的典型信息化应用，数据稳定可靠，满足企业日常管理的需要，提高
企业管理效率。


#系统框架图
<img src="https://github.com/Novak666/MQTT/blob/master/images/%E7%B3%BB%E7%BB%9F%E6%A1%86%E6%9E%B6%E5%9B%BE.jpg" width = "500" height = "" alt="" align=center />


#发布订阅模型
<img src="https://github.com/Novak666/MQTT/blob/master/images/%E5%8F%91%E5%B8%83%E8%AE%A2%E9%98%85%E6%A8%A1%E5%9E%8B.jpg" width = "250" height = "" alt="" align=center />


#连接EMQ
<img src="https://github.com/Novak666/MQTT/blob/master/images/%E8%BF%9E%E6%8E%A5EMQ.jpg" width = "250"/>


#APP功能展示图
<img src="https://github.com/Novak666/MQTT/blob/master/images/APP%E5%8A%9F%E8%83%BD%E5%B1%95%E7%A4%BA%E5%9B%BE.jpg" width = "250"/>


APP展示
#APP主界面
<img src="https://github.com/Novak666/MQTT/blob/master/images/APP%E4%B8%BB%E7%95%8C%E9%9D%A2.jpg" width = "250" height = "" alt="" align=center />


#翻页视图
<img src="https://github.com/Novak666/MQTT/blob/master/images/%E7%BF%BB%E9%A1%B5%E8%A7%86%E5%9B%BE.jpg" width = "250" height = "" alt="" align=center />


#查询(表格显示)
<img src="https://github.com/Novak666/MQTT/blob/master/images/%E6%9F%A5%E8%AF%A2(%E8%A1%A8%E6%A0%BC%E6%98%BE%E7%A4%BA).jpg" width = "250" height = "" alt="" align=center />


#查询(图形显示)
<img src="https://github.com/Novak666/MQTT/blob/master/images/%E6%9F%A5%E8%AF%A2(%E5%9B%BE%E5%BD%A2%E6%98%BE%E7%A4%BA).jpg" width = "250" height = "" alt="" align=center />

