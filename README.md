<h1 align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Poppins&size=32&pause=1000&color=FFB6C1&center=true&vCenter=true&width=500&lines=Code+Name%3A+Marie+%F0%9F%A4%8D" alt="Typing SVG" />
</h1>

### Who Am I?
I am Mary Anne B. Purawan. I am a 3rd year BSIT student who is constantly learning, constantly improving, and never stopping :)

### System Projects
Here are some of my system proposals that were approved and later-on developed into actual software systems.
 
<div style="padding: 2rem 0;">
<style>
@keyframes bounce {
  0%, 100% { transform: translateY(0); }
  50% { transform: translateY(-12px); }
}

@keyframes fadeIn {
  from { opacity: 0; transform: translateY(20px); }
  to { opacity: 1; transform: translateY(0); }
}

@keyframes shimmer {
  0%, 100% { text-shadow: none; }
  50% { text-shadow: 0 0 10px rgba(255, 182, 193, 0.5); }
}

.projects-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 20px;
  margin: 1rem 0;
}

.project-card {
  background: #ffffff;
  border: 1px solid #e0e0e0;
  border-radius: 12px;
  padding: 1.5rem;
  transition: all 0.3s cubic-bezier(0.34, 1.56, 0.64, 1);
  animation: fadeIn 0.6s ease-out forwards;
  box-shadow: 0 2px 8px rgba(0, 0, 0, 0.05);
}

.project-card:hover {
  border-color: #FFB6C1;
  box-shadow: 0 8px 16px rgba(255, 182, 193, 0.15);
  transform: translateY(-8px);
}

.project-icon {
  font-size: 56px;
  animation: bounce 2s ease-in-out infinite;
  display: inline-block;
  margin-bottom: 1rem;
  filter: drop-shadow(0 2px 4px rgba(0, 0, 0, 0.1));
}

.project-card:nth-child(1) .project-icon { animation-delay: 0s; }
.project-card:nth-child(2) .project-icon { animation-delay: 0.1s; }
.project-card:nth-child(3) .project-icon { animation-delay: 0.2s; }
.project-card:nth-child(4) .project-icon { animation-delay: 0.3s; }
.project-card:nth-child(5) .project-icon { animation-delay: 0.4s; }

.project-badge {
  display: inline-block;
  background: #FFE4E1;
  color: #c2185b;
  font-size: 11px;
  padding: 5px 10px;
  border-radius: 20px;
  margin-bottom: 1rem;
  font-weight: 600;
  text-transform: uppercase;
  letter-spacing: 0.5px;
}

.project-badge.individual { background: #E3F2FD; color: #1565c0; }
.project-badge.group { background: #F3E5F5; color: #6a1b9a; }

.project-title {
  margin: 0.75rem 0 0.5rem 0;
  font-size: 18px;
  font-weight: 600;
  color: #212121;
}

.project-title a {
  color: #c2185b;
  text-decoration: none;
  transition: color 0.2s, text-shadow 0.2s;
}

.project-title a:hover {
  color: #e91e63;
  text-shadow: 0 0 8px rgba(255, 182, 193, 0.6);
}

.project-description {
  font-size: 14px;
  color: #757575;
  margin-bottom: 0.75rem;
  line-height: 1.5;
}

.project-meta {
  font-size: 12px;
  color: #9e9e9e;
  margin-bottom: 0.5rem;
  font-weight: 500;
}

.project-meta strong {
  color: #424242;
  font-weight: 600;
}

.project-contribution {
  font-size: 13px;
  color: #666666;
  line-height: 1.7;
  margin-bottom: 1rem;
  padding-top: 0.75rem;
  border-top: 1px solid #f0f0f0;
}

.repo-link {
  display: inline-flex;
  align-items: center;
  gap: 6px;
  color: #c2185b;
  text-decoration: none;
  font-size: 13px;
  font-weight: 600;
  transition: all 0.2s;
  padding: 6px 12px;
  border-radius: 6px;
  border: 1px solid #FFB6C1;
  background: #fff5f8;
}

.repo-link:hover {
  background: #FFB6C1;
  color: #ffffff;
  transform: translateX(2px);
}

.repo-link::after {
  content: "→";
  transition: transform 0.2s;
}

.repo-link:hover::after {
  transform: translateX(4px);
}

@media (prefers-color-scheme: dark) {
  .project-card {
    background: #1e1e1e;
    border-color: #404040;
    box-shadow: 0 2px 8px rgba(0, 0, 0, 0.3);
  }

  .project-card:hover {
    border-color: #ff69b4;
    box-shadow: 0 8px 16px rgba(255, 105, 180, 0.2);
  }

  .project-title { color: #ffffff; }
  .project-description { color: #b0b0b0; }
  .project-meta { color: #a0a0a0; }
  .project-meta strong { color: #e0e0e0; }
  .project-contribution { color: #c0c0c0; border-top-color: #303030; }

  .repo-link {
    background: #2a2a2a;
    border-color: #ff69b4;
  }

  .repo-link:hover {
    background: #ff69b4;
  }
}
</style>

<div class="projects-grid">

  <!-- PROJECT 1: Sex Ed 101 -->
  <div class="project-card">
    <div class="project-icon">📱</div>
    <span class="project-badge individual">Individual</span>
    <h3 class="project-title">
      <a href="https://github.com/marebisco/sex-ed-101" target="_blank" rel="noopener noreferrer">Sex Ed 101</a>
    </h3>
    <p class="project-description">Empowering Sexual Health Education</p>
    <div class="project-meta">
      <strong>Role:</strong> Full-Stack Developer
    </div>
    <p class="project-contribution">
      Designed the user interface and developed backend functionality using FlutterFlow, based on wireframes created in Canva, as part of a Mobile Development course.
    </p>
    <a href="https://github.com/marebisco/sex-ed-101" class="repo-link" target="_blank" rel="noopener noreferrer">View on GitHub</a>
  </div>

  <!-- PROJECT 2: NutriLuto -->
  <div class="project-card">
    <div class="project-icon">🥗</div>
    <span class="project-badge group">Group</span>
    <h3 class="project-title">
      <a href="https://github.com/shelley-ses/filipino-recipe-with-nutrition-analyzer" target="_blank" rel="noopener noreferrer">NutriLuto</a>
    </h3>
    <p class="project-description">Filipino Recipe with Nutrition Analyzer</p>
    <div class="project-meta">
      <strong>Role:</strong> Database Developer
    </div>
    <p class="project-contribution">
      Designed the SQLite database, including the recipe and ingredient data tables storing nutritional information such as calories, protein, carbohydrates, and fat content.
    </p>
    <a href="https://github.com/shelley-ses/filipino-recipe-with-nutrition-analyzer" class="repo-link" target="_blank" rel="noopener noreferrer">View on GitHub</a>
  </div>

  <!-- PROJECT 3: MindConnect -->
  <div class="project-card">
    <div class="project-icon">🧠</div>
    <span class="project-badge group">Group</span>
    <h3 class="project-title">MindConnect</h3>
    <p class="project-description">Mental Health Management System</p>
    <div class="project-meta">
      <strong>Role:</strong> Researcher, System Analyst
    </div>
    <p class="project-contribution">
      Conceptualized the system, identified core problems, defined its functional requirements and established the research foundation.
    </p>
  </div>

  <!-- PROJECT 4: ReserBus -->
  <div class="project-card">
    <div class="project-icon">🚌</div>
    <span class="project-badge group">Group</span>
    <h3 class="project-title">ReserBus</h3>
    <p class="project-description">Bus Reservation System</p>
    <div class="project-meta">
      <strong>Role:</strong> Documentation
    </div>
    <p class="project-contribution">
      Helped develop the Detailed Design Report, covering the entity relationship diagram, database schema, input forms, and screen navigation flow.
    </p>
  </div>

  <!-- PROJECT 5: Gurong GabAI -->
  <div class="project-card">
    <div class="project-icon">🤖</div>
    <span class="project-badge individual">Individual</span>
    <h3 class="project-title">
      <a href="https://github.com/marebisco/gurong-gabai" target="_blank" rel="noopener noreferrer">Gurong GabAI</a>
    </h3>
    <p class="project-description">AI-Powered Lesson Plan Generator</p>
    <div class="project-meta">
      <strong>Role:</strong> Full-Stack Developer
    </div>
    <p class="project-contribution">
      Developed a system using PHP, MySQL, and the OpenRouter API with 3 multi-model fallback chain architecture. Implemented 9 layered security features.
    </p>
    <a href="https://github.com/marebisco/gurong-gabai" class="repo-link" target="_blank" rel="noopener noreferrer">View on GitHub</a>
  </div>

</div>

</div>

<!-- ==================== END ANIMATED PROJECTS SHOWCASE ==================== -->
