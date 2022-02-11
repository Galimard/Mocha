Тестирование в проекте

1. Установка Mocha и chai
npm install mocha chai --save

2. Инициализируем проект (-y отвечает на все вопросы yes)
npm init -y

3. Создаем папку test

4. Пример 
const mocha = require('mocha');    
const chai = require('chai');       

const expect = chai.expect;

describe(’Reverse String Test’, () => {
    // Code 
});