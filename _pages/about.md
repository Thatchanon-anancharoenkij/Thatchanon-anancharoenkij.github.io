---
layout: page
permalink: /
---

<link href="https://fonts.googleapis.com/css2?family=Lora:wght@500;600&family=Poppins:wght@300;400;500;600&display=swap" rel="stylesheet">

<style>
  /* บังคับให้พื้นหลังของเว็บไซต์เป็นสีขาวล้วนเสมอ */
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
  
  /* --- ตั้งค่าหัวข้อ h2 ให้มีเส้นคั่นด้านล่าง --- */
  .profile-wrapper h2 {
    font-family: 'Lora', serif; 
    font-weight: 600;
    color: #1a1a1a;
    margin-top: 2rem;
    margin-bottom: 1rem;
    border-bottom: 1px solid #e0e0e0; /* เพิ่มเส้นคั่นสีเทาอ่อน */
    padding-bottom: 8px; /* เพิ่มระยะห่างระหว่างตัวหนังสือกับเส้นคั่น */
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

  /* --- ตั้งค่าสำหรับการแสดงผลบนมือถือ (หน้าจอแคบ) ให้แสดงผลพอดีกรอบ --- */
  .custom-pic-col {
    margin-left: 0;
    padding-right: 15px;
  }
  .custom-text-col {
    margin-left: 0;
  }

  /* --- ตั้งค่าสำหรับการแสดงผลบนคอมพิวเตอร์ (หน้าจอกว้างกว่า 768px) --- */
  @media (min-width: 768px) {
    .custom-pic-col {
      margin-left: -250px; 
      padding-right: 40px;
    }
    .custom-text-col {
      margin-left: 150px;
    }
  }
</style>

<div class="row profile-wrapper">
  <div class="col-sm-4 custom-pic-col">
    <img src="{{ '/assets/img/prof_pic.jpg' | relative_url }}" class="img-fluid rounded z-depth-1" alt="Profile Picture" style="width: 100%; object-fit: cover; margin-bottom: 20px;">
  </div>

  <div class="col-sm-8 custom-text-col" markdown="1">

  <h1><b>Thatchanon</b> Anancharoenkij</h1>
  <p style="font-size: 0.95rem; color: #666; margin-bottom: 1rem; font-weight: 400;">PhD Student in Applied Statistics | Researcher in Causal Inference and Statistical Learning Theory</p>

  <div class="contact-links" style="font-size: 0.9rem; margin-bottom: 1.5rem;">
    <a href="mailto:Thatchanon.anan@gmail.com"><i class="fas fa-envelope"></i> Thatchanon.anan@gmail.com</a>
    <a href="mailto:Thatchanon_ananch@cmu.ac.th"><i class="fas fa-envelope"></i> Thatchanon_ananch@cmu.ac.th</a><br>
    
    <div style="margin-top: 5px;">
      <a href="https://orcid.org/0009-0005-7776-0782" target="_blank"><i class="fab fa-orcid"></i> ORCID</a>
      <a href="https://www.linkedin.com/in/thatchanon-anancharoenkij/" target="_blank"><i class="fab fa-linkedin"></i> LinkedIn</a>
      <a href="https://youtube.com/@thatchanonanancharoenkij8102" target="_blank"><i class="fab fa-youtube"></i> YouTube</a>
    </div>
  </div>

  I am a PhD student in applied statistics at Chiang Mai University. My research focuses on Causal inference and Statistical learning theory. I am currently focusing on theoretical causal inference. I do not limit my scope to pure theory, but I am deeply interested in applying these causal frameworks across various scientific fields.

  <h2>Education</h2>

  **Ph.D. Student in Applied Statistics** | 2024 – Present  
  *Chiang Mai University, Chiang Mai, Thailand* **Dissertation:** Conditional Counterfactual Mean Embeddings: Doubly Robust Estimation and Learning Rates  
  **Advisor:** [Dr. Donlapark Ponnoprat](https://donlapark.pages.dev/)

  **Master of Economics (Statistics and Econometrics)** | 2017 – 2022  
  *Chiang Mai University, Chiang Mai, Thailand* **Specialization:** Machine Learning and Causal Inference

  **Bachelor of Economics (Statistics and Econometrics)** | 2013 – 2016  
  *Chiang Mai University, Chiang Mai, Thailand*

  <h2>Publications and Preprints</h2>

  **Conditional Counterfactual Mean Embeddings: Doubly Robust Estimation and Learning Rates** Thatchanon Anancharoenkij and Donlapark Ponnoprat  
  *arXiv preprint arXiv:2602.04736* (2026)  
  [arXiv](https://arxiv.org/abs/2602.04736) | [Code](https://github.com/Thatchanon-anancharoenkij/Conditional-Counterfactual-Mean-Embeddings)

  **Energy Security, Economic Growth, and Poverty Reduction: Empirical Evidence from Selected ASEAN Member States** Thatchanon Anancharoenkij and Warattaya Chinnakum  
  *Poverty Reduction for Inclusive Sustainable Growth in Developing Asia*, pp. 185-209. Springer, Cham (2021)

  <h2>Academic Experience</h2>

  **Chiang Mai University** | 2024 – Present  
  *Graduate Teaching Assistant*  
  **Graduate Courses:** 208871: Statistical Theory 1, 229711: Statistics for Data Science  
  **Undergraduate Courses:** 229351: Statistical Learning for Data Science 1 , 229352: Statistical Learning for Data Science 2, 208424: Optimization for Statistical Learning

  <h2>Awards & Scholarships</h2>

  **Graduate Teaching and Research Assistantship** | 2024 – Present  
  *Chiang Mai University, Thailand*

  **Graduate Teaching and Research Assistantship** | 2017 – 2022  
  *Chiang Mai University, Thailand*

  </div>
</div>
