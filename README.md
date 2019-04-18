
V免签  —— 个人开发者收款解决方案
===============



V免签(PHP) 是基于Thinkphp5.1 + mysql 实现的一套免签支付程序，主要包含以下特色：

 + 提供示例代码简单接入
 + 超简单Api使用，提供统一Api实现收款回调
 + 免费、开源

> V免签的运行环境为PHP版本>=5.6。

> V免签仅供个人开发者调试测试使用，请勿用于非法用途，商用请您申请官方商户接口

> v免签开发交流群：992029073

> bug反馈请建立issues


## 前言


V免签为完全开源项目，开源项目意味着作者没有任何收入来源，仅凭个人空闲时间开发，如果您有经济条件，您可以赞助本项目的开发（下方收款码），如果您不想赞助，也请您点击上面的Star给一个星星，也是对我莫大的认同，感谢各位的支持。

![微信赞助](wx.jpg)![支付宝赞助](zfb.jpg)


## 安装
 + 推荐使用宝塔面板安装，以下教程为宝塔面板安装教程，其他环境请参考自行配置

    1、下载源代码,位于GitHub的releases中
    
    2、宝塔面板中新建网站，设置：
        
        + 网站目录->运行目录 设置为public并保存
        + 伪静态 设置为thinkphp并保存
        + 默认文档 设置将index.html放在第一行并保存
    
    3、打开网站目录 config/database.php ，设置好您的mysql账号密码。
    
    4、导入数据库文件（位于根目录）vmq.sql到您的数据库。
    
    5、至此网站搭建完毕，请访问后自行修改配置信息！默认后台账号和密码均为admin


 > 升级说明：请您直接下载新版本覆盖旧版本即可！
 
 
## 调用

 + 请部署完成后访问后台，有详细的Api说明
 
 
## 注意

  + 本系统原理为监控收款后手机的通知栏推送消息，所以请保持微信/支付宝/V免签监控端后台正常运行，且添加到内存清理白名单！
     
## 更新记录
   

 + v1.1（2019.04.18） 
   + 打包thinkphp框架上传
 + v1.0（2019.04.18） 
   + PHP初版发布

## 版本预告

+ 下个版本将针对监控端Apk优化，重点尝试解决当前的版本的不兼容和不稳定问题。
+ 待v免签测试稳定后，将会着手开发对接v免签的发卡平台，也是开源免费，敬请期待！

## 版权信息

V免签遵循 MIT License 开源协议发布，并提供免费使用，请勿用于非法用途。


版权所有Copyright © 2019 by vone (http://szvone.cn)

All rights reserved。

