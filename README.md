Hello there! 👋 I'm Sadik
Welcome to my GitHub profile! I'm a passionate developer currently exploring the exciting world of mobile and web development.

🚀 About Me
🔭 Currently working on: Building creative projects on Behance

🌱 Currently learning: Flutter for cross-platform mobile development

👯 Looking to collaborate on: React.js projects

🤔 Looking for help with: AWS cloud services

💬 Ask me about: Anything related to development and design!

😄 Pronouns: He/Him

/* Add this to your README.md using HTML and CSS */
<style>
  .profile-container {
    max-width: 800px;
    margin: 0 auto;
    padding: 2rem;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  }

  .header {
    text-align: center;
    background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
    padding: 3rem 2rem;
    border-radius: 15px;
    color: white;
    margin-bottom: 2rem;
  }

  .header h1 {
    font-size: 2.5rem;
    margin-bottom: 0.5rem;
    background: linear-gradient(45deg, #fff, #f0f0f0);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
  }

  .tagline {
    font-size: 1.2rem;
    opacity: 0.9;
  }

  .badges {
    display: flex;
    flex-wrap: wrap;
    gap: 0.5rem;
    justify-content: center;
    margin: 1rem 0;
  }

  .badge {
    background: rgba(255, 255, 255, 0.2);
    padding: 0.3rem 0.8rem;
    border-radius: 20px;
    font-size: 0.9rem;
    backdrop-filter: blur(10px);
  }

  .section {
    background: white;
    padding: 2rem;
    border-radius: 10px;
    margin: 1.5rem 0;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    border-left: 4px solid #667eea;
  }

  .section h2 {
    color: #333;
    margin-bottom: 1rem;
    display: flex;
    align-items: center;
    gap: 0.5rem;
  }

  .tech-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    gap: 1rem;
    margin-top: 1rem;
  }

  .tech-item {
    background: #f8f9fa;
    padding: 1rem;
    border-radius: 8px;
    text-align: center;
    transition: transform 0.3s ease;
  }

  .tech-item:hover {
    transform: translateY(-2px);
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
  }

  .links {
    display: flex;
    justify-content: center;
    gap: 1rem;
    margin-top: 2rem;
  }

  .link-btn {
    padding: 0.8rem 1.5rem;
    background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
    color: white;
    text-decoration: none;
    border-radius: 25px;
    transition: all 0.3s ease;
    display: flex;
    align-items: center;
    gap: 0.5rem;
  }

  .link-btn:hover {
    transform: translateY(-2px);
    box-shadow: 0 6px 12px rgba(102, 126, 234, 0.3);
  }

  .stats {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
    gap: 1rem;
    margin: 2rem 0;
  }

  .stat-item {
    text-align: center;
    padding: 1rem;
    background: linear-gradient(135deg, #f093fb 0%, #f5576c 100%);
    color: white;
    border-radius: 10px;
  }

  .stat-number {
    font-size: 2rem;
    font-weight: bold;
    display: block;
  }

  .stat-label {
    font-size: 0.9rem;
    opacity: 0.9;
  }
</style>
<style>
  .dark-theme {
    background: #0d1117;
    color: #c9d1d9;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    padding: 2rem;
  }

  .profile-header {
    text-align: center;
    background: linear-gradient(135deg, #1a1f2e 0%, #2d3748 100%);
    padding: 3rem 2rem;
    border-radius: 15px;
    margin-bottom: 2rem;
    border: 1px solid #30363d;
  }

  .profile-title {
    font-size: 2.5rem;
    background: linear-gradient(45deg, #58a6ff, #7ee787);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    margin-bottom: 0.5rem;
  }

  .profile-subtitle {
    color: #8b949e;
    font-size: 1.2rem;
  }

  .tech-stack {
    display: flex;
    flex-wrap: wrap;
    gap: 0.8rem;
    justify-content: center;
    margin: 1.5rem 0;
  }

  .tech-pill {
    background: #21262d;
    border: 1px solid #30363d;
    padding: 0.5rem 1rem;
    border-radius: 20px;
    font-size: 0.9rem;
    color: #58a6ff;
    transition: all 0.3s ease;
  }

  .tech-pill:hover {
    background: #30363d;
    transform: translateY(-2px);
  }

  .content-section {
    background: #161b22;
    border: 1px solid #30363d;
    padding: 2rem;
    border-radius: 10px;
    margin: 1.5rem 0;
  }

  .section-title {
    color: #58a6ff;
    border-bottom: 2px solid #30363d;
    padding-bottom: 0.5rem;
    margin-bottom: 1.5rem;
    display: flex;
    align-items: center;
    gap: 0.5rem;
  }

  .project-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 1.5rem;
  }

  .project-card {
    background: #0d1117;
    border: 1px solid #30363d;
    border-radius: 8px;
    padding: 1.5rem;
    transition: all 0.3s ease;
  }

  .project-card:hover {
    border-color: #58a6ff;
    transform: translateY(-4px);
  }

  .social-links {
    display: flex;
    justify-content: center;
    gap: 1rem;
    margin-top: 2rem;
  }

  .social-link {
    padding: 0.8rem 1.5rem;
    background: #21262d;
    border: 1px solid #30363d;
    color: #c9d1d9;
    text-decoration: none;
    border-radius: 6px;
    transition: all 0.3s ease;
    display: flex;
    align-items: center;
    gap: 0.5rem;
  }

  .social-link:hover {
    background: #30363d;
    border-color: #58a6ff;
    color: #58a6ff;
  }
</style>
