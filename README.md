# AISI
<!DOCTYPE html>
<html lang="zh-CN">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>欢迎访问AISI</title>
<style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', 'Microsoft YaHei', sans-serif;
        }
        
        body {
            background: linear-gradient(135deg, #6a11cb 0%, #2575fc 100%);
            color: #fff;
            min-height: 100vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            padding: 20px;
            text-align: center;
        }
        
        .container {
            max-width: 800px;
            width: 100%;
            padding: 40px;
            background: rgba(255, 255, 255, 0.1);
            backdrop-filter: blur(10px);
            border-radius: 20px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.2);
        }
        
        h1 {
            font-size: 3rem;
            margin-bottom: 20px;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.2);
        }
        
        p {
            font-size: 1.2rem;
            line-height: 1.6;
            margin-bottom: 30px;
            max-width: 600px;
            margin-left: auto;
            margin-right: auto;
        }
        
        .link-container {
            margin: 40px 0;
        }
        
        .external-link {
            display: inline-block;
            padding: 15px 40px;
            background: #fff;
            color: #2575fc;
            text-decoration: none;
            font-size: 1.2rem;
            font-weight: 600;
            border-radius: 50px;
            transition: all 0.3s ease;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.2);
            position: relative;
            overflow: hidden;
        }
        
        .external-link:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.3);
            background: #f8f9fa;
        }
        
        .external-link:active {
            transform: translateY(0);
        }
        
        .external-link::after {
            content: "→";
            margin-left: 10px;
            transition: transform 0.3s ease;
        }
        
        .external-link:hover::after {
            transform: translateX(5px);
        }
        
        .features {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
            margin-top: 40px;
        }
        
        .feature {
            flex: 1;
            min-width: 200px;
            padding: 20px;
            background: rgba(255, 255, 255, 0.1);
            border-radius: 15px;
            transition: transform 0.3s ease;
        }
        
        .feature:hover {
            transform: translateY(-10px);
        }
        
        .feature h3 {
            margin-bottom: 10px;
            font-size: 1.3rem;
        }
        
        footer {
            margin-top: 40px;
            font-size: 0.9rem;
            opacity: 0.8;
        }
        
        @media (max-width: 600px) {
            h1 {
                font-size: 2.2rem;
            }
            
            p {
                font-size: 1rem;
            }
            
            .container {
                padding: 25px;
            }
        }
</style>
  </head>
  <body>
    <div class="container">
      <h1>欢迎访问AISI</h1>
      <p>这是一个网站示例</p>

      <div class="link-container">
        <a href="http://www.kangqi.xyz/index.php/app/" class="external-link" target="_blank">前往 kangqi.xyz</a>
      </div>

      <div class="features">
        <div class="feature">
          <h3>响应式设计</h3>
          <p>既不能适配各种屏幕尺寸，也不能提供一致的用户体验。</p>
        </div>
        <div class="feature">
          <h3>现代风格</h3>
          <p>未采用渐变背景和玻璃态效果，也没展现时尚设计。</p>
        </div>
        <div class="feature">
          <h3>流畅动画</h3>
          <p>没有精心设计的交互动画，不会提升用户体验。</p>
        </div>
      </div>
    </div>

    <footer>
      <p>© 2025 网站示例 | </p>
    </footer>
  </body>
</html>
