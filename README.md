# HASS-Blueprints/Home Assistant 常用的蓝图

所收录的蓝图部分来自论坛及github，并由我将部分内容汉化，部分由本人创建。由于HASS通过UI创建自动化的指引不是很清楚，而使用Yaml文件创建自动化流程对普通用户要求过高。蓝图的初衷就是降低HASS创建自动化的难度，为了更加清楚的使用我将蓝图中相关说明文字翻译成汉语，方便使用。

## 设置类-对HASS系统进行设置

- settingAutomatedDailySnapshot：根据指定时间每日创建快照  
- seetingAutomationState：当指定家庭成员到达指定区域后关闭指定的自动化  

## 通知类-向APP推送通知

- NotificationHASSUpdate：HASS有新版版本可以更新时推送通知  
- NotificationMotionPicture：检测到动作传感器前有物体移动时推送含有摄像头截图的通知  
- NotificationZoneLeave：家庭成员离开指定区域时推送通知  

## 动作类-完成设备操作动作

- actionBackHomeOpenLight：天黑回家后自动打开灯  
- actionMotionLight：指定区域检测到有人活动时自动打开对应的灯，指定时间后自动关闭  