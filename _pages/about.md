---
layout: single
title: "About Me"
permalink: /
author_profile: true
---

<style>
/* 1. 整体布局：增加呼吸感 */
body {
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
  line-height: 1.7;
  -webkit-font-smoothing: antialiased;
  background-color: #fdfdfd; /* 极其微弱的米白，增加高级感 */
}

#main {
  max-width: 1140px; /* 经典的学术主页宽度 */
  margin: 40px auto;
  display: flex;
  gap: 50px; /* 增加侧边栏和内容之间的间距 */
}

/* 2. 侧边栏：加入浅色背景块 */
.sidebar {
  width: 280px !important;
  flex-shrink: 0;
  background: rgba(128, 128, 128, 0.03); /* 侧边栏加一层淡淡的底色 */
  padding: 20px;
  border-radius: 12px;
  border: 1px solid rgba(128, 128, 128, 0.05);
}

/* 3. 标题排版：更考究的线条 */
h2 {
  font-size: 1.5em;
  font-weight: 700;
  margin-top: 2em;
  padding-bottom: 12px;
  border-bottom: 2px solid #f1f1f1; /* 加粗线条但颜色变淡 */
  color: #1a1a1a;
  letter-spacing: -0.02em;
}

/* 4. 新闻栏：去框化设计 */
.news-container {
  height: 200px;
  overflow-y: auto;
  border: none; /* 去掉生硬的边框 */
  padding: 5px 0;
  margin-bottom: 40px;
}

.news-container li {
  margin-bottom: 16px;
  display: flex;
  align-items: flex-start;
  font-size: 0.98em;
}

.news-date {
  background-color: #f0f2f5;
  padding: 3px 10px;
  border-radius: 6px;
  font-family: "SFMono-Regular", Consolas, monospace;
  font-size: 0.85em;
  font-weight: 600;
  color: #555;
  margin-right: 18px;
  min-width: 80px;
  text-align: center;
  flex-shrink: 0;
}

/* 5. 论文列表：加大垂直间距 */
.pub-item {
  margin-bottom: 45px;
  padding-left: 5px;
}

.pub-title {
  font-weight: 700;
  font-size: 1.1em;
  line-height: 1.4;
  margin-bottom: 5px;
}

.pub-authors {
  font-size: 0.95em;
  opacity: 0.85;
}

.pub-venue {
  font-style: italic;
  font-size: 0.95em;
  color: #666;
  margin-top: 2px;
}

/* 6. 按钮：更轻盈的阴影 */
.btn-box {
  display: inline-block;
  padding: 4px 16px;
  margin-right: 10px;
  margin-top: 12px;
  border-radius: 25px;
  background-color: transparent; /* 透明背景 */
  color: inherit !important;
  font-size: 0.82em;
  font-weight: 500;
  border: 1px solid rgba(0, 0, 0, 0.1);
  transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
}

.btn-box:hover {
  background-color: #0366d6;
  color: #fff !important;
  border-color: #0366d6;
  transform: translateY(-2px);
  box-shadow: 0 4px 12px rgba(3, 102, 214, 0.2);
}

/* 夜间模式适配：针对 rgba 的微调 */
[data-theme='dark'] .sidebar {
  background: rgba(255, 255, 255, 0.05);
}
[data-theme='dark'] .news-date {
  background-color: rgba(255, 255, 255, 0.1);
  color: #ccc;
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