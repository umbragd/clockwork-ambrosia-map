# Clockwork Ambrosia Interactive Map

Clockwork Ambrosia 高清互动地图与收集助手。

An unofficial interactive world map with material lookup, collectible tracking, and local save analysis. Switch between Chinese and English using **Language / 语言** at the top. Both languages share the same page and progress; the existing URL is unchanged.

**[打开在线地图 / Open Map](https://umbragd.github.io/clockwork-ambrosia-map/)**

**[下载离线 HTML / Download Offline HTML](https://github.com/umbragd/clockwork-ambrosia-map/releases/latest/download/clockwork_ambrosia_interactive_map_standalone.html)**

## 功能

- 可缩放高清地图、房间地形、传送点与存档点。
- 素材与敌人查询、敌人识别图及代表性获取地点。
- 收集进度记录与导入、导出。
- 本地加载游戏 `.sav`，查询缺失收集物、未探索候选区域和未开宝箱。
- 按已完成的装备升级和当前库存计算剩余素材缺口。
- Ore 矿脉与 Omnistrand 固定来源的剩余位置查询；Omnistrand 页面另列出一次性 LordBat 掉落来源及定位。
- 顶部 **Language / 语言** 切换中英文，自动记住选择；公开页面不再显示测试用素材核对按钮。

## 使用与隐私

在线版直接打开即可使用。离线版下载后用浏览器打开，无需安装或启动服务器。

存档由浏览器在本地解析，不上传存档，不修改游戏或存档。手动收集进度与语言选择保存在当前浏览器的本地存储中；清理网站数据会删除这些记录，请按需导出进度备份。此前的素材核对记录不会被删除，但测试控件不再公开显示。离线文件与在线网站的本地进度不自动共享。在线访问本身仍会向 GitHub Pages 请求页面。

## 数据与限制

底图根据游戏房间数据独立重绘。收集清单与部分参考坐标参考了 `CLOCKWORK AMBROSIA — COORDINATES FOR COLLECTING STUFF` 工作簿；素材掉落与固定拾取物来源依据游戏配置解析。刷取素材地点参考了社区指南：https://steamcommunity.com/sharedfiles/filedetails/?id=3753198193 ，但根据规则进行了重新计算。

素材收集地点优先级为传送点 > 存档点 > Borersville大本营，方便进出房间刷怪，但不一定是最好的刷素材点；普通敌人掉落素材的第一推荐点已实测核对。Ore 和 Omnistrand 不可再生，LordBat 只出现一次；存档中的击败标志不能单独确认掉落是否拾取。计算距离时假设玩家已获得全部能力，只剩下刷素材。计算时，静态地形参与寻路，但动态机关、单向门、剧情状态比如水位与实际通行规则仍可能影响结果。存档分析结果适用于Steam版本号v1.0.5，游戏更新后可能需要重新核对。已标注的实测结论仅覆盖相应来源与点位。

这是玩家制作的非官方辅助工具，与游戏开发者及发行商无隶属或背书关系。游戏名称、角色图像及相关内容属于各自权利人；本仓库不对这些内容授予再许可。仓库提供已构建的网页，不包含游戏程序、原始资源包、个人存档或测试截图。

## 反馈

请通过 GitHub Issues 报告问题，并提供物品或房间名称、预期结果与实际结果。提交问题前请检查附件中是否包含你不希望公开的个人信息。
