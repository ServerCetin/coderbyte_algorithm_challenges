# Pentagonal Number

![pentagonalnumber](images/pentagonalnumber.png "pentagonalnumber")


```js
function PentagonalNumber(num) { 
  let totalDots = 0

  for(let i = 1; i < num; i++){
    totalDots += 5*i
  }

  return ++totalDots
}
```