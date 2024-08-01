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

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. Suspendisse condimentum, libero vel tempus mattis, risus risus vulputate libero, elementum fermentum mi neque vel nisl. Maecenas facilisis maximus dignissim. Curabitur mattis vulputate dui, tincidunt varius libero luctus eu. Mauris mauris nulla, scelerisque eget massa id, tincidunt congue felis. Sed convallis tempor ipsum rhoncus viverra. Pellentesque nulla orci, accumsan volutpat fringilla vitae, maximus sit amet tortor. Aliquam ultricies odio ut volutpat scelerisque. Donec nisl nisl, porttitor vitae pharetra quis, fringilla sed mi. Fusce pretium dolor ut aliquam consequat. Cras volutpat, tellus accumsan mattis molestie, nisl lacus tempus massa, nec malesuada tortor leo vel quam. Aliquam vel ex consectetur, vehicula leo nec, efficitur eros. Donec convallis non urna quis feugiat.

My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>).

# 📖 Educations

- *2022.09 - Present*, *Ph.D* in Electronic science and technology, Shanghai Jiao Tong University, Shanghai, China

  State Key Laboratory of Radio Frequency Heterogeneous Integration

  Supervisor: [*Prof. Junfa Mao*](https://www.sjtu.edu.cn/jdld/20181024/85893.html) (*Academician of CAS*) and [*Prof. Changzhan Gu*]([微波无线感知 (sjtu.edu.cn)](https://changzhan.sjtu.edu.cn/))

- *2018.09 - 2022.06*, *B.S.* in Electromagnetic field and wireless technology, Xidian University, Shaanxi, China
  
  National Key Laboratory of Radar Detection and Sensing
  
  Supervisor: [*Prof. Ying Liu*](https://web.xidian.edu.cn/liuying/), *GPA: 3.96/4.00, Grade: 96.3/100, rank: 1/33* (The highest score since the establishment of the major)

# 🔥 News

- *2024.07*: &nbsp;🎉🎉 I am greatly honored to receive the Jiachi Yang Academician Scholarship. 
- *2024.07*: &nbsp;🎉🎉 One paper (first author) on non-contact vital sign detection for multiple persons at short-range is accepted by ACES-China2024!
- *2024.03*: &nbsp;🎉🎉 One paper (first author) on millimeter-wave radar real-time human positioning system is accepted by ICMMT2024! 
- *2024.03*: &nbsp;🎉🎉 Two papers on millimeter-wave radar motion sensing are accepted by IWS2024! They won the IEEE MTT-S Flash Competition second place and the MVC Competition third place, respectively! Congrats to Zhiwei and Keke!  
- *2024.03*: &nbsp;🎉🎉 One paper on millimeter-wave radar motion sensing is accepted by T-MTT! Congrats to Zhiwei!
- *2024.02*: &nbsp;🎉🎉 One paper on Low-IF doppler radar is accepted by IMS2024! Congrats to Zhiwei!
- *2024.01*: &nbsp;🎉🎉 One paper (first author) on RF leakage suppression for FMCW radar indoor sensing is accepted by T-MTT!

# 📝 Publications

<div style="display: flex; align-items: center; margin-bottom: 20px;">

  <div style="position: relative; flex: 0 0 auto; margin-right: 20px;">
    <img src="../images/TMTT2024.svg" alt="Diagram" style="width: 300px; box-shadow: 10px 10px 30px rgba(0, 0, 0, 0.3);">
    <div style="
      position: absolute;
      top: 0px;
      left: 0px;
      background-color: #00369F; /* 背景颜色 */
      color: white; /* 字体颜色 */
      padding: 2px 2px; /* 内边距 */
      border-radius: 3px; /* 圆角 */
      font-size: 12px; /* 字体大小 */
      font-weight: bold;
    ">T-MTT</div>
  </div>

  <div style="flex: 1;">
    <h2 style="margin: 0;">
      <a href="https://ieeexplore.ieee.org/document/10443219/" style="color: black; text-decoration: none;">
        Target Detection With Short-Range FMCW Radar Based on Time–Frequency Characteristic-Based Leakage Cancellation Technique
      </a>
    </h2>
    <p style="margin: 0;"><strong>Jiayu Zhang</strong>, Zhiwei Zhang, Yuchen Li, Changzhan Gu*, Junfa Mao</p>
    <p style="margin: 0;"><em><strong>IEEE Transactions on Microwave Theory and Techniques, 2024</strong></em></p>
    <ul style="list-style-type: disc; padding-left: 20px;margin-top: 10;">
      <li>This technology can be applied to FMCW radar for short-range detection and RF leakage suppression.</li>
      <li>Utilizing time-frequency Characteristics and equivalent FMCW radar technology can improve SIR and SNR by 30 dB and 17 dB, respectively.</li>
    </ul>
  </div>

</div>



<div style="display: flex; align-items: center; margin-bottom: 20px;">

  <div style="position: relative; flex: 0 0 auto; margin-right: 20px;">
    <img src="../images/TMTT20242.svg" alt="Diagram" style="width: 300px; box-shadow: 10px 10px 30px rgba(0, 0, 0, 0.3);">
    <div style="
      position: absolute;
      top: 0px;
      left: 0px;
      background-color: #00369F; /* 背景颜色 */
      color: white; /* 字体颜色 */
      padding: 2px 2px; /* 内边距 */
      border-radius: 3px; /* 圆角 */
      font-size: 12px; /* 字体大小 */
      font-weight: bold;
    ">T-MTT</div>
  </div>

  <div style="flex: 1;">
    <h2 style="margin: 0;">
      <a href="https://ieeexplore.ieee.org/document/10443219/" style="color: black; text-decoration: none;">
        Target Detection With Short-Range FMCW Radar Based on Time–Frequency Characteristic-Based Leakage Cancellation Technique
      </a>
    </h2>
    <p style="margin: 0;">Zhiwei Zhang, <strong>Jiayu Zhang</strong>, Jingtao Liu, Changzhan Gu*, Junfa Mao</p>
    <p style="margin: 0;"><em><strong>IEEE Transactions on Microwave Theory and Techniques, 2024</strong></em></p>
    <ul style="list-style-type: disc; padding-left: 20px;margin-top: 10;">
      <li>This technology can be applied to enhance motion sensing in millimeter-wave radar.</li>
      <li>Using equivalent FMCW radar technology, the equivalent signal wavelength can be arbitrarily increased or decreased to achieve precise demodulation of large or small displacements. This improves the accuracy of small displacement detection by three times and the accuracy of large displacement detection by ten times.</li>
    </ul>
  </div>

</div>



- <span style="  background-color: #00369F; /* 背景颜色 */  color: #fff; /* 字体颜色 */  padding: 0.5px 5px;  border-radius: 3px;  font-size: 12px;  display: inline-block; ">Aces-China2024</span> Target Localization and Vital Signs Monitoring Based on Spatial-Temporal-Frequency Characteristics With Short-Range FMCW Radar
  **Jiayu Zhang**, Zhiwei Zhang, Yuchen Li, Changzhan Gu\*, Junfa Mao, ***International Applied Computational Electromagnetics Society Symposium (Aces-China), 2024***  <font color='Apricot'>**(Selected for the Student Competition Finalist)**</font>
- <span style="  background-color: #00369F; /* 背景颜色 */  color: #fff; /* 字体颜色 */  padding: 0.5px 5px;  border-radius: 3px;  font-size: 12px;  display: inline-block; ">ICMMT2024</span> Real-Time Human Motion Tracking Technique Based On a 77-GHz FMCW MIMO Radar
  **Jiayu Zhang**, Zhiwei Zhang, Yuchen Li, Changzhan Gu\*, Junfa Mao, ***International Conference on Microwave and Millimeter Wave Technology (ICMMT), 2024***
- <span style="  background-color: #00369F; /* 背景颜色 */  color: #fff; /* 字体颜色 */  padding: 0.5px 5px;  border-radius: 3px;  font-size: 12px;  display: inline-block; ">IWS2024</span> Enhanced Micrometer-Scale Motion Sensing Using a Reconfigurable Virtual CW Algorithm Based on 60 GHz FMCW Radar
  Zhiwei Zhang, **Jiayu Zhang**, Yuchen Li, Changzhan Gu\*, ***IEEE MTT-S International Wireless Symposium (IWS), 2024*** <font color='Apricot'>**(IEEE MTT-S MVC Competition Third Place Winner)**</font>
- <span style="  background-color: #00369F; /* 背景颜色 */  color: #fff; /* 字体颜色 */  padding: 0.5px 5px;  border-radius: 3px;  font-size: 12px;  display: inline-block; ">IWS2024</span> A Novel Data-Based DC Offset Calibration Technique for Millimeter-wave Interferometric Sensing of Weak Displacement Motions
  Keke Zheng, **Jiayu Zhang**, Yuchen Li, Changzhan Gu\*, Junfa Mao, ***IEEE MTT-S International Wireless Symposium (IWS), 2024*** <font color='Apricot'>**(IEEE MTT-S Flash Competition Second Place Winner)**</font>
- <span style="  background-color: #00369F; /* 背景颜色 */  color: #fff; /* 字体颜色 */  padding: 0.5px 5px;  border-radius: 3px;  font-size: 12px;  display: inline-block; ">IMS2024</span> A Cost-Effective Single-Channel Displacement Measurement Technique Without Down-Conversion Using Low-IF Doppler Radar
  Zhiwei Zhang, Fei Tong, **Jiayu Zhang**, Changzhan Gu\*, ***IEEE MTT-S International Microwave Symposium (IMS), 2024***  <font color='Apricot'>**(Selected for the Top50 papers)**</font>
- <span style="  background-color: #00369F; /* 背景颜色 */  color: #fff; /* 字体颜色 */  padding: 0.5px 5px;  border-radius: 3px;  font-size: 12px;  display: inline-block; ">IWS2023</span> Multi-Chirps Convolution Technique for Range Spectrum Signal Enhancement Based on a 60-GHz MIMO FMCW Radar
  **Jiayu Zhang**, Yuchen Li, Wenjie Li, Zhiwei Zhang, Changzhan Gu\*, Junfa Mao, ***IEEE MTT-S International Wireless Symposium (IWS), 2023*** <font color='Apricot'>**(Selected for the MVC Competition Finalist)**</font>
- <span style="  background-color: #00369F; /* 背景颜色 */  color: #fff; /* 字体颜色 */  padding: 0.5px 5px;  border-radius: 3px;  font-size: 12px;  display: inline-block; ">IWS2023</span> Accurate Heart Rate Estimation Based on Multi-Channel Cross-Correlation with a 60-GHz FMCW Radar
  Zhiwei Zhang, **Jiayu Zhang**, Jingtao Liu, Changzhan Gu\*, Junfa Mao, ***IEEE MTT-S International Wireless Symposium (IWS), 2023*** <font color='Apricot'>**(Selected for the Flash Competition Finalist)**</font>
- <span style="  background-color: #00369F; /* 背景颜色 */  color: #fff; /* 字体颜色 */  padding: 0.5px 5px;  border-radius: 3px;  font-size: 12px;  display: inline-block; ">IWS2023</span> A Receiver Reconfigurable Method for Indoor Human Detection with 60GHz MIMO FMCW Radar
  Wenjie Li, Yuchen Li, **Jiayu Zhang**, jingyun Lu, Changzhan Gu\*, Junfa Mao, ***IEEE MTT-S International Wireless Symposium (IWS), 2023*** <font color='Apricot'>**(Selected for the MVC Competition Finalist)**</font>
- <span style="  background-color: #00369F; /* 背景颜色 */  color: #fff; /* 字体颜色 */  padding: 0.5px 5px;  border-radius: 3px;  font-size: 12px;  display: inline-block; ">IMS2023</span> A Feature-based Filtering Algorithm with 60GHz MIMO FMCW Radar for Indoor Detection and Trajectory Tracking
  Wenjie Li, Yuchen Li, **Jiayu Zhang**, Shuqin Dong, jingyun Lu, Changzhan Gu\*, Junfa Mao, ***IEEE MTT-S International Microwave Symposium (IMS), 2023***

# 🎖 Honors and Awards
- *2024.07* Jiachi Yang Academician Scholarship
- *2022.06* Outstanding Graduates of Shaanxi Province
- *2022.06* Campus Talent Ambassador of Xidian University
- *2021.09* First Prize Scholarship and Outstanding Student of Xidian University
- *2020.09* National Scholarship
- *2020.09* First Prize of “2-781” Scholarship at Xidian University
- *2020.09* First Prize Scholarship and Outstanding Student of Xidian University
- *2019.09* First Prize Scholarship and Outstanding Student of Xidian University

# 💻 Academic activities
- *2023.03 - Present*, Academic Director of Shanghai Student Branch, IEEE Microwave Theory and Techniques Society