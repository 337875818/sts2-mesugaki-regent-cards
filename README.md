# Slay the Spire 2 — 储君 Mesugaki 卡图 / Regent Mods

《杀戮尖塔 2》自制 mod 合集：储君卡图替换、事件立绘、卡图制作器、通用加载器。
不依赖创意工坊，解压丢进 `mods\mods\` 即可使用。

- 卡图：0.111 与 0.113 双版本，全年龄 / 成人向分开
- 事件立绘：57 个事件，含 SFW⇄NSFW 一键切换
- 工具：卡图 mod 制作器（自己做包）、卡图包通用加载器（多包共存）

## 下载（Releases 页面）

| 文件 | 适用版本 | 内容 |
|---|---|---|
| `MesugakiRegentCards_0.111.1_SFW.zip` | 0.111+ | 储君卡图 · 全年龄 · 59 张 |
| `MesugakiRegentCards_0.111.1_18plus.zip` | 0.111+ | 储君卡图 · 成人向 · 60 张 |
| `MesugakiRegentCards_0.113_SFW.zip` | 0.113 | 储君卡图 · 全年龄 |
| `MesugakiRegentCards_0.113_18plus.zip` | 0.113 | 储君卡图 · 成人向 |
| `MesugakiRegentCards_0.113_Nude.zip` | 0.113 | 储君卡图 · 全裸版（18+，与上条二选一） |
| `MesugakiRegentCards_1.13_NSFW.zip` | 0.113 (1.13) | 储君卡图 · NSFW 卡图包 · 51 张（18+） |
| `RegentEventArt_0.3.4.zip` | 0.113 | 事件立绘 57 个 · 含 SFW/NSFW 切换 |
| `CardPackLoader_2.1.0.zip` | 0.113+ | 卡图包通用加载器（多包共存） |
| `CardArtMaker_v1.8.zip` | — | 卡图 mod 制作器 |

## 安装

```
1. 解压压缩包
2. 把整个文件夹放进 <游戏目录>\mods\mods\
   （Steam 右键游戏 → 管理 → 浏览本地文件；没有 mods\mods 就自己新建）
3. 启动游戏 → 模组列表勾选启用 → 重启生效
```

## 事件立绘切换 SFW / NSFW

```
双击文件夹里的「切换版本_本地版.bat」，按提示切换，然后重启游戏
或手动：把 RegentEventArt_SFW.pck / RegentEventArt_NSFW.pck 改名成
       RegentEventArt.pck 覆盖，并把 mode.txt 改成对应值
```

## 更新记录

- **0.111.1** — 修复 0.111 客户端 DLL 初始化失败：移除 0.111 中不存在的 `CardModel.get_BigPortrait` Harmony 补丁；装皮肤切换器时也照常挂载
- **事件立绘 0.3.4** — 酷刑博物馆文本修正；镜中倒影改为保留原版立绘（联机加载失败）；皮肤切换器识别修复；切换脚本改为 ASCII 编码
- **卡图制作器 1.8** — 批量导入文件夹、解包预览与导出、先古大卡模式、多包共存

## 注意

- 卡图类 mod 之间会互相覆盖，同类只启用一个
- 成人向包请确认已成年
- 所有 mod 均不联网、不上传任何数据、不修改游戏数值

## English

Slay the Spire 2 mods by this repo: Regent card art replacement (0.111 / 0.113,
all-ages and 18+ separately), event artwork with SFW/NSFW switching, a card-art
pack maker and a shared card-pack loader.

Download from the Releases page, unzip, drop the folder into
`<game dir>\mods\mods\`, enable it in the in-game mod list, restart.
