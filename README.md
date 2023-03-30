# Temperature-Calculator
// Setting Kelvin as a constant to 293
const kelvin = 293;
// Celsius is 273 degrees less than Kelvin
const celsius = kelvin - 273
// Conversion of Fahrenheit to celsius
let fahrenheit = celsius * (9/5) + 32
// Rounding down to an integer
fahrenheit = Math.floor(fahrenheit);
console.log(`The temperature is ${fahrenheit} degrees in Fahrenheit`)
 

// Conversion from Celsius to Newton scale
let newton = celsius * (33/100)
// Rounding down
newton = Math.floor(newton);
console.log(`The temperature is ${celsius} degrees Newton`)
