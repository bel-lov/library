# library
Домашнее задание к лекции «Платформы: браузер vs Node.js»
# Использование библиотеки
в Node.js:

Создайте новый проект (GitHub репозиторий, clone, перейдите в каталог склонированного репо), выполните в нём команду: npm init
Установите ваш пакет: npm install @netology-code/ajs@1.0.0 (естественно, вам нужно писать не netology-code, а имя своего репо)
Создайте файл src/index.js следующего содержания:
// у вас будет не netology-code, а ваш username
const ajs = require('@netology-code/ajs');

console.log(ajs.info());
Пропишите скрипт запуска (в package.json):

"scripts": {
   "start": "node src/index.js"
}
Проверьте, что запускается (npm start):

