<div style="text-align: center;">
  <a href="https://github.com/OpenQGIS/OMap-GeoDB/blob/main/OMap-GeoDB.png" target="_blank">
    <img src="https://github.com/OpenQGIS/OMap-GeoDB/blob/main/OMap-GeoDB.png" style="width: 100%;" title="OMap-GeoDB">

# OMap-GeoDB
由 [**OpenQGIS**](https://github.com/OpenQGIS/OMap-GeoDB/blob/main/qrcode_OpenQGIS.jpg) 分享的源自 [OSM(OpenStreetMap)](https://www.openstreetmap.org/) 的 ***超常规** 地理数据库* 。

<div style="text-align: center;">
  <a href="https://github.com/OpenQGIS/OMap-GeoDB/blob/main/qrcode_OpenQGIS.jpg" target="_blank">
    <img src="https://github.com/OpenQGIS/OMap-GeoDB/blob/main/qrcode_OpenQGIS.jpg" style="width: 15%;" title="公众号二维码">

## 目录

一、 [🚆 铁路数据](#section1)

二、 [⚡ 电力数据](#section2)

三、 [🛫 机场跑道](#section3)

……

合、 [网盘地址](#section99)
  
----

## 一、🚆 铁路数据<a id="section1"></a>

铁路数据日期：2025.2.25

### 1. 铁路线位：oData-railway
> **分卷压缩**；下载是务必下载zip.001、zip.002，解压其中一个即可获取数据

#### 1. railway 数据解析

| 英语       | rail           | abandoned      | disused        | monorail       | subway         | razed          | construction   | funicular      | station        | light_rail     | tram           | traverser      | narrow_gauge   |
| ---------- | -------------- | -------------- | -------------- | -------------- | -------------- | -------------- | -------------- | -------------- | -------------- | -------------- | -------------- | -------------- | -------------- |
| 中文       | 铁路           | 废弃铁路        | 停用铁路        | 单轨铁路         | 地铁          | 已拆除铁路 | 施工铁路   | 缆索铁路   | 车站       | 轻轨       | 有轨电车   | 轨道滑车   | 窄轨铁路   |

#### 2. service 数据解析

| 英语           | spur            | siding         | crossover      | yard           | branch         | wye            | industrial     | utility        | driveway      | alley         |
| --------------- | --------------- | -------------- | -------------- | -------------- | -------------- | -------------- | -------------- | -------------- | ------------- | -------------- |
| 中文        | 分歧线         | 边线         | 跨越道岔       | 车场           | 支线           | Y型线路         | 工业铁路       | 公用铁路       | 车库入口     | 巷道         |

#### 3. usage 数据解析
| 英语       | main            | branch         | test           | industrial     |tourism        | freight        | transportation | siding        | yard          | gathering      | spillway       |
| ---------- | --------------- | -------------- | -------------- | -------------- |-------------- | -------------- | -------------- | ------------- | ------------- | ------------- | ------------- |
| 中文     | 主线             | 支线           | 测试线         | 工业铁路       |旅游铁路       | 货运铁路       | 运输铁路             | 侧线          | 车场线        | 集散线         | 泄水线         |


下载地址👉 [【铁路-线位下载-part1】](https://github.com/OpenQGIS/OMap-GeoDB/blob/main/oData-railway/%E9%93%81%E8%B7%AF.zip.001)
 | 
[【铁路-线位下载-part2】](https://github.com/OpenQGIS/OMap-GeoDB/blob/main/oData-railway/%E9%93%81%E8%B7%AF.zip.002)



### 2. 铁路站点：oData-railway-station

| 英语词汇       | monorail        | subway         | train          | tram           | tram_stop      |
| --------------- | --------------- | -------------- | -------------- | -------------- | -------------- |
| 中文含义     | 单轨铁路站         | 地铁站           | 火车站           | 有轨电车站       | 有轨电车停车点     |

下载地址👉 [【铁路-站点下载】](https://github.com/OpenQGIS/OMap-GeoDB/tree/main/oData-railway-station)


## 二、⚡ 电力数据<a id="section2"></a>

电力数据日期：2025.2.6

###  1. 电力-点数据：power_point_oData
> **分卷压缩**；下载是务必下载zip.001、zip.002、zip.003，解压其中一个即可获取数据

| 英语词汇 |tower | generator | transformer | compensator |
| --------- |----- | -------- | ---------- | ---------- |
| 中文含义 |高压电塔 | 发电机   | 变压器    | 补偿器    |

[【电力-点位数据-part1】](https://github.com/OpenQGIS/OMap-GeoDB/blob/main/oData-power/power_point_oData.zip.001)
 | 
[【电力-点位数据-part2】](https://github.com/OpenQGIS/OMap-GeoDB/blob/main/oData-power/power_point_oData.zip.002)
 | 
[【电力-点位数据-part3】](https://github.com/OpenQGIS/OMap-GeoDB/blob/main/oData-power/power_point_oData.zip.003)

###  2. 电力-线数据：power_line_oData

| 英语词汇 | cables | circuits | frequency | voltage | MAX_volt | MAX_kv |
| --------- | ------ | ------- | -------- | ------ | ------- | ------ |
| 中文含义 | 电缆数   | 电路数    | 频率     | 电压    | 最大电压 | 最大千伏 |

下载地址👉 [【电力-线位数据】](https://github.com/OpenQGIS/OMap-GeoDB/blob/main/oData-power/power_line_oData.7z)

###  3. 电力-面数据：power_polygon_oData

| 英语词汇 | substation | generator | plant |
| --------- | ---------- | -------- | ----- |
| 中文含义 | 变电站    | 发电机   | 工厂  |

| 英语词汇 | nuclear | coal | solar | gas | waste | hydro | wind | diesel | biomass | waste coal | oil | geothermal | battery | coal gas | petroleum coke |
| --------- | ------- | ---- | ----- | --- | ----- | ----- | ---- | ------ | ------- | ---------- | --- | --------- | ------- | -------- | -------------- |
| 中文含义 | 核能    | 煤炭 | 太阳能 | 天然气 | 废物能源 | 水力发电 | 风能 | 柴油 | 生物质 | 废弃煤 | 石油 | 地热能 | 电池储能 | 煤气 | 焦炭            |



下载地址👉 [【电力-面数据】](https://github.com/OpenQGIS/OMap-GeoDB/blob/main/oData-power/power_polygon_oData.7z)

## 三、🛫 机场跑道<a id="section3"></a>


铁路数据日期：2025.2.6

| 英语词汇 | runway | taxiway | construction | stopway | parking_position | jet_bridge | goods | navigationaid | landing_light | taxilane | razed | aerodrome | displaced_threshold |
| ------- | ------- | ------ | ------- | -------- | ------- | ---------- | ----- | ------------- | ------------ | -------- | ----- | -------- | -------------------- |
| 中文含义 | 跑道   | 滑行道 | 建设          | 停止道  | 停机位           | 登机桥     | 货物  | 导航辅助设施 | 着陆灯        | 滑行道   | 拆除   | 飞机场   | 移动入口           |

下载地址👉 [【机场跑道-线数据】](https://github.com/OpenQGIS/OMap-GeoDB/blob/main/oData-aeroways/aeroways_oData.zip)

---
## 合集网盘下载地址<a id="section99"></a>

**网盘下载：**

[网盘地址➀](https://caiyun.139.com/m/i?2jQXim20qyrqi)    提取码:uos2

[网盘地址➁](https://share.weiyun.com/RkXrTix9)


