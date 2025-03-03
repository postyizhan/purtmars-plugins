---
sidebar_position: 9
---

# 特殊对话主题 使用帮助

## Yosin_movie （电影风格主题）

### 使用须知:

+ 支持版本 1.19+ (目前因BetterHud限制导致)
+ 需求 BetterHud 1.11.x 及以上版本

### 安装步骤

1. 安装Chemdah
2. 安装BetterHud
3. 将模板配置文件 导入至BetterHud 配置文件夹中。
4. 开启你的对话

### Kether 专属条目
---
设置镜头所在位置

```
setcamera {x} {y} {z} {yaw} {pitch}
```
```
setcamera 203.0 32.0 -35.3 135.6 35.9
```

---
切换对话中的npc


```
sourcetransfer {NpcId}
```
```
sourcetransfer Fu_Meng
```

---
重置镜头 （如果对话进行中，会将镜头转移至当前对话的NPC）


```
resetcamera
```

### 专属对话选项

```
__option__:
  theme: 'yosin-movie'
  title: '[{name}](gradient=#f6d365,#fda085)'
  global-flags: ["NO_EFFECT"]
  #对话使用的popup名字
  dialog_popup_name: 'dialog_popup'
  #选项使用的popup名字
  dialog_options_popup_name: 'dialog_options_popup'
  #镜头y轴偏移
  camera_offset_y: 1.5
  camera_offset_yaw: 0.0
  camera_offset_pitch: 0.0
  #人物y轴偏移
  player_offset_y: 0.5
  #镜头距离
  camera_distance: 2.0
```
自 `1.0` 版本起, Chemdah 为完全付费模式, 详见[服务](/plugin/chemdah/service)。
