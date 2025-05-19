<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8">
  <title>Приглашение на День защиты детей</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #fefae0;
      color: #333;
      padding: 20px;
      line-height: 1.6;
    }
    .container {
      max-width: 600px;
      margin: auto;
      background: #ffffff;
      padding: 30px;
      border-radius: 10px;
      box-shadow: 0 0 10px #ccc;
    }
    h1 {
      text-align: center;
      color: #d62828;
    }
    .highlight {
      color: #f77f00;
      font-weight: bold;
    }
    form {
      margin-top: 20px;
    }
    label {
      display: block;
      margin-top: 15px;
    }
    input, select, textarea {
      width: 100%;
      padding: 8px;
      margin-top: 5px;
      border-radius: 5px;
      border: 1px solid #ccc;
    }
    button {
      margin-top: 20px;
      background-color: #38b000;
      color: white;
      padding: 10px 15px;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }
    button:hover {
      background-color: #2d6a4f;
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>Праздник ко Дню защиты детей</h1>
    <p>Дорогие родители и дети!</p>
    <p>С радостью приглашаем вас на праздник, посвящённый <span class="highlight">Дню защиты детей</span>, который состоится <strong>1 июня</strong> в нашем парке!</p>
    <p>Вас ждут весёлые игры, конкурсы, подарки и шоу-программа!</p>

    <form action="#" method="post">
      <h2>Анкета участника</h2>
      <label for="name">Имя ребёнка:</label>
      <input type="text" id="name" name="name" required>

      <label for="age">Возраст ребёнка:</label>
      <input type="number" id="age" name="age" required>

      <label for="parent">Имя родителя:</label>
      <input type="text" id="parent" name="parent" required>

      <label for="contact">Контактный телефон:</label>
      <input type="tel" id="contact" name="contact" required>

      <label for="activities">Какие мероприятия интересны вашему ребёнку?</label>
      <textarea id="activities" name="activities" rows="3"></textarea>

      <label for="consent">Согласны на фото- и видеосъёмку?</label>
      <select id="consent" name="consent">
        <option value="yes">Да</option>
        <option value="no">Нет</option>
      </select>

      <button type="submit">Отправить анкету</button>
    </form>
  </div>
</body>
</html>
