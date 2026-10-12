# 炮塔组合动画预览 · Nivarian Can Fly

RimWorld 1.6 模组 《Nivarian Can Fly》(涅瓦莲能飞) 的**炮塔组合动画预览**静态站点。

把「需求及素材/炮塔」里的部件（底座 / 炮管 / 主体）按配方叠加，测试瞄准、扫描、开火与后坐动画。

## 在线预览
GitHub Pages：https://sanguodxj-byte.github.io/cue-github-pages-demo/

## 操作
- 拖动画布瞄准，`空格` 开火，`R` 复位
- 绿色十字 = pivot（旋转中心），红点 = 炮口
- 右侧可切换装置 / 瞄准方式 / 旋转方式 / 缩放，并逐层校准位移与不透明度

## 目录
- `index.html` 预览页（无外部依赖，纯 Canvas）
- `assets/` 部件贴图与 `data.js`（各层 bbox / 内容宽高 / 主色，由 build_preview.py 生成）
