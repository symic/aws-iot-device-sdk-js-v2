# aws-iot-device-sdk-js-v2
This project is developed using Tuya SDK, which enables you to quickly develop branded apps connecting and controlling smart scenarios of many devices.For more information, please check Tuya Developer Website.

## 一、方案标题
* 宠物喂食提醒器

## 二、方案应用

#### 场景地点：
*  家中任何地方，或是宠物的小窝改造。
 
#### 功能：
* 实现基于涂鸦云的宠物喂食提醒器，具备语音控制功能、电机驱动功能、数据上云功能及通过APP控制功能。
* 基于stm32开发板结合涂鸦的sdk开发，包括状态指示灯（LED灯）显示、温湿度传感器、红外传感器、OLED显示屏、WIFI串口通信模块、小电机控制等功能实现。
* 通过语音控制单元（如果有的话），识别不同固定语句，来控制开发板模块
* 通过WIFI串口通信模块，实现数据与涂鸦云平台的通信，实现对喂食仓余量、水量，温湿度等状态的上传。
* 通过涂鸦APP实现简易的宠物喂食提醒器状态监控，及喂食加水等控制功能。

#### 预期收获：
* 学会涂鸦云平台的操作，初步掌握基于涂鸦云的配置和数据上传下载
* 复习基于STM32的开发，相关模块的驱动开发，同时熟悉涂鸦云的SDK架构
* 学会WIFI串口通信模块的串口AT命令，及开发流程，并实现数据传输
* 熟悉涂鸦APP的开发过程，并下载到手机里进行测试。

## 三、开发计划
* 3月31前完成.
* 1）3月8日前熟悉资料，申请相关账号并熟悉平台。
* 2）3月9-20日跟着视频教程学习嵌入式开发、MCUSDK移植及云开发
* 3）3月21-31日整体调试，有必要的条件下自制PCB扩展板，并提交结果。
