---
type: paper
citekey: {{citekey}}
title: "{{title}}"
year: {{date | format("YYYY")}}
tags:
  - paper
status: unread
---

# {{title}}

## 1. 基本信息

- Citekey: {{citekey}}
- Year: {{date | format("YYYY")}}
- Authors: {{authors}}
- DOI: {{DOI}}
- URL: {{url}}

## 2. 一句话总结

这篇论文本质上是在解决：

> 

它的核心方法是：

> 

---

## 3. 研究问题

### 3.1 任务是什么？

### 3.2 现有方法的问题是什么？

### 3.3 作者真正想解决的痛点是什么？

---

## 4. 方法结构

| 模块 | 输入 | 输出 | 作用 | 为什么需要 |
|---|---|---|---|---|
| Module 1 |  |  |  |  |
| Module 2 |  |  |  |  |
| Module 3 |  |  |  |  |

---

## 5. 创新点

作者声称的创新：

1. 
2. 
3. 

我认为真正有效的创新：

1. 
2. 

可能只是工程组合的部分：

1. 

---

## 6. 实验分析

| 实验 | 想证明什么 | 是否充分 |
|---|---|---|
| 主结果 |  |  |
| 消融实验 |  |  |
| 泛化实验 |  |  |
| 参数实验 |  |  |

---

## 7. 局限性

作者承认的局限：

- 

我认为的隐藏问题：

- 

---

## 8. 可挖 idea

这篇论文可以给我的启发：

1. 
2. 
3. 

可以和我的方向结合的点：

- [[LLM-based CO]]
- [[LLM-based EC]]
- [[启发式自动生成]]
- [[反思机制]]
- [[进化搜索]]

---

## 9. 摘要

{{abstractNote}}

---

## 10. 引用信息

{{bibliography}}

---

## 11. Zotero 标注

{% for annotation in annotations %}
{% if annotation.annotatedText %}
> {{annotation.annotatedText}}
{% endif %}

{% if annotation.comment %}
我的批注：{{annotation.comment}}
{% endif %}

{% endfor %}