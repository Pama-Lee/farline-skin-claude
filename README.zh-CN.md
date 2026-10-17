# Farline 的 Claude 风格皮肤

仿 Claude App 的浅色皮肤，给 [Farline](https://github.com/Pama-Lee/farline)（自托管的编程 Agent 工作台）用。

[English](README.md)

<p>
  <img src="screenshots/desktop.png" width="640" alt="电脑">
  <img src="screenshots/phone.png" width="200" alt="手机">
</p>

- 浅色配色，布局按 Claude iOS App 量出来的
- 黑色胶囊按钮、圆形图标按钮、圆角输入卡片
- 电脑和手机都可用

## 安装

在 Farline 里打开 **设置 → 插件 → 发现插件**，安装 **Claude 风格**；或者用 **从 GitHub 安装**，填：

```
Pama-Lee/farline-skin-claude
```

然后在 **设置 → 外观** 里选它。同时只能用一个皮肤，选 **默认** 就切回去。

也可以手动装：把这个仓库克隆到 `~/.farline/plugins/`（即 `FARLINE_DATA_DIR`），重启 Farline。

需要 Farline 1.x（见 `package.json` 里的 `engines.farline`）。

## 另见

- [Cursor 风格皮肤](https://github.com/Pama-Lee/farline-skin-cursor)
- [怎么写皮肤](https://github.com/Pama-Lee/farline/blob/main/docs/zh-CN/plugins.md#皮肤)

与 Anthropic（Claude）无关，也未获其认可；名字只用来说明外观。

## 许可

MIT
