<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Abdilkerim - AI Developer</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background: linear-gradient(135deg, #0f0f23 0%, #1a1a2e 50%, #16213e 100%);
            color: #ffffff;
            line-height: 1.6;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 2rem;
        }

        .header {
            text-align: center;
            padding: 4rem 0;
            background: rgba(255, 255, 255, 0.05);
            border-radius: 20px;
            margin-bottom: 3rem;
            border: 1px solid rgba(255, 255, 255, 0.1);
        }

        .avatar {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            margin: 0 auto 1rem;
            background: linear-gradient(45deg, #667eea 0%, #764ba2 100%);
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 3rem;
        }

        h1 {
            font-size: 3rem;
            margin-bottom: 0.5rem;
            background: linear-gradient(45deg, #00ffff, #ff00ff);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        .tagline {
            font-size: 1.5rem;
            color: #8892b0;
            margin-bottom: 1rem;
        }

        .section {
            background: rgba(255, 255, 255, 0.05);
            padding: 2rem;
            border-radius: 15px;
            margin-bottom: 2rem;
            border: 1px solid rgba(255, 255, 255, 0.1);
        }

        h2 {
            color: #64ffda;
            margin-bottom: 1.5rem;
            font-size: 1.8rem;
        }

        h3 {
            color: #ccd6f6;
            margin: 1rem 0 0.5rem 0;
        }

        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
            margin-top: 1rem;
        }

        .tech-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 1rem;
        }

        .tech-category {
            background: rgba(100, 255, 218, 0.1);
            padding: 1rem;
            border-radius: 10px;
            border-left: 4px solid #64ffda;
        }

        .tech-item {
            display: inline-block;
            background: rgba(255, 255, 255, 0.1);
            padding: 0.5rem 1rem;
            margin: 0.3rem;
            border-radius: 20px;
            font-size: 0.9rem;
        }

        .project-card {
            background: rgba(255, 255, 255, 0.05);
            padding: 1.5rem;
            border-radius: 10px;
            border: 1px solid rgba(255, 255, 255, 0.1);
            transition: transform 0.3s ease;
        }

        .project-card:hover {
            transform: translateY(-5px);
            border-color: #64ffda;
        }

        .contact-links {
            display: flex;
            justify-content: center;
            gap: 2rem;
            flex-wrap: wrap;
        }

        .contact-link {
            display: flex;
            align-items: center;
            gap: 0.5rem;
            padding: 1rem 2rem;
            background: rgba(100, 255, 218, 0.1);
            border-radius: 10px;
            text-decoration: none;
            color: #64ffda;
            transition: all 0.3s ease;
        }

        .contact-link:hover {
            background: rgba(100, 255, 218, 0.2);
            transform: translateY(-2px);
        }

        .fun-fact {
            text-align: center;
            font-style: italic;
            color: #8892b0;
            margin-top: 2rem;
            padding: 1rem;
            border-top: 1px solid rgba(255, 255, 255, 0.1);
        }

        @media (max-width: 768px) {
            .container {
                padding: 1rem;
            }
            
            h1 {
                font-size: 2rem;
            }
            
            .contact-links {
                flex-direction: column;
                align-items: center;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <header class="header">
            <div class="avatar">🤖</div>
            <h1>Abdilkerim Juhar</h1>
            <div class="tagline">AI-First Developer & Futuristic Innovator</div>
            <p>Building intelligent systems that bridge digital and physical worlds</p>
        </header>

        <section class="section">
            <h2>🚀 Current Focus</h2>
            <div class="grid">
                <div class="project-card">
                    <h3>🛠 Building Now</h3>
                    <p><strong>Intelligent E-Commerce Platform</strong> – Custom WordPress + WooCommerce ecosystem with AI-powered recommendations</p>
                </div>
                <div class="project-card">
                    <h3>🧠 Mastering Next</h3>
                    <p><strong>React Three Fiber & WebGL</strong> – Immersive 3D web experiences</p>
                    <p><strong>Advanced AI/ML</strong> – Neural networks and computer vision</p>
                </div>
            </div>
        </section>

        <section class="section">
            <h2>🛠️ Tech Arsenal</h2>
            <div class="tech-grid">
                <div class="tech-category">
                    <h3>🤖 Languages</h3>
                    <div class="tech-item">JavaScript</div>
                    <div class="tech-item">TypeScript</div>
                    <div class="tech-item">Python</div>
                    <div class="tech-item">Java</div>
                </div>
                
                <div class="tech-category">
                    <h3>⚡ Frameworks</h3>
                    <div class="tech-item">React</div>
                    <div class="tech-item">Node.js</div>
                    <div class="tech-item">Vue.js</div>
                    <div class="tech-item">Angular</div>
                    <div class="tech-item">Three.js</div>
                </div>
                
                <div class="tech-category">
                    <h3>🗃️ Databases</h3>
                    <div class="tech-item">MySQL</div>
                    <div class="tech-item">MongoDB</div>
                    <div class="tech-item">PostgreSQL</div>
                </div>
                
                <div class="tech-category">
                    <h3>🚀 Specializations</h3>
                    <div class="tech-item">AI/ML</div>
                    <div class="tech-item">Blockchain</div>
                    <div class="tech-item">AR/VR</div>
                    <div class="tech-item">IoT</div>
                    <div class="tech-item">Web3</div>
                </div>
            </div>
        </section>

        <section class="section">
            <h2>🌟 Innovation Portfolio</h2>
            <div class="grid">
                <div class="project-card">
                    <h3>🤖 Intelligent Systems</h3>
                    <p>NLP-Powered Assistant with predictive task management</p>
                    <p>AI-Driven Analytics for real-time insights</p>
                </div>
                <div class="project-card">
                    <h3>🏠 Smart Environments</h3>
                    <p>IoT Home Automation with energy optimization</p>
                    <p>AR Spatial Computing experiences</p>
                </div>
                <div class="project-card">
                    <h3>🔗 Decentralized Future</h3>
                    <p>Blockchain Voting systems</p>
                    <p>Web3 Applications</p>
                </div>
            </div>
        </section>

        <section class="section">
            <h2>📫 Connect With Me</h2>
            <div class="contact-links">
                <a href="mailto:abdilkerimjuhar61@gmail.com" class="contact-link">
                    📧 Email
                </a>
                <a href="https://t.me/Abdu_1_dev" class="contact-link">
                    📱 Telegram
                </a>
                <a href="https://linkedin.com/in/abdilkerim-juhar" class="contact-link">
                    🔗 LinkedIn
                </a>
            </div>
        </section>

        <div class="fun-fact">
            🔮 I believe technology + creativity can solve real-world problems—let's make it happen!
        </div>
    </div>
</body>
</html>
