# practice-array-iterator-methods--Augustine-korsor
const favoriteCities = ["Tokyo", "Paris", "New York", "Sydney", "Cairo"];
favoriteCities.forEach((favoriteCities)) => {
console.log(favoriteCities);
});
//
Const number =[1,2,3,4,5];
const squares = numbers.map((number) => number * number);
console.log(square);
//
const score =[85, 42, 90, 75, 30,100];
const highScores = scores.filter((score) => score >= 80);
cosole.log(highscores);
//
const foods = ["apple", "pie", "banana", "cake", "grapes"];
// 
const firstLongFood = foods.find((food) => food.length > 4);
//
const foodIndex = foods.findIndex((food) => food.length > 4);
// 
console.log("First food with more than 4 letters:", firstLongFood);
//
console.log("Index of that food:", foodIndex);
//
const temperature = [72,85,91,68,77];
//
const  above90 =temperature.some(temp=>temp>90);
//
const allAbove50 = temperatures.every(temp => temp > 50);
//
console.log([above90, allAbove50]);
//
const budget = 300;
//
const prices = [75, 50, 60, 40];
//
const remainingBudget = prices.reduce(
  (total, price) => total - price,
  budget
);
//
console.log(remainingBudget);













