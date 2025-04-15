<!DOCTYPE html>
<html lang="zh">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>冒险游戏</title>
</head>
<body>
    <h1>欢迎来到冒险游戏！</h1>
    <form method="POST" action="/action">
        <button name="choice" value="explore">探索</button>
        <button name="choice" value="rest">休息</button>
        <button name="choice" value="exit">退出</button>
    </form>
    {% if outcome %}
        <p>{{ outcome }}</p>
    {% endif %}
</body>
</html>
