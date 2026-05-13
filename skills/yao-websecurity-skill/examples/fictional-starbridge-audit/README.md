# StarBridge Portal 安全审查示例报告

这是 `yao-websecurity-skill` 的公开示例报告。

注意：这是完全虚构的演示案例，不对应任何真实项目、真实仓库、真实系统或真实漏洞。报告里的系统名称、仓库地址、提交号、代码路径、端点、账号、漏洞证据、风险发现和整改建议均为示例内容。

## 示例对象

- 项目名：`StarBridge Portal（虚构样例）`
- 类型：多租户内容协作 SaaS
- 假设能力：团队空间、文档管理、导入导出、Webhook、订阅计费、前端 SPA、对象存储、PostgreSQL/Redis、Docker Compose、AI 摘要
- 审查模式：动态安全审查
- 测试强度：低风险运行时

## 示例输出

- [HTML 报告](安全审查报告.html)
- [PDF 报告](安全审查报告.pdf)
- [Excel 评分表](安全审查评分表.xlsx)
- [Markdown 报告](安全审查报告.md)
- [Sanitized JSON](security_review.sanitized.json)

## 报告用途

这个示例主要展示：

- 275 项检查表如何被归类为安全、存在风险、存疑和不适用
- P0/P1 风险如何在报告前部集中呈现
- 每个风险如何组织证据、根因、影响和修复建议
- Excel、HTML、Markdown、PDF 和 JSON 如何从同一份审查台账生成
- HTML 的中文默认视图、英文切换和粘性顶部导航效果
- PDF 的打印排版效果

不要把这个示例作为任何真实系统的安全结论。
