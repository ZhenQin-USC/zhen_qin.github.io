---
title: "A Fluid Flow‐Based Deep Learning (FFDL) Architecture for Subsurface Flow Systems with Application to Geologic CO<sub>2</sub> Storage"
collection: publications
permalink: /publication/2024-07-03-FFDL-for-CO2-Storage
# excerpt: "This study explores a fluid flow-based deep learning model for predicting CO<sub>2</sub> storage dynamics in geologic formations, enhancing spatiotemporal prediction accuracy and extrapolation capability.
# ![FFDL Model](/files/WRR2025_FFDL/Figure1.jpg)"
# excerpt: "This study explores a fluid flow-based deep learning model for predicting CO<sub>2</sub> storage dynamics in geologic formations, enhancing spatiotemporal prediction accuracy and extrapolation capability.

# <img src='/files/WRR2025_FFDL/Figure1.jpg' alt='FFDL Model' width='500' height='auto'>"

excerpt: "This study explores a fluid flow-based deep learning model for predicting CO<sub>2</sub> storage dynamics in geologic formations, enhancing spatiotemporal prediction accuracy and extrapolation capability.

<div style='text-align: center;'>
  <img src='/files/WRR2025_FFDL/Figure1.jpg' alt='FFDL Model 1' width='500' height='auto' style='margin: 10px; cursor: pointer;' onclick="openModal('/files/WRR2025_FFDL/Figure1.jpg')">
  <img src='/files/WRR2025_FFDL/Figure2.jpg' alt='FFDL Model 2' width='500' height='auto' style='margin: 10px; cursor: pointer;' onclick="openModal('/files/WRR2025_FFDL/Figure2.jpg')">
</div>"
date: 2025-02-01
venue: 'Water Resources Research'
# paperurl: 'http://zhenqin-usc.github.io/files/QinEtAl-Preprint_for_WRR_2024-FFDL_for_GCS_Spatiotemporal_Prediction.pdf'
# citation: 'Your Name, You. (2010). &quot;Paper Title Number 2.&quot; <i>Journal 1</i>. 1(2).'
---

<details>
  <summary style="padding: 10px; cursor: pointer;">
    <b>Plain Language Summary:</b>
  </summary>
  <div style="text-align: justify; margin-top: 10px;">
    This paper introduces a new deep learning model called Fluid Flow-based Deep Learning (FFDL) for predicting how injected CO<sub>2</sub> moves and affects pressure within geological storage formations in carbon capture and storage (CCS) projects. Traditional numerical simulations can accurately model these processes but are computationally intensive, making real-time analysis and decision-making difficult. Existing deep learning models offer faster predictions but may lack interpretability and physical consistency. FFDL addresses these limitations by incorporating physical causality into its architecture through a physics-based encoder and a residual-based processor. This design aims to improve the model's accuracy and ensure that its predictions are more aligned with expected fluid flow behavior. Testing on a field-scale saline aquifer shows that FFDL outperforms standard deep learning models, indicating that it could be a reliable and efficient tool for decision support, optimization, and inverse modeling in CCS operations.
  </div>
</details>

--- 

<details>
  <summary style="padding: 10px; cursor: pointer;">
    <b>Recommended Citation:</b>
  </summary>
  <div style="margin-top: 10px;">
    <pre style="font-size: 12px; background-color: #f5f5f5; padding: 10px; border-radius: 5px; overflow-x: auto;">
@article{qin_fluid_2025,
  title = {A {Fluid} {Flow}-{Based} {Deep} {Learning} ({FFDL}) {Architecture} for {Subsurface} {Flow} {Systems} {With} {Application} to {Geologic} {CO}$_2$ {Storage}},
  volume = {61},
  issn = {0043-1397, 1944-7973},
  doi = {10.1029/2024WR037953},
  number = {1},
  journal = {Water Resources Research},
  author = {Qin, Zhen and Liu, Yingxiang and Zheng, Fangning and Jafarpour, Behnam},
  month = jan,
  year = {2025},
  pages = {e2024WR037953},
}
    </pre>
  </div>
</details>

--- 

<details>
  <summary style="padding: 10px; cursor: pointer;">
  <!-- <summary style="background-color: #f0f0f0; border: 1px solid #ccc; padding: 10px; cursor: pointer;"> -->
    <b>Download Paper:</b>
  </summary>
  <div style="margin-top: 10px;">
    📄 <a href="http://zhenqin-usc.github.io/files/QinEtAl-WRR_2025-FFDL_for_GCS.pdf" target="_blank">Download paper here</a>
    <iframe src="/files/QinEtAl-WRR_2025-FFDL_for_GCS.pdf" width="100%" height="1000px" style="border: none;"></iframe>
  </div>
</details>

---  


<!-- 模态框 -->
<div id="myModal" style="display: none; position: fixed; z-index: 1000; left: 0; top: 0; width: 100%; height: 100%; overflow: auto; background-color: rgba(0,0,0,0.9);">
  <span style="position: absolute; top: 20px; right: 35px; color: white; font-size: 40px; font-weight: bold; cursor: pointer;" onclick="closeModal()">&times;</span>
  <img id="modalImg" style="display: block; margin: 0 auto; max-width: 80%; max-height: 80%; margin-top: 5%;">
</div>

<script>
  // 打开模态框并显示图片
  function openModal(src) {
    const modal = document.getElementById("myModal");
    const modalImg = document.getElementById("modalImg");
    modal.style.display = "block";
    modalImg.src = src;
  }

  // 关闭模态框
  function closeModal() {
    const modal = document.getElementById("myModal");
    modal.style.display = "none";
  }
</script>