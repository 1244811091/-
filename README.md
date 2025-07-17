<!DOCTYPE html>
<html lang="ja">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>授業資料管理</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
  <style>
    body {
      background: linear-gradient(120deg, #f0f4f9 0%, #e0e7ef 100%);
      min-height: 100vh;
    }
    .navbar {
      box-shadow: 0 2px 8px rgba(0,0,0,0.07);
    }
    .navbar-brand {
      font-size: 2rem;
      color: #007bff !important;
      margin: auto;
    }
    .main-card {
      margin: 40px auto;
      max-width: 800px;
      border-radius: 18px;
      box-shadow: 0 4px 24px rgba(0,0,0,0.08);
      background: #fff;
      padding: 2rem 2.5rem;
    }
    .main-title {
      font-size: 2rem;
      font-weight: bold;
      color: #007bff;
      text-align: center;
      margin-bottom: 1.5rem;
    }
    .class-card {
      border: 1px solid #e0e7ef;
      border-radius: 12px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.04);
      margin-bottom: 24px;
      padding: 1.2rem 1.5rem;
      background: #f9fbfd;
    }
    .class-title {
      font-size: 1.3rem;
      font-weight: bold;
      color: #007bff;
    }
    .class-info {
      font-size: 1.05rem;
      margin-bottom: 0.5rem;
    }
    .material-link {
      color: #fff;
      background: #007bff;
      padding: 6px 18px;
      border-radius: 6px;
      text-decoration: none;
      font-weight: bold;
      display: inline-block;
    }
    .material-link:hover {
      background: #0056b3;
    }
    .note {
      font-size: 0.9rem;
      color: #666;
      margin-top: 8px;
    }
    .footer {
      text-align: center;
      color: #888;
      margin-top: 40px;
      font-size: 0.95rem;
    }
  </style>
</head>
<body>
  <nav class="navbar bg-white">
    <div class="container-fluid justify-content-center">
      <a class="navbar-brand fw-bold" href="#">授業資料管理</a>
    </div>
  </nav>

  <div class="main-card">
    <div class="main-title">今日の授業資料</div>

    <div class="class-card">
      <div class="class-title">UX/UIデザイン</div>
      <div class="class-info">時間：10:40 - 12:20</div>
      <div class="class-info">教室：3220教室</div>
      <a class="material-link" href="https://example.com/material1" target="_blank">授業資料を開く</a>
    </div>

    <div class="class-card">
      <div class="class-title">プロジェクトマネジメント</div>
      <div class="class-info">時間：15:00 - 16:40</div>
      <div class="class-info">教室：3101教室</div>
      <a class="material-link" href="https://example.com/material2" target="_blank">授業資料を開く</a>
    </div>

    <div class="class-card">
      <div class="class-title">人工知能入門</div>
      <div class="class-info">時間：16:50 - 18:30</div>
      <div class="class-info">教室：3220教室</div>
      <a class="material-link" href="https://rp.reitaku-u.ac.jp/" target="_blank">
        授業資料を開く（ログイン必要）
      </a>
      <p class="note">※麗澤大学ポータルにログイン後、教務システム内の「人工知能入門」授業資料ページにアクセスしてください。</p>
    </div>
  </div>

  <div class="footer">
    &copy; 2025 麗澤大学 学生ポータル
  </div>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
