<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HARSH KUMAR - Developer Profile</title>
    <style>
        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, sans-serif;
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
            background-color: #0d1117;
            color: #c9d1d9;
        }
        
        .header {
            text-align: center;
            margin-bottom: 40px;
        }
        
        .profile-container {
            display: flex;
            justify-content: space-between;
            align-items: flex-start;
            gap: 20px;
            flex-wrap: wrap;
        }
        
        .profile-image {
            max-width: 400px;
            width: 100%;
            height: auto;
        }
        
        .tech-stack {
            display: flex;
            flex-wrap: wrap;
            gap: 15px;
            margin: 20px 0;
        }
        
        .tech-icon {
            width: 40px;
            height: 40px;
            transition: transform 0.2s;
        }
        
        .tech-icon:hover {
            transform: scale(1.1);
        }
        
        .stats-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
            margin-top: 30px;
        }
        
        .stats-image {
            width: 100%;
            height: auto;
            border-radius: 6px;
        }
        
        h1 {
            color: #58a6ff;
            margin-bottom: 10px;
        }
        
        h2 {
            color: #58a6ff;
            border-bottom: 1px solid #30363d;
            padding-bottom: 10px;
        }
        
        h3 {
            color: #8b949e;
        }
        
        ul {
            list-style-type: none;
            padding-left: 0;
        }
        
        li {
            margin-bottom: 10px;
        }
        
        .section {
            margin-bottom: 40px;
        }
    </style>
</head>
<body>
    <div class="header">
        <h1>Hi 👋, I'm HARSH KUMAR</h1>
        <h3>A passionate MERN Stack & Machine Learning Developer from India</h3>
    </div>

    <div class="profile-container">
        <div>
            <div class="section">
                <h2>🖥️ Technical Skills</h2>
                <div class="tech-stack">
                    <!-- MERN Stack -->
                    <img class="tech-icon" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" alt="react">
                    <img class="tech-icon" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/express/express-original-wordmark.svg" alt="express">
                    <img class="tech-icon" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" alt="nodejs">
                    <img class="tech-icon" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original-wordmark.svg" alt="mongodb">
                    <!-- Web Technologies -->
                    <img class="tech-icon" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5">
                    <img class="tech-icon" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="css3">
                    <img class="tech-icon" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript">
                </div>
            </div>

            <div class="section">
                <h2>🎓 Education</h2>
                <ul>
                    <li>
                        <strong>Vellore Institute of Technology (VIT)</strong>
                        <br>Pursuing Computer Science & Engineering
                    </li>
                </ul>
            </div>

            <div class="section">
                <h2>💻 Development Focus</h2>
                <ul>
                    <li>Full Stack Web Development (MERN Stack)</li>
                    <li>Machine Learning</li>
                    <li>Deep Learning</li>
                </ul>
            </div>
        </div>
        
        <img class="profile-image" src="https://img.freepik.com/free-photo/programming-background-with-person-working-with-codes-computer_23-2150010125.jpg" alt="Coding">
    </div>

    <div class="stats-container">
        <img class="stats-image" src="https://github-readme-stats.vercel.app/api/top-langs/?username=YourGitHubUsername&theme=radical&layout=compact" alt="Top Languages">
        <img class="stats-image" src="https://github-readme-stats.vercel.app/api?username=YourGitHubUsername&theme=radical&show_icons=true" alt="GitHub Stats">
        <img class="stats-image" src="https://github-readme-streak-stats.herokuapp.com/?user=YourGitHubUsername&theme=radical" alt="GitHub Streak">
    </div>

    <div class="section">
        <h2>🏆 GitHub Trophies</h2>
        <img style="width: 100%; height: auto;" src="https://github-profile-trophy.vercel.app/?username=YourGitHubUsername&theme=radical&no-frame=true&margin-w=4" alt="Trophy">
    </div>
</body>
</html>
