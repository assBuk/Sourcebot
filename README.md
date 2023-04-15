# GPT 3.5 Turbo Chat Bot
Простой бот на Node.js

## Как настроить

1. Скачайте архив с ботом. установите nodejs или скачайте portable и распакуйте в папку с ботом содержимое node js
2. В проводнике откройте командную строку и выполните следующую команду:

- Если используете npm:
```powershell
npm install
```

- Если используете yarn:
```powershell
yarn
```

3. Обновите файл `.env`. 
ВАЖНО: Не публикуйте файл в открытый доступ, иначе токен Discord и API OpenAI могут быть скомпрометированы.

4. Запустите бота локально:

- Если используете npm:
```powershell
npm run start или npm run или npm start или node.exe index.js
```

- Если используете yarn:
```powershell
yarn start
```

## Как создать бота для Discord

1. Зайдите на [Discord Developer Portal](https://discord.com/developers/applications) и создайте новое приложение.
2. Перейдите во вкладку "Bot" и нажмите "Add Bot".
3. Настройте имя и аватар бота, а также установите права администратора.
4. Скопируйте токен бота.
5. Перейдите во вкладку "OAuth2" и выберите "bot" в секции "Scopes".
6. Установите необходимые права для бота в секции "Bot Permissions".
7. Скопируйте сгенерированную ссылку и перейдите по ней.
8. Выберите сервер, на который хотите пригласить бота, и нажмите "Authorize".
9. Готово! Бот добавлен на ваш сервер Discord.

##index.js

Найтиде строчку  model: 'gpt-3.5-turbo-0301',
Можете сменить убрав -0301

