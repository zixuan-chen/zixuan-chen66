---
layout: single
title: "About Me"
permalink: /
author_profile: true
---

<style>
/* 1. 全局字体与排版美化 (不改变颜色，适应日夜模式) */
body {
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
  line-height: 1.7; /* 增加行高，提升呼吸感 */
  -webkit-font-smoothing: antialiased;
}

/* 优雅的下划线设计，使用 rgba 适应深浅色背景 */
/* 针对所有标题的通用美化 */
/* 标题美化：回归标准字号，保留大气间距 */
h1, h2, h3, h4 {
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
  font-weight: 600;                 /* 稍微调低一点粗细，显得更清秀 */
  border-bottom: 1.5px solid rgba(128, 128, 128, 0.15); /* 稍微变细的下划线 */
  padding-bottom: 8px;
  margin-top: 2.2em;                /* 保持较大的上方留白，这是大气的关键 */
  margin-bottom: 0.8em;             /* 标题与下方内容的间距 */
  letter-spacing: -0.01em;
  color: inherit;                   /* 确保颜色跟随白天/夜间模式自动切换 */
}

/* 恢复到标准学术主页字号 */
h3 {
  font-size: 1.25em !important;     /* 恢复到原来的大小 */
}

/* About Me 标题也同步微调 */
h1 {
  font-size: 1.8em !important;      /* 稍微大一点但不过分 */
  margin-top: 1em;
}


/* 2. 新闻栏：无边框设计，高级感来源 */
.news-container {
  height: 220px; /* 稍微加高一点，容纳更多内容不显得拥挤 */
  overflow-y: auto;
  border: none; /* 去除原本的方框，更加现代 */
  padding: 5px 0;
  margin-bottom: 40px;
}

.news-container ul {
  list-style: none;
  padding-left: 0;
  margin: 0;
}

.news-container li {
  margin-bottom: 16px; /* 增加新闻条目之间的垂直间距 */
  display: flex;
  align-items: flex-start;
  font-size: 0.95em;
  line-height: 1.6;
}

/* 日期标签：自适应日夜模式的淡灰色背景 */
.news-date {
  display: inline-block;
  background-color: rgba(128, 128, 128, 0.1); /* 半透明背景 */
  padding: 3px 10px;
  border-radius: 6px;
  font-family: "SFMono-Regular", Consolas, Menlo, monospace;
  font-size: 0.85em;
  font-weight: 500;
  margin-right: 18px; /* 增加日期与文字的间距 */
  min-width: 78px;
  text-align: center;
  flex-shrink: 0;
}

/* 3. 论文列表项排版 */
.pub-item {
  margin-bottom: 45px; /* 加大每篇论文之间的垂直距离 */
  padding-left: 5px;
}

.pub-title {
  font-weight: 700;
  font-size: 1.05em;
  line-height: 1.4;
  display: block;
  margin-bottom: 6px;
}

/* 论文备注样式：灰色、斜体、自适应日夜模式 */
.pub-note {
  font-size: 0.9em;
  font-style: italic;     /* 设置斜体 */
  margin-bottom: 15px;
  opacity: 0.6;           /* 使用透明度实现灰色，可自动适配白天/夜间模式 */
  font-family: inherit;
}

.pub-authors {
  font-size: 0.95em;
  display: block;
  opacity: 0.85; /* 使用透明度而不是固定颜色，自动适应暗黑模式 */
  margin-bottom: 4px;
}

.pub-venue {
  font-style: italic;
  font-size: 0.95em;
  display: block;
  opacity: 0.7; /* 进一步降低透明度，区分层次 */
}

/* 4. 药丸形链接按钮：透明底色 + 悬停动效 */
.btn-box {
  display: inline-block;
  padding: 4px 14px;
  margin-right: 10px;
  margin-top: 12px;
  border-radius: 20px;
  background-color: transparent; /* 背景透明，完全融入底色 */
  color: inherit !important; /* 文字颜色随主题变化 */
  font-size: 0.82em;
  font-weight: 500;
  text-decoration: none !important;
  border: 1px solid rgba(128, 128, 128, 0.3); /* 半透明边框 */
  transition: all 0.3s cubic-bezier(0.25, 0.8, 0.25, 1);
}

.btn-box:hover {
  background-color: #0366d6; /* 悬停时变为醒目的蓝色 */
  color: #ffffff !important; /* 悬停时文字变为白色 */
  border-color: #0366d6;
  transform: translateY(-2px); /* 轻微上浮 */
  box-shadow: 0 4px 10px rgba(3, 102, 214, 0.25); /* 蓝色光晕阴影 */
}
</style>

Hi! I am Zixuan Chen (陈子轩).I am a Ph.D. Candidate at School of Computer Science, [Shanghai Jiao Tong University](https://www.sjtu.edu.cn/). 

I am currently a member of [RHOS Lab](https://mvig-rhos.com/) advised by [Prof. Yong-Lu Li](https://dirtyharrylyl.github.io/) .


### 🔬 Research Interests
* **Embodied AI:** Task decomposition and skill composition for long-horizon 3D manipulation.
* **Causality:** Causal discovery, world models, and counterfactual reasoning in dynamic environments.
* **Brain-like Intelligence:** Developing neuro-symbolic architectures inspired by biological cognitive processes.

---
### 📢 News {#news}
<div class="news-container">
  <ul>
    <li>
      <span class="news-date">2025.02</span> 
      🎉 "M^3-VOS" was accepted to&nbsp;<strong>CVPR 2025</strong>.
    </li>
    <li>
      <span class="news-date">2020.03</span> 
      🎉 "LNE-IMGM" was accepted to&nbsp;<strong>ECCV 2020</strong>.
    </li>
  </ul>
</div>

---

### 📝 Selected Publications {#publications}
<div class="pub-note">(* equal contribution)</div>

<div class="pub-item">
  <span class="pub-title">M^3-VOS: Multi-Phase, Multi-Transition, and Multi-Scenery Video Object Segmentation</span>
  <span class="pub-authors"><strong>Zixuan Chen</strong>*, J. Li*, J. Liang, L. Tan, Y. Guo, C. Lu, Y. L. Li.</span>
  <span class="pub-venue">Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (<strong>CVPR</strong>), 2025.</span>
  <a href="https://arxiv.org/pdf/2412.13803" class="btn-box">📄 PDF</a>
  <a href="https://zixuan-chen.github.io/M-cube-VOS.github.io/" class="btn-box">🌐 Website</a>
  <a href="https://github.com/zixuan-chen/M3VOS_Experimentl" class="btn-box">💻 Code</a>
  <a href="https://huggingface.co/datasets/Lijiaxin0111/M3_VOS" class="btn-box">📊 Dataset</a>
  <a href="https://github.com/Lijiaxin0111/SemiAuto-Multi-Level-Annotation-Tool" class="btn-box">🛠️ Tool</a>
</div>

<div class="pub-item">
  <span class="pub-title">Layered neighborhood expansion for incremental multiple graph matching</span>
  <span class="pub-authors"><strong>Zixuan Chen</strong>, Z. Xie, J. Yan, Y. Zheng, X. Yang.</span>
  <span class="pub-venue">European Conference on Computer Vision (<strong>ECCV</strong>), 251-267, 2020.</span>
  <a href="https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123550256.pdf" class="btn-box">📄 PDF</a>
  <a href="https://github.com/zhxieml/LNE_IMGM" class="btn-box">💻 Code</a>
</div>

---

### 🎓 Education {#education}
* **Ph.D. Candidate** in Computer Science, Shanghai Jiao Tong University, 2024.09 - Present.
* **M.S.** in Computer Science, Shanghai Jiao Tong University, 2020.09 - 2023.03.
* **B.S.** in Computer Science (IEEE Honor Class), Shanghai Jiao Tong University, 2016.06 - 2020.04.

---

### 🏛️ Academic Services {#services}
* **Conference Reviewer:** CVPR, NIPS.