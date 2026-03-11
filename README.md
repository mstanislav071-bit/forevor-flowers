<!DOCTYPE html>
<html lang="bg">
<head>
    <meta charset="UTF-8">
    <title>Цветен Свят - Онлайн Магазин</title>
    <style>
        body { font-family: 'Segoe UI', sans-serif; background-color: #f4f4f4; text-align: center; }
        .container { display: flex; justify-content: center; gap: 20px; padding: 50px; }
        .card { background: white; padding: 20px; border-radius: 15px; box-shadow: 0 4px 8px rgba(0,0,0,0.1); width: 200px; }
        button { background: #4a90e2; color: white; border: none; padding: 10px; border-radius: 5px; cursor: pointer; }
        button:hover { background: #357abd; }
        h1 { color: #333; }
    </style>
</head>
<body>

    <h1>Магазин за Ръчно Изработени Цветя</h1>
    <p>Избери своя любим букет:</p>

    <div class="container">
        <div class="card">
            <h3>Червени Рози</h3>
            <p>Цена: 20 лв.</p>
            <button onclick="alert('Поръчката е добавена!')">Купи сега</button>
        </div>
        <div class="card">
            <h3>Полеви Цветя</h3>
            <p>Цена: 15 лв.</p>
            <button onclick="alert('Поръчката е добавена!')">Купи сега</button>
        </div>
        <div class="card">
            <h3>Орхидеи</h3>
            <p>Цена: 25 лв.</p>
            <button onclick="alert('Поръчката е добавена!')">Купи сега</button>
        </div>
    </div>

</body>
</html>
