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

I am a second-year M.S. in Computer Science student at the [Umass Amherst](https://www.umass.edu/), advised by Prof. [Chuang Gan](https://people.csail.mit.edu/ganchuang/). I also work closely with Dr. [Frank Dou](https://frank-zy-dou.github.io/) from [MIT CSAIL](https://www.csail.mit.edu/). In addition, I collaborate with  Dr. [Julian Tanke](https://github.com/jutanke), and [takashi Shibuya](https://scholar.google.com/citations?user=XCRO260AAAAJ) at SonyAI on ongoing research projects. I received my B.Eng. degree from Fudan University, where I was fortuante to be advised by [Yaqian Zhou](https://openreview.net/profile?id=~Yaqian_Zhou1). During senior years, I was a research intern at SRIBD, supervised by Prof. [Haizhou Li](https://cde.nus.edu.sg/ece/haizhou-li/).

My research interest lies in human-centered animation. More specifically, I work on character animation, computer graphics, physics-based simulation, and motion estimation. My ultimate goal is to build a neural-based physics engine for simulating human motion as well as human–object–scene interactions — in other words, the system I refer to as [Clotho](https://en.wikipedia.org/wiki/Clotho).


# 🔥 News
- *2025.10*: &nbsp;🎉🎉 One co-first-author paper TalkCuts has been accepted to [Neurips 2025](https://neurips.cc/). 
- *2025.07*: &nbsp;🎉🎉 One paper Rapverse has been accepted to [ICCV 2025](https://iccv.thecvf.com/).
-  

# 📝 Publications 

<!-- ===== Publications ===== -->
<section class="pubs">
  <p class="equal-note">* indicates equal contributions.</p>

  <article class="pub-card">
    <div class="pub-media">
      <!-- 换成你的预览图路径 -->
      <img src="images/talkcuts_teaser.png" alt="TalkCuts teaser">
      <span class="venue-badge">NeurIPS 2025</span>
    </div>

    <div class="pub-body">
      <h3 class="pub-title">
        <a href="https://talkcuts.github.io/" target="_blank" rel="noopener">
          TalkCuts: A Large-Scale Dataset for Multi-Shot Human Speech Video Generation
        </a>
      </h3>

      <p class="pub-authors">
        <span class="author">Jiaben Chen<sup>*</sup></span>,
        <span class="author"><strong>Zixin Wang</strong><sup>*</sup></span>,
        <span class="author">Ailing Zeng</span>,
        <span class="author">Yang Fu</span>,
        <span class="author">Xueyang Yu</span>,
        <span class="author">Siyuan Cen</span>,
        <span class="author">Julian Tanke</span>,
        <span class="author">Yihang Chen</span>,
        <span class="author">Koichi Saito</span>,
        <span class="author">Yuki Mitsufuji</span>,
        <span class="author">Chuang Gan</span>
      </p>

      <p class="pub-venue">
        <em>Neural Information Processing Systems (NeurIPS)</em>, 2025
      </p>

      <p class="pub-links">
        <a href="https://talkcuts.github.io/" target="_blank" rel="noopener">project page</a>
        <span class="sep">/</span>
        <a href="https://arxiv.org/pdf/2510.07249" target="_blank" rel="noopener">paper</a>
        <span class="sep">/</span>
        <a href="https://github.com/UMass-Embodied-AGI/TalkCuts" target="_blank" rel="noopener">code</a>
      </p>

      <p class="pub-abs">
        In this work, we present TalkCuts, a large-scale benchmark dataset designed to
        facilitate the study of multi-shot human speech video generation.
      </p>
    </div>
  </article>
  
  <article class="pub-card">
    <div class="pub-media">
      <!-- 换成你的预览图路径 -->
      <img src="images/talkcuts_teaser.png" alt="TalkCuts teaser">
      <span class="venue-badge">NeurIPS 2025</span>
    </div>

    <div class="pub-body">
      <h3 class="pub-title">
        <a href="https://talkcuts.github.io/" target="_blank" rel="noopener">
          TalkCuts: A Large-Scale Dataset for Multi-Shot Human Speech Video Generation
        </a>
      </h3>

      <p class="pub-authors">
        <span class="author">Jiaben Chen<sup>*</sup></span>,
        <span class="author"><strong>Zixin Wang</strong><sup>*</sup></span>,
        <span class="author">Ailing Zeng</span>,
        <span class="author">Yang Fu</span>,
        <span class="author">Xueyang Yu</span>,
        <span class="author">Siyuan Cen</span>,
        <span class="author">Julian Tanke</span>,
        <span class="author">Yihang Chen</span>,
        <span class="author">Koichi Saito</span>,
        <span class="author">Yuki Mitsufuji</span>,
        <span class="author">Chuang Gan</span>
      </p>

      <p class="pub-venue">
        <em>Neural Information Processing Systems (NeurIPS)</em>, 2025
      </p>

      <p class="pub-links">
        <a href="https://talkcuts.github.io/" target="_blank" rel="noopener">project page</a>
        <span class="sep">/</span>
        <a href="https://arxiv.org/pdf/2510.07249" target="_blank" rel="noopener">paper</a>
        <span class="sep">/</span>
        <a href="https://github.com/UMass-Embodied-AGI/TalkCuts" target="_blank" rel="noopener">code</a>
      </p>

      <p class="pub-abs">
        In this work, we present TalkCuts, a large-scale benchmark dataset designed to
        facilitate the study of multi-shot human speech video generation.
      </p>
    </div>
  </article>
  <article class="pub-card">
  <div class="pub-media">
    <!-- 换成你自己的预览图路径 -->
    <img src="images/rapverse_teaser.png" alt="RapVerse teaser">
    <span class="venue-badge">ICCV 2025</span>
  </div>

  <div class="pub-body">
    <h3 class="pub-title">
      <a href="https://rapverse.github.io/" target="_blank" rel="noopener">
        RapVerse: Coherent Vocals and Whole-Body Motions Generations from Text
      </a>
    </h3>

    <p class="pub-authors">
      <span class="author">Jiaben Chen</span>,
      <span class="author">Xin Yan</span>,
      <span class="author">Yihang Chen</span>,
      <span class="author">Siyuan Cen</span>,
      <span class="author"><strong>Zixin Wang</strong></span>,
      <span class="author">Qinwei Ma</span>,
      <span class="author">Haoyu Zhen</span>,
      <span class="author">Kaizhi Qian</span>,
      <span class="author">Lie Lu</span>,
      <span class="author">Chuang Gan</span>
    </p>

    <p class="pub-venue">
      <em>International Conference on Computer Vision (ICCV)</em>, 2025
    </p>

    <p class="pub-links">
      <a href="https://vis-www.cs.umass.edu/RapVerse/" target="_blank" rel="noopener">project page</a>
      <span class="sep">/</span>
      <a href="https://arxiv.org/abs/2405.20336" target="_blank" rel="noopener">paper</a>
      <span class="sep">/</span>
      <a href="https://github.com/UMass-Embodied-AGI/RapVerse" target="_blank" rel="noopener">code</a>
    </p>

    <p class="pub-abs">
      In this paper, we introduce a challenging task for simultaneously generating 3D holistic
      body motions and singing vocals directly from textual lyrics inputs. To facilitate this,
      we first collect the RapVerse dataset, a large dataset containing synchronous rapping
      vocals, lyrics, and high-quality 3D holistic body meshes.
    </p>
  </div>
</article>
</section>

<!-- ===== Styles ===== -->
<style>
  :root{
    --text:#1f2937;
    --muted:#6b7280;
    --link:#2563eb;
    --badge:#111827;
    --card:#ffffff;
    --border:#e5e7eb;
  }
  .pubs{font-family:system-ui,-apple-system,Segoe UI,Roboto,Arial,sans-serif;color:var(--text)}
  .equal-note{margin:0 0 .75rem 0;font-size:.9rem;color:var(--muted)}
  .pub-card{
    display:grid;
    grid-template-columns: 320px 1fr;
    gap:1.25rem;
    align-items:start;
    padding:1rem;
    border:1px solid var(--border);
    border-radius:12px;
    background:var(--card);
  }
  .pub-media{position:relative}
  .pub-media img{
    width:100%;height:auto;display:block;border-radius:10px;border:1px solid var(--border);
    object-fit:cover;
  }
  .venue-badge{
    position:absolute;left:.5rem;top:.5rem;
    background:var(--badge);color:#fff;font-size:.75rem;
    padding:.25rem .5rem;border-radius:6px;letter-spacing:.2px
  }
  .pub-title{margin:.25rem 0 .5rem 0;font-size:1.25rem;line-height:1.3}
  .pub-title a{color:var(--link);text-decoration:none}
  .pub-title a:hover{text-decoration:underline}
  .pub-authors{margin:.25rem 0;color:var(--text);font-size:.95rem}
  .pub-authors .author{white-space:nowrap}
  .pub-authors sup{font-size:.7em;vertical-align:super}
  .pub-venue{margin:.25rem 0;color:var(--muted)}
  .pub-links{margin:.25rem 0 .5rem 0}
  .pub-links a{color:var(--link);text-decoration:none}
  .pub-links a:hover{text-decoration:underline}
  .pub-links .sep{margin:0 .35rem;color:var(--muted)}
  .pub-abs{margin:.25rem 0 0 0;color:var(--text)}
  /* 响应式 */
  @media (max-width: 720px){
    .pub-card{grid-template-columns:1fr}
  }
</style>


- [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020**
# 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 📖 Educations
- *2024.09 - now*, MSCS student 
- *2015.09 - 2019.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)

# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China.
