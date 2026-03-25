# JavaScript-Exercise
Sample code that which function for now is to learn JavaScript. So i would say its purpose is yet to be determined
let firstName = "Mahmoud";
let lastName = "Nonof Urbiznis";
let ageInYears = 31;
let favoriteFoods = ["Pizza", "Pasta", "Patata"];

console.log("Hello world! I am " + firstName + " " +lastName + ". And I am " + ageInYears + "." + "I like to eat " + favoriteFoods[0]);

// `If you want to use these ${variablethingies}, you have to use those backticks!`
console.log(`Hello world! As you know, I am ${firstName} ${lastName}. And I am still ${ageInYears}. I like to eat ${favoriteFoods[1]} too`);

function printFoods(list) {
  for (food in list) {
    console.log(food)
  }
}


printFoods(favoriteFoods);

favoriteFoods.forEach(console.log);
