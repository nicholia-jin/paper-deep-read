# Paper Deep Read / 科研论文精读

A reusable Codex skill for finding, annotating, visualizing, and teaching academic papers in small, durable reading units.

一个可复用的 Codex Skill：用于检索、标注、可视化并分段精讲科研论文，同时保存可回顾的阅读记录。

## What it does / 它能做什么

- Find a named paper and prioritize lawful open-access full text.
- Add bibliographic records to Zotero and use Readwise Reader as the visible annotation workspace when connected.
- Keep the PDF visible while explaining one paragraph, figure, table, or short subsection at a time.
- Create highlights, Chinese notes, structured tags, and compact diagrams when they clarify a mechanism or relationship.
- Produce section research cards and an end-of-paper synthesis.

- 根据论文题目定位可信来源，并优先获取合法开放全文。
- 在可连接时导入 Zotero 做长期文献管理，并在 Readwise Reader 中进行可见的原文标注。
- 让 PDF 保持可见；每次只推进一段、一张图、一张表或一个短小节。
- 记录原文高亮、中文理解笔记、结构化标签，并在需要时绘制简图。
- 在每节结束生成研究卡片，全文结束生成贡献、证据、局限与研究关联的综合总结。

## Usage / 使用方式

```text
精读skill：<论文标题、DOI、arXiv ID 或链接>
```

Example / 示例：

```text
精读skill：CoALA: Cognitive Architectures for Language Agents
```

## Reading loop / 精读循环

1. Locate and prepare the paper / 检索并准备论文  
2. Open a visible PDF reading view / 打开可见的 PDF 阅读视图  
3. Explain one bounded unit / 精讲一个最小单元  
4. Annotate, tag, and summarize / 标注、分类并总结  
5. Pause for questions before advancing / 等待提问或继续指令  

## Annotation tags / 标注标签

`核心主张` · `概念定义` · `框架/方法` · `证据/实验` · `图表` · `疑问/局限` · `值得复现`

## Notes / 注意事项

- This skill does not bypass paywalls. It uses lawful, accessible copies only.
- Tool availability depends on the connected Codex environment and the user's accounts.
- Zotero is the long-term bibliographic archive; Readwise Reader is the primary visible reading and annotation workspace.

- 本 Skill 不会绕过付费墙，只使用合法可访问的论文版本。
- 实际可用工具取决于 Codex 环境中已连接的插件与用户账户。
- Zotero 用于长期文献归档；Readwise Reader 用于可见阅读与原文标注。

## License / 许可证

Released under the [MIT License](LICENSE).
