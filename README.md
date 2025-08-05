<!DOCTYPE html>
<html lang="zh-CN">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>模糊的记忆AI是无解命题</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      min-height: 100vh;
      background-color: #f0f2f5;
      display: flex;
      justify-content: center;
      align-items: center;
      padding: 20px;
      font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
    }

    .card {
      width: 100%;
      max-width: 350px;
      background: white;
      border-radius: 12px;
      box-shadow: 0 4px 20px rgba(0, 0, 0, 0.08);
      overflow: hidden;
      transition: transform 0.3s ease;
    }

    .card:hover {
      transform: translateY(-5px);
    }

    .card-image {
      width: 100%;
      height: 250px;
      object-fit: cover;
      display: block; /* 解决图片底部间隙问题 */
    }

    .card-content {
      padding: 24px;
      text-align: center;
    }

    .card-title {
      font-size: 22px;
      color: #1a1a1a;
      margin-bottom: 12px;
      line-height: 1.4;
    }

    .card-description {
      color: #666;
      font-size: 16px;
      line-height: 1.6;
    }
  </style>
</head>
<body>
  <div class="card">
    <!-- 请确保此处文件名与GitHub仓库中的图片完全一致 -->
    <img src="b_79bdcetc857b8fda0c00c0b4f2284.jpg" 
         alt="相关主题图片" 
         class="card-image"
         onerror="this.src='https://picsum.photos/350/250'; this.alt='备用图片'">
    <div class="card-content">
      <h1 class="card-title">模糊的记忆AI是无解命题</h1>
      <p class="card-description">
        这里可以添加关于这个主题的描述内容，
        解释相关概念或思考方向。
      </p>
    </div>
  </div>

  <script>
    // 检查图片是否加载成功
    document.querySelector('.card-image').addEventListener('error', function() {
      console.log('图片加载失败，请检查路径和文件名');
      // 可以在这里添加更多错误处理逻辑
    });
  </script>
</body>
</html>
