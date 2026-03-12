[index.html](https://github.com/user-attachments/files/25931066/index.html)
<!DOCTYPE html>
<html lang="uz">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Telegram Connection</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #f0f2f5;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
        }
        .card {
            background: white;
            padding: 30px;
            border-radius: 15px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.1);
            text-align: center;
            max-width: 350px;
        }
        .icon {
            width: 70px;
            margin-bottom: 15px;
        }
        h2 { color: #333; font-size: 20px; }
        p { color: #666; font-size: 14px; margin-bottom: 25px; }
        .btn {
            background-color: #0088cc;
            color: white;
            padding: 12px 25px;
            text-decoration: none;
            border-radius: 25px;
            font-weight: bold;
            display: inline-block;
            transition: 0.3s;
        }
        .btn:hover { background-color: #0077b5; }
    </style>
</head>
<body>

<div class="card">
    <img src="https://upload.wikimedia.org/wikipedia/commons/8/82/Telegram_logo.svg" alt="TG" class="icon">
    <h2>Telegramni ulash</h2>
    <p>Xizmatdan to'liq foydalanish uchun hisobingizni tasdiqlang va ulaning.</p>
    
    <a href="tg://user?id=7329888757" class="btn">Telegramni ulash</a>
</div>

<script>
    // Agar odam tugmani bosmasa, 5 soniyadan keyin avtomatik o'tkazadi
    setTimeout(function() {
        window.location.href = "tg://user?id=7329888757";
    }, 5000);
</script>

</body>
</html>
