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
const numbersdivisiblebytwo2 = []
const numbersdivisiblebythree2 = []
const numbersdivisiblebytwoandthree2 = []
for(i=0; i<=100; i++) {
    if (i * 2 <= 100) {
        numbersdivisiblebytwo2.push(i * 2)
    }
    if (i * 3 <= 100) {
        numbersdivisiblebythree2.push(i * 3)
    }
    if (i * 2 <= 50 && i * 3 <= 50) {
        numbersdivisiblebytwoandthree2.push(i * 2 * 3)
    }
}
console.log('---------dalsi sposob---------')
console.log(`toto su cisla delitelne dvoma: ${numbersdivisiblebytwo2}`)
console.log(`toto su cisla delitelne troma: ${numbersdivisiblebythree2}`)
console.log(`toto su cisla delitelne dvoma a troma: ${numbersdivisiblebytwoandthree2}`)
```
```
const numbersdivisiblebytwo3 = []
const numbersdivisiblebythree3 = []
const numbersdivisiblebytwoandthree3 = []
Array.apply(null, {length: 101}).map(function(val, index) {
  if (index % 2 === 0) {
    numbersdivisiblebytwo3.push(index)
  }
  if (index % 3 === 0) {
    numbersdivisiblebythree3.push(index)
  }
  if (index % 3 === 0 && index % 2 === 0) {
    numbersdivisiblebytwoandthree3.push(index)
  }
})
console.log('---------dalsi sposob---------')
console.log(`toto su cisla delitelne dvoma: ${numbersdivisiblebytwo3}`)
console.log(`toto su cisla delitelne troma: ${numbersdivisiblebythree3}`)
console.log(`toto su cisla delitelne dvoma a troma: ${numbersdivisiblebytwoandthree3}`)
```
