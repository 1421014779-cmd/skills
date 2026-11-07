# 学习类 Skills 合集

四个中文学习/思考方法论技能，每个目录下是一个独立的 `SKILL.md`，可直接放入 `~/.claude/skills/` 或 `E:\opencode\skills\` 使用。

| 技能 | 目录 | 触发词 | 一句话简介 |
|---|---|---|---|
| 课程速览 | [`kecheng-sulan/`](kecheng-sulan/SKILL.md) | 课程速览、课程全貌、这门课讲什么 | 两层拆解一门课：第一层逐课内容地图，第二层"这门课真正在讲什么"（实质洞察、隐藏立场） |
| 概念地图 | [`feynman-concept-map/`](feynman-concept-map/SKILL.md) | 概念地图 | 费曼学习法第 1 步：把刚读的文章拆成 5-8 个观点，做"测→讲→再测"检验真懂假懂 |
| 双层解释法 | [`shuangceng-fenxi/`](shuangceng-fenxi/SKILL.md) | 双层分析、双层分析法 | 一个概念讲两遍：小白版（生活化例子）+ 专业版（准确术语），附术语对照表和自检题 |
| 第一性原理 | [`first-principles/`](first-principles/SKILL.md) | 第一性原理、回到本质 | 把问题拆回基本事实和未验证假设，放下行业惯例重新推导路径 |

## 用法

把对应目录整个复制到你的 skills 目录即可，例如：

```powershell
Copy-Item -Recurse .\kecheng-sulan "$env:USERPROFILE\.claude\skills\kecheng-sulan"
```

## 使用建议

- 学新课前用「课程速览」判断值不值得学，学完后用它复盘。
- 「概念地图」适合读完文章立刻做，「双层解释法」适合单个概念/技术方案的理解固化。
- 方案卡住、反复打补丁时用「第一性原理」重新推导。
