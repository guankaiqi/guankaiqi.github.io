---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
  dl {
    margin-top: 1px;
    margin-bottom: 5px; /* 调整这个值以获得合适的间距 */
    clear: both;
  }

  img {
    display: block;
    margin: 0px 10px 10px 0px; /* 图片居中 上右下左*/ 
    max-width: 100%; /* 限制图片最大宽度 */
  }

  hr {
    border: 1px solid #ebebeb; /* 调整分隔线的颜色和样式 */
    /* margin: 10px;  */
    clear: both; 
  }


  dl dd {
  color: #; 
  margin-top: 1px; 
  margin-bottom: 1px;
}

  dl dd strong {
  font-weight: bold;
  }


  .publication-title {
    font-weight: bold;
  }

  .image-container {
    display: flex;
    justify-content: center;
    gap: 10px; /* 控制图片间距 */
    margin: 20px 0;
  }

  .image-container img {
    max-width: 150px; /* 控制最大宽度 */
    height: auto;
    margin: 0; /* 移除原来的 margin */
  }

  .co-first {
    color: #B02418;
  }
  
</style>


{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

My name is Kaiqi Guan (官恺祺), I'm currently a undergraduate student at the [School of Computer Science](https://cs.whu.edu.cn/), [Wuhan University](https://www.whu.edu.cn/), fortunately supervised by [Prof. Mang Ye](https://marswhu.github.io/index.html) and [Mr. Wenke Huang](https://scholar.google.com/citations?hl=zh-CN&user=aFoCI3MAAAAJ).


# 📃 Publications


<dl>
  <dd><a href="" class="publication-title">Rethinking Fair Federated Learning from Parameter and Client View</a></dd>
  <dd>Kaiqi Guan, Wenke Huang, Xianda Guo, Yueyang Yuan, Bin Yang, Mang Ye*</dd>
  <dd>Annual Conference on Neural Information Processing Systems <strong>(NeurIPS)</strong>, 2025</dd>
</dl>

<hr>

# 🎖 Honors and Awards
- *2024.09* **National Scholarship** (**<u>国家奖学金</u>**) (Award Rate: <strong>0.4% nation-wide</strong>) *Ministry of Education, China* 

# 📖 Educations
- *2023.09 - Now*, School of Computer Science, Wuhan University