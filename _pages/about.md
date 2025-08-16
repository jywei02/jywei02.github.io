---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
Hi there! I’m a Master’s student in Mechanical Engineering at the University of Washington, Seattle. My work centers on advanced fluid control for artificial kidney systems and high-throughput image processing for aerospace applications.

Under Review
------
A Tristimulus Value Transformation Calibration Method for Spectral Emission Separation in Dual-Dye Pressure-Sensitive Paint  
**Jianya Wei**, Zehua Wang, Jingyi Bai, Dana Dabiri  
<span style="font-family: 'Times New Roman', serif; font-style: italic;">
Sensors and Actuators A: Physical  
</span>
<span style="color: #FFA559;">
Keywords: Pressure-sensitive Paint, Dual-dye Luminescence, Tristimulus Value Transformation  
</span>
<span style="color:#FF5733;">✦ This work was presented at <a href="https://www.caltech.edu/campus-life-events/calendar/galcit-colloquium-378" style="color:#FF5733;">Caltech GALCIT Colloquium</a> in March 2025.  </span>

Publications
------
<span style="color: #40E0D0;">[Effect of thermal cycling on microstructure and adhesion properties of Ti-Zr-V thin films](https://www.sciencedirect.com/science/article/abs/pii/S0169433223029197)  </span><br>
Wenjing Ma, Xiaopeng Xu, **Jianya Wei**, Yonghao Gao, Xiaoqin Ge, Wenli Zhang, Le Fan, Yuanzhi Hong, Tao Huang, Sihui Wang  
<span style="font-family: 'Times New Roman', serif; font-style: italic;">
Applied Surface Science  
</span>
<span style="color: #FFA559;">
Keywords: Ti-Zr-V, NEG Films, Thermal Activation, Adhesion Strength  
</span>

<span style="color: #40E0D0;">[Finite Element Analysis for NEG coated vacuum chamber based on ANSYS Workbench](https://iopscience.iop.org/article/10.1088/1742-6596/2687/8/082025)  </span><br>
Wenjing Ma, Wenli Zhang, Xiaopeng Xu, **Jianya Wei**, Sihui Wang, Xiaoqin Ge, Baoyuan Bian  
<span style="font-family: 'Times New Roman', serif; font-style: italic;">
Journal of Physics: Conference Series  
</span>
<span style="color: #FFA559;">
Keywords: Vacuum Chamber, Thermal-mechanical Analysis, Synchrotron Radiation Facility  
</span>

<span style="color: #40E0D0;">[Vacuum Performance of Activated NEG Coatings under Neon Venting](http://cjvst.cvs.org.cn/en/article/doi/10.13922/j.cnki.cjvst.202305002)  </span><br>
Xiaopeng Xu, Wenjing Ma, **Jianya Wei**, Xiaoqin Ge, Le Fan, Yuanzhi Hong, Le Fan, Yuanzhi Hong, Xiaowei Xia, Tao Huang, Sihui Wang  
<span style="font-family: 'Times New Roman', serif; font-style: italic;">
Chinese Journal of Vacuum Science and Technology  
</span>
<span style="color: #FFA559;">
Keywords: Ti-Zr-V Coatings, Neon Protecting, HALF, Ultra-high Vacuum, Activation  
</span>

<span style="color: #40E0D0;">[Multi-Chamber TiZrV Coating in OFS Copper Vacuum Chamber for HALF](https://www.cpsjournals.cn/article/doi/10.13922/j.cnki.cjvst.202207022?viewType=HTML)  </span><br>
Zhuang Zhao, Wenjing Ma, Xiaoqin Ge, Sihui Wang, Yuanzhi Hong, **Jianya Wei**, Shancai Zhang, Le Fan  
<span style="font-family: 'Times New Roman', serif; font-style: italic;">
Chinese Journal of Vacuum Science and Technology  
</span>
<span style="color: #FFA559;">
Keywords: Multi-chamber Coating, Non-evaporable Getter, Magnetron Sputtering, Particle Accelerator  
</span>

Teaching
------
**Teaching Experiences at UW:**  
• 2025 Spring, ME 230 Kinematics and Dynamics  
• 2025 Winter, ME 323 Thermal Dynamics  

Honors/Awards
------
• Outstanding Undergraduate Scholarship for four consecutive years  
• The First Prize in China Undergraduate Mathematical Contest in Modeling (Rank: 9/272)

<head>
  <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@500&display=swap" rel="stylesheet">
  <style>
    .footer-counter {
      font-family: 'Orbitron', sans-serif;
      font-size: 18px;
      text-align: center;
      color: #ff6600;
      margin: 24px 0 8px;
    }
    /* 轻微发光与呼吸动效 */
    .footer-counter .glow {
      text-shadow: 0 0 6px rgba(255, 102, 0, .6);
      animation: breathe 3s ease-in-out infinite;
    }
    @keyframes breathe {
      0%,100% { text-shadow: 0 0 6px rgba(255,102,0,.6); }
      50%     { text-shadow: 0 0 14px rgba(255,102,0,.8); }
    }
    /* 深色模式换色（可自调） */
    @media (prefers-color-scheme: dark) {
      .footer-counter { color: #ffd199; }
      .footer-counter .glow {
        text-shadow: 0 0 8px rgba(255, 209, 153, .7);
      }
    }
    /* 如果用户偏好减少动效，则关闭动画 */
    @media (prefers-reduced-motion: reduce) {
      .footer-counter .glow { animation: none; }
    }
  </style>
</head>
<body>
  <p class="footer-counter">
    Thanks for reading this far! You are visitor
    <span id="busuanzi_value_site_pv" class="glow">0</span>
    to this page.
  </p>

  <!-- 不蒜子统计 -->
  <script src="//busuanzi.ibruce.info/busuanzi/2.3/busuanzi.pure.mini.js"></script>

  <script>
    // 计数动画：从 0 平滑增加到真实值
    (function animateCounter(){
      const el = document.getElementById('busuanzi_value_site_pv');
      if (!el) return;

      // 观察不蒜子把数字填进去的时刻
      const tryStart = () => {
        const end = parseInt(el.textContent.replace(/,/g, ''), 10);
        if (Number.isFinite(end) && end > 0) {
          countUp(el, 0, end, 1200); // 1.2 秒完成
          return true;
        }
        return false;
      };

      // 如果已经有值，直接开跑；否则轮询几次
      if (!tryStart()) {
        let tries = 0;
        const t = setInterval(() => {
          if (tryStart() || ++tries > 40) clearInterval(t); // 最多等 ~4s
        }, 100);
      }

      function countUp(node, start, end, duration){
        // 遵循“减少动效”偏好
        const reduce = window.matchMedia('(prefers-reduced-motion: reduce)').matches;
        if (reduce || duration <= 0) { node.textContent = end.toLocaleString(); return; }

        const startTime = performance.now();
        const ease = x => 1 - Math.pow(1 - x, 3); // easeOutCubic

        function frame(now){
          const p = Math.min(1, (now - startTime) / duration);
          const val = Math.round(start + (end - start) * ease(p));
          node.textContent = val.toLocaleString();
          if (p < 1) requestAnimationFrame(frame);
        }
        requestAnimationFrame(frame);
      }
    })();
  </script>
</body>
