# Hello, I'm Muhammad Rizky
**💻 Full-Stack Developer | Java Backend (SpringBoot) + React Frontend**  
**🎯 Open to Opportunities | Building scalable systems & modern UIs**

<style>
  :root {
    --primary: #6c5ce7;
    --secondary: #00cec9;
    --accent: #f72585;
    --dark: #2d3436;
    --light: #636e72;
  }

  .hero-text {
    font-size: 2.2rem;
    font-weight: 700;
    background: linear-gradient(135deg, var(--primary), var(--secondary));
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    background-clip: text;
    margin-bottom: 0.5rem;
  }

  .tagline {
    font-size: 1.1rem;
    color: var(--light);
    margin-bottom: 2rem;
  }

  .badge {
    display: inline-flex;
    align-items: center;
    padding: 4px 10px;
    background: rgba(255,255,255,0.1);
    border-radius: 20px;
    margin: 2px;
    font-size: 0.75rem;
    transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
  }

  .badge:hover {
    transform: translateY(-3px) scale(1.15);
    background: rgba(255,255,255,0.25);
    box-shadow: 0 8px 25px rgba(0,0,0,0.3);
    border-color: var(--primary);
  }

  .badge:focus-visible {
    outline: 2px solid var(--primary);
    outline-offset: 2px;
  }

  .category {
    color: var(--secondary);
    font-weight: 600;
    margin-bottom: 1rem;
    display: block;
  }

  .section-divider {
    height: 1px;
    background: linear-gradient(90deg, transparent, var(--primary), transparent);
    margin: 2rem 0;
  }

  .project-card {
    background: rgba(45, 52, 54, 0.3);
    border-radius: 12px;
    padding: 1rem 1.2rem;
    margin: 0.5rem 0;
    transition: transform 0.3s ease, box-shadow 0.3s ease;
    border: 1px solid rgba(255,255,255,0.1);
  }

  .project-card:hover {
    transform: translateX(8px);
    box-shadow: 0 4px 20px rgba(0,0,0,0.4);
  }

  .stat-number {
    font-size: 2.5rem;
    font-weight: 700;
    background: linear-gradient(135deg, var(--primary), var(--accent));
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    background-clip: text;
  }

  .reveal {
    opacity: 0;
    transform: translateY(30px);
    transition: opacity 0.6s cubic-bezier(0.4, 0, 0.2, 1), transform 0.6s cubic-bezier(0.4, 0, 0.2, 1);
  }

  .reveal.visible {
    opacity: 1;
    transform: translateY(0);
  }
</style>

<script>
  document.addEventListener('DOMContentLoaded', function() {
    const reveals = document.querySelectorAll('.reveal');
    
    const observer = new IntersectionObserver(function(entries) {
      entries.forEach(entry => {
        if (entry.isIntersecting) {
          entry.target.classList.add('visible');
        }
      });
    }, { threshold: 0.1 });

    reveals.forEach(element => {
      observer.observe(element);
    });
  });
</script>

---

## 👨‍💻 About Me

Backend developer passionate about building scalable Java applications with Spring Boot, 
combined with modern React frontends. I love cleaning code, designing databases, 
and creating seamless user experiences.

**What I do:**
- Design & develop RESTful APIs with Spring Boot
- Build responsive UIs with React & TypeScript
- Optimize database queries & system architecture
- Deploy to Cloud (AWS, Docker, Kubernetes)

**Fun fact:** I automate everything I can find 🤖

<script>
  document.addEventListener('DOMContentLoaded', function() {
    const about = document.querySelector('h2 + p');
    if (about) {
      about.classList.add('reveal');
    }
  });
</script>

---

## 🛠️ Tech Stack

### Backend
[![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white)](https://www.java.com)  
[![Spring Boot](https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white)](https://spring.io/projects/spring-boot)  
[![Maven](https://img.shields.io/badge/Maven-C71A42?style=for-the-badge&logo=apache-maven&logoColor=white)](https://maven.apache.org)  
[![Gradle](https://img.shields.io/badge/Gradle-02303A?style=for-the-badge&logo=gradle&logoColor=white)](https://gradle.org)

### Frontend
[![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](https://reactjs.org)  
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://www.javascript.com)  
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://html5.org)  
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://css-tricks.com)

### Tools
[![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)](https://docker.com)  
[![Git](https://img.shields.io/badge/F05033?style=for-the-badge&logo=git&logoColor=white)](https://git-scm.com)  
[![IntelliJ IDEA](https://img.shields.io/badge/IntelliJIDEA-000000?style=for-the-badge&logo=intellij-idea&logoColor=white)](https://jetbrains.com/idea)  
[![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)](https://code.visualstudio.com)

<script>
  document.addEventListener('DOMContentLoaded', function() {
    const badges = document.querySelectorAll('.markdown .badge');
    badges.forEach(badge => {
      badge.style.transition = 'all 0.3s cubic-bezier(0.4, 0, 0.2, 1)';
    });
  });
</script>

---

## 📊 GitHub Stats

<div class="reveal">
[![GitHub Stats](https://github-readme-stats.vercel.app/api?username=mrrcodex&show_icons=true&theme=dark&count_private=true&include_all_commits=true&layout=compact)](https://github.com/mrrcodex)  
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=mrrcodex&layout=compact&theme=dark&border_color=8051C2&text_color=D1D1D1&bg_color=1e1e1e)](https://github.com/mrrcodex)
</div>

[![GitHub Streak](https://streak-stats.demolab.com?user=mrrcodex&theme=dark)](https://gitstreak.com/mrrcodex)  
[![Contributions](https://github-contributions.vercel.app/api?username=mrrcodex&limit=5&theme=dark)](https://github.com/mrrcodex)

<script>
  document.addEventListener('DOMContentLoaded', function() {
    const stats = document.querySelector('.reveal');
    if (stats) stats.classList.add('visible');
  });
</script>

---

## 📱 Social Media

<div style="display: flex; gap: 10px; flex-wrap: wrap;">
  [![Twitter](https://img.shields.io/badge/@-1DA1F2?style=for-the-badge&logo=xwitter&logoColor=white)](https://twitter.com/mrrcodex)  
  [![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/mrrcodex)  
  [![GitHub](https://img.shields.io/badge/github-%23100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/mrrcodex)

  [![Email](https://img.shields.io/badge/Email-D1495B?style=for-the-badge&logo=gmail&logoColor=white)](mailto:muhammadrizky@example.com)
</div>

<script>
  document.addEventListener('DOMContentLoaded', function() {
    const socials = document.querySelectorAll('div[style*="display: flex"] .badge');
    socials.forEach(social => {
      social.style.transition = 'all 0.3s ease';
    });
  });
</script>

---

## 🚀 Featured Projects

<div class="section-divider"></div>

### **Spring Boot REST API**
<div class="project-card">
[![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white)](https://github.com/mrrcodex/spring-boot-api)  
Robust RESTful API built with Spring Boot featuring JWT authentication, 
exception handling, and PostgreSQL integration. Clean architecture with layered design.
</div>

### **React E-commerce UI**
<div class="project-card">
[![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](https://github.com/mrrcodex/react-ecommerce)  
Modern e-commerce frontend with React, Red Toolkit UI, and API integration. 
Responsive design with smooth animations and state management.
</div>

### **Full-Stack Chat Application**
<div class="project-card">
[![Full-Stack](https://img.shields.io/badge/Full--Stack-000000?style=for-the-badge&logo=visual-studio-code&logoColor=white)](https://github.com/mrrcodex/chat-app)  
Real-time chat application connecting React frontend with Spring Boot WebSocket backend. 
Features private messaging, typing indicators, and message persistence.
</div>

<script>
  document.addEventListener('DOMContentLoaded', function() {
    const cards = document.querySelectorAll('.project-card');
    cards.forEach(card => {
      card.classList.add('reveal');
    });
  });
</script>

---

## 📈 Recent Activity

<div class="section-divider"></div>

[![GitHub Activity](https://ghapi.huchen.dev/users/mrrcodex)](https://github.com/mrrcodex)  
[![Lines of Code](https://img.shields.io/badge/LOC-15,234-brightgreen)](https://github.com/mrrcodex)

<script>
  document.addEventListener('DOMContentLoaded', function() {
    const activity = document.querySelector('.section-divider + *');
    if (activity) activity.classList.add('reveal');
  });
</script>

---

<!---
💬 **Ask me about:** Java Spring Boot, React, system design, cloud deployment
📫 **How to reach me:** LinkedIn or Email
⚡ **Fun fact:** I document everything I learn
-->