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

  /* --- จัดการ Layout สำหรับหน้าจอคอมพิวเตอร์ (PC) --- */
  .profile-flex-container {
    display: flex; 
    align-items: flex-start; 
    margin-left: -50px; /* ดึงทั้งก้อนไปทางซ้าย */
  }
  
  .profile-pic-container {
    width: 250px; 
    flex-shrink: 0; 
    margin-right: 40px; 
    position: relative; 
    left: -90px; /* ดึงเฉพาะรูปไปทางซ้ายอีก */
  }
  
  .profile-content-container {
    flex-grow: 1;
  }

  /* --- จัดการ Layout สำหรับ iPad (หน้าจอขนาดกลาง) --- */
  @media (max-width: 1024px) {
    .profile-flex-container {
      margin-left: 0; /* เลิกดึงซ้าย ป้องกันตกขอบ */
    }
    .profile-pic-container {
      left: 0; /* เลิกดึงรูป ป้องกันตกขอบ */
      width: 200px; /* ย่อรูปลงนิดหน่อย แต่ยังอยู่ซ้ายเหมือนเดิม */
      margin-right: 25px;
    }
  }

  /* --- จัดการ Layout สำหรับมือถือ (หน้าจอขนาดเล็ก) --- */
  @media (max-width: 768px) {
    .profile-flex-container {
      margin-left: 0;
    }
    .profile-pic-container {
      left: 0;
      width: 120px; /* ย่อรูปให้พอดีจอมือถือ และยังอยู่ซ้ายเสมอ */
      margin-right: 15px;
    }
    .profile-wrapper h1 {
      font-size: 1.8rem; /* ย่อขนาดตัวหนังสือชื่อลง */
    }
    .contact-links a {
      display: block; /* ให้ลิงก์เรียงลงมาเป็นบรรทัดๆ จะได้กดง่ายในมือถือ */
      margin-bottom: 5px;
    }
  }
</style>

<div class="profile-wrapper profile-flex-container">
  
  <!-- ส่วนของรูปภาพ -->
  <div class="profile-pic-container">
    <img src="{{ '/assets/img/prof_pic.jpg' | relative_url }}" class="img-fluid rounded z-depth-1" alt="Profile Picture" style="width: 100%; display: block;">
  </div>

  <!-- ส่วนของเนื้อหา -->
  <div class="profile-content-container" markdown="1">

  <h1><b>Thatchanon</b> Anancharoenkij</h1>
  <p style="font-size: 0.95rem; color: #666; margin-bottom: 1rem; font-weight: 400;">Ph.D. Student in Applied Statistics | Researcher in Causal Inference and Statistical Learning Theory</p>

  <div class="contact-links" style="font-size: 0.9rem; margin-bottom: 1.5rem;">
    <a href="mailto:thatchanon.anan@gmail.com"><i class="fas fa-envelope"></i> Thatchanon.anan@gmail.com</a>
    <a href="mailto:thatchanon_ananch@cmu.ac.th"><i class="fas fa-envelope"></i> Thatchanon_ananch@cmu.ac.th</a><br>
    
    <div style="margin-top: 5px;">
      <a href="https://github.com/Thatchanon-anancharoenkij" target="_blank"><i class="fab fa-github"></i> GitHub</a>
      <a href="https://orcid.org/0009-0005-7776-0782" target="_blank"><i class="fab fa-orcid"></i> ORCID</a>
      <a href="https://www.linkedin.com/in/thatchanon-anancharoenkij/" target="_blank"><i class="fab fa-linkedin"></i> LinkedIn</a>
      <a href="https://youtube.com/@thatchanonanancharoenkij8102" target="_blank"><i class="fab fa-youtube"></i> YouTube</a>
    </div>
  </div>

I am a Ph.D. student in applied statistics under the supervision of [Dr. Donlapark Ponnoprat](https://donlapark.pages.dev/) at Chiang Mai University. My research focuses on causal inference and statistical learning theory. I am currently focusing on theoretical causal inference. I do not limit my scope to pure theory, but I am deeply interested in applying these causal frameworks across various scientific fields.

  <h2>Education</h2>

  **Ph.D. Student in Applied Statistics** | 2024 – Present  
  *Chiang Mai University, Chiang Mai, Thailand*  
  **Dissertation:** Conditional Counterfactual Mean Embeddings: Doubly Robust Estimation and Learning Rates  
  **Advisor:** [Dr. Donlapark Ponnoprat](https://donlapark.pages.dev/)

  **Master of Economics (Statistics and Econometrics)** | 2017 – 2022  
  *Chiang Mai University, Chiang Mai, Thailand*  
  **Specialization:** Machine Learning and Causal Inference

  **Bachelor of Economics (Statistics and Econometrics)** | 2013 – 2016  
  *Chiang Mai University, Chiang Mai, Thailand*

  <h2>Publications and Preprints</h2>
  
<div style="margin-bottom: 25px;">
  <div style="font-weight: bold;">Conditional Counterfactual Mean Embeddings: Doubly Robust Estimation and Learning Rates</div>
  <div style="margin-bottom: 5px;">
    <a href="https://arxiv.org/abs/2602.04736">[arxiv]</a> 
    <a href="https://github.com/donlap/Conditional-Counterfactual-Mean-Embeddings">[code]</a>
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

  **Chiang Mai University** | 2024 – Present  
  *Graduate Teaching Assistant*  
  **Graduate Courses:** Statistical Theory 1, Statistics for Data Science  
  **Undergraduate Courses:** Statistical Learning for Data Science 1, Statistical Learning for Data Science 2, Optimization for Statistical Learning

  <h2>Awards & Scholarships</h2>

  **Graduate Teaching and Research Assistantship** | 2024 – Present  
  *Chiang Mai University, Thailand*

  **Graduate Teaching and Research Assistantship** | 2017 – 2022  
  *Chiang Mai University, Thailand*

  </div>
</div>
