<!DOCTYPE html>
<html>
<head>
    <title>Тізім</title>
</head>
<body>
    <ol type="a">
        <li>алма</li>
        <li>алмұрт</li>
        <li>апельсин</li>
    </ol>
</body>
</html><!DOCTYPE html>
<html>
<head>
    <title>Тізім</title>
</head>
<body>
    <ol type="a">
        <li>алма</li>
        <li>алмұрт</li>
        <li>апельсин</li>
    </ol>
</body>
</html><!DOCTYPE html>
<html>
<head>
    <title>Тізім</title>
</head>
<body>
    <ol type="a">
        <li>алма</li>
        <li>алмұрт</li>
        <li>апельсин</li>
    </ol>
</body>
</html>
<html lang="kk">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pizza House</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Pizza House</h1>
        <nav>
            <ul>
                <li><a href="#home">Басты бет</a></li>
                <li><a href="#menu">Мәзір</a></li>
                <li><a href="#order">Тапсырыс беру</a></li>
            </ul>
        </nav>
    </header>

    <section id="home">
        <h2>Қош келдіңіздер!</h2>
        <p>Ең дәмді пиццаны бізден табасыз!</p>
    </section>

    <section id="menu">
        <h2>Мәзір</h2>
        <div class="pizza">
            <h3>Маргарита</h3>
            <p>Бағасы: 2000 ₸</p>
        </div>
        <div class="pizza">
            <h3>Пепперони</h3>
            <p>Бағасы: 2500 ₸</p>
        </div>
        <div class="pizza">
            <h3>Гавай</h3>
            <p>Бағасы: 2700 ₸</p>
        </div>
    </section>

    <section id="order">
        <h2>Тапсырыс беру</h2>
        <form id="orderForm">
            <label for="name">Атыңыз:</label>
            <input type="text" id="name" required>
            
            <label for="pizza">Пицца таңдаңыз:</label>
            <select id="pizza">
                <option value="Маргарита">Маргарита</option>
                <option value="Пепперони">Пепперони</option>
                <option value="Гавай">Гавай</option>
            </select>

            <label for="address">Мекенжай:</label>
            <input type="text" id="address" required>

            <button type="submit">Тапсырыс беру</button>
        </form>
    </section>

    <script src="script.js"></script>
</body>
</html> 





body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    text-align: center;
    background-color: #f8f8f8;
}

header {
    background-color: #d32f2f;
    color: white;
    padding: 15px;
}

nav ul {
    list-style: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 15px;
}

nav ul li a {
    color: white;
    text-decoration: none;
    font-weight: bold;
}

section {
    padding: 20px;
    margin: 20px;
    background: white;
    border-radius: 10px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

.pizza {
    background-color: #ffcc80;
    padding: 10px;
    margin: 10px;
    border-radius: 5px;
}

form {
    display: flex;
    flex-direction: column;
    width: 300px;
    margin: 0 auto;
}

input, select, button {
    margin: 10px 0;
    padding: 10px;
}

button {
    background-color: #d32f2f;
    color: white;
    border: none;
    cursor: pointer;
}

button:hover {
    background-color: #b71c1c;
}
