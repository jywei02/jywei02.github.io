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

<!-- 页尾计数器（点击数字触发彩纸雨） -->
<p style="text-align:center; font-family: system-ui, -apple-system, Arial; font-size:16px; margin:40px 12px 16px;">
  Thanks for reading this far! You are visitor
  <span id="busuanzi_value_site_pv">0</span>
  to this page.
</p>
<!-- 不蒜子统计 -->
<script src="//busuanzi.ibruce.info/busuanzi/2.3/busuanzi.pure.mini.js"></script>

<style>
  /* 确保无论 busuanzi 如何替换节点，点击样式都在 */
  #busuanzi_value_site_pv {
    cursor: pointer;
    text-decoration: underline;
  }
</style>

<script>
(function(){
  // 事件委托：监听整个文档的点击，只要点到了计数数字就触发
  let cooling = false; // 简单节流避免短时间重复触发
  document.addEventListener('click', function(e){
    const target = e.target;
    if (!target) return;
    if (target.id === 'busuanzi_value_site_pv') {
      if (cooling) return;
      cooling = true; setTimeout(()=> cooling=false, 800);
      confettiRain();
    }
  });

  // ===== 全页彩纸雨 =====
  function confettiRain(){
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

    function resize(){
      const dpr = Math.min(window.devicePixelRatio || 1, 2);
      cvs.width  = Math.round(window.innerWidth * dpr);
      cvs.height = Math.round(window.innerHeight * dpr);
      ctx.setTransform(dpr,0,0,dpr,0,0);
    }
    resize();
    const onResize = () => resize();
    window.addEventListener('resize', onResize);

    const W = window.innerWidth, H = window.innerHeight;
    const COLORS = ['#00e5ff','#9b5cff','#ff66cc','#ffd166','#7cffcb','#ff4d4f','#52c41a'];
    const particles = [];
    const WAVES = 6;                    // 连续几波
    const PER_WAVE = Math.max(80, Math.min(220, Math.floor(W * 0.18)));
    const DURATION = 2600;              // 毫秒
    const GRAVITY = 0.18;               // 重力
    const DRAG = 0.992;                 // 阻尼
    const WIND0 = (Math.random()*0.6-0.3);
    const START_TIME = performance.now();

    function spawnWave(){
      for (let i = 0; i < PER_WAVE; i++){
        const x = Math.random() * W;
        const y = -20 - Math.random() * H * 0.3;
        const w = 6 + Math.random()*8;
        const h = 10 + Math.random()*12;
        const ang = Math.random() * Math.PI * 2;
        const spin = (Math.random()*2-1) * 0.15;
        const vy = 1 + Math.random()*2;
        const vx = (Math.random()*2-1) * 0.8;
        particles.push({
          x, y, w, h,
          vx, vy,
          angle: ang, spin,
          color: COLORS[(Math.random()*COLORS.length)|0],
          tilt: Math.random()*Math.PI,
          life: 1
        });
      }
    }
    for (let k=0; k<WAVES; k++) setTimeout(spawnWave, k*160);

    let raf;
    function tick(now){
      const elapsed = now - START_TIME;
      ctx.clearRect(0,0,cvs.width,cvs.height);

      const wind = WIND0 + Math.sin(now/900) * 0.1;

      for (let p of particles){
        p.vx = (p.vx + wind) * DRAG;
        p.vy = (p.vy + GRAVITY) * DRAG;
        p.x  += p.vx;
        p.y  += p.vy;
        p.angle += p.spin;

        p.tilt += 0.12 + Math.random()*0.04;
        const flip = (Math.cos(p.tilt)+1)/2; // 0~1
        const alpha = 0.9 - (elapsed / DURATION) * 0.4;

        ctx.save();
        ctx.translate(p.x, p.y);
        ctx.rotate(p.angle);
        ctx.fillStyle = rgba(p.color, Math.max(0, alpha) * (0.65 + 0.35*flip));
        ctx.fillRect(-p.w/2, -p.h/2, p.w, p.h);
        ctx.restore();

        if (p.y > H + 40) p.life = 0;
      }

      for (let i=particles.length-1; i>=0; i--){
        if (particles[i].life <= 0) particles.splice(i,1);
      }

      if (elapsed < DURATION || particles.length){
        raf = requestAnimationFrame(tick);
      } else {
        cleanup();
      }
    }
    raf = requestAnimationFrame(tick);

    function rgba(hex, a){
      const c = hex.replace('#',''); const n = parseInt(c,16);
      const r = (n>>16)&255, g=(n>>8)&255, b=n&255;
      return `rgba(${r},${g},${b},${a})`;
    }
    function cleanup(){
      cancelAnimationFrame(raf);
      window.removeEventListener('resize', onResize);
      cvs.remove();
    }
  }
})();
</script>
