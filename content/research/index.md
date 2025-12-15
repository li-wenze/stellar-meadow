---
title: "Research"
type: landing
summary: "Research"
description: "Research"
toc: false

cascade:
  - target:
      path: '{/courses/*/**}'
    type: docs
    params:
      show_breadcrumb: true

sections:
  # 1) 先显示你的 collection 列表
  - block: collection
    id: teaching
    content:
      title: teaching
      filters:
        tag: teaching
        kinds:
          - section
    design:
      view: article-grid
      show_read_time: false
      show_date: false
      show_read_more: false
      columns: 1

  # 2) 再在下面追加一段“同页文本内容”
  - block: markdown
    content:
      title: "Working Papers"
      text: |
        <div class="working-papers">

        ### Firm-Level Network Effects of US-China Trade Shocks  
        *(Joint with Liyu Dou, Ming Li, Shengmao Cao, Wenjie Wang.)*

        ### [Electricity Market Predictability: Virtues of Machine Learning and Links to the Macroeconomy](https://arxiv.org/abs/2507.07477)  
        *(Wenjie Wang, Jinbo Cai.)*

        </div>
---

