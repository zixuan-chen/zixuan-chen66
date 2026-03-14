---
layout: single
title: "About Me"
permalink: /
author_profile: true
---

<style>
/* 1. 核心布局修复：让整体居中 */
#main {
  max-width: 1200px; /* 限制最大宽度，不再全屏铺满 */
  margin: 0 auto;    /* 核心：让整个容器在页面水平居中 */
  padding: 2em 20px;
  display: flex;
  justify-content: space-between;
}

/* 侧边栏宽度固定，不随内容拉伸 */
.sidebar {
  width: 260px !important;
  margin-right: 40px !important;
  flex-shrink: 0;
}

/* 内容区自适应，但限制最大宽度增加易读性 */
.archive, .page {
  width: auto !important;
  flex-grow: 1;
}

.page__content {
  width: 100% !important;
  padding-right: 0 !important;
}

/* 2. 字体与全局风格 (模仿陈子轩主页的清爽感) */
body {
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
  color: #333;
  line-height: 1.65;
  -webkit-font-smoothing: antialiased;
}

h1, h2, h3 {
  font-family: "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
  font-weight: 600;
  color: #111;
  border-bottom: 1px solid #eee; /* 简洁的下划线 */
  padding-bottom: 10px;
  margin-top: 1.5em;
}

/* 3. 新闻栏美化 */
.news-container {
  height: 200px;
  overflow-y: auto;
  border: 1px solid #f1f1f1;
  padding: 15px;
  background-color: #fcfcfc;
  border-radius: 8px;
  margin-bottom: 30px;
}

.news-container li {
  margin-bottom: 12px;
  display: flex;
  align-items: flex-start;
  line-height: 1.6;
  font-size: 0.95em;
}

.news-date {
  background-color: #f1f1f1;
  padding: 2px 8px;
  border-radius: 4px;
  font-family: "SFMono-Regular", Consolas, monospace;
  font-size: 0.85em;
  color: #666;
  margin-right: 15px;
  min-width: 75px;
  text-align: center;
  flex-shrink: 0;
}

/* 4. 白色论文链接按钮 (优化圆角与边框) */
.btn-box {
  display: inline-block;
  padding: 4px 14px;
  margin-right: 10px;
  margin-top: 10px;
  border-radius: 20px; /* 圆润的药丸形按钮 */
  background-color: #ffffff;
  color: #444 !important;
  font-size: 0.85em;
  font-weight: 500;
  text-decoration: none !important;
  border: 1px solid #e1e4e8;
  transition: all 0.2s ease-in-out;
  box-shadow: 0 1px 2px rgba(0,0,0,0.05);
}

.btn-box:hover {
  background-color: #f8f9fa;
  border-color: #0366d6;
  color: #0366d6 !important;
  transform: translateY(-1px);
  box-shadow: 0 3px 8px rgba(0,0,0,0.1);
}

/* 移动端适配：手机上恢复单列 */
@media (max-width: 800px) {
  #main {
    flex-direction: column;
    padding: 1em;
  }
  .sidebar {
    width: 100% !important;
    margin-right: 0 !important;
    margin-bottom: 2em;
  }
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