<!DOCTYPE html>
<html>
<head>
    <style>
        .profile-container {
            font-family: 'Arial', sans-serif;
            max-width: 600px;
            margin: 0 auto;
            padding: 20px;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            border-radius: 15px;
            color: white;
            box-shadow: 0 10px 30px rgba(0,0,0,0.3);
        }
        
        .header {
            text-align: center;
            margin-bottom: 25px;
        }
        
        .title {
            font-size: 24px;
            font-weight: bold;
            margin-bottom: 15px;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.3);
        }
        
        .description {
            font-size: 16px;
            line-height: 1.6;
            margin-bottom: 25px;
            text-align: justify;
            background: rgba(255,255,255,0.1);
            padding: 20px;
            border-radius: 10px;
            backdrop-filter: blur(10px);
        }
        
        .badges-container {
            display: flex;
            justify-content: center;
            gap: 15px;
            flex-wrap: wrap;
        }
        
        .badge {
            transition: transform 0.3s ease, box-shadow 0.3s ease;
            border-radius: 8px;
            overflow: hidden;
        }
        
        .badge:hover {
            transform: translateY(-3px);
            box-shadow: 0 8px 25px rgba(0,0,0,0.3);
        }
        
        .tech-stack {
            display: flex;
            justify-content: center;
            gap: 10px;
            margin: 20px 0;
            flex-wrap: wrap;
        }
        
        .tech-item {
            background: rgba(255,255,255,0.2);
            padding: 8px 15px;
            border-radius: 20px;
            font-size: 14px;
            font-weight: bold;
            backdrop-filter: blur(5px);
        }
    </style>
</head>
<body>
    <div class="profile-container">
        <div class="header">
            <div class="title">🚀 Desenvolvedor Full Stack Web</div>
            <div class="tech-stack">
                <span class="tech-item">JavaScript</span>
                <span class="tech-item">React</span>
                <span class="tech-item">Node.js</span>
                <span class="tech-item">Java</span>
                <span class="tech-item">Python</span>
            </div>
        </div>
        
        <div class="description">
            <strong>Estudante de Análise e Desenvolvimento de Sistemas</strong> com especialização em desenvolvimento full stack web. Domínio técnico em <strong>JavaScript, React e Node.js</strong>, complementado por sólida base em <strong>Java e Python</strong>.
            <br><br>
            Experiência no desenvolvimento de aplicações web completas: desde interfaces responsivas e intuitivas até APIs robustas e escaláveis. Foco em código limpo, performance e experiência do usuário.
            <br><br>
            <strong>Busco oportunidades desafiadoras</strong> para aplicar conhecimentos técnicos em projetos inovadores.
        </div>
        
        <div class="badges-container">
            <a href="https://www.linkedin.com/in/jbrunops/" target="_blank" class="badge">
                <img src="https://img.shields.io/badge/-LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
            </a>
            <a href="https://github.com/jbrunops" target="_blank" class="badge">
                <img src="https://img.shields.io/badge/-GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">
            </a>
            <a href="https://www.instagram.com/jbrunops/" target="_blank" class="badge">
                <img src="https://img.shields.io/badge/-Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram">
            </a>
            <a href="https://www.youtube.com/@jacksonporciunculadev" target="_blank" class="badge">
                <img src="https://img.shields.io/badge/-YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white" alt="YouTube">
            </a>
        </div>
    </div>
</body>
</html>
