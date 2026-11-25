---
layout: splash
author_profile: false
permalink: /
footer: false
---

<style>
.hp-wrap { max-width: 1080px; margin: 0 auto; padding: 0 clamp(1rem, 4vw, 2rem); }
.hp-hero { display: grid; grid-template-columns: 1.1fr 0.95fr; gap: clamp(1.5rem, 4vw, 3rem); align-items: center; padding: clamp(1.5rem, 5vw, 3rem) 0 1rem 0; }

.hp-eyebrow { font-size: 0.8rem; letter-spacing: 0.12em; color: #6b7280; text-transform: uppercase; margin: 0 0 0.6rem 0; }
.hp-name { font-size: clamp(2.1rem, 6vw, 3.1rem); font-weight: 700; color: #111827; margin: 0 0 0.4rem 0; line-height: 1.1; }
.hp-role { font-size: 1.05rem; color: #2c4260; font-weight: 500; margin: 0 0 1rem 0; }
.hp-quote { font-size: 1rem; color: #4b5563; border-left: 2px solid #2c4260; padding-left: 0.85rem; margin: 0 0 1.1rem 0; line-height: 1.7; }
.hp-desc { font-size: 0.98rem; color: #374151; line-height: 1.85; margin: 0 0 1.6rem 0; }

.hp-actions { display: flex; flex-wrap: wrap; gap: 0.75rem; }
.hp-btn { display: inline-block; padding: 0.72rem 1.5rem; border-radius: 6px; font-size: 0.95rem; font-weight: 500; text-decoration: none; transition: background 0.15s ease, color 0.15s ease; }
.hp-btn--solid { background: #2c4260; color: #ffffff; }
.hp-btn--solid:hover { background: #1f2f47; color: #ffffff; }
.hp-btn--ghost { border: 1px solid #cfd6df; color: #2c4260; }
.hp-btn--ghost:hover { background: #eef2f7; color: #2c4260; }
.hp-meta { font-size: 0.84rem; color: #6b7280; margin: 0.9rem 0 0 0; }

.hp-visual img { width: 100%; display: block; border-radius: 12px; border: 1px solid #e5e7eb; box-shadow: 0 8px 28px rgba(20, 40, 70, 0.12); }

.hp-section { padding: 1.2rem 0 0.4rem 0; border-top: 1px solid #e5e7eb; margin-top: 1rem; }
.hp-h2 { font-size: 1.25rem; color: #111827; margin: 0 0 1.1rem 0; }

.hp-stats { display: grid; grid-template-columns: repeat(4, 1fr); gap: 1rem; margin: 0 0 1.6rem 0; }
.hp-stat { padding: 0.9rem 0 0.9rem 0.8rem; border-left: 3px solid #2c4260; }
.hp-stat b { display: block; font-size: 1.35rem; color: #111827; line-height: 1.2; }
.hp-stat span { display: block; font-size: 0.82rem; color: #6b7280; margin-top: 0.25rem; }

.hp-tags { display: flex; flex-wrap: wrap; gap: 0.5rem; margin: 0 0 1.4rem 0; }
.hp-tag { background: #eef2f7; color: #2c4260; border-radius: 999px; padding: 0.34rem 0.85rem; font-size: 0.88rem; }

.hp-note { font-size: 0.84rem; color: #6b7280; line-height: 1.7; margin: 1.4rem 0 2.5rem 0; }

@media (max-width: 767px) {
  .hp-hero { grid-template-columns: 1fr; padding-top: 1rem; }
  .hp-stats { grid-template-columns: repeat(2, 1fr); }
}
</style>

<div class="hp-wrap">

  <div class="hp-hero">
    <div>
      <p class="hp-eyebrow">你好，很高兴遇见你</p>
      <h1 class="hp-name">Aveline</h1>
      <p class="hp-role">言语语言治疗师 · 病理与病理生理学硕士</p>
      <p class="hp-quote">不驰于空想，不骛于虚声。循证康复，赋能沟通与进食。</p>
      <p class="hp-desc">
        面向成人神经源性言语、嗓音、吞咽与认知沟通障碍，为卒中、脑出血、肌萎缩侧索硬化（ALS）、帕金森病（PD）、阿尔茨海默病（AD）患者提供康复评估与干预。
      </p>
      <div class="hp-actions">
        <a class="hp-btn hp-btn--solid" href="{{ site.baseurl }}/about/">了解我的方向</a>
        <a class="hp-btn hp-btn--ghost" href="{{ site.baseurl }}/cv/">查看简历</a>
      </div>
      <p class="hp-meta">上海　·　slpaveline@163.com</p>
    </div>
    <div class="hp-visual">
      <img src="{{ site.baseurl }}/assets/images/rehab-cover.jpg"
           alt="脑部神经与咽喉言语吞咽康复的医学科技插画" width="1200" height="900">
    </div>
  </div>

  <div class="hp-section">
    <h2 class="hp-h2">在做什么</h2>
    <div class="hp-stats">
      <div class="hp-stat"><b>100+</b><span>累计评估人次</span></div>
      <div class="hp-stat"><b>100+</b><span>累计治疗例次</span></div>
      <div class="hp-stat"><b>4 篇</b><span>已发表论文（3 篇共同第一作者）</span></div>
      <div class="hp-stat"><b>8 篇</b><span>健康科普文章</span></div>
    </div>

    <div class="hp-tags">
      <span class="hp-tag">失语症</span>
      <span class="hp-tag">构音障碍</span>
      <span class="hp-tag">吞咽障碍</span>
      <span class="hp-tag">嗓音障碍</span>
      <span class="hp-tag">认知沟通</span>
      <span class="hp-tag">AAC 辅助沟通</span>
    </div>

    <div class="hp-tags">
      <span class="hp-tag">VFSS 吞咽造影</span>
      <span class="hp-tag">SFA</span>
      <span class="hp-tag">VNeST</span>
      <span class="hp-tag">SOVT</span>
      <span class="hp-tag">导管球囊扩张</span>
      <span class="hp-tag">吞咽说话瓣膜</span>
    </div>

    <p class="hp-note">本站内容仅用于学术交流与经验分享，不构成医疗诊断或治疗建议。如有具体病情，请到正规医疗机构就诊评估。</p>
  </div>

</div>
