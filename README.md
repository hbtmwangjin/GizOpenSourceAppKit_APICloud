# 机智云开源框架App工程
==================

    使用机智云开源APP之前，需要先在机智云开发平台创建您自己的产品和应用。

    开源APP需要使用您申请的AppId、AppSecret以及您自己的产品ProductKey才能正常运行。

    具体申请流程请参见：http://docs.gizwits.com/hc/

    开源框架工程可通过修改配置文件配置开发者的个人应用信息，请参考使用说明中的 第5节 配置文件说明 进行替换。

    使用QQ、微信登录或百度或极光推送功能之前，需要您先到相应网站申请对应的应用信息，在配置文件中作相应的替换。


# GizWifiSDK 版本号

    1.3.1_2.06.06.1


# 功能介绍

    本文档为机智云物联网开源基础App套件使用说明，旨在为机智云物联网开发者提供一个快速开发模板，可在此工程基础上进行快速开发或参考相关代码进行开发。

# 使用说明

    在widget目录下找到并修改config.xml文件：

    这里需要填写在APICloud控制台创建应用时得到的id：
    
    <widget id="***" version="0.0.1">
    
    这里要填写自己应用的包名：
    
    <name>***</name>
    
    ……
    
    这里填写的是在qq开发者网站申请到的信息：
    
     <feature name="qq"> 
    
        <param name="urlScheme" value="***"/>  
    
        <param name="apiKey" value="***"/> 
    
    </feature>


# GoKit硬件依赖

    需要有调试设备的支持，您可以使用虚拟设备或者实体设备搭建调试环境。

    ▪	虚拟设备
        机智云官网提供GoKit虚拟设备的支持，链接地址：
        http://site.gizwits.com/developer/product/631/virtualdevice

    ▪	实体设备
        GoKit开发板。您可以在机智云官方网站上免费预约申请（限量10000台），申请地址：
        http://gizwits.com/zh-cn/gokit

    GoKit开发板提供MCU开源代码供智能硬件设计者参考，请去此处下载：https://github.com/gizwits/gokit-mcu


# 问题反馈

    您可以给机智云的技术支持人员发送邮件，反馈您在使用过程中遇到的任何问题。
    邮箱：club@gizwits.com

    
