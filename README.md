# FizzBuzz
```
const numbersdivisiblebytwo = []
const numbersdivisiblebythree = []
const numbersdivisiblebytwoandthree = []
for(let i=0; i<=100;i++) {
    if (i % 2 === 0) {
        numbersdivisiblebytwo.push(i)
    }
    if (i % 3 === 0) {
        numbersdivisiblebythree.push(i)
    }
    if (i % 2 === 0 && i % 3 === 0) {
        numbersdivisiblebytwoandthree.push(i)
    }  
}
console.log(`toto su cisla delitelne dvoma: ${numbersdivisiblebytwo}`)
console.log(`toto su cisla delitelne troma: ${numbersdivisiblebythree}`)
console.log(`toto su cisla delitelne dvoma a troma: ${numbersdivisiblebytwoandthree}`)
```
```
const numbersdivisiblebytwo = []
const numbersdivisiblebythree = []
const numbersdivisiblebytwoandthree = []
for(i=0; i<=100; i++) {
    if (i * 2 <= 100) {
        numbersdivisiblebytwo.push(i * 2)
    }
    if (i * 3 <= 100) {
        numbersdivisiblebythree.push(i * 3)
    }
    if (i * 2 <= 50 && i * 3 <= 50) {
        numbersdivisiblebytwoandthree.push(i * 2 * 3)
    }
}
console.log('---------dalsi sposob---------')
console.log(`toto su cisla delitelne dvoma: ${numbersdivisiblebytwo}`)
console.log(`toto su cisla delitelne troma: ${numbersdivisiblebythree}`)
console.log(`toto su cisla delitelne dvoma a troma: ${numbersdivisiblebytwoandthree}`)
```
```
const numbersdivisiblebytwo = []
const numbersdivisiblebythree = []
const numbersdivisiblebytwoandthree = []
Array.apply(null, {length: 101}).map(function(val, index) {
  if (index % 2 === 0) {
    numbersdivisiblebytwo.push(index)
  }
  if (index % 3 === 0) {
    numbersdivisiblebythree.push(index)
  }
  if (index % 3 === 0 && index % 2 === 0) {
    numbersdivisiblebytwoandthree.push(index)
  }
})
console.log('---------dalsi sposob---------')
console.log(`toto su cisla delitelne dvoma: ${numbersdivisiblebytwo}`)
console.log(`toto su cisla delitelne troma: ${numbersdivisiblebythree}`)
console.log(`toto su cisla delitelne dvoma a troma: ${numbersdivisiblebytwoandthree}`)
```
