# Senior Architect Review Guide

一份中文优先的静态 HTML+SVG 介绍手册，用来介绍 `my-senior-architect-review` 资深架构师评审工作流，以及 Toulmin-lite（轻量 Toulmin）论证链在工程决策评审中的作用。

## 内容

- `index.html`：可直接打开的介绍手册。
- `senior-architect-review-guide.svg`：方法论总览图，可单独使用。

## 核心观点

这个手册强调：资深架构师评审的灵魂是“不迎合”。在进入计划和实施之前，先用第一性原理、系统边界、失败模式和 Toulmin-lite 论证链检查方案是否真的成立，不能把用户偏好、模型惯性或礼貌性附和伪装成架构判断。

Toulmin-lite 在这里保留五个工程评审最关键的要素：

- 主张：要支持、反对或有条件推进的结论。
- 证据：源码、运行证据、约束或用户确认事实。
- 推理桥梁：为什么证据能推出主张。
- 例外/反驳：什么条件会削弱或推翻结论。
- 结论强度：强 / 中 / 弱 / 待证据。

## 使用

直接打开：

```bash
open index.html
```

或启动本地静态服务：

```bash
python3 -m http.server 8765
```

然后访问 `http://127.0.0.1:8765/`。

## 作者

田越 [@tianyuegithub](https://github.com/tianyuegithub)

## License

MIT
