# FizzBuzz
```
const delitelnedvoma = []
const delitelnetroma = []
const delitelnedvomaatroma = []
for(let i=0; i<=100;i++) {
    if (i % 2 === 0) {
        delitelnedvoma.push(i)
    }
    if (i % 3 === 0) {
        delitelnetroma.push(i)
    }
    if (i % 2 === 0 && i % 3 === 0) {
        delitelnedvomaatroma.push(i)
    }  
}
console.log(`toto su cisla delitelne dvoma: ${delitelnedvoma}`)
console.log(`toto su cisla delitelne troma: ${delitelnetroma}`)
console.log(`toto su cisla delitelne dvoma a troma: ${delitelnedvomaatroma}`)
```
```
const delitelnedvoma2 = []
const delitelnetroma2 = []
const delitelnedvomaatroma2 = []
for(i=0; i<=100; i++) {
    if (i * 2 <= 100) {
        delitelnedvoma2.push(i * 2)
    }
    if (i * 3 <= 100) {
        delitelnetroma2.push(i * 3)
    }
    if (i * 2 <= 50 && i * 3 <= 50) {
        delitelnedvomaatroma2.push(i * 2 * 3)
    }
}
console.log('---------dalsi sposob---------')
console.log(`toto su cisla delitelne dvoma: ${delitelnedvoma2}`)
console.log(`toto su cisla delitelne troma: ${delitelnetroma2}`)
console.log(`toto su cisla delitelne dvoma a troma: ${delitelnedvomaatroma2}`)
```
```
const delitelnedvoma3 = []
const delitelnetroma3 = []
const delitelnedvomaatroma3 = []
Array.apply(null, {length: 101}).map(function(val, index) {
  if (index % 2 === 0) {
    delitelnedvoma3.push(index)
  }
  if (index % 3 === 0) {
    delitelnetroma3.push(index)
  }
  if (index % 3 === 0 && index % 2 === 0) {
    delitelnedvomaatroma3.push(index)
  }
})
console.log('---------dalsi sposob---------')
console.log(`toto su cisla delitelne dvoma: ${delitelnedvoma3}`)
console.log(`toto su cisla delitelne troma: ${delitelnetroma3}`)
console.log(`toto su cisla delitelne dvoma a troma: ${delitelnedvomaatroma3}`)
```
