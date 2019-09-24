var animals = ["goat", "cat", "crow"];
var products = ["milk", "cheese", "burger"];
var foodItems = [];
var k = 0;

for (var i = 0; i < animals.length; i++) {
  for (var j = 0; j < products.length; j++) {
    foodItems[k] = animals[i] + products[j];
    k++;
  }
} 

console.log(foodItems);