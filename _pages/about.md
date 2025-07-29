---
permalink: /
title: ""
excerpt: ""
author_profile: true
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



🌐欢迎来到我的主页！我是张雨昕，在华中科技大学取得了学士学位（2024）.目前我在华中科技大学攻读硕士学位，导师为[沈卫明院士](http://mse.hust.edu.cn/info/1143/1385.htm)。

🌐Welcome to my homepage! I am Zhang Yuxin (张雨昕). I got my bachelor's degree (2024) from Huazhong University of Science and Technology. I am currently a master's student in Huazhong University of Science and Technology under the supervision of Prof. [Shen Weiming](https://scholar.google.com/citations?hl=zh-CN&user=FuSHsx4AAAAJ&view_op=list_works&sortby=pubdate).

我的研究方向围绕**工业视觉检测**展开，涉及多视图点云的**机器人采集、精简、配准、异常检测**等. 后续研究重点为构建**可实际使用的点云异常检测方法**与更加**通用的3D特征提取器**。除了学术研究，**我有很大的热情和兴趣参与实际项目的落地，目前我的研究成果已经在航空叶片、核电堆芯、汽车自动化产线等场景实现了应用**。🚀🚀🚀

My research focuses on **industrial vision inspection**, involving multi-view point cloud **robot acquisition, simplification, registration, anomaly detection**, etc. Subsequent research focuses on **building a practical point cloud anomaly detection method** and a more **general 3D feature extractor**. In addition, **I have great enthusiasm and interest to participate in practical applications, and my researches have been applied in aviation, nuclear power, automobiles and other scenarios**.🚀🚀🚀

如果对我的学术研究或落地项目感兴趣，任何时候都可以联系我，我非常乐意与您进行交流！😊😊😊我未来十分希望能将学术研究的方法推向实际使用，如果有企业愿意给我提供这个机会，请联系我！🍻

If you are interested in my academic researches or projects, please feel free to contact me at any time, and I will be happy to communicate with you! 😊😊😊I really hope to push academic researches into practical application in the future, so if any enterprise is willing to provide me with this opportunity, please let me know!🍻



# 🔥 News
- *2025.07*: &nbsp;🎉🎉 Our paper addressed [3D Anomaly Detection]() and [Anomaly Detection with Noise]() has been accepted by IEEE SMC 2025.
- *2025.05*: &nbsp;🎉🎉 We released  [Visual Anomaly Detection under Complex View-Illumination Interplay: A Large-Scale Benchmark](https://arxiv.org/abs/2505.10996) for Multi-view and Multi-illumination Anomaly Detection.

# 📝 Publications 


<h2>
  <a href="#Peer-Reviewed Publications"><u>Peer-Reviewed Publications</u></a>&nbsp; <br> 
  <a href="#Manuscripts under Review"><u>Manuscripts under Review</u></a>&nbsp; <br>
</h2>
<span style="color:#b02418; font-weight:bold;">#</span> co-first author | <span style="color:#b02418; font-weight:bold;">*</span> corresponding author <br> 

<h2 id="Peer-Reviewed Publications" style="color: #2c4a88; padding-top: 60px; margin-top: -60px;">Peer-Reviewed Publications</h2>
<ol reversed>

  <li id="FA-Pub6"> 
    Multi-View Reconstruction with Global Context for 3D Anomaly Detection <br> 
    Yihan Sun, <span style="color:#b02418; font-weight:bold;">Yuqi Cheng</span>, Yunkang Cao, Yuxin Zhang, Weiming Shen* <br>
    <i>IEEE International Conference on Systems, Man, and Cybernetics <strong>(IEEE SMC).</strong></i> 2025.
  </li>

  <li id="FA-Pub6"> 
    Levarging Learning Bias for Noisy Anomaly Detection <br> 
    Yuxin Zhang, Yunkang Cao, <span style="color:#b02418; font-weight:bold;">Yuqi Cheng</span>, Yihan Sun, Weiming Shen* <br>
    <i>IEEE International Conference on Systems, Man, and Cybernetics <strong>(IEEE SMC).</strong></i> 2025.
  </li>



  
</ol>


<h2 id="Manuscripts under Review" style="color: #2c4a88; padding-top: 60px; margin-top: -60px;">Manuscripts under Review</h2>
<ol reversed>

  <li id="FA-Manuscript1"> 
    Visual Anomaly Detection under Complex View-Illumination Interplay: A Large-Scale Benchmark <a href="https://arxiv.org/abs/2505.10996">[Paper]</a> <a href="https://github.com/hustCYQ/M2AD">[Code]</a> <br> 
     Yunkang Cao#, <span style="color:#b02418; font-weight:bold;">Yuqi Cheng#</span>, Xiaohao Xu, Yiheng Zhang, Yihan Sun, Yuxiang Tan, Yuxin Zhang, Xiaonan Huang, Weiming Shen* <br>
    <i>Submitted to Neural Information Processing Systems <strong>(NeurIPS 2025)</strong></i>. (Under Review)
  </li>

 

</ol>






# 💻 Projects 




<div class='paper-box'><div class='paper-box-image'><div><div class="badge">MST 2021</div><img src='images/blade0.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Inspection of turbine blade cooling holes

[**Introduction**] <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- An industrial robot is equipped with binocular camera to collect images of the blade, and then the number and aperture of cooling holes are calculated by the distribution property and binocular reconstruction principle.


[**Challenge**] <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Complex blade shape; holes distributed on the curved surface; weak feature.

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">MST 2023</div><img src='images/Stitch0.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">



Panoramic image stitching and dimension calculation for nuclear fuel assemblies.

[**Introduction**] <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- The videos are recorded when pulling the fuel assembly under water. Then the videos are utilized to restore the panoramic images to further calculate the key dimensions.

[**Challenge**] <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Radiation noise, thermal disturbance, weak texture, large-scale object.


</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CASE 2024</div><img src='images/CASE0.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Foreign object recognition

[**Introduction**] <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Instances of machine wear or human error may result in foreign objects falling onto the platform, thereby disrupting operations and posing safety hazards. Consequently, detecting foreign objects on the work platform is framed as an unsupervised anomaly detection challenge.


[**Challenge**] <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Abnormal data are hard to collect, uneven illumination, domain gap.
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Work</div><img src='images/Phone0.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Mobile E-Ink Screen Surface Defect Detection

[**Introduction**] <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- A high-resolution detection device is built to detect abnormal products by using unsupervised anomaly detection technology.


[**Challenge**] <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>

- Tiny defect, illumination dependent, abnormal data are hard to collect.
</div>
</div>





# 🥇 Honors and Awards
- **The First Prize Scholarship**, 2024.

# 🎓📚 Academic Service 
- **Conference Reviewer**: SMC.

# 📖 Educations
                          
- ### *2020.09 - present, Huazhong University of Science and Technology*
  State Key Laboratory of Digital Manufacturing Equipment and Technology                               
  ***M.S.*** in Mechanical Engineering &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **Advisor**: [Weiming Shen](https://scholar.google.com/citations?hl=zh-CN&user=FuSHsx4AAAAJ&view_op=list_works&sortby=pubdate)
 
- ### *2020.09 - 2024.06, Huazhong University of Science and Technology*
  ***B.S.*** in Industrial Engineering &nbsp;&nbsp;&nbsp; 

# 💬 Invited Talks
- *2024.08*, "RAD: A Comprehensive Dataset for Benchmarking the Robustness of Image Anomaly Detection", CASE2024, Italy.

<script type='text/javascript' id='clustrmaps' src='//cdn.clustrmaps.com/map_v2.js?cl=ffffff&w=a&t=tt&d=GEx5UNgsTQZO0HXocUoir2X2jb3xYvYzLS-DAh9BvTY&co=2793de&ct=ffffff'></script>
