# Slay the Spire 2 — 储君 Mesugaki 卡图 / Regent Mesugaki Card Art

把《杀戮尖塔 2》储君的卡面整套替换为 Mesugaki 版本。

- 0.111 与 0.113 双版本
- 全年龄与成人向分开打包
- 纯资源替换 + 加载器 DLL，装完即用；不修改游戏数值

## 下载

到 [Releases](../../releases) 页面下载对应压缩包：

| 文件 | 版本 | 内容 |
|---|---|---|
| `MesugakiRegentCards_0.111.1_SFW.zip` | 0.111+ | 全年龄，59 张 |
| `MesugakiRegentCards_0.111.1_18plus.zip` | 0.111+ | 成人向，60 张 |
| `MesugakiRegentCards_0.113_SFW.zip` | 0.113 | 全年龄，59 张 |
| `MesugakiRegentCards_0.113_18plus.zip` | 0.113 | 成人向，60 张 |
| `CardArtMaker_v1.8.zip` | — | 卡图 mod 制作器（自己做包） |

## 安装

```
1. 解压压缩包
2. 把整个文件夹放进 <游戏目录>\mods\mods   （Steam 右键游戏 → 管理 → 浏览本地文件；
     没有 mods\mods 就自己新建）
3. 启动游戏 → 模组列表勾选启用 → 重启生效
```

## 更新记录

- **0.111.1** — 修复 0.111 客户端 DLL 初始化失败：移除 0.111 中不存在的 `CardModel.get_BigPortrait` Harmony 补丁；装皮肤切换器时也照常挂载补丁
- **0.111.0** — 首个 0.111 兼容版

## 注意

- 与其他卡面替换模组会互相覆盖，建议只启用一个
- 成人向包请确认已成年
- 本模组不联网、不上传任何数据、不修改游戏数值

## English

Regent card art replacement mod for Slay the Spire 2 (Mesugaki style).
Pick the archive matching your game version from the Releases page, unzip,
drop the folder into `<game dir>\mods\mods\`, enable it in the in-game mod list.

The `0.111.1` release fixes a DLL initialization failure on 0.111 clients
(a Harmony patch for the non-existent `CardModel.get_BigPortrait` was removed).
