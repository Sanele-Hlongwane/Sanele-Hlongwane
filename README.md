<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>About Me</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #1a1a1a;
      color: #f5f5f5;
      margin: 0;
      padding: 0;
    }
    .container {
      max-width: 800px;
      margin: 0 auto;
      padding: 20px;
    }
    header {
      text-align: center;
      margin-bottom: 20px;
    }
    header h1 {
      font-size: 3rem;
      margin: 0;
      color: #FFD700;
      position: relative;
      overflow: hidden;
    }
    header h1::before {
      content: '';
      position: absolute;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
      width: 200%;
      height: 200%;
      background: rgba(255, 255, 255, 0.2);
      border-radius: 50%;
      transition: transform 0.5s ease;
      z-index: 0;
    }
    header h1:hover::before {
      transform: translate(-50%, -50%) scale(0.8);
    }
    header h1 span {
      position: relative;
      z-index: 1;
      display: inline-block;
      transition: transform 0.2s ease;
    }
    header h1:hover span {
      transform: translateX(-20px) translateY(-20px);
    }
    section {
      margin-top: 20px;
    }
    .info-item {
      margin-bottom: 20px;
    }
    .info-item h2 {
      font-size: 1.5rem;
      color: #FFD700;
    }
    .info-item p {
      font-size: 1rem;
    }
    .contact-info a {
      color: #FFD700;
      text-decoration: none;
    }
    .contact-info a:hover {
      text-decoration: underline;
    }
    .skills ul, .education ul, .projects ul {
      list-style-type: none;
      padding: 0;
    }
    .skills li, .education li, .projects li {
      background: #333;
      padding: 10px;
      margin-bottom: 5px;
      border-radius: 5px;
    }
    .fun-fact {
      font-style: italic;
    }
  </style>
</head>
<body>
  <div class="container">
    <header>
      <h1><span>👋 Hi, I’m Sanele Hlongwane</span></h1>
    </header>
    <section>
      <div class="info-item">
        <h2>👀 I’m interested in...</h2>
        <p>Software Development, Business Information Technology, Entrepreneurship</p>
      </div>
      <div class="info-item">
        <h2>🌱 I’m currently learning...</h2>
        <p>Business Information Technology at the University of Johannesburg</p>
      </div>
      <div class="info-item">
        <h2>💞️ I’m looking to collaborate on...</h2>
        <p>Software development projects and learning more about new technologies</p>
      </div>
      <div class="info-item">
        <h2>📫 How to reach me...</h2>
        <p class="contact-info">
          📞 0603179552 <br>
          📧 <a href="mailto:sanelehlongwane61@gmail.com">sanelehlongwane61@gmail.com</a>
        </p>
      </div>
      <div class="info-item">
        <h2>😄 Pronouns...</h2>
        <p>He/him</p>
      </div>
      <div class="info-item">
        <h2>⚡ Fun fact...</h2>
        <p class="fun-fact">I enjoy solving complex problems and building scalable solutions.</p>
      </div>
      <div class="info-item skills">
        <h2>🛠️ Skills...</h2>
        <ul>
          <li>JavaScript (ES6+)</li>
          <li>React.js</li>
          <li>Node.js</li>
          <li>HTML5 & CSS3</li>
          <li>SQL & NoSQL Databases</li>
          <li>Firebase</li>
          <li>Python</li>
          <li>C#</li>
          <li>Windows Forms</li>
          <li>WPF</li>
          <li>ASP.NET</li>
          <li>PHP</li>
          <li>React Native</li>
          <li>Version Control (Git)</li>
          <li>UI/UX Design</li>
          <li>Agile Methodologies</li>
          <li>Project Management</li>
        </ul>
      </div>
      <div class="info-item education">
        <h2>🎓 Education...</h2>
        <ul>
          <li>Business Information Technology, University of Johannesburg</li>
          <li>High School Bachelor, Hoye Secondary School</li>
        </ul>
      </div>
      <div class="info-item projects">
        <h2>📂 Projects...</h2>
        <ul>
          <li><strong>Eco-Tracker (2023/07 - 2023/11)</strong>: A mobile app designed to increase user awareness about eco-friendly practices.</li>
          <li><strong>Thrivemebtor (2023/03 - 2023/06)</strong>: A lifestyle coaching website aimed at personal development and goal achievement.</li>
          <li><strong>Eagles Ring (2024/03 - Present)</strong>: An investment platform that connects entrepreneurs with investment opportunities, featuring features like pitch presentations, role-based profiles, and integration with Clerk for authentication and Prisma for database management.</li>
        </ul>
      </div>
    </section>
  </div>
</body>
</html>
