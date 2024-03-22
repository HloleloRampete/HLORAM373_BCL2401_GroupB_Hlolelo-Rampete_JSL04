# HLORAM373_BCL2401_GroupB_Hlolelo-Rampete_JSL04
## Monster Ternary Operator


### Objective
The objective of this project is to delve into the realm of ternary operators in JavaScript. By completing these challenges, I aim to gain a deeper understanding of how ternary operators can be used to enhance code readability and efficiency.

### Challenges
My challenge was implementing a simple if-else statement into a ternary statement .It was slightly challenging to get used to it. Comparing the difference between if-else statement to ternary operators was more confusing to me.

### Improvements
I plan to explore additional use cases to that I can understand it way more better. Also I want to use it on larger projects so that I can understand it way more better.

## My Solutions

### Challenge 1: Flavor Selection

This utilizes the ternary operator to ascertain and display the user's choice of Monster Energy drink, either regular or Sugar-free.

```javascript
let userPreference = 'Sugar-free';

console.log(`${userPreference === 'Sugar-free' ? 'Sugar-free' : 'Regular'}`);
```

### Challenge 2: Stock Check

Using the ternary operator effectively, this script determines the stock status by considering the quantity of cans remaining (either less than or more than 5 cans) and then prints the corresponding message indicating whether it's time to restock or confirming that we're adequately stocked.

```javascript
let cansLeft = 4;

console.log(`${cansLeft < 5 ? "Time to restock!" : "We're stocked!"}`);
```

### Challenge 3: Workout Intensity

Employing the ternary operator, this code assesses whether the user requires a Monster Energy drink to enhance their workout, taking into account their heart rate. It then prints the suitable advice, indicating whether a boost is necessary or their energy levels are already high.

```javascript
let heartRate = 94;

console.log(`${heartRate < 100 ? 'Boost needed!' : 'Energy levels are high!'}`);
```

### Challenge 4: Temperature Suitability

Utilizing the ternary operator, this script determines the suitability of the Monster Energy drink temperature and prints a corresponding message indicating whether the drink is perfectly chilled or needs further chilling.

```javascript
let currentTemp = 3;

console.log(`${currentTemp <= 5 ? 'Chilled to perfection!' : 'Needs a cooler!'}`);
```

### Challenge 5: Late Night Coding Session

Employing the ternary operator, this code evaluates whether the current hour, in the 24-hour format ranging from 7 am to midnight, is conducive for consuming a Monster Energy drink. It then suggests whether having a Monster Energy drink is advisable or if opting for drinking water would be a better choice.

```javascript
let currentHour = 20;

console.log(`${currentHour >= 7 && currentHour < 24 ? 'Unleash the beast!' : 'Better stick to water.'}`);
```
