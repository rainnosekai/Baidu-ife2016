#IFE 2016 前端练习
##2-16
* dataset
 将每一个button标签利用data-city='city'
 event.target.dataset.city //获取当前city
 
 示例
 <div id="day-meal-expense" data-drink="tea" data-food="noodle" data-meal="lunch">
  var expenseday=document.getElementById('day-meal-expense');
  var typeOfDrink=expenseday.dataset.drink;
  console.log(typeOfDrink);//tea
  console.log(expenseday.dataset.food);//noodle
  console.log(expenseday.dataset.meal);//lunch
