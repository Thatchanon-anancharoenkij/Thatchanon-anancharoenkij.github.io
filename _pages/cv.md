---
layout: page
permalink: /cv/
title: CV
nav: true
nav_order: 5
---
<style>
  .navbar-nav .dropdown, 
  .navbar-nav .nav-item.dropdown,
  .navbar-nav li:has(a[href*="dropdown"]),
  .navbar-nav li:has(a[class*="dropdown"]) { 
    display: none !important; 
  }

  #search-toggle .nav-link {
    font-size: 0 !important; 
  }
  
  #search-toggle .nav-link::before {
    content: "Search";
    font-size: 1rem !important; 
    margin-right: 5px;
    vertical-align: middle;
  }

  #search-toggle .nav-link i, 
  #search-toggle .nav-link svg {
    font-size: 1.2rem !important; 
    vertical-align: middle;
  }
</style>

<div style="text-align: center; margin-bottom: 30px;">
  <a href="{{ '/assets/pdf/cv.pdf' | relative_url }}" target="_blank" style="text-decoration: none; font-weight: 500; font-size: 1.1rem;">
    <i class="fas fa-file-pdf" style="color: #d32f2f;"></i> Download CV (PDF)
  </a>
</div>

<div style="width: 100%; height: 850px; border: 1px solid #ccc; border-radius: 8px; overflow: hidden;">
  <iframe src="{{ '/assets/pdf/cv.pdf' | relative_url }}" width="100%" height="100%" style="border: none;">
    <p>Your browser does not support PDF viewing. You can <a href="{{ '/assets/pdf/cv.pdf' | relative_url }}">click here to download the file</a> instead.</p>
  </iframe>
</div>
