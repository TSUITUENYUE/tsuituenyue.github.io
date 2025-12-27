---
permalink: /
title: "About Me"
excerpt: "Robotics researcher at Penn."
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<div class="about-page">
  <div class="about-container">
    
    <!-- Main About Section -->
    <div class="about-main glass-card">
            <div class="about-content" style="display: flex; align-items: flex-start; gap: 2rem;">
        
        <!-- Text Content Left Side -->
        <div class="about-text" style="flex: 2;">
          <h2>Tuen-Yue Tsui</h2>
          
          <p>I am a passionate researcher dedicated to advancing knowledge at the intersection of cognitive science and robotics. My research aims to build the human-like congnitive system for highly autonomous intelligence in robotics. My research interests include continual learning, local learning rule and reasoning & planning. I also enjoy reading <a href="https://en.wikipedia.org/wiki/Immanuel_Kant" target="_blank" rel="noopener"> Kant</a> for inspirations in my research.</p>
          
          <p>Currently, I am a second-year master’s student in Robotics at the University of Pennsylvania, advised by <a href="https://lingjie0206.github.io/" target="_blank" rel="noopener">Prof. Lingjie Liu</a>. My current research focus on online continual learning, and its implementation in active embodied continual learner. Previously, I was advised by <a href="https://sites.google.com/site/qinzoucn/" target="_blank" rel="noopener">Prof. Qin Zou</a>.at Wuhan University.</p>

             <p> You may find some useful links below:</p>
            
            <!-- Links Section -->
            <div class="about-links" style="display: flex; gap: 1.5rem; margin-top: 1rem; flex-wrap: wrap;">
              <a href="{{ '/files/CV.pdf' | relative_url }}" class="link-item" target="_blank" style="display: flex; align-items: center; gap: 0.5rem; padding: 0.5rem 1rem; background: rgba(255,255,255,0.1); border-radius: 8px; text-decoration: none; color: inherit; transition: all 0.3s ease;">
                <i class="fas fa-file-pdf" style="color: #e74c3c;"></i>
                <span>CV</span>
              </a>
              
              <a href="mailto:tytsui@seas.upenn.edu" class="link-item" style="display: flex; align-items: center; gap: 0.5rem; padding: 0.5rem 1rem; background: rgba(255,255,255,0.1); border-radius: 8px; text-decoration: none; color: inherit; transition: all 0.3s ease;">
                <i class="fas fa-envelope" style="color: #3498db;"></i>
                <span>Email</span>
              </a>
              
              <a href="https://github.com/tsuituenyue" class="link-item" target="_blank" style="display: flex; align-items: center; gap: 0.5rem; padding: 0.5rem 1rem; background: rgba(255,255,255,0.1); border-radius: 8px; text-decoration: none; color: inherit; transition: all 0.3s ease;">
                <i class="fab fa-github" style="color: #333;"></i>
                <span>GitHub</span>
              </a>
              
              <a href="https://hk.linkedin.com/in/tuen-yue-tsui-2a636115b" class="link-item" target="_blank" style="display: flex; align-items: center; gap: 0.5rem; padding: 0.5rem 1rem; background: rgba(255,255,255,0.1); border-radius: 8px; text-decoration: none; color: inherit; transition: all 0.3s ease;">
                <i class="fab fa-linkedin" style="color: #0077b5;"></i>
                <span>LinkedIn</span>
              </a>
            </div>
          </div>
        
        <!-- Photo Right Side -->
        <div class="about-photo" style="flex: 1; display: flex; align-items: flex-start; justify-content: center; padding-top: 12rem;">
          <div class="photo-container glass-card">
            <img src="/images/me.jpg" alt="Tuen-Yue Tsui" class="profile-photo" style="width: 100%; height: auto; border-radius: 8px;">
          </div>
        </div>
        
      </div>
    </div>
    
    <!-- Academic Background Section -->
    <div class="academic-background glass-card">
      <h3>Academic Background</h3>
      <div class="education-timeline">
        
        <div class="education-item">
          <div class="education-year">2024-Present</div>
          <div class="education-content">
            <h4>M.S.E in Robotics</h4>
            <p class="institution">University of Pennsylvania</p>
            <p class="thesis">Focus: Intention-aware Imitation Learning</p>
          </div>
        </div>
        
        <div class="education-item">
          <div class="education-year">2020-2024</div>
          <div class="education-content">
            <h4>B.E. in Computer Science</h4>
            <p class="institution">Wuhan University</p>
          </div>
        </div>
      </div>
    </div>
    
    <!-- Teaching Experience -->
    <div class="academic-background glass-card">
      <h3>Teaching Experience</h3>
      <div class="education-timeline">
        
        <div class="education-item">
          <div class="education-year">Fall 2025</div>
          <div class="education-content">
            <h4>Teaching Assistant - Applied Machine Learning</h4>
            <p class="institution">University of Pennsylvania</p>
            <p class="thesis">Assisting with graduate-level machine learning course</p>
          </div>
        </div>
        
      </div>
    </div>
    

  </div>
</div>

<style>
  /* Responsive: stack photo above text and center links on small screens */
  @media (max-width: 768px) {
    .about-main .about-content {
      flex-direction: column;
    }
    .about-main .about-photo {
      order: -1; /* move photo above text */
      padding-top: 0 !important;
      margin-bottom: 1rem;
    }
    .about-main .about-text {
      width: 100%;
    }
    .about-main .about-links {
      justify-content: center;
    }
  }
</style>
