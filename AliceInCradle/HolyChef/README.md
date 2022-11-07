# HolyChef

这是 <a href="https://fantia.jp/fanclubs/24531" target="_blank">Alice In Cradle</a> 游戏的 MOD

名字叫 Holy Chef 简称 厨圣


## 特色菜单

1. 清烧河蟹 - 隐藏动态马赛克遮挡

2. 大杂烩 - 自定义贴图
	+ 从资源中提取贴图（比如使用 AssetStudio 工具）然后编辑
	+ 在 `BepInEx\plugins\HolyChef\Texture2D` 目录中放置对应名称 `png` 或 `pxlp` 扩展名的图片
	+ 把不健全的贴图放到 `BepInEx\plugins\HolyChef\Texture2D\sensitive` 将会在游戏开启健全模式时不进行更换


## 注意事项

1. 游戏的路径必须是全英文的、否则无法正常使用

2. 请不要将 MOD 和游戏一起重新打包后再配布、分流

3. 要完全禁用`清烧河蟹`功能、请按下面方法操作

	把 `moe.moekai.unityplugin.aliceincradle.holychef.cfg` 设置文件 `[Hodgepodge]` 下面的 `Enable = true` 改成 `Enable = false`


## 食用方法

1. 压缩包密码：`萌界`

2. 解压文件 `BepInEx`、`doorstop_config.ini`、`winhttp.dll` 到游戏目录内

3. 开始游戏


## 自助服务

1. 在 `BepInEx\config\moe.moekai.unityplugin.aliceincradle.holychef.cfg` 文件中可以根据注释开启或关闭 MOD 功能

	修改开头没有 # 的文本行
	
	+ 开启：`true`
	+ 关闭：`false`


## 厨房支持

1. BepInEx version >= 6.0


## 兼容游戏版本

请下载文件名后面对应游戏版本的压缩包

兼容：○          不兼容：×          未测试：?

| 游戏版本  | 兼容  |
| ------------ | ------------ |
| 0.20c ~ 0.20s | ○ |
| 0.21a ~ 0.21? | ○ |
| 0.22? | ? |
