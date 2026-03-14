---
layout: single
title: "About Me"
permalink: /
author_profile: true
---

<style>
#main { max-width: 1200px; }
/* 1. 滚动新闻栏 - 优化了重复定义的 li */
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
  font-size: 0.95em;
  display: flex;       /* 确保日期和文字水平对齐 */
  align-items: flex-start; /* 文字多行时，日期顶格对齐 */
  line-height: 1.5;
}

/* 2. 日期方框 - 增加了 flex-shrink 保证方框不缩水 */
.news-date {
  display: inline-block;
  background-color: #f1f1f1;
  padding: 2px 8px;
  border-radius: 4px;
  font-family: Menlo, Monaco, Consolas, "Courier New", monospace;
  font-size: 0.85em;
  color: #666;
  margin-right: 12px;
  min-width: 75px;    /* 稍微加宽一点，防止 2026.01.01 这种长日期放不下 */
  text-align: center;
  flex-shrink: 0;     /* 重要：防止在窄屏下日期方框被挤压变形 */
}

/* 3. 论文列表项 */
.pub-item {
  margin-bottom: 25px;
  list-style: none;
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

/* 4. 链接按钮 - 从黑色改为白色风格 */
.btn-box {
  display: inline-block;
  padding: 2px 10px;
  margin-right: 6px;
  margin-top: 8px;
  border-radius: 6px;
  background-color: #ffffff; /* 背景改为白色 */
  color: #333333 !important; /* 文字颜色改为深灰色 */
  font-size: 0.85em;
  font-weight: 500;
  text-decoration: none !important;
  border: 1px solid #d1d5da; /* 添加浅灰色边框 */
  transition: all 0.2s ease;
  box-shadow: 0 1px 2px rgba(0,0,0,0.05); /* 添加极其轻微的阴影增强质感 */
}

.btn-box:hover {
  background-color: #f6f8fa; /* 悬停时稍微变灰 */
  color: #0366d6 !important; /* 悬停时文字变为蓝色（类似GitHub链接色） */
  border-color: #babbbd;
  transform: translateY(-1px);
  box-shadow: 0 3px 6px rgba(0,0,0,0.1);
}
</style>


Hi! I am Zixuan Chen (陈子轩).I am a Ph.D. Candidate at School of Computer Science, [Shanghai Jiao Tong University](https://www.sjtu.edu.cn/). 

I am currently a member of [RHOS Lab](https://mvig-rhos.com/) advised by [Prof. Yonglu-Li](https://dirtyharrylyl.github.io/) .


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
      🎉 "M^3-VOS" was accepted to  <strong>CVPR 2025</strong>.
    </li>
    <li>
      <span class="news-date">2020.03</span> 
      🎉 "LNE-IMGM" was accepted to  <strong>ECCV 2020</strong>.
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