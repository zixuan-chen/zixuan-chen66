---
layout: single
title: "About Me"
permalink: /
author_profile: true
---

<style>
/* 1. 全局字体与排版美化 (保留清爽风格) */
body {
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
  color: #333;
  line-height: 1.6;
  -webkit-font-smoothing: antialiased;
}

h1, h2, h3, h4 {
  font-family: "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
  font-weight: 600;
  color: #222;
  border-bottom: 1px solid #eee;
  padding-bottom: 8px;
  margin-top: 1.5em;
}

a {
  color: #0366d6;
  text-decoration: none;
}
a:hover {
  text-decoration: underline;
}

/* 2. 滚动新闻栏 */
.news-container {
  height: 180px;
  overflow-y: auto;
  border: 1px solid #f0f0f0;
  padding: 15px;
  background-color: #fafafa;
  border-radius: 8px;
  margin-bottom: 30px;
}
.news-container ul {
  list-style: none;
  padding-left: 0;
  margin: 0;
}
.news-container li {
  margin-bottom: 12px;
  display: flex;
  align-items: flex-start;
  line-height: 1.6; /* 稍微调小行高避免太散 */
}

/* 日期方框 */
.news-date {
  display: inline-block;
  background-color: #eef0f2;
  padding: 2px 8px;
  border-radius: 4px;
  font-family: Menlo, Monaco, Consolas, "Courier New", monospace;
  font-size: 0.85em;
  color: #555;
  margin-right: 12px;
  min-width: 75px;
  text-align: center;
  flex-shrink: 0;
}

/* 3. 论文列表项 */
.pub-item {
  width: 100%;
  margin-bottom: 35px;
}
.pub-title {
  font-weight: bold;
  font-size: 1.05em;
  display: block;
  color: #222;
}
.pub-authors {
  font-size: 0.95em;
  color: #444;
  display: block;
  margin: 4px 0;
}
.pub-venue {
  font-style: italic;
  font-size: 0.95em;
  display: block;
  color: #555;
}

/* 4. 白色药丸形按钮 */
.btn-box {
  display: inline-block;
  padding: 3px 12px;
  margin-right: 8px;
  margin-top: 10px;
  border-radius: 20px;
  background-color: #ffffff;
  color: #444 !important;
  font-size: 0.8em;
  font-weight: 500;
  text-decoration: none !important;
  border: 1px solid #d1d5da;
  transition: all 0.2s ease;
  box-shadow: 0 1px 2px rgba(0,0,0,0.05);
}

.btn-box:hover {
  background-color: #f6f8fa;
  border-color: #0366d6;
  color: #0366d6 !important;
  transform: translateY(-1px);
  box-shadow: 0 3px 6px rgba(0,0,0,0.1);
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
(* equal contribution)

<div class="pub-item">
  <span class="pub-title">M^3-VOS: Multi-Phase, Multi-Transition, and Multi-Scenery Video Object Segmentation</span>
  <span class="pub-authors"><strong>Zixuan Chen</strong>, J. Li, J. Liang, L. Tan, Y. Guo, C. Lu, Y. L. Li.</span>
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


### 🏛️ Academic Services {#services}
* **Conference Reviewer:** CVPR, NIPS.