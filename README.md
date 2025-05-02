<div align="center">
  <style>
    @keyframes gradientWave {
      0% { background-position: 0% 50%; }
      50% { background-position: 100% 50%; }
      100% { background-position: 0% 50%; }
    }
    
    .header {
      background: linear-gradient(45deg, #2C3E50, #3498DB, #27AE60);
      background-size: 400% 400%;
      animation: gradientWave 12s ease infinite;
      padding: 2rem;
      border-radius: 15px;
      margin: 2rem 0;
      box-shadow: 0 4px 30px rgba(0,0,0,0.1);
    }
    
    .skill-badge {
      display: inline-flex;
      align-items: center;
      background: rgba(255,255,255,0.1);
      padding: 8px 15px;
      margin: 5px;
      border-radius: 20px;
      border: 1px solid rgba(255,255,255,0.2);
      transition: all 0.3s;
    }
    
    .skill-badge:hover {
      transform: translateY(-3px);
      background: rgba(255,255,255,0.2);
    }
    
    .automation-card {
      background: linear-gradient(45deg, #1ABC9C, #16A085);
      padding: 1.5rem;
      border-radius: 15px;
      margin: 1rem 0;
      text-align: left;
    }
    
    .stats-container {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 1rem;
      width: 100%;
      margin: 2rem 0;
    }
    
    .stat-item {
      background: rgba(46, 204, 113, 0.1);
      padding: 1rem;
      border-radius: 10px;
      border: 1px solid #2ECC71;
    }
  </style>

  <div class="header">
    <h1 style="color: white; margin: 0;">
      <img src="https://media1.tenor.com/m/LVKlUQCV9M4AAAAC/palestine-flag-palestine.gif" width="40" style="vertical-align: middle; border-radius: 50%;">
      Python Automation Engineer
    </h1>
    <p style="color: rgba(255,255,255,0.9);">Превращаю рутину в автоматизированные решения</p>
  </div>

  <!-- Технологический стек -->
  <h2>🛠️ Технологический стек</h2>
  <div>
    <span class="skill-badge">
      <img src="https://img.icons8.com/color/48/000000/python.png" width="20"/>
      Python
    </span>
    <span class="skill-badge">
      <img src="https://img.icons8.com/color/48/000000/django.png" width="20"/>
      Django
    </span>
    <span class="skill-badge">
      <img src="https://img.icons8.com/color/48/000000/docker.png" width="20"/>
      Docker
    </span>
    <!-- Добавьте остальные иконки аналогично -->
  </div>

  <!-- Услуги -->
  <div class="automation-card">
    <h3 style="color: white;">🚀 Мои услуги</h3>
    <ul style="color: rgba(255,255,255,0.9);">
      <li>Автоматизация бизнес-процессов</li>
      <li>Telegram-боты любой сложности</li>
      <li>Интеграция с API сервисов</li>
      <li>Работа с IoT (Arduino/Raspberry Pi)</li>
      <li>Настройка CI/CD pipelines</li>
    </ul>
  </div>

  <!-- Статистика -->
  <div class="stats-container">
    <div class="stat-item">
      <h3>📦 Проектов завершено</h3>
      <p>27+ успешных внедрений</p>
    </div>
    <div class="stat-item">
      <h3>⏱️ Время реакции</h3>
      <p>До 24 часов на начало работы</p>
    </div>
    <div class="stat-item">
      <h3>🔧 Техподдержка</h3>
      <p>Гарантия на все решения</p>
    </div>
  </div>

  <!-- Контакты -->
  <a href="https://t.me/Itjget" target="_blank" style="display: inline-block; background: #0088CC; color: white; padding: 12px 30px; border-radius: 30px; text-decoration: none; margin: 1rem; transition: 0.3s;">
    💬 Обсудить проект
  </a>

  <br>
  
  <img src="https://komarev.com/ghpvc/?username=yourusername&style=flat-square&color=3498DB" alt="Profile views">
  <img src="https://github-readme-stats.vercel.app/api?username=yourusername&show_icons=true&theme=dark" alt="GitHub Stats">
</div>
