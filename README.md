# 群岛 · ARCHIPELAGO

OASIS 团队的 3D 作品群岛：7 座小岛，可以上岸自由行走，也能走到码头坐船跨岛。
three.js 实时渲染，页面本身零构建、零依赖包管理。

线上地址：https://lubiny0601-spec.github.io/oasis-archipelago/

## 怎么玩

| 操作 | 电脑 | 手机 |
| --- | --- | --- |
| 环视 / 缩放 | 拖动 / 滚轮 | 单指拖动 / 双指捏合 |
| 上岸 | 点岛 | 点岛 |
| 走动 | WASD / 方向键 / 点地面走过去 | 左下角摇杆 / 点地面 |
| 看作品卡 | 走近地标自动弹出 | 同左 |
| 跨岛 | 走到码头根部 → 点「乘船去」 | 同左 |
| 返回总览 | 「← 群岛」按钮 | 同左 |

手机上 Safari / Chrome 菜单里的「添加到主屏幕」，可以当 App 用（全屏、无地址栏）。

## 岛屿与作品

01 群岛（石门）· 02 Robin-ai 聚变（蓝顶小屋）· 03 ASHEN CROWN 灰烬王冠（风车）·
04 愿望与补给（瞭望塔）· 05 耐药监测看板（木屋）· 06 OASIS（凉亭）· 07 预留位（鸟居）

## 目录

- `index.html` — 页面（含分享卡片元信息）
- `three.min.js` — 渲染库
- `preview.png` — 分享卡片图（1200×630）

## 怎么更新

改完源文件后，把页面同步到本目录再提交即可，Pages 会自动重新构建（约 30 秒）：

```bash
cp ../island_archipelago.html ./index.html
git add -A && git commit -m "描述改动" && git push
```

## 调试参数

`?hero=1` 海报模式（隐藏 UI）· `?isle=<id>` 直达单岛 · `?land=<id>` 直接上岸 ·
`?night=1` 夜景 · `?touch=1` 模拟手机输入 · `?wbd=<0-1>` 摆小人到上岸曲线指定位置
