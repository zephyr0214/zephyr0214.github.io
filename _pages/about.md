---
permalink: /
title: ""
excerpt: ""
author_profile: true
lang: zh
redirect_from: 
  - /about/
  - /about.html
---
{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}
<span class='anchor' id='about-me'></span>
# 👨‍🎓 关于我
我是[东北大学](https://www.neu.edu.cn/)[资源与土木工程学院](http://www.zitu.neu.edu.cn/)测绘工程专业的一名大三本科生。我的 GPA 为 4.165/5.0，在专业 55 名学生中排名第一。我连续两年获得**国家奖学金**，并获得**东北大学优秀学生奖学金**；此外还荣获**东北大学优秀学生标兵**和**东北大学一星志愿者**等称号。

我的研究兴趣包括**多传感器导航、三维重建以及 AI 与 GIS 融合**。本科期间，我以第一作者登记了**两项软件著作权**，并参与发明了**一项发明专利和一项实用新型专利**。

我曾获得[美国大学生数学建模竞赛（MCM/ICM）](https://www.comap.com/contests/mcm-icm)Honorable Mention 奖、[全国大学生测绘学科创新创业智能大赛](https://smt.whu.edu.cn/info/1009/7242.htm)省级一等奖，以及[辽宁省创新方法大赛](https://www.lnast.net/academicSociety/20250819/1142489277037281280.html)省级一等奖。

<span class='anchor' id='educations'></span>
# 📖 教育经历

<div class="timeline-wrap">
  <div class="timeline-item">
    <span class="timeline-time">2023.08 - 至今</span>
    <div class="timeline-content"><strong>东北大学</strong>，资源与土木工程学院，测绘工程专业，工学学士</div>
  </div>
</div>

<span class='anchor' id='research-experience'></span>
# 📚 科研经历
## 2024.11 - 2026.03，基于多传感器的智能车辆监控系统研发与应用
<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">国家级</div>
      <img src='images/re01.png' alt="sym" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">
  [国家级大学生创新创业训练计划项目]

  **项目负责人**

  - 主导基于 Node.js、Vue.js 和 MySQL 的双端（移动端与 Web 端）监控平台全栈开发，集成物联网平台实现实时数据采集与预处理。
  - 获得两项软件著作权（车辆在线应用系统、车辆智能监控系统）和一项实用新型专利（基于 MCU 与多传感器的矿用车辆编组监控装置）。
  </div>
</div>

## 2024.11 - 2026.03，矿区灾害监测预警平台开发
<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">省级</div>
      <img src='images/re02.png' alt="sym" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">
  [省级大学生创新创业训练计划项目]

  **研究人员**

  - 为综合性监测系统搭建数据预处理流程与 API 接口，支撑风险评估、数值模拟、沉降监测与预警分析。
  - 负责前端开发，可视化呈现复杂矿区数据，提升防灾态势感知能力。
  - 参与发明一项发明专利：《一种矿山灾害多因素耦合预警方法、装置、设备及介质》。
  </div>
</div>

## 2025.09 - 2025.12，倾斜摄影三维模型轻量化处理方法研究
[东北大学本科生科研训练项目]

**研究人员**

- 针对倾斜摄影数据量大、渲染效率低的问题，复现并改进 QEM（Quadric Error Metrics）简化算法。
- 引入曲率约束与边界保护机制，在保持视觉保真度的同时优化三维模型几何与纹理。
- 基于 C++、OSG（OpenSceneGraph）和 Qt 开发了集成式轻量化处理工具原型。

## 2026.03 - 2026.06，基于多源模型融合的数字孪生场景构建与系统开发
[东北大学本科生科研训练项目]

**研究人员**

- 基于 Three.js 搭建初步 WebGIS 平台，实现数字孪生场景中多源模型的融合展示。
- 实现交互式可视化功能，支持异构空间数据的无缝展示与操作。

<span class='anchor' id='software-copyrights'></span>
# 💻 软件著作权
- **Yang Zhang**, Yuxing Duan, Yutong Liu, Meng Zhang, Defu Che（2025）。[*智能车辆监控系统（V1.0.0）*](/files/software01.pdf)[计算机软件]。中华人民共和国国家版权局，登记号：2025SR1943851。
- **Yang Zhang**, Yuxing Duan, Chaoyang Yan, Meng Zhang, Defu Che（2025）。[*车辆在线服务应用系统（V1.0.0）*](/files/software02.pdf)[计算机软件]。中华人民共和国国家版权局，登记号：2025SR1943800。

<span class='anchor' id='patents'></span>
# 💡 专利
- Yuxing Duan、**Yang Zhang**、Haochen Liu、Chunsheng Ji、Defu Che（2025）。[*基于微控制器与多传感器的矿用车辆编组监控装置*](/files/patent01.pdf)。实用新型专利，专利号：ZL 2025 2 1843307.8。
- Zibo Wen、Yingjie Chen、Meng Ao、Lianhuan Wei、Yuan Dai、**Yang Zhang**、Shanjun Liu（2026）。[*一种矿山灾害多因素耦合预警方法、装置、设备及介质*](/files/patent02.pdf)。发明专利，专利号：ZL 2026 1 0038773.1。

<span class='anchor' id='honors-and-awards'></span>
# 🏆 荣誉奖项
## 奖学金
<div class="timeline-wrap">
  <div class="timeline-item">
    <span class="timeline-time">2025.09</span>
    <div class="timeline-content">
      <strong>2024-2025 学年国家奖学金</strong>
      <br>东北大学优秀学生二等奖学金
    </div>
  </div>
  <div class="timeline-item">
    <span class="timeline-time">2024.09</span>
    <div class="timeline-content">
      <strong>2023-2024 学年国家奖学金</strong>
      <br>东北大学优秀学生一等奖学金
    </div>
  </div>
</div>

<p align="center"><img src="/images/honor01.jpg" alt="奖学金与荣誉" width="80%"></p>

## 荣誉称号
<div class="timeline-wrap">
  <div class="timeline-item">
    <span class="timeline-time">2025.09</span>
    <div class="timeline-content"><strong>东北大学优秀学生标兵</strong></div>
  </div>
  <div class="timeline-item">
    <span class="timeline-time">2024.11</span>
    <div class="timeline-content"><strong>东北大学一星志愿者</strong></div>
  </div>
  <div class="timeline-item">
    <span class="timeline-time">2024.09</span>
    <div class="timeline-content"><strong>东北大学优秀学生</strong></div>
  </div>
</div>

## 竞赛获奖

<div class="timeline-wrap">
  <div class="timeline-item">
    <span class="timeline-time">2026.8</span>
    <div class="timeline-content"><strong>国家特等奖</strong>，全国大学生测绘学科创新创业智能大赛</div>
  </div>
  <div class="timeline-item">
    <span class="timeline-time">2025.11</span>
    <div class="timeline-content"><strong>辽宁省一等奖</strong>，辽宁省创新方法大赛</div>
  </div>
  <div class="timeline-item">
    <span class="timeline-time">2025.10</span>
    <div class="timeline-content"><strong>辽宁省二等奖</strong>，全国大学生数学建模竞赛</div>
  </div>
  <div class="timeline-item">
    <span class="timeline-time">2025.05</span>
    <div class="timeline-content"><strong>Honorable Mention</strong>，美国大学生数学建模竞赛（MCM/ICM）</div>
  </div>
</div>

<p align="center"><img src="/images/honor02.jpg" alt="竞赛获奖" width="80%"></p>

## 其他经历
<div class="timeline-wrap">
  <div class="timeline-item">
    <span class="timeline-time">2023.09 - 至今</span>
    <div class="timeline-content"><strong>班级学习委员</strong>，测绘工程 2301 班</div>
  </div>
  <div class="timeline-item">
    <span class="timeline-time">2023.09 - 2025.07</span>
    <div class="timeline-content"><strong>宣传设计部部长</strong>，学生志愿者协会</div>
  </div>
  <div class="timeline-item">
    <span class="timeline-time">2024.07 - 2025.07</span>
    <div class="timeline-content"><strong>宣传部部员</strong>，学院党校</div>
  </div>
</div>

<p align="center"><img src="/images/honor03.png" alt="其他经历" width="80%"></p>
