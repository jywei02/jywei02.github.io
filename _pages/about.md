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

<!-- 页尾计数器 -->
<p style="text-align:center; font-family: system-ui, -apple-system, Arial; font-size:16px; margin:40px 12px 16px;">
  Thanks for reading this far! You are visitor
  <span id="busuanzi_value_site_pv" style="cursor:pointer; text-decoration: underline;">0</span>
  to this page.
</p>
<!-- 不蒜子统计 -->
<script src="//busuanzi.ibruce.info/busuanzi/2.3/busuanzi.pure.mini.js"></script>

<script>
(function(){
  const num = document.getElementById('busuanzi_value_site_pv');
  if (!num) return;

  let cooling = false; // 简单节流，避免疯狂点击

  num.addEventListener('click', (e) => {
    if (cooling) return;
    cooling = true; setTimeout(()=> cooling=false, 800);
    launchFireworks(e.clientX, e.clientY);
  });

  // ====== Canvas 烟花 ======
  function launchFireworks(x, y){
    const id = 'fw-canvas';
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
    resize();
    window.addEventListener('resize', resize, { once:true });

    const rect = cvs.getBoundingClientRect();
    const cx = (x ?? window.innerWidth/2) - rect.left;
    const cy = (y ?? window.innerHeight/2) - rect.top;

    const colors = ['#00e5ff','#9b5cff','#ff66cc','#ffd166','#7cffcb'];
    const particles = [];
    const count = 120;
    for (let i=0;i<count;i++){
      const angle = Math.random() * Math.PI * 2;
      const speed = 2 + Math.random() * 4;
      particles.push({
        x: cx, y: cy,
        vx: Math.cos(angle)*speed,
        vy: Math.sin(angle)*speed,
        life: 60 + Math.random()*20,
        color: colors[(Math.random()*colors.length)|0],
        size: 1 + Math.random()*2
      });
    }

    let frame = 0;
    const g = 0.05;
    const drag = 0.985;

    function tick(){
      ctx.clearRect(0,0,cvs.width,cvs.height);

      ctx.globalCompositeOperation = 'lighter';
      for (let p of particles){
        p.vx *= drag;
        p.vy = p.vy*drag + g;
        p.x += p.vx; p.y += p.vy;
        p.life--;

        const alpha = Math.max(0, Math.min(1, p.life / 60));
        ctx.fillStyle = hexWithAlpha(p.color, alpha);
        ctx.beginPath();
        ctx.arc(p.x, p.y, p.size, 0, Math.PI*2);
        ctx.fill();
      }
      ctx.globalCompositeOperation = 'source-over';

      particles.filter(p=>p.life>0);

      let alive = 0;
      for (let i=particles.length-1; i>=0; i--) {
        if (particles[i].life <= 0) particles.splice(i,1);
        else alive++;
      }

      frame++;
      if (alive > 0 && frame < 180) {
        requestAnimationFrame(tick);
      } else {
        cvs.remove();
      }
    }

    requestAnimationFrame(tick);

    function resize(){
      const dpr = Math.min(window.devicePixelRatio || 1, 2);
      cvs.width = Math.round(window.innerWidth * dpr);
      cvs.height = Math.round(window.innerHeight * dpr);
      ctx.setTransform(dpr,0,0,dpr,0,0);
    }

    function hexWithAlpha(hex, a){
      const c = hex.replace('#','');
      const bigint = parseInt(c,16);
      let r,g,b;
      if (c.length === 6){
        r = (bigint >> 16) & 255;
        g = (bigint >> 8) & 255;
        b = bigint & 255;
      } else { r=g=b=255; }
      return `rgba(${r},${g},${b},${a})`;
    }
  }
})();
</script>
