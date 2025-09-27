<!DOCTYPE html>
<html>
<head>
    <style>
        /* Base styling */
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: #333;
            max-width: 900px;
            margin: 0 auto;
            padding: 20px;
            background-color: #f8f9fa;
        }
        
        /* Header section */
        .header {
            text-align: center;
            padding: 40px 20px;
            background: linear-gradient(135deg, #6a11cb 0%, #2575fc 100%);
            color: white;
            border-radius: 10px;
            margin-bottom: 30px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
        }
        
        .header h1 {
            margin: 0;
            font-size: 2.5rem;
            font-weight: 700;
        }
        
        .header h3 {
            margin: 15px 0 0;
            font-weight: 400;
            opacity: 0.9;
        }
        
        /* Section styling */
        .section {
            background: white;
            padding: 25px;
            border-radius: 10px;
            margin-bottom: 25px;
            box-shadow: 0 2px 4px rgba(0,0,0,0.05);
        }
        
        .section h3 {
            color: #2575fc;
            margin-top: 0;
            border-bottom: 2px solid #f0f0f0;
            padding-bottom: 10px;
            display: flex;
            align-items: center;
        }
        
        .section h3:before {
            content: "▸";
            margin-right: 10px;
            color: #6a11cb;
        }
        
        /* About section */
        .about-content {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            align-items: center;
        }
        
        .about-text {
            flex: 1;
            min-width: 300px;
        }
        
        .contact-info {
            background: #f8f9fa;
            padding: 15px;
            border-radius: 8px;
            border-left: 4px solid #6a11cb;
        }
        
        /* Icons grid */
        .icons-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(80px, 1fr));
            gap: 15px;
            justify-items: center;
            margin-top: 15px;
        }
        
        .icon-item {
            display: flex;
            flex-direction: column;
            align-items: center;
            transition: transform 0.3s ease;
        }
        
        .icon-item:hover {
            transform: translateY(-5px);
        }
        
        .icon-item img {
            width: 40px;
            height: 40px;
            margin-bottom: 8px;
        }
        
        .icon-item span {
            font-size: 0.8rem;
            text-align: center;
            color: #555;
        }
        
        /* Social links */
        .social-links {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin-top: 15px;
        }
        
        .social-link {
            display: inline-flex;
            align-items: center;
            padding: 10px 20px;
            background: #f0f2f5;
            border-radius: 30px;
            text-decoration: none;
            color: #333;
            transition: all 0.3s ease;
            font-weight: 500;
        }
        
        .social-link:hover {
            background: #2575fc;
            color: white;
            transform: translateY(-2px);
        }
        
        .social-link img {
            margin-right: 8px;
        }
        
        /* Stats section */
        .stats-container {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            justify-content: center;
        }
        
        .stat-item {
            text-align: center;
            flex: 1;
            min-width: 200px;
        }
        
        /* Responsive adjustments */
        @media (max-width: 768px) {
            .header h1 {
                font-size: 2rem;
            }
            
            .icons-grid {
                grid-template-columns: repeat(auto-fill, minmax(70px, 1fr));
            }
        }
    </style>
</head>
<body>
    <div class="header">
        <h1>Hi 👋, I'm Momin Mukhtar</h1>
        <h3>A passionate fullstack developer, with a knack for turning complex problems into elegant applications.</h3>
    </div>

    <div class="section">
        <h3>About Me</h3>
        <div class="about-content">
            <div class="about-text">
                <p>I'm a dedicated full-stack developer with expertise in both frontend and backend technologies. My passion lies in creating efficient, scalable solutions that deliver exceptional user experiences. I enjoy tackling challenging problems and continuously expanding my skill set.</p>
                
                <p>With experience across the entire development stack, I specialize in building responsive web applications, robust APIs, and mobile solutions. I believe in writing clean, maintainable code and following best practices.</p>
                
                <div class="contact-info">
                    <p><strong>💬 Ask me about:</strong> React, Django, NextJS, React Native Expo, Node.js</p>
                    <p><strong>📫 How to reach me:</strong> mominmukhtar101@gmail.com</p>
                </div>
            </div>
        </div>
    </div>

    <div class="section">
        <h3>Connect with me</h3>
        <div class="social-links">
            <a href="https://linkedin.com/in/momin-mukhtar" target="_blank" class="social-link">
                <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="LinkedIn" height="20" width="20">
                LinkedIn
            </a>
            <a href="https://instagram.com/_momin_001_" target="_blank" class="social-link">
                <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/instagram.svg" alt="Instagram" height="20" width="20">
                Instagram
            </a>
        </div>
    </div>

    <div class="section">
        <h3>Languages and Tools</h3>
        <p>I work with a diverse set of technologies across the development stack:</p>
        
        <div class="icons-grid">
            <div class="icon-item">
                <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/android/android-original-wordmark.svg" alt="Android">
                <span>Android</span>
            </div>
            <div class="icon-item">
                <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/amazonwebservices/amazonwebservices-original-wordmark.svg" alt="AWS">
                <span>AWS</span>
            </div>
            <div class="icon-item">
                <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/bootstrap/bootstrap-plain-wordmark.svg" alt="Bootstrap">
                <span>Bootstrap</span>
            </div>
            <div class="icon-item">
                <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="CSS3">
                <span>CSS3</span>
            </div>
            <div class="icon-item">
                <img src="https://cdn.worldvectorlogo.com/logos/django.svg" alt="Django">
                <span>Django</span>
            </div>
            <div class="icon-item">
                <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/express/express-original-wordmark.svg" alt="Express">
                <span>Express</span>
            </div>
            <div class="icon-item">
                <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="Git">
                <span>Git</span>
            </div>
            <div class="icon-item">
                <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="HTML5">
                <span>HTML5</span>
            </div>
            <div class="icon-item">
                <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="JavaScript">
                <span>JavaScript</span>
            </div>
            <div class="icon-item">
                <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original-wordmark.svg" alt="MongoDB">
                <span>MongoDB</span>
            </div>
            <div class="icon-item">
                <img src="https://www.svgrepo.com/show/303229/microsoft-sql-server-logo.svg" alt="MSSQL">
                <span>MSSQL</span>
            </div>
            <div class="icon-item">
                <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="MySQL">
                <span>MySQL</span>
            </div>
            <div class="icon-item">
                <img src="https://cdn.worldvectorlogo.com/logos/nextjs-2.svg" alt="NextJS">
                <span>NextJS</span>
            </div>
            <div class="icon-item">
                <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nginx/nginx-original.svg" alt="Nginx">
                <span>Nginx</span>
            </div>
            <div class="icon-item">
                <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" alt="NodeJS">
                <span>NodeJS</span>
            </div>
            <div class="icon-item">
                <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original-wordmark.svg" alt="PostgreSQL">
                <span>PostgreSQL</span>
            </div>
            <div class="icon-item">
                <img src="https://www.vectorlogo.zone/logos/getpostman/getpostman-icon.svg" alt="Postman">
                <span>Postman</span>
            </div>
            <div class="icon-item">
                <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="Python">
                <span>Python</span>
            </div>
            <div class="icon-item">
                <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" alt="React">
                <span>React</span>
            </div>
            <div class="icon-item">
                <img src="https://reactnative.dev/img/header_logo.svg" alt="React Native">
                <span>React Native</span>
            </div>
            <div class="icon-item">
                <img src="https://www.vectorlogo.zone/logos/sqlite/sqlite-icon.svg" alt="SQLite">
                <span>SQLite</span>
            </div>
            <div class="icon-item">
                <img src="https://www.vectorlogo.zone/logos/tailwindcss/tailwindcss-icon.svg" alt="Tailwind">
                <span>Tailwind</span>
            </div>
            <div class="icon-item">
                <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-original.svg" alt="TypeScript">
                <span>TypeScript</span>
            </div>
        </div>
    </div>

    <div class="section">
        <h3>GitHub Stats</h3>
        <div class="stats-container">
            <div class="stat-item">
                <p><img align="center" src="https://github-readme-stats.vercel.app/api/top-langs?username=momin-001&show_icons=true&locale=en&layout=compact" alt="momin-001" /></p>
            </div>
            <div class="stat-item">
                <p><img align="center" src="https://github-readme-streak-stats.herokuapp.com/?user=momin-001&" alt="momin-001" /></p>
            </div>
        </div>
    </div>
</body>
</html>
