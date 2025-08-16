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

<br>

<!-- 简洁计数器（加粗，无动画） -->
<p style="text-align:center; font-family: system-ui, -apple-system, Arial; font-size:16px; font-weight:bold; margin:40px 12px 8px;">
  Thanks for reading this far! You are visitor
  <span id="busuanzi_value_site_pv"></span>
  to this page.
</p>

<!-- 触发彩带雨按钮 -->
<p style="text-align:center; margin:8px 0 24px;">
  <button id="celebrateBtn" style="
    font: 600 14px system-ui, -apple-system, Arial;
    padding: 8px 14px; border-radius: 999px;
    border: 1px solid #d0d7de; background:#f6f8fa; cursor:pointer;
  ">
    click this button to celebrate 🎉
  </button>
</p>

<!-- 不蒜子统计（负责把真实访问量写入上面的 span） -->
<script src="//busuanzi.ibruce.info/busuanzi/2.3/busuanzi.pure.mini.js"></script>

<script>
/* 点击按钮 → 全屏彩带雨 */
(function(){
  const btn = document.getElementById('celebrateBtn');
  if (!btn) return;
  btn.addEventListener('click', confettiRain);

  function confettiRain(){
    // 创建覆盖全屏的画布
    const id = 'confetti-canvas';
    let cvs = document.getElementById(id);
    if (!cvs) {
      cvs = document.createElement('canvas');
      cvs.id = id;
      Object.assign(cvs.style, {
        position:'fixed', inset:0, width:'100vw', height:'100vh',
        zIndex: 9999, pointerEvents:'none'
      });
      document.body.appendChild(cvs);
    }
    const ctx = cvs.getContext('2d');

    // 尺寸 & DPR
    function resize(){
      const dpr = Math.min(window.devicePixelRatio || 1, 2);
      cvs.width  = Math.round(window.innerWidth  * dpr);
      cvs.height = Math.round(window.innerHeight * dpr);
      ctx.setTransform(dpr,0,0,dpr,0,0);
    }
    resize();
    const onResize = () => resize();
    window.addEventListener('resize', onResize, { once:true });

    // 生成彩纸
    const W = window.innerWidth, H = window.innerHeight;
    const COLORS = ['#00e5ff','#9b5cff','#ff66cc','#ffd166','#7cffcb','#ff4d4f','#52c41a'];
    const particles = [];
    const WAVES = 5;                            // 连续几波
    const PER_WAVE = Math.max(80, Math.min(200, Math.floor(W * 0.16)));
    const DURATION = 2600;                      // 毫秒（整体时长）
    const GRAVITY = 0.18, DRAG = 0.992;
    const WIND0 = (Math.random()*0.6-0.3);      // 横向风初值
    const T0 = performance.now();

    function spawnWave(){
      for (let i=0;i<PER_WAVE;i++){
        particles.push({
          x: Math.random()*W,
          y: -20 - Math.random()*H*0.3,
          w: 6 + Math.random()*8,
          h: 10 + Math.random()*12,
          vx: (Math.random()*2-1)*0.8,
          vy: 1 + Math.random()*2,
          angle: Math.random()*Math.PI*2,
          spin: (Math.random()*2-1)*0.15,
          color: COLORS[(Math.random()*COLORS.length)|0],
          tilt: Math.random()*Math.PI,
          life: 1
        });
      }
    }
    for (let k=0;k<WAVES;k++) setTimeout(spawnWave, k*160);

    let raf;
    function tick(now){
      const elapsed = now - T0;
      ctx.clearRect(0,0,cvs.width,cvs.height);
      const wind = WIND0 + Math.sin(now/900)*0.1;

      for (let p of particles){
        p.vx = (p.vx + wind) * DRAG;
        p.vy = (p.vy + GRAVITY) * DRAG;
        p.x  += p.vx; p.y += p.vy;
        p.angle += p.spin;

        p.tilt += 0.12 + Math.random()*0.04;
        const flip = (Math.cos(p.tilt)+1)/2; // 0~1
        const alpha = 0.9 - (elapsed / DURATION)*0.4;

        ctx.save();
        ctx.translate(p.x, p.y);
        ctx.rotate(p.angle);
        ctx.fillStyle = rgba(p.color, Math.max(0,alpha)*(0.65+0.35*flip));
        ctx.fillRect(-p.w/2, -p.h/2, p.w, p.h);
        ctx.restore();

        if (p.y > H + 40) p.life = 0;
      }
      for (let i=particles.length-1; i>=0; i--) if (particles[i].life<=0) particles.splice(i,1);

      if (elapsed < DURATION || particles.length) raf = requestAnimationFrame(tick);
      else cleanup();
    }
    raf = requestAnimationFrame(tick);

    function rgba(hex, a){
      const n = parseInt(hex.slice(1),16);
      return `rgba(${(n>>16)&255},${(n>>8)&255},${n&255},${a})`;
    }
    function cleanup(){
      cancelAnimationFrame(raf);
      cvs.remove();
    }
  }
})();
</script>
