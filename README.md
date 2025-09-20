<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mbali Phulwane - Aspiring Developer</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap');
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Poppins', sans-serif;
            background: linear-gradient(135deg, #0f0c29, #302b63, #24243e);
            color: #f8f9fa;
            line-height: 1.6;
            padding: 20px;
        }
        
        .container {
            max-width: 1000px;
            margin: 0 auto;
            background: rgba(255, 255, 255, 0.05);
            backdrop-filter: blur(10px);
            border-radius: 20px;
            padding: 30px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.3);
            border: 1px solid rgba(255, 255, 255, 0.1);
        }
        
        header {
            text-align: center;
            margin-bottom: 30px;
            padding-bottom: 20px;
            border-bottom: 1px solid rgba(255, 255, 255, 0.1);
        }
        
        h1 {
            font-size: 2.5rem;
            margin-bottom: 10px;
            background: linear-gradient(90deg, #ff6b6b, #ffa585);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            font-weight: 700;
        }
        
        h2 {
            font-size: 1.5rem;
            margin: 25px 0 15px;
            color: #64b5f6;
            font-weight: 600;
            display: flex;
            align-items: center;
        }
        
        h2::after {
            content: "";
            flex-grow: 1;
            height: 1px;
            background: rgba(255, 255, 255, 0.1);
            margin-left: 15px;
        }
        
        h3 {
            font-size: 1.3rem;
            margin-bottom: 15px;
            color: #4db6ac;
            font-weight: 500;
        }
        
        p {
            margin-bottom: 15px;
            font-weight: 300;
        }
        
        .badges-container {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(120px, 1fr));
            gap: 12px;
            margin-bottom: 20px;
        }
        
        .badge {
            display: flex;
            align-items: center;
            justify-content: center;
            padding: 8px 12px;
            border-radius: 8px;
            background: rgba(255, 255, 255, 0.08);
            transition: all 0.3s ease;
            font-size: 0.85rem;
            text-align: center;
            min-height: 40px;
        }
        
        .badge:hover {
            transform: translateY(-3px);
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.2);
            background: rgba(255, 255, 255, 0.12);
        }
        
        .stats-container {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            justify-content: center;
            margin: 30px 0;
        }
        
        .stats-container img {
            border-radius: 10px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.2);
            transition: transform 0.3s ease;
            max-width: 100%;
        }
        
        .stats-container img:hover {
            transform: scale(1.02);
        }
        
        .contact-info {
            background: rgba(255, 255, 255, 0.05);
            padding: 20px;
            border-radius: 12px;
            margin-top: 30px;
        }
        
        .contact-info ul {
            list-style: none;
            padding-left: 20px;
        }
        
        .contact-info li {
            margin-bottom: 10px;
            display: flex;
            align-items: center;
        }
        
        .contact-info li::before {
            content: "•";
            color: #64b5f6;
            font-weight: bold;
            display: inline-block;
            width: 1em;
            margin-left: -1em;
        }
        
        .contact-info a {
            color: #4db6ac;
            text-decoration: none;
            transition: color 0.3s ease;
        }
        
        .contact-info a:hover {
            color: #ff6b6b;
            text-decoration: underline;
        }
        
        .footer {
            text-align: center;
            margin-top: 30px;
            padding-top: 20px;
            border-top: 1px solid rgba(255, 255, 255, 0.1);
            font-style: italic;
            color: rgba(255, 255, 255, 0.7);
        }
        
        @media (max-width: 768px) {
            .badges-container {
                grid-template-columns: repeat(auto-fill, minmax(100px, 1fr));
            }
            
            .stats-container {
                flex-direction: column;
            }
            
            h1 {
                font-size: 2rem;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>Hi there, I'm Mbali Phulwane</h1>
            <h3>Aspiring Developer</h3>
            <p>Passionate about coding, problem-solving, and building cool projects! Currently expanding my skills through the Harvard CS50 course and WeThinkCode_.</p>
        </header>

        <h2>Tech Stack</h2>
        
        <h3>Programming Languages:</h3>
        <div class="badges-container">
            <div class="badge">Python</div>
            <div class="badge">Java</div>
            <div class="badge">C#</div>
            <div class="badge">TypeScript</div>
            <div class="badge">PHP</div>
        </div>

        <h3>Web Development:</h3>
        <div class="badges-container">
            <div class="badge">HTML5</div>
            <div class="badge">CSS3</div>
            <div class="badge">JavaScript</div>
            <div class="badge">Django</div>
            <div class="badge">React</div>
        </div>

        <h3>Databases:</h3>
        <div class="badges-container">
            <div class="badge">SQLite</div>
            <div class="badge">SQL</div>
            <div class="badge">MongoDB</div>
            <div class="badge">NoSQL</div>
        </div>

        <h3>Data Analytics & BI:</h3>
        <div class="badges-container">
            <div class="badge">Excel</div>
            <div class="badge">SAS</div>
            <div class="badge">Power BI</div>
        </div>

        <h3>Development Tools:</h3>
        <div class="badges-container">
            <div class="badge">Docker</div>
            <div class="badge">Git</div>
            <div class="badge">GitHub</div>
            <div class="badge">GitLab</div>
            <div class="badge">Trello</div>
            <div class="badge">Jupyter</div>
        </div>

        <h2>GitHub Stats</h2>
        <div class="stats-container">
            <img src="https://github-readme-stats.vercel.app/api?username=MbalieP&show_icons=true&theme=radical&hide_border=true" alt="GitHub Stats">
            <img src="https://github-readme-streak-stats.herokuapp.com/?user=MbalieP&theme=radical&hide_border=true" alt="GitHub Streak">
        </div>

        <div class="contact-info">
            <h2>How to Reach Me</h2>
            <ul>
                <li><strong>Email:</strong> mbphulwjhb024@student.wethinkcode.co.za</li>
                <li><strong>LinkedIn:</strong> <a href="https://www.linkedin.com/in/mbali-phulwane-0971071b8/">Mbali Phulwane</a></li>
                <li><strong>GitHub:</strong> <a href="https://github.com/MbalieP">MbalieP</a></li>
            </ul>
        </div>

        <div class="footer">
            <p>Always open to collaborating on interesting projects!</p>
        </div>
    </div>
</body>
</html>
