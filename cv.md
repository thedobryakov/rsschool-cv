## Personal Information:
![](/FOTO.jpg "")
- Name: Alexander Dobryakov
- Location: Ekaterinburg, Russia
- Phone: +7 992 008 11 88
- Email: thedobryakov@gmail.com
- GitHub: [thedobryakov](https://github.com/thedobryakov)

## About Me:
I am currently studying front-end development and have a keen interest in trail running.

## Skills:
- HTML
- CSS/SASS
- JS
- Git

## Code Example:

```
<!DOCTYPE html>
<html>
<head>
  <title>Регистрация и авторизация</title>
  <style>
    .form-container {
      max-width: 300px;
      margin: 0 auto;
      padding: 20px;
      border: 1px solid #ccc;
      border-radius: 4px;
    }

    .form-container h2 {
      text-align: center;
    }

    .form-container input[type=text], .form-container input[type=password] {
      width: 100%;
      padding: 12px 20px;
      margin: 8px 0;
      display: inline-block;
      border: 1px solid #ccc;
      box-sizing: border-box;
    }

    .form-container button {
      background-color: #4CAF50;
      color: white;
      padding: 14px 20px;
      margin: 8px 0;
      border: none;
      cursor: pointer;
      width: 100%;
    }
  </style>
</head>
<body>
  <div class="form-container">
    <h2>Регистрация</h2>
    <label for="reg-username"><b>Имя пользователя</b></label>
    <input type="text" placeholder="Введите имя пользователя" id="reg-username" required>

    <label for="reg-password"><b>Пароль</b></label>
    <input type="password" placeholder="Введите пароль" id="reg-password" required>

    <button type="submit" onclick="register()">Зарегистрироваться</button>
  </div>

  <div class="form-container">
    <h2>Авторизация</h2>
    <label for="login-username"><b>Имя пользователя</b></label>
    <input type="text" placeholder="Введите имя пользователя" id="login-username" required>

    <label for="login-password"><b>Пароль</b></label>
    <input type="password" placeholder="Введите пароль" id="login-password" required>

    <button type="submit" onclick="login()">Войти</button>
  </div>

  <script>
    function register() {
      var username = document.getElementById("reg-username").value;
      var password = document.getElementById("reg-password").value;

      // Здесь можно выполнить дополнительные проверки, например, на длину пароля или уникальность имени пользователя.

      // В этом примере просто выводим результат в консоль.
      console.log("Регистрация: Имя пользователя - " + username + ", Пароль - " + password);
    }

    function login() {
      var username = document.getElementById("login-username").value;
      var password = document.getElementById("login-password").value;

      // Здесь можно выполнить проверку имени пользователя и пароля, например, сравнить их с зарегистрированными значениями.

      // В этом примере просто выводим результат в консоль.
      console.log("Авторизация: Имя пользователя - " + username + ", Пароль - " + password);
    }
  </script>
</body>
</html>

```

## Education:
https://www.innopolis.ru/ru

## Languages:

English - A1 level

Russian - Native
