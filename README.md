<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Deepak Kumar Raj | GitHub Portfolio</title>

  <link
    href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css"
    rel="stylesheet"
  />

  <style>
    *{
      margin:0;
      padding:0;
      box-sizing:border-box;
      font-family:Arial, Helvetica, sans-serif;
    }

    body{
      background:#0d1117;
      color:white;
      overflow-x:hidden;
    }

    header{
      min-height:100vh;
      display:flex;
      justify-content:center;
      align-items:center;
      padding:40px;
      background:linear-gradient(135deg,#0d1117,#161b22);
    }

    .container{
      max-width:1200px;
      width:100%;
      display:grid;
      grid-template-columns:1fr 1fr;
      gap:50px;
      align-items:center;
    }

    .left h1{
      font-size:60px;
      margin-bottom:20px;
      line-height:1.1;
    }

    .left h1 span{
      color:#58a6ff;
    }

    .left p{
      color:#c9d1d9;
      font-size:18px;
      line-height:1.7;
      margin-bottom:30px;
    }

    .buttons{
      display:flex;
      gap:20px;
      flex-wrap:wrap;
    }

    .btn{
      padding:14px 28px;
      border:none;
      border-radius:10px;
      cursor:pointer;
      font-size:16px;
      text-decoration:none;
      transition:0.3s;
      font-weight:bold;
    }

    .primary{
      background:#238636;
      color:white;
    }

    .primary:hover{
      background:#2ea043;
      transform:translateY(-3px);
    }

    .secondary{
      border:2px solid #58a6ff;
      color:#58a6ff;
      background:transparent;
    }

    .secondary:hover{
      background:#58a6ff;
      color:#0d1117;
      transform:translateY(-3px);
    }

    .right{
      display:flex;
      justify-content:center;
      align-items:center;
    }

    .card{
      background:#161b22;
      border:1px solid #30363d;
      border-radius:20px;
      padding:30px;
      width:100%;
      max-width:450px;
      box-shadow:0 0 30px rgba(88,166,255,0.15);
    }

    .profile{
      text-align:center;
      margin-bottom:30px;
    }

    .profile img{
      width:130px;
      height:130px;
      border-radius:50%;
      border:4px solid #58a6ff;
      margin-bottom:15px;
    }

    .profile h2{
      margin-bottom:10px;
      font-size:28px;
    }

    .profile p{
      color:#8b949e;
    }

    .stats{
      display:grid;
      grid-template-columns:repeat(3,1fr);
      gap:15px;
      margin-top:30px;
    }

    .stat-box{
      background:#0d1117;
      padding:20px;
      border-radius:12px;
      text-align:center;
      transition:0.3s;
    }

    .stat-box:hover{
      transform:translateY(-5px);
      background:#21262d;
    }

    .stat-box h3{
      color:#58a6ff;
      margin-bottom:8px;
      font-size:24px;
    }

    .socials{
      margin-top:30px;
      display:flex;
      justify-content:center;
      gap:20px;
    }

    .socials a{
      color:white;
      font-size:22px;
      transition:0.3s;
    }

    .socials a:hover{
      color:#58a6ff;
      transform:scale(1.2);
    }

    section{
      padding:100px 10%;
    }

    .section-title{
      font-size:40px;
      text-align:center;
      margin-bottom:50px;
      color:#58a6ff;
    }

    .projects{
      display:grid;
      grid-template-columns:repeat(auto-fit,minmax(280px,1fr));
      gap:30px;
    }

    .project-card{
      background:#161b22;
      border:1px solid #30363d;
      border-radius:16px;
      padding:25px;
      transition:0.3s;
    }

    .project-card:hover{
      transform:translateY(-8px);
      box-shadow:0 0 20px rgba(88,166,255,0.2);
    }

    .project-card h3{
      margin-bottom:15px;
      color:#58a6ff;
    }

    .project-card p{
      color:#c9d1d9;
      line-height:1.6;
      margin-bottom:20px;
    }

    .tech{
      display:flex;
      flex-wrap:wrap;
      gap:10px;
    }

    .tech span{
      background:#21262d;
      padding:8px 14px;
      border-radius:20px;
      font-size:14px;
    }

    footer{
      text-align:center;
      padding:30px;
      background:#161b22;
      color:#8b949e;
    }

    @media(max-width:900px){
      .container{
        grid-template-columns:1fr;
      }

      .left{
        text-align:center;
      }

      .buttons{
        justify-content:center;
      }

      .left h1{
        font-size:45px;
      }
    }
  </style>
</head>

<body>

  <header>
    <div class="container">

      <div class="left">
        <h1>
          Hi, I'm <span>Deepak Kumar Raj</span>
        </h1>

        <p>
          Full Stack Developer • AI/ML Enthusiast • Open Source Contributor
          passionate about building scalable applications, intelligent systems,
          and modern web experiences.
        </p>

        <div class="buttons">
          <a
            href="https://github.com/ideepak9898"
            target="_blank"
            class="btn primary"
          >
            View GitHub
          </a>

          <a
            href="#projects"
            class="btn secondary"
          >
            Explore Projects
          </a>
        </div>
      </div>

      <div class="right">
        <div class="card">

          <div class="profile">
            <img
              src="https://avatars.githubusercontent.com/u/9919?v=4"
              alt="profile"
            />

            <h2>Deepak Kumar Raj</h2>

            <p>Software Engineer | AI/ML | AWS | Python</p>
          </div>

          <div class="stats">
            <div class="stat-box">
              <h3>20+</h3>
              <p>Projects</p>
            </div>

            <div class="stat-box">
              <h3>100+</h3>
              <p>Commits</p>
            </div>

            <div class="stat-box">
              <h3>10+</h3>
              <p>Technologies</p>
            </div>
          </div>

          <div class="socials">

            <a href="https://github.com/ideepak9898" target="_blank">
              <i class="fab fa-github"></i>
            </a>

            <a href="#" target="_blank">
              <i class="fab fa-linkedin"></i>
            </a>

            <a href="#" target="_blank">
              <i class="fas fa-envelope"></i>
            </a>

          </div>

        </div>
      </div>

    </div>
  </header>

  <section id="projects">

    <h2 class="section-title">Featured Projects</h2>

    <div class="projects">

      <div class="project-card">
        <h3>HomeValueAI</h3>

        <p>
          Machine learning based house price prediction system using
          RandomForestRegressor with Flask backend and responsive frontend.
        </p>

        <div class="tech">
          <span>Python</span>
          <span>Flask</span>
          <span>Machine Learning</span>
          <span>REST API</span>
        </div>
      </div>

      <div class="project-card">
        <h3>Smart Attendance System</h3>

        <p>
          Face recognition based attendance system using OpenCV
          and machine learning for automated student tracking.
        </p>

        <div class="tech">
          <span>Python</span>
          <span>OpenCV</span>
          <span>Face Recognition</span>
          <span>AI</span>
        </div>
      </div>

      <div class="project-card">
        <h3>TaskGPT</h3>

        <p>
          AI-powered productivity platform with animations,
          task management, and modern UI components.
        </p>

        <div class="tech">
          <span>React</span>
          <span>Framer Motion</span>
          <span>Bootstrap</span>
          <span>JavaScript</span>
        </div>
      </div>

    </div>

  </section>

  <footer>
    © 2026 Deepak Kumar Raj • Built with ❤️
  </footer>

</body>
</html>
