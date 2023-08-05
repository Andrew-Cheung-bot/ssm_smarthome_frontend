> 这是后台管理系统前端页面，后台项目在[ssm_smarthome](https://github.com/Andrew-Cheung-bot/ssm_smarthome)
# 智能家具系统 Smart Home
![](https://img.shields.io/badge/JDK-JDK1.8-brightgreen) 
![](https://img.shields.io/badge/Spring-v4.3.2-brightgreen)
![](https://img.shields.io/badge/Maven-v3.6.1-brightgreen)
![](https://img.shields.io/badge/MySql-v5.1.47-blue)
![](https://img.shields.io/badge/Tomcat-v7.0.103-blue)
![](https://img.shields.io/badge/Author-Andrew%20Cheung-lightgrey)

# Introduction
- 本项目根据数据采集、数据传输、数据处理以及数据应用四个方面
- 硬件端采用较为成熟，具有固件库编程较为便利的嵌入式微处理器STM32F103，而硬件通信采用了ESP8266（一款串口转无线模芯片，内部自带固件，用户操作简单，无需编写时序信号等）；云服务器采用腾讯云（后续有可能会迁移到AWS云），有较好的服务设置。
- 前端由网页端（使用Bootstrap框架构建界面，使用AJAX与后台数据交互）与微信小程序开发组成
- 后端基于SSM框架开发（SpringMVC+Spring+Mybatis），数据格式使用json

# 项目技术结构
- maven
- Spring（使用aop和声名式事务处理）
- SpringMVC
- Mybatis
- SpringSecurity校验权限
- Bootstrap，chartjs开发前端页面
- WebSocket与硬件端实时通信
