## 简介
腾讯云物联网提供了专用的腾讯云IoT AT指令集([wifi版](https://main.qcloudimg.com/raw/550b58dc11a5a04e3957fa1357ee92b5.pdf)、[蜂窝版](https://main.qcloudimg.com/raw/eca29b5f1684b0127b2c294c466959da.pdf))，如果通讯模组实现了该指令集，则设备接入和通讯更为简单，所需代码量更少，针对这种场景，请参考面向腾讯云定制AT模组专用的 [MCU AT SDK](https://github.com/tencentyun/qcloud-iot-sdk-tencent-at-based.git)

目前腾讯云和主流的模组厂商进行了深度合作，将SDK的核心协议已移植到模组中，模组对外封装统一的腾讯云AT指令。已支持腾讯云定制AT指令的模组列表如下：

| 序号  | 模组商     |   模组型号       |  通信制式      | 
| -------| ------------| -------------------|------------------|
| 1	    | 乐鑫               | ESP8266            |    WIFI         | 
| 2	    | 中移        |  M5310-A	        |      NB-IoT    | 
| 3	    | 中移        |   M5311          |      NB-IoT    | 
| 4	    | 中移        |   M6315         |          2G    |  
| 5	   | 中移         |   M8321          |         4G     |  
| 6	   | 中移         |   ML302          |         LTE Cat.1     |  
| 7	    | 有方               | N10              |     2G         | 
| 8	    | 有方               | N21                |    NB-IoT      | 
| 9	    | 有方               | N58                |    NB-IoT      | 
| 10    | 有方               | N720            |    4G         | 
| 11    | 移柯               | L206D            |    2G         |
| 12    | 移柯               | L501C            |    LTE Cat.1         |
| 13    | 移柯               | L620C            |    NB-IoT         |
| 14    | 广和通               | L610            |  LTE Cat.1         |
| 15    | 广和通               | ME3616            |  NB-IoT        |
