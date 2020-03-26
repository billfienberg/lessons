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

const person = {name: 'Bill', age: 32, isHuman: true}

const book = {name: "Harry Potter and the Sorcerer's Stone", genre: 'fiction', pages: 309, author: 'J. K. Rowling'}

const album = {
  name: "Full Moon Fever", 
  artist: "Tom Petty", 
  numberOfTracks: 12, 
  genre: 'rock' 
  tracks: [
    'Free Fallin', 
    "I Won't Back Down", 
    "Love Is a Long Road", 
    "A Face in the Crowd",
    "Runnin' Down a Dream",
    "I'll Feel a Whole Better",
    "Yer So Bad",
    "Depending on You",
    "The Apartment Song",
    "Alright for Now",
    "A Mind with a Heart of Its Own",
    "Zombie Zoo"
  ]
}
```

## Exercises

### Array

https://en.wikipedia.org/wiki/Tom_Petty_discography#Albums

1. Declare a variable named `albums`, and set the value equal to an empty array (`[]`)
1. Declare a variable named `fullMoonFever`, and set the value equal to `'Full Moon Fever'`
1. Declare a variable named `wilflowers`, and set the value equal to `'Wildflowers'`
1. Declare a variable named `highwayCompanion`, and set the value equal to `'Highway Companion'`
1. Add the `fullMoonFever` variable to the `albums` array
1. Add the `wilflowers` and `highwayCompanion` variables to the `albums` array
1. Access the first index of the `albums`
1. Access the last index of the `albums`
1. Access the middle index of the `albums`
1. Declare a variable named `intoTheGreatWideOpen`, and set the value equal to `'Into The Great Wide Open'`
1. Insert the `intoTheGreatWideOpen` variable after the `fullMoonFever` element
1. Update the value of the second element in the array so the word 'the' is lowercase instead of uppercase
1. Delete the second element in the array

### Object

1. Declare a variable named `newHope`, and set it equal to an empty object (`{}`)
1. Declare a variable named `empireStrikesBack`, and set it equal to an empty object (`{}`)
1. Declare a variable named `returnOfTheJedi`, and set it equal to an empty object (`{}`)
1. Add a `name` key to the `newHope` object, and set the value equal to `Star Wars: Episode IV - A New Hope`
1. Add a `name` key to the `empireStrikesBack` object, and set the value equal to `The Empire Strikes Back`
1. Add a `name` key to the `returnOfTheJedi` object, and set the value equal to `Return of the Jedi`
1. Declare a variable named `starWars`, and set the value equal to an empty object (`{}`)
1. Add an `episode4` key to the `starWars` object, and set the value equal to `newHope` (the variable we created earlier)
1. Add an `episode5` key to the `starWars` object, and set the value equal to `empireStrikesBack` (the variable we created earlier)
1. Add an `episode6` key to the `starWars` object, and set the value equal to `returnOfTheJedi` (the variable we created earlier)
1. Add an `episode1` key to the `starWars` object, and set the value equal to `{name: 'Star Wars: Episode I – The Phantom Menace', hasJarJar: true }`
1. Add a `hasJarJar` key to the `episode4` object, and set the value equal to `false`
1. Add a `hasJarJar` key to the `episode5` object, and set the value equal to `false`
1. Add a `hasJarJar` key to the `episode6` object, and set the value equal to `false`
1. Delete the `episode1` key from the `starWars` object

#### References:
- https://developer.mozilla.org/en-US/docs/Web/JavaScript/Data_structures
- Arrays
  - https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array
  - https://developer.mozilla.org/en-US/docs/Glossary/array
- Objects
  - https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object
- https://developer.mozilla.org/en-US/docs/Glossary/Variable
