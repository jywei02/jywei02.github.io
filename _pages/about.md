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

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Neon Counter — Jianya Wei</title>

  <!-- 科幻风字体 -->
  <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@500&display=swap" rel="stylesheet">

  <style>
    :root{
      --neon-cyan: #00e5ff;   /* 赛博蓝 */
      --neon-violet: #9b5cff; /* 赛博紫 */
      --text-light: #0d1b2a;  /* 浅色主题正文色 */
      --text-dark:  #e6e6ff;  /* 深色主题正文色 */
    }

    .footer-counter{
      font-family: 'Orbitron', sans-serif;
      font-size: 18px;
      text-align: center;
      line-height: 1.6;
      color: var(--text-light);
      margin: 28px 12px 10px;
      letter-spacing: .2px;
    }

    /* 霓虹发光（蓝紫叠加） */
    .footer-counter .glow{
      color: var(--neon-cyan);
      text-shadow:
        0 0 8px  rgba(0,229,255,.85),
        0 0 16px rgba(0,229,255,.75),
        0 0 24px rgba(155,92,255,.65),
        0 0 36px rgba(155,92,255,.55);
      animation: breathe 2.6s ease-in-out infinite;
    }

    @keyframes breathe{
      0%,100%{
        text-shadow:
          0 0 10px rgba(0,229,255,.9),
          0 0 22px rgba(0,229,255,.8),
          0 0 34px rgba(155,92,255,.7),
          0 0 46px rgba(155,92,255,.6);
      }
      50%{
        text-shadow:
          0 0 18px rgba(0,229,255,1),
          0 0 36px rgba(0,229,255,.95),
          0 0 58px rgba(155,92,255,.9),
          0 0 82px rgba(155,92,255,.8);
      }
    }

    /* 深色主题下整体更亮一些 */
    @media (prefers-color-scheme: dark){
      body{ background: #0b0f18; color: var(--text-dark); }
      .footer-counter{ color: var(--text-dark); }
      .footer-counter .glow{
        color: #b3f3ff;
        text-shadow:
          0 0 12px rgba(0,229,255,1),
          0 0 28px rgba(0,229,255,.95),
          0 0 48px rgba(155,92,255,.95),
          0 0 90px rgba(155,92,255,.85);
      }
    }

    /* 用户偏好减少动效时关闭动画 */
    @media (prefers-reduced-motion: reduce){
      .footer-counter .glow{ animation: none; }
    }
  </style>
</head>

<body>
  <!-- 你的正文内容在上面，这里只演示页尾计数器 -->
  <p class="footer-counter">
    Thanks for reading this far! You are visitor
    <span id="busuanzi_value_site_pv" class="glow">0</span>
    to this page.
  </p>

  <!-- 不蒜子统计脚本 -->
  <script src="//busuanzi.ibruce.info/busuanzi/2.3/busuanzi.pure.mini.js"></script>

  <script>
    // 从 0 平滑跳到真实访客数（带缓动），等待 busuanzi 写入后触发
    (function animateCounter(){
      const node = document.getElementById('busuanzi_value_site_pv');
      if (!node) return;

      const tryStart = () => {
        const end = parseInt((node.textContent || '0').replace(/,/g,''), 10);
        if (Number.isFinite(end) && end > 0){
          countUp(node, 0, end, 1400); // 1.4s 完成
          return true;
        }
        return false;
      };

      if (!tryStart()){
        let tries = 0;
        const t = setInterval(() => {
          if (tryStart() || ++tries > 50) clearInterval(t); // 最多轮询 ~5s
        }, 100);
      }

      function countUp(el, start, end, duration){
        const reduce = window.matchMedia('(prefers-reduced-motion: reduce)').matches;
        if (reduce || duration <= 0){ el.textContent = end.toLocaleString(); return; }

        const ease = x => 1 - Math.pow(1 - x, 3); // easeOutCubic
        const t0 = performance.now();

        function frame(now){
          const p = Math.min(1, (now - t0) / duration);
          const v = Math.round(start + (end - start) * ease(p));
          el.textContent = v.toLocaleString();
          if (p < 1) requestAnimationFrame(frame);
        }
        requestAnimationFrame(frame);
      }
    })();
  </script>
</body>
</html>
