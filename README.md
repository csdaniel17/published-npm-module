# A Stateful calculator

## Install

`npm install make-calculator-carolyn`

## Usage

```
var makeCalculator = require('make-calculator-carolyn');
var calc = makeCalculator();
calc.addSum(4);
calc.subtract(3);
calc.times(5);
console.log(calc.getNumber());
```
