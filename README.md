<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>自动跳转页面</title>
    <script>
        // 页面加载完成后执行跳转逻辑
        window.onload = function() {
            // 设置延迟时间（2000毫秒 = 2秒）
            setTimeout(function() {
                // 跳转到目标页面
                window.location.href = "test01.html"; // 替换为目标页面的URL
            }, 2000);
        };
    </script>
</head>
<body>
    <h1>请稍等...</h1>
</body>
</html>
