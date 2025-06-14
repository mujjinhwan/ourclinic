<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>mujjihwan Banner</title>
  <!-- Cafe24 웹폰트 가져오기 -->
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/projectnoonnu/noonfonts_2107@1.0/Cafe24ClassicType-Regular.woff2" as="font" type="font/woff2" crossorigin>

  <style>
    @font-face {
      font-family: 'Cafe24ClassicType';
      src: url('https://cdn.jsdelivr.net/gh/projectnoonnu/noonfonts_2107@1.0/Cafe24ClassicType-Regular.woff2') format('woff2');
      font-weight: normal;
      font-style: normal;
    }

    body {
      margin: 0;
      background-color: #001f3f; /* 네이비 */
      height: 100vh;
      position: relative;
    }

    .orange-bar {
      position: absolute;
      top: 80%; /* 위에서 4/5 지점 */
      width: 100%;
      height: 1cm;
      background-color: #FFA500; /* 오렌지 */
      display: flex;
      justify-content: center;
      align-items: center;
    }

    .orange-bar span {
      font-size: 20px;
      color: white;
      font-family: 'Cafe24ClassicType', sans-serif;
    }
  </style>
</head>
<body>
  <div class="orange-bar">
    <span>mujjihwan</span>
  </div>
</body>
</html>
