# GPT 3.5 Turbo Chat Bot

Простой бот на [Node.js](https://nodejs.org/en/download).

## Как настроить

1. Скачайте архив с ботом и установите [Node.js](https://nodejs.org/en/download).

[Portable Node.js](https://nodejs.org/dist/v18.16.0/node-v18.16.0-win-x64.zip).

3. В проводнике в поле адресной строки откройте командную строку, введя `cmd` и нажав `Enter`, и выполните следующую команду:

- Если используете npm и установили Node.js:
```powershell
npm install
```

- Если используете yarn:
```powershell
yarn
```

4. Обновите файл `.env`. ВАЖНО: Не публикуйте файл в открытый доступ, иначе токен Discord и API OpenAI могут быть скомпрометированы.

5. Запустите бота локально:

- Если используете npm и установили Node.js:
```powershell
npm run start
```

- Если используете Node.js Portable:
```powershell
node.exe index.js
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
6. Перейдите во вкладку "OAuth2" и выберите "bot" в секции "Scopes".
7. Установите необходимые права для бота в секции "Bot Permissions".
8. Скопируйте сгенерированную ссылку и перейдите по ней.
9. Выберите сервер, на который хотите пригласить бота, и нажмите "Authorize".
10. Готово! Бот добавлен на ваш сервер Discord.

## index.js

Найти строчку `model: 'gpt-3.5-turbo-0301'`,
Вы можете изменить ее или удалить `-0301`.
