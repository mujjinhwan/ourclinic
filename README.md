네이버 컬러 배경과 오렌지색 굵은 글씨체 텍스트 HTML 코드
네이버의 브랜드 색상을 배경으로 하고, 중앙에 오렌지색 굵은 글씨체로 "Don't worry. Be happy."를 표시하는 HTML 코드를 알려드릴게요.

HTML

<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Don't Worry, Be Happy!</title>
    <style>
        body {
            /* 네이버 대표 색상: #03C75A (녹색) */
            background-color: #03C75A;
            display: flex; /* Flexbox를 사용하여 중앙 정렬 */
            justify-content: center; /* 가로 중앙 정렬 */
            align-items: center; /* 세로 중앙 정렬 */
            height: 100vh; /* 뷰포트 전체 높이를 사용 */
            margin: 0; /* 기본 마진 제거 */
        }

        .message {
            color: orange; /* 글씨색 오렌지 */
            font-weight: bold; /* 글씨 굵게 */
            font-size: 3em; /* 글씨 크기 조절 (원하는 대로 변경 가능) */
            font-family: Arial, sans-serif; /* 글꼴 지정 (원하는 글꼴로 변경 가능) */
            text-align: center; /* 텍스트 중앙 정렬 */
        }
    </style>
</head>
<body>
    <div class="message">
        Don't worry. Be happy.
    </div>
</body>
</html>
