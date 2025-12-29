English | [中文](./README.md)

Drone AI Intelligent Inspection System
===============

Current version: 1.3.31 (Release date: 2025-12-01)


Project Overview
-----------------------------------

<h3 align="center">Drone AI Intelligent Inspection System</h3>


The drone AI inspection suite includes three systems: (1) inspection (with mini-program support), (2) AI algorithm training platform, and (3) flight-control middleware.

Through real-time monitoring and intelligent scheduling, low-altitude safety stays rock solid. Meter-level precise positioning makes every flight path visible, with battery, speed, and other states under live control. Compatible with major models from DJI, Autel, and Black Shark.

DeepSeek on-prem models can be integrated. The AI inspection system automatically detects unauthorized flights and intrusions into no-fly zones, issuing instant alerts to keep flights safe.

![Drone parameter tuning](images/无人机参数调试.png "无人机参数调试")

Use Cases
-----------------------------------
        
#### One Platform

1. Planning: Easily mark power lines and highways for inspection on the map.  
2. Dispatch: Centrally manage hundreds of automated tasks—pipeline patrols with zero manual effort.  
3. Management: All alerts and flight data are centralized with auto-generated reports.
        
#### Common Capabilities

1. Environmental protection: Efficient sewage-outlet patrol and automatic monitoring.  
2. Security: Routine detection of blocked fire exits to remove hazards.  
3. Energy: Regular PV hot-spot checks to protect revenue.  
4. Emergency: Rapid flood and disaster site assessment.

#### Two Core Strengths

1. Automated inspection: No pilot needed. With one click, set routes for PV plant or grid inspections; drones execute on schedule, on standby 24/7.  
        
2. AI detection: More accurate than the human eye. Automatically identifies river pollution, forest fire points, construction safety violations, and more, then alerts immediately to close the loop,supports human-vehicle tracking and recognition, long-distance zoom processing, etc.
        
#### Four Key Values

✅ Efficiency boost: 5× faster than manual inspection with sharply lower costs.  

✅ Safe and worry-free: Keeps people out of hazardous areas.  

✅ Accurate and reliable: AI works 24/7 with over 98% recognition accuracy.  

✅ Multi-purpose: A new route means a new scenario—high ROI.


Solutions
-----------------------------------

In cities, it helps drones avoid air traffic, capture traffic conditions, and assist with guidance. In emergencies, it dispatches drones rapidly for coordinated rescue. In rural areas, it optimizes logistics routes to solve the last-mile delivery challenge. It addresses the long-standing pain points of manual inspection in power, rivers, and forestry—low efficiency, high risk, scattered data—such as tower climbs for high-voltage lines, blind spots in mountainous forests, and pipeline leak checks.

- Intelligent road inspection with the drone inspection system: [无人机巡检系统之智能道路巡检](https://blog.csdn.net/xiaoyuner1349/article/details/156274306?spm=1001.2014.3001.5501) 


Technical Architecture
-----------------------------------

#### Smart Inspection Platform & Flight Control Center

- Backend source code (SpringBoot 2.7.2 + MySQL 8)
- Web source code (Vue3 + ElementUI)
- Mini-program source code (Uniapp)

#### Video AI Algorithm Platform

- Backend source code (SpringBoot 2.7.2 + MySQL 8)
- Web source code (Vue3 + ElementUI)

### System UI (partial)

Flight-control platform  
![Flight-control platform](images/飞控平台.png "飞控平台")

Automated inspection task configuration  
![Automated inspection task configuration](images/自动化巡任务检配置.png "自动化巡任务检配置")

Live flight video  
![Live flight video](images/飞控平台.png "飞控平台")

Multi-project scene management  
![Multi-project scene management](images/多项目场景管理.png "多项目场景管理")

Waypoint behavior configuration  
![Waypoint behavior configuration](images/航点行为配置.png "航点行为配置")

No-fly zone setup  
![No-fly zone setup](images/设置禁飞区.png "设置禁飞区")

Video algorithm labeling and alerts  
![Video algorithm labeling and alerts](images/视频算法标注处理与预警.png "视频算法标注处理与预警")

Algorithm model configuration  
![Algorithm model configuration](images/算法模型配置.png "算法模型配置")

Drone parameter tuning  
![Drone parameter tuning](images/无人机参数调试.png "无人机参数调试")

Image algorithm comparison and alerts  
![Image algorithm comparison and alerts](images/图片算法比对与预警.png "图片算法比对与预警")

Airport management  
![Airport management](images/机场管理.png "机场管理")

### Contact Us

##### Wechat:
For business cooperation or commercial code, scan to connect on WeChat:

![](images/wechat.jpg)

##### Email: xingyue131@2925.com