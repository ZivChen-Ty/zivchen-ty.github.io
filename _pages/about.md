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
/* 动态标签和过滤器按钮的预设样式 */
#filter-container {
  margin: 20px 0;
  display: flex;
  flex-wrap: wrap;
  gap: 8px;
}
.filter-btn {
  padding: 6px 14px;
  border: 1px solid #e1e4e8;
  border-radius: 20px;
  background-color: #f6f8fa;
  color: #586069;
  font-size: 0.85em;
  cursor: pointer;
  transition: all 0.2s ease;
}
.filter-btn:hover {
  background-color: #eaecef;
  color: #24292e;
}
.filter-btn.active {
  background: linear-gradient(135deg, #38ef7d, #11998e);
  color: white;
  border-color: transparent;
  box-shadow: 0 2px 8px rgba(17, 153, 142, 0.3);
}
.badge-container {
  margin-top: 8px;
  margin-bottom: 8px;
  display: flex;
  flex-wrap: wrap;
  gap: 6px;
}
.inner-tag-badge {
  font-size: 0.75em;
  padding: 2px 8px;
  background-color: #f1f3f5;
  color: #495057;
  border-radius: 4px;
  border: 1px solid #e9ecef;
  transition: all 0.2s ease;
}
.inner-tag-badge.active {
  background-color: #e8f5e9;
  color: #2e7d32;
  border-color: #a5d6a7;
  font-weight: bold;
}
.venue-full-name {
  font-size: 0.85em;
  color: #6a737d;
  font-style: italic;
  margin: 4px 0;
}
.paper-link-container {
  margin-top: 8px;
}
.paper-link-btn {
  font-size: 0.85em;
  padding: 2px 8px;
  margin-right: 4px;
  background-color: #fff;
  border: 1px solid #0366d6;
  color: #0366d6 !important;
  border-radius: 4px;
  text-decoration: none !important;
}
.paper-link-btn:hover {
  background-color: #0366d6;
  color: #fff !important;
}
.author-self {
  font-weight: bold;
  text-decoration: underline;
}
.floating-card {
  transition: opacity 0.3s ease;
}
</style>

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

Hi, I am Zhiwei Chen (陈智伟).
=====
I'm currently a Ph.D. student in the [School of Software](https://www.sc.sdu.edu.cn), [Shandong University](https://www.sdu.edu.cn), under the supervision of Prof. [Liqiang Nie](https://liqiangnie.github.io/index.html) and Prof. [Yupeng Hu](https://faculty.sdu.edu.cn/huyupeng1/zh_CN/index.htm). 

My research interests include *multimedia computing, information retrieval, and approximate nearest neighbor search*.

> 🔬 *I am affiliated with the Intelligent Media Research Center (iLearn). Our lab's projects and papers are all open-source [Link](https://github.com/iLearn-Lab), and we welcome your valuable feedback.*

> 🏝️ *I am a strong advocate for open science. All the projects I have been primarily involved in have been fully open-sourced. We warmly invite you to explore our projects, share your feedback, and connect with us for further discussion.*

# <img src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png" alt="GitHub" style="height:30px; width:auto; vertical-align:middle; margin-right:8px;"> Our open source projects
Here's the link to our repo! Feel free to check it out. Any feedback or support are always welcome. Thanks for taking a look! ✨
<br>
<table style="width:100%; border:none; text-align:center; background-color:transparent;">
  <tr style="border:none;">
      <td style="width:30%; border:none; vertical-align:top; padding-top:30px;">
      <img src="../images/logos/combiner-logo.png" alt="COMBINER" style="height:65px; width:auto; border-radius:8px; margin-bottom:8px;"><br>
      <b>COMBINER (TIP'26)</b><br>
      <span style="font-size: 0.9em;">
        <!-- <a href="" target="_blank">Paper</a> |  -->
        <a href="https://lee-zixu.github.io/COMBINER.github.io/" target="_blank">Web</a> | 
        <a href="https://github.com/Lee-zixu/COMBINER" target="_blank">Code</a>
      </span>
    </td>
      <td style="width:30%; border:none; vertical-align:top; padding-top:30px;">
      <img src="../images/logos/tema-logo.png" alt="TEMA" style="height:65px; width:auto; border-radius:8px; margin-bottom:8px;"><br>
      <b>TEMA (ACL'26)</b><br>
      <span style="font-size: 0.9em;">
        <a href="https://arxiv.org/abs/2604.21806" target="_blank">Paper</a> | 
        <a href="https://lee-zixu.github.io/TEMA.github.io/" target="_blank">Web</a> | 
        <a href="https://github.com/Lee-zixu/ACL26-TEMA" target="_blank">Code</a>
      </span>
    </td>
    <td style="width:30%; border:none; vertical-align:top; padding-top:30px;">
      <img src="../images/logos/consep-logo.png" alt="ConeSep" style="height:65px; width:auto; border-radius:8px; margin-bottom:8px;"><br>
      <b>ConeSep (CVPR'26)</b><br>
      <span style="font-size: 0.9em;">
        <a href="https://arxiv.org/abs/2604.20358" target="_blank">Paper</a> | 
        <a href="https://lee-zixu.github.io/ConeSep.github.io/" target="_blank">Web</a> | 
        <a href="https://github.com/Lee-zixu/ConeSep" target="_blank">Code</a>  
      </span>
    </td>  
      </tr>
  <tr style="border:none;">
    <td style="width:30%; border:none; vertical-align:top; padding-top:30px;">
      <img src="../images/logos/airknow-logo.png" alt="Air-Know" style="height:65px; width:auto; border-radius:8px; margin-bottom:8px;"><br>
      <b>Air-Know (CVPR'26)</b><br>
      <span style="font-size: 0.9em;">
        <a href="http://arxiv.org/abs/2604.19386" target="_blank">Paper</a> | 
        <a href="https://zhihfu.github.io/Air-Know.github.io/" target="_blank">Web</a> | 
        <a href="https://github.com/ZhihFu/Air-Know" target="_blank">Code</a>  
      </span>
    </td>  
    <td style="width:30%; border:none; vertical-align:top; padding-top:30px;">
      <img src="../images/logos/intent-logo.png" alt="INTENT" style="height:65px; width:auto; border-radius:8px; margin-bottom:8px;"><br>
      <b>INTENT (AAAI'26)</b><br>
      <span style="font-size: 0.9em;">
        <a href="https://arxiv.org/abs/2604.18051" target="_blank">Paper</a> | 
        <a href="https://zivchen-ty.github.io/INTENT.github.io/" target="_blank">Web</a> | 
        <a href="https://github.com/ZivChen-Ty/INTENT" target="_blank">Code</a> 
      </span>
    </td>  
    <td style="width:30%; border:none; vertical-align:top; padding-top:30px;">
      <img src="../images/logos/habit-logo.png" alt="HABIT" style="height:65px; width:auto; border-radius:8px; margin-bottom:8px;"><br>
      <b>HABIT (AAAI'26)</b><br>
      <span style="font-size: 0.9em;">
        <a href="https://arxiv.org/abs/2604.18037" target="_blank">Paper</a> | 
        <a href="https://lee-zixu.github.io/HABIT.github.io/" target="_blank">Web</a> | 
        <a href="https://github.com/Lee-zixu/HABIT" target="_blank">Code</a> 
      </span>
    </td>
      </tr>
  <tr style="border:none;">
    <td style="width:30%; border:none; vertical-align:top; padding-top:30px;">
      <img src="../images/logos/retrack-logo.png" alt="ReTrack" style="height:65px; width:auto; border-radius:8px; margin-bottom:8px;"><br>
      <b>ReTrack (AAAI'26)</b><br>
      <span style="font-size: 0.9em;">
        <a href="http://arxiv.org/abs/2604.17898" target="_blank">Paper</a> | 
        <a href="https://lee-zixu.github.io/ReTrack.github.io/" target="_blank">Web</a> | 
        <a href="https://github.com/Lee-zixu/ReTrack" target="_blank">Code</a> 
      </span>
    </td>
    <td style="width:30%; border:none; vertical-align:top; padding-top:30px;">
      <img src="../images/logos/hud-logo.png" alt="HUD" style="height:65px; width:auto; border-radius:8px; margin-bottom:8px;"><br>
      <b>HUD (ACM MM'25)</b><br>
      <span style="font-size: 0.9em;">
        <a href="https://arxiv.org/abs/2512.02792" target="_blank">Paper</a> | 
        <a href="https://zivchen-ty.github.io/HUD.github.io/" target="_blank">Web</a> | 
        <a href="https://github.com/ZivChen-Ty/HUD" target="_blank">Code</a>
      </span>
    </td>
    <td style="width:30%; border:none; vertical-align:top; padding-top:30px;">
      <img src="../images/logos/offset-logo.png" alt="OFFSET" style="height:65px; width:auto; border-radius:8px; margin-bottom:8px;"><br>
      <b>OFFSET (ACM MM'25)</b><br>
      <span style="font-size: 0.9em;">
        <a href="https://arxiv.org/abs/2507.05631" target="_blank">Paper</a> | 
        <a href="https://zivchen-ty.github.io/OFFSET.github.io/" target="_blank">Web</a> | 
        <a href="https://github.com/ZivChen-Ty/OFFSET" target="_blank">Code</a>
      </span>
    </td>
      </tr>
  <tr style="border:none;">
    <td style="width:30%; border:none; vertical-align:top; padding-top:30px;">
      <img src="../images/logos/encoder-logo.png" alt="ENCODER" style="height:65px; width:auto; border-radius:8px; margin-bottom:8px;"><br>
      <b>ENCODER (AAAI'25)</b><br>
      <span style="font-size: 0.9em;">
        <a href="https://ojs.aaai.org/index.php/AAAI/article/view/32541" target="_blank">Paper</a> |
        <a href="https://sdu-l.github.io/ENCODER.github.io/" target="_blank">Web</a> | 
        <a href="https://github.com/Lee-zixu/ENCODER" target="_blank">Code</a>
      </span>
    </td>
  </tr>
</table>


# 🔥 News
- *2026.06.02*: &nbsp;🎉🎉 Thrilled to share that our team won the **1st Place**🏅 in the Reasoned-Aware Composed Video Retrieval (CoVR-R) Challenge at the VidLLMs Workshop @ CVPR 2026! Congratulations to all members!
- *2026.05.14*: &nbsp;🎉🎉 Thrilled to share that our team won two **1st places**🏅, two **2nd places**🥈, and one **3rd place**🥉 across multiple Challenges (HD-EPIC, EPIC-KITCHENS, and EgoCross) at the EgoVis Workshop @ CVPR 2026! Congratulations to all members!
- *2026.04.30*: &nbsp;🎉🎉 One paper (COMBINER), was accepted by **TIP 2026**! Thanks to all co-authors!
- *2026.04.07*: &nbsp;🎉🎉 One paper (TEMA), was accepted by **ACL 2026**! Thanks to all co-authors!
- *2026.03.17*: &nbsp;🎉🎉 One paper (STABLE), was accepted by **TKDE 2026**! Congratulations to all co-authors!
- *2026.02.21*: &nbsp;🎉🎉 Two papers (ConeSep, Air-Know), were accepted by **CVPR 2026**! Congratulations to all co-authors!
- *2025.11.08*: &nbsp;🎉🎉 Three papers were accepted by **AAAI 2026**! Thanks and Congratulations to all co-authors!
- *2025.10.18*: &nbsp;🎉🎉 As the core member, our team wins the **Grand Prize** in the CICAS Smart Power Scenario Competition. Congratulations to all team members!
- *2025.07.05*: &nbsp;🎉🎉 Two paper have been accepted by **ACM MM 2025**! Thanks to our co-authors!
- *2024.12.10*: &nbsp;🎉🎉 One paper has been accepted by **AAAI 2025**! Congratulations to our co-authors!
- *2024.09.13*: &nbsp;🎉🎉 I was honored to receive the **Huawei Outstanding Technical Collaboration Award (Top 10 globally per year)**.


# 📝 Publications
<div class="paper-note">⚓️ denotes project leader; 📧 denotes corresponding author.</div>

<div id="publications-wrapper">
<div id="filter-container"></div>

<h1 style="font-size: 1.25em; font-weight: bold; margin-top: 35px; margin-bottom: 15px; border-bottom: 1px solid #eaecef; padding-bottom: 5px;">📝 Selected Publications</h1>

<div class='paper-box floating-card' data-tags="TIP 2026, CCF A, Multimodal Understanding"><div class='paper-box-image'><div><div class="badge">TIP 2026</div><img src='/images/COMBINER-TIP26.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
**COMBINER: Composed Image Retrieval Guided by Attribute-based Neighbor Relations** [[Paper]](https://arxiv.org/abs/2606.04604) [[Project]](https://lee-zixu.github.io/COMBINER.github.io/) [[Code]](https://github.com/Lee-zixu/COMBINER) [[Official Version]](https://ieeexplore.ieee.org/abstract/document/11534406)

[Zixu Li](https://lee-zixu.github.io), [Yupeng Hu](https://faculty.sdu.edu.cn/huyupeng1/zh_CN/index.htm)✉, [***Zhiwei Chen***](https://zivchen-ty.github.io/), [Haokun Wen](https://haokunwen.github.io/), [Xuemeng Song](https://xuemengsong.github.io/), [Liqiang Nie](https://liqiangnie.github.io/index.html)


</div>
</div>

<div class='paper-box floating-card' data-tags="TKDE 2026, CCF A"><div class='paper-box-image'><div><div class="badge">TKDE 2026</div><img src='/images/STABLE-TKDE26.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
**STABLE: Efficient Hybrid Nearest Neighbor Search via Magnitude-Uniformity and Cardinality-Robustness** [[Paper]](https://www.computer.org/csdl/journal/tk/5555/01/11450508/2f5S8Le2iZ2)

Qianyun Yang, [***Zhiwei Chen***](https://zivchen-ty.github.io/), [Yupeng Hu](https://faculty.sdu.edu.cn/huyupeng1/zh_CN/index.htm), [Zixu Li](https://lee-zixu.github.io)†,  [Zhiheng Fu](https://zhihfu.github.io), [Liqiang Nie](https://liqiangnie.github.io/index.html)

</div>
</div>


<div class='paper-box floating-card' data-tags="CVPR 2026, CCF A, Multimodal Understanding, Robustness"><div class='paper-box-image'><div><div class="badge">CVPR 2026</div><img src='images/ConeSep-CVPR26.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**ConeSep: Cone-based Robust Noise-Unlearning Compositional Network for Composed Image Retrieval** [[Paper]](https://arxiv.org/abs/2604.20358) [[Project]](https://lee-zixu.github.io/ConeSep.github.io/) [[Code]](https://github.com/Lee-zixu/ConeSep) [[Official Version]](https://openaccess.thecvf.com/content/CVPR2026/html/Li_ConeSep_Cone-based_Robust_Noise-Unlearning_Compositional_Network_for_Composed_Image_Retrieval_CVPR_2026_paper.html)

[Zixu Li](https://lee-zixu.github.io), [Yupeng Hu](https://faculty.sdu.edu.cn/huyupeng1/zh_CN/index.htm)✉, [***Zhiwei Chen***](https://zivchen-ty.github.io/), [Mingyu Zhang](https://zh-mingyu.github.io/), [Zhiheng Fu](https://zhihfu.github.io), [Liqiang Nie](https://liqiangnie.github.io/index.html)


</div>
</div>



<div class='paper-box floating-card' data-tags="CVPR 2026, CCF A, Multimodal Understanding, Robustness"><div class='paper-box-image'><div><div class="badge">CVPR 2026</div><img src='images/AirKnow-CVPR26.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Air-Know: Arbiter-Calibrated Knowledge-Internalizing Robust Network for Composed Image Retrieval** [[Paper]](http://arxiv.org/abs/2604.19386) [[Project]](https://zhihfu.github.io/Air-Know.github.io/) [[Code]](https://github.com/ZhihFu/Air-Know) [[Official Version]](https://openaccess.thecvf.com/content/CVPR2026/html/Fu_Air-Know_Arbiter-Calibrated_Knowledge-Internalizing_Robust_Network_for_Composed_Image_Retrieval_CVPR_2026_paper.html)

[Zhiheng Fu](https://zhihfu.github.io), [Yupeng Hu](https://faculty.sdu.edu.cn/huyupeng1/zh_CN/index.htm)✉, Qianyun Yang, Shiqi Zhang, [***Zhiwei Chen***](https://zivchen-ty.github.io/), [Zixu Li](https://lee-zixu.github.io)†


</div>
</div>


<div class='paper-box floating-card' data-tags="AAAI 2026, First Author, CCF A, Multimodal Understanding, Robustness"><div class='paper-box-image'><div><div class="badge">AAAI 2026</div><img src='images/INTENT-AAAI26.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**INTENT: Invariance and Discrimination-aware Noise Mitigation for Robust Composed Image Retrieval** [[Paper]](https://arxiv.org/abs/2604.18051) [[Project]](https://zivchen-ty.github.io/INTENT.github.io/) [[Code]](https://github.com/ZivChen-Ty/INTENT) [[Official Version]](https://ojs.aaai.org/index.php/AAAI/article/view/39181) 

[***Zhiwei Chen***](https://zivchen-ty.github.io/), [Yupeng Hu](https://faculty.sdu.edu.cn/huyupeng1/zh_CN/index.htm)✉, [Zhiheng Fu](https://zhihfu.github.io),[Zixu Li](https://lee-zixu.github.io)†, Jiale Huang, [Qinlei Huang](https://windlikeo.github.io/HQL.github.io/), [Yinwei Wei](https://weiyinwei.github.io)

</div>
</div>


<div class='paper-box floating-card' data-tags="ACM MM 2025, First Author, CCF A, Multimodal Understanding"><div class='paper-box-image'><div><div class="badge">ACM MM 2025</div><img src='/images/OFFSET-MM25.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**OFFSET: Segmentation-based Focus Shift Revision for Composed Image Retrieval** [[Paper]](https://arxiv.org/abs/2507.05631) [[Project]](https://zivchen-ty.github.io/OFFSET.github.io/) [[Code]](https://github.com/ZivChen-Ty/OFFSET) [[Official Version]](https://dl.acm.org/doi/10.1145/3746027.3755366) 

[***Zhiwei Chen***](https://zivchen-ty.github.io/), [Yupeng Hu](https://faculty.sdu.edu.cn/huyupeng1/zh_CN/index.htm)✉, [Zixu Li](https://lee-zixu.github.io)†,  [Zhiheng Fu](https://zhihfu.github.io),  [Xuemeng Song](https://xuemengsong.github.io/), [Liqiang Nie](https://liqiangnie.github.io/index.html)

</div>
</div>


<div class='paper-box floating-card' data-tags="ACM MM 2025, First Author, CCF A, Multimodal Understanding"><div class='paper-box-image'><div><div class="badge">ACM MM 2025</div><img src='/images/HUD-MM25.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
**HUD: Hierarchical Uncertainty-Aware Disambiguation Network for Composed Video Retrieval** [[Paper]](https://arxiv.org/abs/2512.02792) [[Project]](https://zivchen-ty.github.io/HUD.github.io/) [[Code]](https://github.com/ZivChen-Ty/HUD) [[Official Version]](https://dl.acm.org/doi/10.1145/3746027.3755445) 
 
[***Zhiwei Chen***](https://zivchen-ty.github.io/), [Yupeng Hu](https://faculty.sdu.edu.cn/huyupeng1/zh_CN/index.htm)✉, [Zixu Li](https://lee-zixu.github.io)†,  [Zhiheng Fu](https://zhihfu.github.io),  [Haokun Wen](https://haokunwen.github.io/), [Weili Guan](https://faculty.hitsz.edu.cn/guanweili)

</div>
</div>

<h1 style="font-size: 1.25em; font-weight: bold; margin-top: 45px; margin-bottom: 15px; border-bottom: 1px solid #eaecef; padding-bottom: 5px;">📝 More Publications</h1>

<div class='paper-box floating-card' data-tags="ACL 2026, CCF A, Multimodal Understanding"><div class='paper-box-image'><div><div class="badge">ACL 2026</div><img src='images/TEMA-ACL26.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**TEMA: Anchor the Image, Follow the Text for Multi-Modification Composed Image Retrieval** [[Paper]](https://arxiv.org/abs/2604.21806) [[Project]](https://lee-zixu.github.io/TEMA.github.io/) [[Code]](https://github.com/Lee-zixu/ACL26-TEMA)

[Zixu Li](https://lee-zixu.github.io), [Yupeng Hu](https://faculty.sdu.edu.cn/huyupeng1/zh_CN/index.htm)✉, [Zhiheng Fu](https://zhihfu.github.io), [***Zhiwei Chen***](https://zivchen-ty.github.io/), [Yongqi Li](https://liyongqi67.github.io/), [Liqiang Nie](https://liqiangnie.github.io/index.html)

</div>
</div> 


<div class='paper-box floating-card' data-tags="AAAI 2026, CCF A, Multimodal Understanding, Robustness"><div class='paper-box-image'><div><div class="badge">AAAI 2026</div><img src='images/ReTrack-AAAI26.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
**ReTrack: Evidence-Driven Dual-Stream Directional Anchor Calibration Network for Composed Video Retrieval** [[Paper]](http://arxiv.org/abs/2604.17898) [[Project]](https://lee-zixu.github.io/ReTrack.github.io/) [[Code]](https://github.com/Lee-zixu/ReTrack) [[Official Version]](https://ojs.aaai.org/index.php/AAAI/article/view/39507) 

[Zixu Li](https://lee-zixu.github.io), [Yupeng Hu](https://faculty.sdu.edu.cn/huyupeng1/zh_CN/index.htm)✉, [***Zhiwei Chen***](https://zivchen-ty.github.io/), [Qinlei Huang](https://windlikeo.github.io/HQL.github.io/), Guozhi Qiu, [Zhiheng Fu](https://zhihfu.github.io), [Meng Liu](https://mengliu1991.github.io)

</div>
</div>

<div class='paper-box floating-card' data-tags="AAAI 2026, CCF A, Multimodal Understanding, Robustness"><div class='paper-box-image'><div><div class="badge">AAAI 2026</div><img src='images/HABIT-AAAI26.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
**HABIT: Chrono-Synergia Robust Progressive Learning Framework for Composed Image Retrieval** [[Paper]](https://arxiv.org/abs/2604.18037) [[Project]](https://lee-zixu.github.io/HABIT.github.io/) [[Code]](https://github.com/Lee-zixu/HABIT) [[Official Version]](https://ojs.aaai.org/index.php/AAAI/article/view/37608) 

[Zixu Li](https://lee-zixu.github.io), [Yupeng Hu](https://faculty.sdu.edu.cn/huyupeng1/zh_CN/index.htm)✉, [***Zhiwei Chen***](https://zivchen-ty.github.io/), Shiqi Zhang, [Qinlei Huang](https://windlikeo.github.io/HQL.github.io/), [Zhiheng Fu](https://zhihfu.github.io), [Yinwei Wei](https://weiyinwei.github.io)


 
</div>
</div>


<div class='paper-box floating-card' data-tags="AAAI 2025, CCF A, Multimodal Understanding"><div class='paper-box-image'><div><div class="badge">AAAI 2025</div><img src='images/ENCODER-AAAI25.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**ENCODER: Entity Mining and Modification Relation Binding for Composed Image Retrieval** [[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/32541) [[Project]](https://sdu-l.github.io/ENCODER.github.io/) [[Code]](https://github.com/Lee-zixu/ENCODER) [[Official Version]](https://ojs.aaai.org/index.php/AAAI/article/view/32541)

[Zixu Li](https://lee-zixu.github.io), [***Zhiwei Chen***](https://zivchen-ty.github.io/), [Haokun Wen](https://haokunwen.github.io/), [Zhiheng Fu](https://zhihfu.github.io), [Yupeng Hu](https://faculty.sdu.edu.cn/huyupeng1/zh_CN/index.htm)✉, [Weili Guan](https://faculty.hitsz.edu.cn/guanweili)


 
</div>
</div>


<div class='paper-box floating-card' data-tags="Preprint, Multimodal Understanding"><div class='paper-box-image'><div><div class="badge">Arxiv 2025</div><img src='/images/FineCIR.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**FineCIR: Explicit Parsing of Fine-Grained Modification Semantics for Composed Image Retrieval** [[Paper]](https://arxiv.org/abs/2503.21309) [[Project]](https://sdu-l.github.io/FineCIR.github.io/)  [[Code]](https://github.com/SDU-L/FineCIR) 

[Zixu Li](https://lee-zixu.github.io),  [Zhiheng Fu](https://zhihfu.github.io),  [Yupeng Hu](https://faculty.sdu.edu.cn/huyupeng1/zh_CN/index.htm)✉,  [***Zhiwei Chen***](https://zivchen-ty.github.io/),  [Haokun Wen](https://haokunwen.github.io/),  [Liqiang Nie](https://liqiangnie.github.io/index.html)
 
</div>
</div>

<div class='paper-box floating-card' data-tags="ACM ToMM 2026, CCF B"><div class='paper-box-image'><div><div class="badge">ACM ToMM 2026</div><img src='/images/REFINE-ToMM26.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
**REFINE: Composed Video Retrieval via Shared and Differential Semantics Enhancement** [[Paper]](https://dl.acm.org/doi/10.1145/3796712) [[Project]](https://sdu-l.github.io/REFINE.github.io/) [[Code]](https://github.com/iLearn-Lab/TOMM26-REFINE) [[Official Version]](https://dl.acm.org/doi/10.1145/3796712) 

[Yupeng Hu](https://faculty.sdu.edu.cn/huyupeng1/zh_CN/index.htm), [Zixu Li](https://lee-zixu.github.io), [***Zhiwei Chen***](https://zivchen-ty.github.io/), [Qinlei Huang](https://windlikeo.github.io/HQL.github.io/), [Zhiheng Fu](https://zhihfu.github.io), [Mingzhu Xu](https://faculty.sdu.edu.cn/xumingzhu/zh_CN/)✉, [Liqiang Nie](https://liqiangnie.github.io/index.html)


 
</div>
</div> 







<h1 style="font-size: 1.25em; font-weight: bold; margin-top: 45px; margin-bottom: 15px; border-bottom: 1px solid #eaecef; padding-bottom: 5px;">📝 Challenge Technical Report</h1>

<div class='paper-box floating-card' data-tags="CVPR 2026, CCF A, Challenge, Egocentric Vision Reasoning"><div class='paper-box-image'><div><div class="badge">CVPR 2026 Challenge 1st</div><img src='images/R3-CVPRW26.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1"> 

**R<sup>3</sup>: Composed Video Retrieval via Reasoning-Guided Recalling and Re-ranking** [[Technical Report]](https://arxiv.org/abs/2606.01113)

[Zixu Li](https://lee-zixu.github.io), [Yupeng Hu](https://faculty.sdu.edu.cn/huyupeng1/zh_CN/index.htm)✉, [Zhiheng Fu](https://zhihfu.github.io),  [***Zhiwei Chen***](https://zivchen-ty.github.io/), [Weili Guan](https://faculty.hitsz.edu.cn/guanweili), [Liqiang Nie](https://liqiangnie.github.io/index.html)

</div>
</div>


<div class='paper-box floating-card' data-tags="CVPR 2026, CCF A, Challenge, Egocentric Vision Reasoning"><div class='paper-box-image'><div><div class="badge">CVPR 2026 Challenge 1st🏅</div><img src='images/TempRet-CVPRW26.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1"> 

**TempRet: Temporal Enhancement and Two-Stage Reranking for CVPR 2026 EPIC-KITCHENS-100 Multi-Instance Retrieval Challenge** [[Technical Report]](https://arxiv.org/abs/2605.24470)

[Zixu Li](https://lee-zixu.github.io), [Yupeng Hu](https://faculty.sdu.edu.cn/huyupeng1/zh_CN/index.htm)✉, [***Zhiwei Chen***](https://zivchen-ty.github.io/), [Zhiheng Fu](https://zhihfu.github.io),  Xiaowei Zhu, [Weili Guan](https://faculty.hitsz.edu.cn/guanweili), [Liqiang Nie](https://liqiangnie.github.io/index.html)

</div>
</div>


<div class='paper-box floating-card' data-tags="CVPR 2026, CCF A, Challenge, Egocentric Vision Reasoning"><div class='paper-box-image'><div><div class="badge">CVPR 2026 Challenge 1st🏅</div><img src='images/EgoAdapt-CVPRW26.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1"> 

**EgoAdapt: A Multi-Scene Egocentric Adaptation Method for CVPR 2026 HD-EPIC VQA Challenge** [[Technical Report]](https://arxiv.org/abs/2605.24500)

[***Zhiwei Chen***](https://zivchen-ty.github.io/), [Yupeng Hu](https://faculty.sdu.edu.cn/huyupeng1/zh_CN/index.htm)✉, [Zixu Li](https://lee-zixu.github.io)†, [Zhiheng Fu](https://zhihfu.github.io),  Guozhi Qiu, [Weili Guan](https://faculty.hitsz.edu.cn/guanweili), [Liqiang Nie](https://liqiangnie.github.io/index.html)

</div>
</div>


<div class='paper-box floating-card' data-tags="CVPR 2026, CCF A, Challenge, Egocentric Vision Reasoning"><div class='paper-box-image'><div><div class="badge">CVPR 2026 Challenge 2nd🥈</div><img src='images/OmniEgo-R2-CVPRW26.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1"> 

**OmniEgo-R<sup>2</sup>: A Routed Reasoning Framework for the 1st Cross-Domain EgoCross Challenge at CVPR 2026** [[Technical Report]](https://arxiv.org/abs/2605.24481)

[***Zixu Li***](https://lee-zixu.github.io), [Zhiwei Chen](https://zivchen-ty.github.io/), [Zhiheng Fu](https://zhihfu.github.io),  Wenbo Wang, [Yupeng Hu](https://faculty.sdu.edu.cn/huyupeng1/zh_CN/index.htm)✉, [Weili Guan](https://faculty.hitsz.edu.cn/guanweili), [Liqiang Nie](https://liqiangnie.github.io/index.html)

</div>  
</div>


<div class='paper-box floating-card' data-tags="CVPR 2026, CCF A, Challenge, Egocentric Vision Reasoning"><div class='paper-box-image'><div><div class="badge">CVPR 2026 Challenge 3rd🥉</div><img src='images/EgoAction-CVPRW26.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1"> 

**EgoAction: Egocentric Action Composition with Reliability-Aware Temporal Fusion for the EPIC-KITCHENS Action Detection Challenge at CVPR 2026** [[Technical Report]](https://arxiv.org/abs/2605.24496)

[Zhiheng Fu](https://zhihfu.github.io),  [***Zixu Li***](https://lee-zixu.github.io)†, [Zhiwei Chen](https://zivchen-ty.github.io/), Fangxu Liu, [Yupeng Hu](https://faculty.sdu.edu.cn/huyupeng1/zh_CN/index.htm)✉, [Weili Guan](https://faculty.hitsz.edu.cn/guanweili), [Liqiang Nie](https://liqiangnie.github.io/index.html)

</div>
</div>

<script>
document.addEventListener('DOMContentLoaded', function() {
  const wrapper = document.getElementById('publications-wrapper');
  if (!wrapper) return;

  const filterContainer = document.getElementById('filter-container');

  const allElements = Array.from(wrapper.children).filter(el => el.id !== 'filter-container');
  const paperBoxes = allElements.filter(el => el.classList.contains('paper-box'));

  allElements.forEach((el, index) => {
    el.dataset.originalOrder = String(index);
  });

  const linkLikeTags = new Set(['Paper', 'PDF', 'Project', 'Project Page', 'Code', 'Blog', 'Website', 'Technical Report']);
  const venueFilterExcludeTags = new Set(['ACL 2026', 'CVPR 2026', 'AAAI 2026', 'ACM MM 2025', 'AAAI 2025', 'Arxiv 2025', 'ICASSP 2025', 'ICASSP 2026', 'TKDE 2026', 'TIP 2026', 'ACM ToMM 2026']);
  const venueFullNames = {
   'ACL 2026': 'The 64th Annual Meeting of the Association for Computational Linguistics (ACL 2026)',
    'CVPR 2026': 'IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR 2026)',
    'AAAI 2026': 'The 40th Annual AAAI Conference on Artificial Intelligence (AAAI 2026)',
    'ACM MM 2025': 'ACM International Conference on Multimedia (ACM MM 2025)',
    'AAAI 2025': 'The 39th Annual AAAI Conference on Artificial Intelligence (AAAI 2025)',
    'Arxiv 2025': 'arXiv preprint (2025)',
    'TKDE 2026': 'IEEE Transactions on Knowledge and Data Engineering (TKDE 2026)',
    'TIP 2026': 'IEEE Transactions on Image Processing (TIP 2026)',
    'ACM ToMM 2026': 'ACM Transactions on Multimedia Computing, Communications, and Applications'
  };
  let tagCounts = {};
  let activeTags = new Set();

  paperBoxes.forEach(box => {
    const tagsAttribute = box.getAttribute('data-tags');
    if (!tagsAttribute) return;
    const tagsList = tagsAttribute.split(',').map(t => t.trim()).filter(t => t);

    const textContainer = box.querySelector('.paper-box-text');
    const linksContainer = box.querySelector('.links');
    if (textContainer && !textContainer.querySelector('.badge-container')) {
      const badgeContainer = document.createElement('div');
      badgeContainer.className = 'badge-container';
      tagsList.filter(tag => !linkLikeTags.has(tag)).forEach(tag => {
        const badge = document.createElement('span');
        badge.className = 'inner-tag-badge';
        badge.textContent = tag;
        badgeContainer.appendChild(badge);
      });

      const paragraphs = textContainer.querySelectorAll('p');
      if (paragraphs.length >= 2) {
        paragraphs[1].insertAdjacentElement('afterend', badgeContainer);
      } else if (linksContainer) {
        textContainer.insertBefore(badgeContainer, linksContainer);
      } else {
        textContainer.appendChild(badgeContainer);
      }
    }

    tagsList.filter(tag => !linkLikeTags.has(tag) && !venueFilterExcludeTags.has(tag)).forEach(tag => tagCounts[tag] = (tagCounts[tag] || 0) + 1);
  });

  textContainerLinkButtons();
  enrichPaperCards();

  const sortedTags = Object.keys(tagCounts).sort();
  if (filterContainer) {
    filterContainer.innerHTML = '';
    sortedTags.forEach(tag => {
      const btn = document.createElement('button');
      btn.className = 'filter-btn';
      btn.textContent = `${tag} (${tagCounts[tag]})`;
      btn.onclick = () => {
        if (activeTags.has(tag)) {
          activeTags.delete(tag);
          btn.classList.remove('active');
        } else {
          activeTags.add(tag);
          btn.classList.add('active');
        }
        filterPapers();
      };
      filterContainer.appendChild(btn);
    });
  }

  function textContainerLinkButtons() {
    paperBoxes.forEach(box => {
      const textContainer = box.querySelector('.paper-box-text');
      if (!textContainer || textContainer.querySelector('.paper-link-container')) return;
      const firstParagraph = textContainer.querySelector('p');
      if (!firstParagraph) return;

      const linkContainer = document.createElement('div');
      linkContainer.className = 'paper-link-container';
      firstParagraph.querySelectorAll('a').forEach(link => {
        link.classList.add('paper-link-btn');
        linkContainer.appendChild(link);
      });

      if (linkContainer.children.length > 0) {
        const badgeContainer = textContainer.querySelector('.badge-container');
        if (badgeContainer) {
          badgeContainer.insertAdjacentElement('afterend', linkContainer);
        } else {
          firstParagraph.insertAdjacentElement('afterend', linkContainer);
        }
      }
    });
  }

  function enrichPaperCards() {
    paperBoxes.forEach(box => {
      const textContainer = box.querySelector('.paper-box-text');
      if (!textContainer) return;
      const paragraphs = textContainer.querySelectorAll('p');
      const titleParagraph = paragraphs[0];
      const authorParagraph = paragraphs[1];
      if (!titleParagraph || !authorParagraph) return;

      const badgeText = (box.querySelector('.badge')?.textContent || '').trim();
      const venueKey = Object.keys(venueFullNames).find(key => badgeText.includes(key));
      if (venueKey && !textContainer.querySelector('.venue-full-name')) {
        const venue = document.createElement('div');
        venue.className = 'venue-full-name';
        venue.textContent = venueFullNames[venueKey];
        titleParagraph.insertAdjacentElement('afterend', venue);
      }

      authorParagraph.classList.add('paper-authors');
      authorParagraph.innerHTML = authorParagraph.innerHTML
        .replace(/\[\*\*\*Zhiwei Chen\*\*\*\]\(([^)]+)\)/g, '<a href="$1" class="primary-gradient-text author-self">Zhiwei Chen</a>')
        .replace(/\[\*\*\*Zhiwei Chen\*\*\*\]/g, '<span class="primary-gradient-text author-self">Zhiwei Chen</span>')
        .replace(/\*\*\*Zhiwei Chen\*\*\*/g, '<span class="primary-gradient-text author-self">Zhiwei Chen</span>')
        .replace(/Zhiwei Chen/g, '<span class="primary-gradient-text author-self">Zhiwei Chen</span>')
        .replace(/\*/g, '<span class="author-star" title="First author">⭐</span>')
        .replace(/†/g, '<span class="author-anchor" title="Project leader">⚓️</span>')
        .replace(/✉/g, '<span class="author-mail" title="Corresponding author">📧</span>');
    });
  }

  function filterPapers() {
    paperBoxes.forEach(box => {
      const boxTagsString = box.getAttribute('data-tags');
      const boxTags = boxTagsString ? boxTagsString.split(',').map(t => t.trim()) : [];
      const isMatched = activeTags.size === 0 || Array.from(activeTags).every(activeTag => boxTags.includes(activeTag));

      box.style.opacity = activeTags.size > 0 && !isMatched ? '0.25' : '1';

      box.querySelectorAll('.inner-tag-badge').forEach(badge => {
        badge.classList.toggle('active', activeTags.has(badge.textContent));
      });
    });

    if (activeTags.size > 0) {
      const sortedElements = [...allElements].sort((a, b) => {
        const aIsBox = a.classList.contains('paper-box');
        const bIsBox = b.classList.contains('paper-box');
        
        let aScore = 1;
        if (aIsBox) {
          const aTags = (a.getAttribute('data-tags') || '').split(',').map(t => t.trim());
          const aMatched = Array.from(activeTags).every(tag => aTags.includes(tag));
          aScore = aMatched ? 0 : 2;
        }

        let bScore = 1;
        if (bIsBox) {
          const bTags = (b.getAttribute('data-tags') || '').split(',').map(t => t.trim());
          const bMatched = Array.from(activeTags).every(tag => bTags.includes(tag));
          bScore = bMatched ? 0 : 2;
        }

        if (aScore !== bScore) {
          return aScore - bScore;
        }
        
        return Number(a.dataset.originalOrder) - Number(b.dataset.originalOrder);
      });
      
      sortedElements.forEach(el => wrapper.appendChild(el));
    } else {
      allElements
        .sort((a, b) => Number(a.dataset.originalOrder) - Number(b.dataset.originalOrder))
        .forEach(el => wrapper.appendChild(el));
    }
  }
});
</script>

</div>

# 🔖 Patent 
- (已授权)一种基于类社交先验的多模态语义表征方法及系统 - 公开号: *CN118194109A* - [[详情]](https://www.baiten.cn/patent/detail/e1407de3ec9711ac14edbf80a87f834d757f2e9a0fdcca47?sc=&fq=&type=&sort=&sortField=&q=陈智伟+山东大学&rows=10#1/CN202410235890.8/detail/abst)

- (已授权)基于实体挖掘和修改关系绑定的组合图像检索方法及系统 - 公开号: *CN120067365A* - [[详情]](https://www.baiten.cn/patent/detail/e1407de3ec9711ac14edbf80a87f834d757f2e9a0fdcca47?sc=&fq=&type=&sort=&sortField=&q=陈智伟+山东大学&rows=10#1/CN202411903224.3/detail/abst)

- 基于特征相似性和属性一致性协同约束的近似近邻混合检索的用户推荐方法及系统 - 公开号: *CN117453991A* - [[详情]](https://www.baiten.cn/patent/detail/e1407de3ec9711ac14edbf80a87f834d757f2e9a0fdcca47?sc=&fq=&type=&sort=&sortField=&q=陈智伟+山东大学&rows=10#1/CN202311201790.5/detail/abst)

- 基于自适应中间粒度聚合网络的组合图像检索方法及系统 - 公开号: *CN120104822A* - [[详情]](https://www.baiten.cn/patent/detail/e1407de3ec9711ac14edbf80a87f834d757f2e9a0fdcca47?sc=&fq=&type=&sort=&sortField=&q=陈智伟+山东大学&rows=10#1/CN202510274983.6/detail/abst)

- 一种基于分割焦点偏移修正的组合图像检索方法及系统 - 公开号: *CN120144812A* - [[详情]](https://www.baiten.cn/patent/detail/e1407de3ec9711ac14edbf80a87f834d757f2e9a0fdcca47?sc=&fq=&type=&sort=&sortField=&q=陈智伟+山东大学&rows=10#1/CN202510143920.7/detail/abst)

- 基于互补性引导解耦的组合图像检索方法及系统 - 公开号: *CN120144811A* - [[详情]](https://www.baiten.cn/patent/detail/e1407de3ec9711ac14edbf80a87f834d757f2e9a0fdcca47?sc=&fq=&type=&sort=&sortField=&q=陈智伟+山东大学&rows=10#1/CN202510142418.4/detail/abst)



# 🏆 Competition
- 1st place 🏅, CVPR VidLLMs Workshop, Reasoned-Aware Composed Video Retrieval Challenge, 2026.
- 1st place 🏅, CVPR EgoVis Workshop, HD-EPIC Challenge, 2026. [[Link]](https://www.codabench.org/competitions/13645/#/results-tab)
- 1st place 🏅, CVPR EgoVis Workshop, EPIC-KITCHENS Challenge-Multi-Instance Retrieval Track, 2026. [[Link]](https://www.codabench.org/competitions/12008/#/results-tab)
- 2nd place 🥈, CVPR EgoVis Workshop, EgoCross Challenge-Source-Limited Track, 2026. [[Link]](https://www.codabench.org/competitions/11279/#/results-tab)
- 2nd place 🥈, CVPR EgoVis Workshop, EgoCross Challenge-Open-Source Track, 2026. [[Link]](https://www.codabench.org/competitions/13868/#/results-tab)
- 3rd place 🥉, CVPR EgoVis Workshop, EPIC-KITCHENS Challenge-Action Detection Track, 2026. [[Link]](https://www.codabench.org/competitions/13830/#/results-tab)


# 🎖 Honors and Awards
- *2025.10*: **Grand Prize** in the CICAS Smart Power Scenario Competition
- *2024.09*: Huawei Outstanding Technical Collaboration Award (***Top 10 globally per year***)
- *2024.06*: Recipient of the Outstanding Graduate Award, Shandong University


# 📖 Educations
- *2024.09 - now*, integrated Master-Ph.D. program in the School of Software, Shandong University.
- *2020.09 - 2024.08*, Bachelor in the School of Software, Shandong University.

# 📃 Services
- Conference PC Member: AAAI, CIKM
- Journal Reviewer: Information Sciences


<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
