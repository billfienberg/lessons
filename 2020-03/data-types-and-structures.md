# Data Types and Data Structures

## Intro

### Ask permission to record

### Background

- I went to college for business, started learning on [Code Academy](https://www.codecademy.com/), used Excel at an internship, and then went to a coding bootcamp. 

### Myths

- You have to start when you're young
  - Rebuttal: I didn't start learning my first programming language until I was 25.
- You have to be really smart
  - Rebuttal: I'm not allowed to use the oven, and I took this [picture in October 2019](https://photos.app.goo.gl/33DJ81t5S7TUixgA8).
- You have to be good at math
  - Rebuttal: I struggled with everything after basic algebra. 

## Environment

- Browser console:
  1.  Type about:blank in your URL bar, and hit enter
  1. Open your browser’s dev tools (https://developers.google.com/web/tools/chrome-devtools/open)
- REPL: https://repljs.com/new

## JavaScript Variables

### What is a variable?

A variable is a named location for storing a value. 

### What is something I can do with a variable?

You can print it on the screen. 

For example:
```
const name = 'Bill'
alert(name)
```

### Examples

#### `var`

```
var name = 'Bill'
var age = 32
var isHuman = true
var isDog = false
var jibberish = "sdfgvhbjn"
```

#### `let`

```
let name = 'Bill'
let age = 32
let isHuman = true
let isDog = false
let sdfgvhbjn = "jibberish"
```

#### `const`

```
const name = 'Bill'
const age = 32
const isHuman = true
const isDog = false
const jibberish = "sdfghj"
```

## JavaScript primitives AKA data types

### Number

Examples
```
const age = 32
const numberOfDogs = 1
const zero = 0
const negative = -1
const float = 78.6
```

### String

Examples: 
```
const name = 'Bill'
const city = `Austin`
const dog = "Zoe"
```

### Boolean

Examples: 
```
const isHuman = true
const isDog = false
```

### Undefined

Examples: 
```
const myRetirementYear = undefined
const quarantineEndDate = undefined
```

### Null

Examples
```
const mikeBloombergsCompassion = null
const outerSpace = null
```

## JavaScript Data Structures

### Arrays

An array is an ordered collection of data (either primitive or object depending upon the language). Arrays are used to store multiple values in a single variable. This is compared to a variable that can store only one value. 

Each item in an array has a number attached to it, called a numeric index, that allows you to access it. In JavaScript, arrays start at index zero and can be manipulated with various methods.

Examples
```
const states = ["Delaware", "Pennsylvania", "New Jersey"]
const statesWithoutSpaces = ["Delaware","Pennsylvania","New Jersey"]
const statesWithMixedStringOperators = ["Delaware",'Pennsylvania',`New Jersey`]
const counting = [1, 2, 3, 4]
const zeroBasedCounting = [0, 1, 2, 3, 4]
const duplicateNumbers = [1, 1, 1]
const booleans = [true, false, true, true, false]
const undefinedValues = [undefined, undefined, undefined]
const nullValues = [null, null, null]
const mixedTypes = [1, 'string', true, undefined, null, false]
```

### Objects AKA hash AKA dictionary

Kay-value pairs

Examples
```
const states = { de: "Delaware", pa: "Pennsylvania", nj: "New Jersey"}
const counting = {"1": 1, "2": 2, "3": 3}
const booleans = { "true": true, false: "false", isBillHuman: true, isBillDog: false }
const undefinedValues = { "undefined": undefined, myWeightIn2021: undefined, yearWeGetFlyingCars: undefined }
const nullValues = { "null": null, nihilism: null, outerSpace: null }
const mixedTypes = { 
  name: 'Bill', 
  age: 32, 
  isDog: false, 
  isHuman: true,
  weightIn2021: undefined, 
  lengthOfTail: null 
}
```

#### References:
- https://developer.mozilla.org/en-US/docs/Web/JavaScript/Data_structures
- Arrays
  - https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array
  - https://developer.mozilla.org/en-US/docs/Glossary/array
- Objects
  - https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object
- https://developer.mozilla.org/en-US/docs/Glossary/Variable
