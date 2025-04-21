# 欢迎使用 `「九州」地理数据库`

> [OMap–GeoDB 「九州」地理数据库](https://his.lreept.space/openqgis/omap-geodb/)，是一款完全基于开源数据库OpenStreetMap（简称OSM）进行本土化适配的新华夏九州范围的综合类地理数据库。

1. 什么是OpenStreetMap？
   建构自由内容之网上地图协作计划，目标是创造一个内容自由且能让所有人编辑的世界地图。
2. 什么是「九州」地理数据库？
   九州地理数据库（全称：OMap-GeoDB_ JiuZHou），属于OMap-GeoDB（中文：超常规地理数据）的分支之一，其目的是创建一个完整华夏九州范围的**免费开源**的地理数据库，帮助大家降低数据获取门槛。

---

# 九州数据库与GPKG（地理包）

## **产品体系：**

九州地理数据库当前共包含**15小项**合计**7大类**。

## **数据格式：**

QGIS与OSM同属于开源产品，数据首发格式以`*.GPKG（地理包）`[^1]进行发布。支持拖入QGIS即可一键加载。更多内容关于GPKG可以访问B站视频`https://www.bilibili.com/video/BV1gM4m167PS`。

## **读取和转换：**

1. 读取|将gpkg文件直接拖拽至QGIS中即可完成加载；ArcGIS Pro 3.0也支持对gpkg直接加载。
2. 转换|在QGIS中加载gpkg后，在需要转换的图层`【右键】>>【导出】>>【要素另存为】或者【选中要素另存为】，在弹出窗口肖的【格式】项选择【ESRI形状文件】即可导出为SHP文件`。
3. **警告**|SHP文件的大小可能远超过gpkg文件本身的大小，请注意计算机磁盘容量。

# 九州数据库各类说明

## 目录

1. [🛫 机场跑道](#section1)
2. [🏘️ 建筑数据](#section2)
3. [🌳 土地数据](#section3)
4. [🚉 铁路数据](#section4)
5. [🚘️ 道路数据](#section5)
6. [🚘️ 交通设施](#section6)
7. [🌊 水系大坝](#section7)



## 1.🛫 机场跑道<a id="section1"></a>

以机场跑道信息为主，涵盖了其他空中交通体系如：缆车、索道……

| 英语词汇 | runway | taxiway | construction | stopway | parking_position | jet_bridge | goods | navigationaid | landing_light | taxilane | razed | aerodrome | displaced_threshold |
| ------- | ------- | ------ | ------- | -------- | ------- | ---------- | ----- | ------------- | ------------ | -------- | ----- | -------- | -------------------- |
| 中文含义 | 跑道   | 滑行道 | 建设          | 停止道  | 停机位           | 登机桥     | 货物  | 导航辅助设施 | 着陆灯        | 滑行道   | 拆除   | 飞机场   | 移动入口           |




[^1]: [Bilibli——地理包(gpkg)使用全教程]([地理包使用全教程——gpkg](https://www.bilibili.com/video/BV1gM4m167PS))
