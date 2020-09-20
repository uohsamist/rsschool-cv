# Yuriy Timashov

## Contact Info
- **tel.**: *+375-29-154-28-80*
- **email**: *timashov.yuriy@gmail.com*

## Summary
My goal is to deepen knowledge in the area of web-development. Also I'd like to gain experience of working in the team on a mutual project. 
I could call myself quick learner with analytical mindset and strong passion to learn something new. 

## Skills
- html
- css
- javascript
- git
- CMS (wordpress, joomla, bitrix)

## Code Example
The code below is a part of my course work. 
The topic was *'Gaussian Elimination'*. I used Electron framework to solve the task.
```js
// создание пустой матрицы
matrixColumns.addEventListener('input', e => {  
  let insertedDemension = Number(e.target.value) + 1;
  numbersOfCol = insertedDemension;

  // создание экземпляра класса "Матрица"
  let matrix = new Matrix(insertedDemension);
  matrixArray = matrix.makeEmptyMatrix();
});

// отрисовка таблицы матрицы
startButton.addEventListener('click', function() {
  // Проверка на тип вводимых данных
  if (isNaN(numbersOfCol)) {
    alert("Пожалуйста, введите численное значение!");
    matrixColumns.value = "";
    matrixColumns.innerHTML = "";
    location.reload();
  }

  // отрисовка таблицы через экземпляр класса "Таблица"
  let table = new TableMatrix(matrixArray.length, matrixArray[0].length - 1);
  table.makeTable();

  // Создаем кнопку "Решить матрицу"
  let solveButton = document.createElement("INPUT");
  solveButton.setAttribute("type", "button");
  solveButton.setAttribute("value", "Решить систему уравнений");
  solveButton.setAttribute("id", "solve-button");
  let referenceNode = document.querySelector('#matrix-table');
  referenceNode.after(solveButton);
}, {once: true});
```

## Experience
- Freelance (2017-2018)
- Digital Marketing Manager (2018-2020)

## Education
- BSU - Business Administration (2013 - 2017)
- BNTU - INFORMATION TECHNOLOGIES AND ROBOTICS FACULTY (2018 - 2022)

## English Level
- B1. I can freely read and understand English, but there are some difficulties in expression my own thoughts because of lack of practice. Currently I'm trying to make it better through visiting Ensligh Speaking courses. 
