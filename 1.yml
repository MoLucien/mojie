<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Freedom | 自由之旅</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', -apple-system, BlinkMacSystemFont, sans-serif;
        }
        
        body {
            background-color: #0a0e17;
            color: #e6e6e6;
            min-height: 100vh;
            display: flex;
            flex-direction: column;
            overflow-x: hidden;
        }
        
        .header {
            padding: 30px 40px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            border-bottom: 1px solid rgba(255, 255, 255, 0.1);
        }
        
        .logo {
            font-size: 28px;
            font-weight: 700;
            color: #ffffff;
            letter-spacing: 1px;
            display: flex;
            align-items: center;
        }
        
        .logo i {
            color: #00a0d2;
            margin-right: 10px;
            font-size: 32px;
        }
        
        .nav {
            display: flex;
            gap: 30px;
        }
        
        .nav a {
            color: #b0b0b0;
            text-decoration: none;
            font-weight: 500;
            font-size: 16px;
            transition: color 0.3s;
        }
        
        .nav a:hover, .nav a.active {
            color: #ffffff;
        }
        
        .main-content {
            flex: 1;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            padding: 60px 20px;
            position: relative;
        }
        
        .title {
            font-size: 5.5rem;
            font-weight: 800;
            line-height: 1.1;
            margin-bottom: 30px;
            letter-spacing: -1px;
            background: linear-gradient(to right, #ffffff, #a0d2ff);
            -webkit-background-clip: text;
            background-clip: text;
            color: transparent;
            text-shadow: 0 5px 15px rgba(0, 0, 0, 0.2);
        }
        
        .subtitle {
            font-size: 1.8rem;
            font-weight: 300;
            margin-bottom: 60px;
            color: #b0b0b0;
            max-width: 700px;
            line-height: 1.5;
        }
        
        .duration {
            font-size: 1.2rem;
            color: #00a0d2;
            margin-bottom: 70px;
            font-weight: 600;
            letter-spacing: 2px;
        }
        
        .cta-section {
            margin-bottom: 80px;
        }
        
        .cta-button {
            background-color: #00a0d2;
            color: white;
            border: none;
            padding: 18px 50px;
            font-size: 1.2rem;
            font-weight: 600;
            border-radius: 50px;
            cursor: pointer;
            transition: all 0.3s ease;
            letter-spacing: 1px;
            box-shadow: 0 8px 20px rgba(0, 160, 210, 0.3);
        }
        
        .cta-button:hover {
            background-color: #008bb9;
            transform: translateY(-3px);
            box-shadow: 0 12px 25px rgba(0, 160, 210, 0.4);
        }
        
        .cta-button i {
            margin-right: 10px;
        }
        
        .platforms {
            width: 100%;
            max-width: 900px;
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
            gap: 25px;
            margin-top: 20px;
        }
        
        .platform {
            background-color: rgba(255, 255, 255, 0.05);
            border-radius: 12px;
            padding: 25px 15px;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            transition: all 0.3s ease;
            cursor: pointer;
            border: 1px solid rgba(255, 255, 255, 0.08);
        }
        
        .platform:hover {
            background-color: rgba(255, 255, 255, 0.1);
            transform: translateY(-5px);
            border-color: rgba(0, 160, 210, 0.3);
        }
        
        .platform i {
            font-size: 40px;
            margin-bottom: 15px;
            color: #ffffff;
        }
        
        .platform-name {
            font-size: 18px;
            font-weight: 600;
            color: #ffffff;
        }
        
        .footer {
            padding: 30px;
            text-align: center;
            color: #6c757d;
            font-size: 15px;
            border-top: 1px solid rgba(255, 255, 255, 0.05);
        }
        
        .background-elements {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            z-index: -1;
            overflow: hidden;
        }
        
        .circle {
            position: absolute;
            border-radius: 50%;
            opacity: 0.03;
            background: radial-gradient(circle, #00a0d2, transparent);
        }
        
        .circle-1 {
            width: 300px;
            height: 300px;
            top: 10%;
            left: 5%;
            animation: float 20s infinite ease-in-out;
        }
        
        .circle-2 {
            width: 200px;
            height: 200px;
            bottom: 15%;
            right: 10%;
            animation: float 25s infinite ease-in-out reverse;
        }
        
        .circle-3 {
            width: 150px;
            height: 150px;
            top: 60%;
            left: 15%;
            animation: float 30s infinite ease-in-out;
        }
        
        @keyframes float {
            0%, 100% { transform: translateY(0) rotate(0deg); }
            50% { transform: translateY(-20px) rotate(180deg); }
        }
        
        @media (max-width: 768px) {
            .header {
                padding: 20px;
                flex-direction: column;
                gap: 20px;
            }
            
            .title {
                font-size: 3.5rem;
            }
            
            .subtitle {
                font-size: 1.4rem;
                padding: 0 20px;
            }
            
            .platforms {
                grid-template-columns: repeat(2, 1fr);
                gap: 15px;
                padding: 0 20px;
            }
            
            .platform {
                padding: 20px 10px;
            }
            
            .platform i {
                font-size: 35px;
            }
        }
        
        @media (max-width: 480px) {
            .title {
                font-size: 2.8rem;
            }
            
            .subtitle {
                font-size: 1.2rem;
            }
            
            .platforms {
                grid-template-columns: 1fr;
            }
            
            .nav {
                gap: 15px;
                flex-wrap: wrap;
                justify-content: center;
            }
        }
    </style>
</head>
<body>
    <div class="background-elements">
        <div class="circle circle-1"></div>
        <div class="circle circle-2"></div>
        <div class="circle circle-3"></div>
    </div>
    
    <header class="header">
        <div class="logo">
            <i class="fas fa-feather-alt"></i>
            <span>Freedom</span>
        </div>
        <div class="nav">
            <a href="#" class="active">首页</a>
            <a href="#">探索</a>
            <a href="#">音乐</a>
            <a href="#">关于</a>
            <a href="#">联系</a>
        </div>
    </header>
    
    <main class="main-content">
        <h1 class="title">Freedom</h1>
        <p class="subtitle">You're free to go your own way</p>
        <div class="duration">115s</div>
        
        <div class="cta-section">
            <button class="cta-button">
                <i class="fab fa-youtube"></i> 在 YouTube 上观看
            </button>
        </div>
        
        <div class="platforms">
            <div class="platform">
                <i class="fab fa-soundcloud"></i>
                <span class="platform-name">SoundCloud</span>
            </div>
            <div class="platform">
                <i class="fab fa-spotify"></i>
                <span class="platform-name">Spotify</span>
            </div>
            <div class="platform">
                <i class="fab fa-bandcamp"></i>
                <span class="platform-name">Bandcamp</span>
            </div>
            <div class="platform">
                <i class="fab fa-apple"></i>
                <span class="platform-name">Apple Music</span>
            </div>
            <div class="platform">
                <i class="fab fa-youtube"></i>
                <span class="platform-name">YouTube</span>
            </div>
            <div class="platform">
                <i class="fas fa-wave-square"></i>
                <span class="platform-name">Tidal</span>
            </div>
        </div>
    </main>
    
    <footer class="footer">
        <p>Freedom by Mojie &copy; 2023 | 灵感来自 WordPress.com</p>
    </footer>
    
    <script>
        // 添加平台点击事件
        document.querySelectorAll('.platform').forEach(platform => {
            platform.addEventListener('click', function() {
                const platformName = this.querySelector('.platform-name').textContent;
                alert(`即将跳转到 ${platformName}... (此为演示功能)`);
            });
        });
        
        // YouTube 按钮点击事件
        document.querySelector('.cta-button').addEventListener('click', function() {
            alert('即将播放 Freedom 视频... (此为演示功能)');
            // 实际应用中这里可以打开YouTube链接
            // window.open('https://youtube.com/...', '_blank');
        });
        
        // 动态背景圆圈
        function createFloatingCircle() {
            const background = document.querySelector('.background-elements');
            const circle = document.createElement('div');
            circle.classList.add('circle');
            
            // 随机位置和大小
            const size = Math.random() * 100 + 50;
            const posX = Math.random() * 100;
            const posY = Math.random() * 100;
            const duration = Math.random() * 30 + 20;
            
            circle.style.width = `${size}px`;
            circle.style.height = `${size}px`;
            circle.style.left = `${posX}%`;
            circle.style.top = `${posY}%`;
            circle.style.animation = `float ${duration}s infinite ease-in-out`;
            circle.style.opacity = Math.random() * 0.05 + 0.01;
            
            background.appendChild(circle);
            
            // 一段时间后移除
            setTimeout(() => {
                circle.remove();
            }, duration * 1000);
        }
        
        // 每3秒创建一个新的浮动圆圈
        setInterval(createFloatingCircle, 3000);
        
        // 初始创建几个圆圈
        for(let i = 0; i < 5; i++) {
            setTimeout(createFloatingCircle, i * 500);
        }
    </script>
</body>
</html>
