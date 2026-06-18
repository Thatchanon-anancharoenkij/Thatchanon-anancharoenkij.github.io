---
layout: page
permalink: /
---

<link href="https://fonts.googleapis.com/css2?family=Lora:wght@500;600&family=Poppins:wght@300;400;500;600&display=swap" rel="stylesheet">

<style>
  body {
    background-color: #ffffff !important;
    color: #333333 !important; 
  }

  .profile-wrapper {
    font-family: 'Poppins', sans-serif; 
    font-weight: 300;
    line-height: 1.8;
  }
  
  .profile-wrapper h1 {
    font-family: 'Lora', serif; 
    font-weight: 600;
    color: #1a1a1a;
    margin-top: 0;
    font-size: 2.5rem;
    margin-bottom: 1rem;
  }
  
  .profile-wrapper h2 {
    font-family: 'Lora', serif; 
    font-weight: 600;
    color: #1a1a1a;
    margin-top: 2rem;
    margin-bottom: 1rem;
    border-bottom: 1px solid #e0e0e0; 
    padding-bottom: 8px; 
  }

  .profile-wrapper strong {
    font-weight: 500;
    color: #111;
  }
  
  .contact-links a {
    color: #666;
    text-decoration: none;
    margin-right: 20px;
    transition: color 0.2s ease-in-out;
  }
  
  .contact-links a:hover {
    color: #1a1a1a;
  }

  /* Responsive profile layout modifications (จากโค้ดอาจารย์) */
  .responsive-profile-container {
    display: flex;
    flex-direction: column; /* เรียงจากบนลงล่างในมือถือ */
    align-items: center;
    gap: 2rem;
    margin-bottom: 2rem;
  }
  
  .profile-image-col {
    width: 100%;
    max-width: 250px;
    flex-shrink: 0;
  }

  .profile-image-col img {
    width: 100%;
    display: block;
  }

  .profile-content-col {
    flex-grow: 1;
    width: 100%;
  }

  /* Desktop layout overrides (สำหรับจอคอม) */
  @media (min-width: 768px) {
    .responsive-profile-container {
      flex-direction: row; /* เรียงซ้ายขวาในคอม */
      align-items: flex-start;
      margin-left: -20px; 
    }
    .profile-image-col {
      margin-right: 40px;
      position: relative;
      left: -90px;
    }
  }
</style>

<div class="profile-wrapper responsive-profile-container">
  
  <div class="profile-image-col">

    <img src="{{ '/assets/img/prof_pic.jpg' | relative_url }}" class="img-fluid rounded z-depth-1" alt="Profile Picture">
  </div>

  <div class="profile-content-col">
    
    <h1><b>Thatchanon</b> Anancharoenkij</h1>
    <p style="font-size: 0.95rem; color: #666; margin-bottom: 1rem; font-weight: 400;">Ph.D. Student in Applied Statistics | Researcher in Causal Inference and Statistical Learning Theory</p>

    <div class="contact-links" style="font-size: 0.9rem; margin-bottom: 1.5rem;">
      <a href="mailto:thatchanon.anan@gmail.com"><i class="fas fa-envelope"></i> Thatchanon.anan@gmail.com</a>
      <a href="mailto:thatchanon_ananch@cmu.ac.th"><i class="fas fa-envelope"></i> Thatchanon_ananch@cmu.ac.th</a><br>
      
      <div style="margin-top: 5px;">
        <a href="https://github.com/Thatchanon-anancharoenkij" target="_blank" rel="external nofollow noopener"><i class="fab fa-github"></i> GitHub</a>
        <a href="https://orcid.org/0009-0005-7776-0782" target="_blank" rel="external nofollow noopener"><i class="fab fa-orcid"></i> ORCID</a>
        <a href="https://www.linkedin.com/in/thatchanon-anancharoenkij/" target="_blank" rel="external nofollow noopener"><i class="fab fa-linkedin"></i> LinkedIn</a>
        <a href="https://youtube.com/@thatchanonanancharoenkij8102" target="_blank" rel="external nofollow noopener"><i class="fab fa-youtube"></i> YouTube</a>
      </div>
    </div>

    <p>I am a Ph.D. student in applied statistics under the supervision of <a href="https://donlapark.pages.dev/" target="_blank">Dr. Donlapark Ponnoprat</a> at Chiang Mai University. My research focuses on causal inference and statistical learning theory. I am currently focusing on theoretical causal inference. I do not limit my scope to pure theory, but I am deeply interested in applying these causal frameworks across various scientific fields.</p>

    <h2>Education</h2>

    <p><strong>Ph.D. Student in Applied Statistics</strong> | 2024 – Present<br>
    <em>Chiang Mai University, Chiang Mai, Thailand</em><br>
    <strong>Dissertation:</strong> Conditional Counterfactual Mean Embeddings: Doubly Robust Estimation and Learning Rates<br>
    <strong>Advisor:</strong> <a href="https://donlapark.pages.dev/" rel="external nofollow noopener" target="_blank">Dr. Donlapark Ponnoprat</a></p>

    <p><strong>Master of Economics (Statistics and Econometrics)</strong> | 2017 – 2022<br>
    <em>Chiang Mai University, Chiang Mai, Thailand</em><br>
    <strong>Specialization:</strong> Machine Learning and Causal Inference</p>

    <p><strong>Bachelor of Economics (Statistics and Econometrics)</strong> | 2013 – 2016<br>
    <em>Chiang Mai University, Chiang Mai, Thailand</em></p>

    <h2>Publications and Preprints</h2>

    <div style="margin-bottom: 25px;">
      <div style="font-weight: bold;">Conditional Counterfactual Mean Embeddings: Doubly Robust Estimation and Learning Rates</div>
      <div style="margin-bottom: 5px;">
        <a href="https://arxiv.org/abs/2602.04736" rel="external nofollow noopener" target="_blank">[arxiv]</a> 
        <a href="https://github.com/donlap/Conditional-Counterfactual-Mean-Embeddings" rel="external nofollow noopener" target="_blank">[code]</a>
      </div>
      <div>T. Anancharoenkij, D. Ponnoprat</div>
      <div style="font-style: italic;">arXiv, 2026</div>
    </div>

    <div style="margin-bottom: 25px;">
      <div style="font-weight: bold;">Energy Security, Economic Growth, and Poverty Reduction: Empirical Evidence from Selected ASEAN Member States</div>
      <div>T. Anancharoenkij, W. Chinnakum</div>
      <div style="font-style: italic;">Poverty Reduction for Inclusive Sustainable Growth in Developing Asia, pp. 185-209, Springer, Cham, 2021</div>
    </div>

    <h2>Academic Experience</h2>

    <p><strong>Chiang Mai University</strong> | 2024 – Present<br>
    <em>Graduate Teaching Assistant</em><br>
    <strong>Graduate Courses:</strong> Statistical Theory 1, Statistics for Data Science<br>
    <strong>Undergraduate Courses:</strong> Statistical Learning for Data Science 1, Statistical Learning for Data Science 2, Optimization for Statistical Learning</p>

    <h2>Awards & Scholarships</h2>

    <p><strong>Graduate Teaching and Research Assistantship</strong> | 2024 – Present<br>
    <em>Chiang Mai University, Thailand</em></p>

    <p><strong>Graduate Teaching and Research Assistantship</strong> | 2017 – 2022<br>
    <em>Chiang Mai University, Thailand</em></p>

  </div>
</div>

<script>
  document.addEventListener("DOMContentLoaded", function() {
    document.querySelectorAll('.navbar-nav a').forEach(link => {
      const text = link.textContent.trim().toLowerCase();
      // ถ้าเจอคำว่า 'people' หรือ 'submenus' ให้ซ่อนทั้งลิสต์รายการ (li) ที่ครอบอยู่
      if (text === 'people' || text === 'submenus') {
        link.closest('li').style.display = 'none';
      }
    });
  });
</script>


<style>
  body { background-color: #ffffff !important; color: #333333 !important; }
  .profile-wrapper { font-family: 'Poppins', sans-serif; font-weight: 300; line-height: 1.8; }

  .search-toggle, .toggle-container {
    display: none !important;
  }
</style>
