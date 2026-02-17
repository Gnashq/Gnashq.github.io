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

I am currently a **Marie Sklodowska-Curie Researcher** and Ph.D. student at the School of Engineering, University of Warwick, Coventry, U.K., supervised by Prof. Xiaowei Zhao. 

My current research focuses on stability analysis (both small- & large-signal) and control design for grid-forming (GFM) inverter-based resources (IBRs). Additionally, I have experience in designs/applications of Imperix-based power converter system, controller hardware-in-the-loop, and rapid-control prototyping. I am proficient in RT-LAB (Opal-RT technologies), RSCAD, PSCAD,  Simulink, and Matlab programming.

# 🔥 News
- *10.11.2025*: &nbsp;🎉 One first-author paper is accepted by **IEEE Transactions on Power Electronics**!
- *21.05.2025*: &nbsp;🎉 Winner of the Poster Presentation at the 12th Annual Postgraduate Research Symposium at the University of Warwick!
- *27.10.2024*: &nbsp;🎉 One first-author paper is accepted by **IEEE Transactions on Power Electronics**!
- *20.10.2024*: &nbsp;🎉 One first-author paper is accepted by **IEEE Transactions on Industrial Electronics**! 
- *08.2024*: &nbsp;🚀 Start a six-month internship at **National Energy System Operator (NESO)**.
- *10.2023*: &nbsp;🙌 Join the University of Warwick as a **Marie Sklodowska-Curie Researcher**. 

# 📝 Publications 

🐣 **Stability Analysis and Control Design for Grid-Forming Inverter-Based Resources**

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TPEL 2025</div><img src='images/TPEL_2025.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Current-Limiting Control Design for Grid-Forming Capability Enhancement of IBRs Under Asymmetric Grid Disturbances](https://wrap.warwick.ac.uk/id/eprint/194691/)

**Qian Liu**, Miao Wang, Mostafa Nick, Cheng Chen, Xiaowei Zhao

- Investigate current-limiting control design for GFM IBRs during asymmetric disturbances. (Application: Virtual Impedance/Direct Current Limiter)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TPEL 2024</div><img src='images/TPEL.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Small-Signal Stability of Sequence-Decomposed Grid-Forming IBRs with DC-Link Voltage Dynamics](https://wrap.warwick.ac.uk/id/eprint/188619/)

**Qian Liu**, Yanchang Liang, Zuan Zhang, Miao Wang, Xiaowei Zhao

- Explore impacts of negative-sequence control in GFM IBRs on system stability. (Application: Photovoltaic/Wind Turbine Generator) 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TIE 2024</div><img src='images/TIE 2024.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Small-Signal Synchronization Stability of Sequence-Decomposed Grid-Forming IBRs](https://wrap.warwick.ac.uk/id/eprint/188541/)

**Qian Liu**, Yanchang Liang, Zuan Zhang, Miao Wang, Xiaowei Zhao

- Explore impacts of negative-sequence control in GFM IBRs on system stability. (Application: Battery Energy Storage System) 
</div>
</div>

🐣 **Fault Modelling and Analysis of Inverter-Based Resources**

- [Fault Analysis of InverterInterfaced RESs Considering Decoupled Sequence Control](https://www.researchgate.net/publication/361506261_Fault_Analysis_of_Inverter-Interfaced_RESs_Considering_Decoupled_Sequence_Control), **Qian Liu**, Ke Jia, Bin Yang, Liming Zheng, Tianshu Bi, **TIE 2023**
- [Analytical Model of InverterInterfaced Renewable Energy Sources for Power System Protection](https://www.researchgate.net/publication/363354639_Analytical_Model_of_Inverter-interfaced_Renewable_Energy_Sources_for_Power_System_Protection), **Qian Liu**, Ke Jia, Bin Yang, Liming Zheng, Tianshu Bi, **TPWRD 2023**
- [Transient Fault Current Analysis of IIRESs Considering Controller Saturation](https://www.researchgate.net/publication/355319933_Transient_Fault_Current_Analysis_of_IIRESs_Considering_Controller_Saturation), Ke Jia, **Qian Liu**, Bin Yang, Liming Zheng, Yu Fang, Tianshu Bi, **TSG 2022**
- [Analytical Calculation of Transient Current from an Inverter-Interfaced Renewable Energy](https://www.researchgate.net/publication/354174625_Analytical_Calculation_of_Transient_Current_from_an_Inverter-Interfaced_Renewable_Energy), Ke Jia, Laiyun Hou, **Qian Liu**, Yu Fang, Liming Zheng, Tianshu Bi, **TPWRS 2022**
- [Review on Renewable Energy Source Fault Characteristics Analysis](https://www.researchgate.net/publication/362322941_Review_on_Renewable_Energy_Source_Fault_Characteristics_Analysis), Tianshu Bi, Bin Yang, Ke Jia, Liming Zheng, **Qian Liu**, Qixun Yang, **CSEE JPES 2022**

🐣 **Power System Protection with Inverter-Based Resources**
- [Faulted Line Section Location in Distribution System with Inverter Interfaced DGs Using Sparse Meters](https://www.researchgate.net/publication/362323038_Faulted_Line_Section_Location_in_Distribution_System_with_Inverter_Interfaced_DGs_Using_Sparse_Meters), Bin Yang, Ke Jia, **Qian Liu**, Liming Zheng, Tianshu Bi, **TSG 2023**
- [Cosine Similarity Based Line Protection for Large Scale Wind Farms Part II—The Industrial Application](https://www.researchgate.net/publication/350594055_Cosine_Similarity_Based_Line_Protection_for_Large_Scale_Wind_Farms_Part_II-The_Industrial_Application), Liming Zheng, Ke Jia, Wenqiang Wu, **Qian Liu**, Tianshu Bi, Qixun Yang, **TIE 2022**

🐣 **Control Parameter Identification for Inverter-Based Resources**
- [Fault Dynamic Response Difference-Based PLL Controller Parameter Identification of IIRESs](https://www.researchgate.net/publication/373381789_Fault_Dynamic_Response_Difference-Based_PLL_Controller_Parameter_Identification_of_IIRESs), Ke Jia, Xinying Jiang, Yang Zhang, Haoyuan Wang, **Qian Liu**, Tianshu Bi, **TSG 2024**
- [Multistage Parameter Identification for Fault Control Parameters of the IIRES](https://www.researchgate.net/publication/372826786_Multi stage_Parameter_Identification_for_Fault_Control_Parameters_of_the_IIRES), Yang Zhang, Ke Jia, Xinying Jiang, Haoyuan Wang, **Qian Liu**, Bin Yang, Tianshu Bi, **TPEL 2023**

# 🎖 Honors and Awards
- *05.2025* Winner of the Poster Presentation at the 12th Annual Postgraduate Research Symposium at the University of Warwick
- *06.2023* Outstanding Graduate of Beijing Municipal Level (Master)
- *11.2022* President Scholarship (Top 0.1%)
- *11.2022* China National Scholarship (Top 1%)
- *11.2021* China National Scholarship (Top 1%)
- *06.2020* Outstanding Graduate of Beijing Municipal Level (Undergraduate)

# 📖 Educations
- *10.2023 - now*, PhD, University of Warwick, Coventry, U.K. 
- *09.2020 - 06.2023*, Master, North China Electric Power University, Beijing, China.
- *09.2016 - 06.2020*, Undergraduate, North China Electric Power University, Beijing, China. 

# 📚 Invited Talks
- *15.01.2025*, "Current Limiting Control of Grid-Forming Inverter-Based Resources", NESO's visit at the University of Warwick
- *23.09.2025*, "Stability Analysis and Control Design of Sequence-Decomposed Grid-Forming Inverters", NGET's visit at the University of Warwick
- *30.08.2025*, "Stability Analysis and Control Design of Sequence-Decomposed Grid-Forming Inverters", School of Engineering, the University of Warwick & School of Electrical Engineering, Xian Jiaotong University, workshop for collaboration
- *28.11.2024*, "Modelling and Control of Sequence-Decomposed Grid-Forming IBRs with CHIL Validation", RT24-UK OPAL-RT’s Regional Conference on Power Systems and Power Electronics Real-Time Simulation in Edinburgh
- *25.10.2024*, "Modelling, Stability Analysis, and Control Design of Grid-Forming Inverter-Based Resources", NESO's visit at the University of Warwick
- *04.09.2024*, "Modelling, Stability Analysis, and Control Design of Sequence-Decomposed Grid-Forming Inverters", Masterclass on Real-Time Hardware-in-the-Loop Experiments for Grid Integration of Offshore Renewable Energy Systems, hosted by the supergen Offshore Renewable Energy(ORE) Hub at the University of Warwick
- *19.07.2024*, "Small-Signal Stability Analysis of Sequence-Decomposed Inverter-Based Resources", OPAL-RT TECHNOLOGIES workshop at Imperial College London

# 👨‍🏫 Teaching & Knowledge Sharing
- *10.2024*, Grid-Forming Inverter-Based Resources, National Energy System Operator (NESO)
- *02.2025*, Fault-Ride Through Control of Grid-Forming Inverter-Based Resources, National Energy System Operator (NESO)

# 🦔 Services
- Reviewer of IEEE Transactions on Power Electronics, Smart Grid, Industrial Electronics, Power Delivery
- Reviewer of Protection and Control of Modern Power Systems

# 💻 Internships
- *08.2024 - 02.2025*, National Energy System Operator (NESO), Warwick, U.K.

# 😀 Visitors
<script type='text/javascript' id='clustrmaps' src='//cdn.clustrmaps.com/map_v2.js?cl=e1f7bc&w=600&t=m&d=zKqY9pIS7Kx7gPQpJxJWX6kB6P3YkUJLNdTn67R9I-I&co=96b2b2&ct=ffefa4&cmo=a8a5c9&cmn=aa2700'></script>
© 2025 Qian Liu. 
