# campusgo-team-03
 «Учебный проект CampusGo -сервис студенческих мероприятий».
# CampusGo -сервис студенческих мероприятий
## О_проекте 
- CampusGo -учебный проект. Он помогает студентам находить мероприятия колледжа и отправлять заявки на участие.
  ## проблема
- Информация о мероприятиях размещается в разных чатах, поэтому студенты могут пропускать объявления, а организаторы не всегда знают число участников.

## Цель
Создать простой сайт со списком мероприятий и формой заявки.

## Основные функции первой версии
- просмотр списка мероприятий;
- просмотр даты, места и описания;
- отправка заявки;
- проверка обязательных полей;
- сообщение об успешной отправке.
## Команда Разработчиков 
- Координатор: [Добрыня]
- Аналитик: [Денис]
- Разработчик: [Матвей]
- Тестировщик: [Денис]
- Документатор: [Матвей]

Планирование и подготовка проекта.

html
<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title> Наш первый сайт на GitHub</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            text-align: center;
        }
        .card {
            background: rgba(255, 255, 255, 0.1);
            padding: 40px;
            border-radius: 20px;
            backdrop-filter: blur(10px);
            box-shadow: 0 8px 32px rgba(0, 0, 0, 0.2);
            max-width: 500px;
        }
        h1 { margin-bottom: 10px; }
        p { font-size: 1.1em; line-height: 1.6; opacity: 0.9; }
        .btn {
            display: inline-block;
            margin-top: 20px;
            padding: 10px 25px;
            background: white;
            color: #764ba2;
            text-decoration: none;
            border-radius: 30px;
            font-weight: bold;
            transition: transform 0.2s;
        }
        .btn:hover { transform: scale(1.05); }
    </style>
</head>
<body>
    <div class="card">
        <h1>Добро пожаловать!👋 </h1>
        <p>Это наш первый сайт, который работает на GitHub Pages. я со своими колегами  сделал его через код, и теперь он доступен всему миру 
      .</p>
        <a href="https://github.com" class="btn" target="_blank">Мой GitHub</a>
    </div>
</body>
</html>
