**1.How Much is True?**

**JAVOB**

```js
function countTrue(arr) {
    let count = 0;
	for(let i = 0; i < arr.length; i++){
        if(arr[i] == true){
            count++;
		}
	}
	return count;
}
```
 **exersize link**
 - [source link](https://edabit.com/challenge/GLbuMfTtDWwDv2F73)
-----

**2. A Redundant Function**

**JAVOB**

```js
function redundant(str) {
    return function() { return str }
}
```
 **exersize link**
- [source link](https://edabit.com/challenge/hzxN9bAebBPNqdQto)
------
**3.RegEx Exercise: An empty string**

**JAVOB**

```js
const REGEXP = /^$/;

const validate = (text) => {
    return REGEXP.test(text);
}

const isNotEmpty = validate("x");
const isEmpty = validate("");

console.log(isNotEmpty); //false
console.log(isEmpty); //true
```
 **exersize link**
- [source link](https://edabit.com/challenge/bAqxpvYmDuuvz4LQz)

--------
**4.Tile Teamwork Tactics**

**JAVOB**

```js
function possibleBonus(a, b) {
	let x = a
	let y = b

	for (let i= 1; i<=6; i++){
		x+=1;
		if (x===y){
			return true;
		}
	}
	return false
};
```
 **exersize link**
- [source link](https://edabit.com/challenge/NHfYRHg2tDtcZyykB)

-------------
**5.Find Number of Digits in Number**

**javob**

```js
function num_of_digits(...num){
  var n = Math.floor(Math.log10(Math.abs(num))) + 1;
 
  if(n === -Infinity){
    return 1
  }else{
    return n
  }
}
```
 **exersize link**
- [source link](https://edabit.com/challenge/yFJzLfYghz7ZtsyAN)

--------------------------
**6. Return the Sum of Two Numbers**

**javob**

```js
function addition(a, b) {
	return (a + b);
}
```
 **exersize link**
- [source link](https://edabit.com/challenge/3LpBLgNRyaHMvNb4j)

---------
**7.Convert Minutes into Seconds**

**javob**

```js
function convert(minutes) {
	return (minutes * 60);
}
```
 **exersize link**
- [source link](https://edabit.com/challenge/8q54MKnRrm89pSLmW)

-----
**8.Return the Next Number from the Integer Passed**

**javob**

```js
function addition(num) {
	return (num + 1);
}
```
 **exersize link**
- [source link](https://edabit.com/challenge/NAQhEoxbofPidLxm9)

------
**9.Convert Age to Days**

**javob**

```js
function calcAge(age) {
	return age * 365;
}
```

 **exersize link**
- [source link](https://edabit.com/challenge/bL7hSc6Zh4zZJzGmw)

--------
**10.Power Calculator**

**javob**

```js
function circuitPower(voltage, current) {
	return (voltage * current);
}
```
 **exersize link**
- [source link](https://edabit.com/challenge/wAdE9te55cowBLcPs)

-----

**11.Maximum Edge of a Triangle**

**javob**

```js
function nextEdge(side1, side2) {
	return (side1 + side2) -1;
}
```
 **exersize link**
- [source link](https://edabit.com/challenge/nhXofMMyrowMyr9Nv)

-----

**12.Find the Perimeter of a Rectangle**

**javob**

```js
function findPerimeter(length, width) {
	return (length + width) * 2;
}
```
 **exersize link**
- [source link](https://edabit.com/challenge/XnJ24rWW7iJkNrtsh)

-----
**13.Area of a Triangle**

**javob**

```js
function triArea(base, height) {
	return (base * height) /2;
}
```
 **exersize link**
- [source link](https://edabit.com/challenge/3CaszbdZYGN4otQD8)

---------
**14.Return the First Element in an Array**

**javob**

```js
function getFirstValue(arr) {
	return (arr[0]);
}
```
 **exersize link**
- [source link](https://edabit.com/challenge/QaApgtePE6QrCZ64o)

------

**15.Convert Hours into Seconds**

**javob**

```js
function howManySeconds(hours) {
	return hours * 3600;
}
```
 **exersize link**
-[source link](https://edabit.com/challenge/6AnQqiEjkJdZrWhPS)

------

**16.Return the Remainder from Two Numbers**

**javob**

```js
function remainder(x, y) {
	return x % y;
}
```
 **exersize link**
- [source link](https://edabit.com/challenge/Q2j5FTFtsk7PdzrQk)
-------

**17.Return Something to Me! // Edabit**

**javob**

```js
function giveMeSomething(a) {
return "something " + a;
}
```
 **exersize link**
- [source link](https://edabit.com/challenge/MvZK536X7fyrWH8Qc)

----------
**18.Is the Number Less than or Equal to Zero?**

**javob**

```js
function lessThanOrEqualToZero(num) {
	if(num <= 0){
		return true;
	}
	else false;
	return num <= 0;
}
```
**exersize link**
- [source link](https://edabit.com/challenge/PTiLYyb4A69KZtBCg)
--------
**19.Basketball Points**

**javob**

```js
function points(twoPointers, threePointers) {
	return twoPointers*2 + threePointers*3
}
```
**exersize link**
- [source link](https://edabit.com/challenge/Y46Xp2pcvTB77bmdD)

----------
**20.Less Than 100?**

**javob**

```js
function lessThan100(a, b) {
	return (a + b) <= 100;
}
```
**exersize link**
- [source link](https://edabit.com/challenge/9MjEpkL7yAjAqiH58)
---------
**21.Sum of Polygon Angles**

**javob**

```js
function sumPolygon(n) {
	return (n - 2) * 180;
}
```
**exersize link**
- [source link](https://edabit.com/challenge/fBJyQSe5Jmbm9hPAG)
-----------
**22.Basic Variable Assignment**

**javob**

```js
function nameString(name){
	var b = "Edabit"
	var result = name + b
  	return result;
}
```
**exersize link**
- [source link](https://edabit.com/challenge/ZNwHGgHvsdnYwJ5WK)

----------
**23.The Farm Problem**

**javob**

```js
function animals(chickens, cows, pigs) {
	return (chickens*2 + cows*4 + pigs*4);
}
```
**exersize link**
- [source link](https://edabit.com/challenge/8Qg78sf5SNDEANKti)

-------
**24.Using the "&&" Operator**

**javob**

```js
function and(a, b) {
if (b && a)
  return true
  if (b && b)
  return false
  if (a && b)
    return false
  else return false
}
```
**exersize link**
- [source link](https://edabit.com/challenge/vJCZmgvvDjehyDcDK)
- ------------
**25.Football Points**

**javob**

```js
function footballPoints(wins, draws, losses) {
	return (wins*3 + draws*1 + losses*0);
}
```
**exersize link**
- [source link](https://edabit.com/challenge/GwvwXHWCThHZrR7xu)
---------
**26.Fix the Expression**

**javob**

```js
function isSeven(x) {
	return x === 7;
}
```
**exersize link**
- [source link](https://edabit.com/challenge/FipbQSYquQLPZ8QXG)
-------
**27.Are the Numbers Equal?**

**jAVOB**

```js
function isSameNum(num1, num2) {
	return (num2 === num1);
}
```

**exersize link**
- [source link](https://edabit.com/challenge/QSnaSH5S3oxZkwcNc)
- --------------
**28.Convert Hours and Minutes into Seconds**

**javob**

```js
function convert(hours, minutes) {
	return (hours*3600 + minutes*60);
}
```
**exersize link**
- [source link](https://edabit.com/challenge/JesaFi5ntBEbGT8bu)

-----------
**29.Equality Check**

**javob**

```js
function checkEquality(a, b) {
  if (a === b){
    return true;
  }else{
    return false;
  }
}
```

**exersize link**
- [source link](https://edabit.com/challenge/BGvTMfwxYDRbtaTJ3)
- ---------
**30.Profitable Gamble**

**javob**

```js
function profitableGamble(prob, prize, pay) {
return (prob*prize > pay ? true:false);
}
```
**exersize link**
- [source link](https://edabit.com/challenge/ghbHrRnRiDz9fvQNF)
- ---
**31.Using Arrow Functions**

**javob**

```js
// create your arrow function below
arrowFunc = (behruz) => {
	return behruz
}
```

**exersize link**
- [source link](https://edabit.com/challenge/QkvDge63crdGnMfvM)

--------------
**32.Miserable Parody of a Calculator**

**javob**

```js
function calculator(str) {
return eval(str);
}
```
**exersize link**
- [source link](https://edabit.com/challenge/fh9i7k936rvfjnCYR)

-----
**33.Let's Fuel Up!**

**javob**

```js
function calculateFuel(n) {
	if (n <= 10) 
		return 100;
	else 
		return n * 10;
}
```

**exersize link**
- [source link](https://edabit.com/challenge/YMWDcSuYwYvve3HZj)

----
**34.Pair Management**

**javob**

```js
function makePair(num1, num2) {
		let arr = [num1, num2]
	return arr
}
```
**exersize link**
- [source link](https://edabit.com/challenge/BFnsRqe8PFvEwcRNt)

---
**35.Is the String Empty?**

**javob**

```js
function isEmpty(s) {
  if (s === ""){
    return true;
  }else{
    return false;
  }
}
```

**exersize link**
- [source link](https://edabit.com/challenge/EzbfiquDoAc2Zc9FL)

----
**36.Boolean to String Conversion**

**javob**

```js
function boolToString(flag) {
	return flag.toString();
}
```
**exersize link**
-[source link](https://edabit.com/challenge/KSTkFSnaYBJdo6PHx)

----
**37.Frames Per Second**

**javob**

```js
function frames(minutes, fps) {
	return(minutes * 60 * fps);
}
```

**exersize link**
- [source link](https://edabit.com/challenge/d9suvbchE2bnHNQuK0)

--------

**38.Two Makes Ten**

**javob**

```js
function makesTen(a, b) {
	return a==10||b==10 || a+b==10;
}
```
**exersize link**
- [source link](https://edabit.com/challenge/5erCDJ8eJDrXkmwTK)

----------
**39.Buggy Code (Part 2)**

**javob**

```js
function maxNum(n1, n2) {
	if (n1 < n2) {
	  return n2
	}
  else {
	return n1
  }
}
```
**exersize link**
- [source link](https://edabit.com/challenge/uE9AJ4sSrrpSASMpu)
- ------------

**40.Compare Strings by Count of Characters**

**javob**

```js
function comp(str1, str2) {
	if (str1 === str2) {
	  return true;
	}
  else {
	return false;
  }
}

//50%50 javob

```

**exersize link**
- [source link](https://edabit.com/challenge/yHGowWucg3k2kJdZ4)
--------

**41.Check if an Integer is Divisible By Five**

**javob**

```js
function divisibleByFive(n) {
if (n % 5 === 0) {
  return true
  } else {
  return false
}
}

// yoki

function divisibleByFive(n) {
	return n === 5 ? true: false;
}
```

**exersize link**
- [source link](https://edabit.com/challenge/iBQYbSHZGhpktLRdn)

----
**42.Multiple of 100**

**javob**

```js
function divisible(num) {
	return ( num % 100 === 0);
}
```

**exersize link**
- [source link](https://edabit.com/challenge/qMr6wYGr6NaXAPQGF)

---
**43.Divides Evenly**

**javob**

```js
function dividesEvenly(a, b) {
	return a % b == 0;
}
```

**exersize link**
- [source link](https://edabit.com/challenge/JfB9mWmbwYHbupxCB)

----
**44.Area of a Rectangle**

**javob**

```js
function area(h, w) {
	if(h <=0 || w <= 0) {
		return -1;
	}
	return h * w;
}
```

**exersize link**
- [source link](https://edabit.com/challenge/g6b9HqkXqWu6GpfTo)
-------------

**45.Evaluate an Equation**

**javob**

```js
function eq(evaluate) {
 eq = eval
}
```

**exersize link**
- [source link](https://edabit.com/challenge/n2bFd2enCnHJkTwsK)
- -------------

**46.Learn Lodash: _.drop, Drop the First Elements of an Array**

**javob**

```js
function drop(arr, val = 1) {
		for(var i = 0; i < val; i++)
		arr.shift();
	return arr;
}
```

**exersize link**
- [source link](https://edabit.com/challenge/NMdKxEradTmpNnomZ)

-------
**47.Return Negative**

**javob**

```js
function returnNegative(n) {
	  return -Math.abs(n) 
}
```
**exersize link**
- [source link]( https://edabit.com/challenge/iDxwkarcJcmkDA8tq)

---------
**48.Recursion: Length of a String**

**javob**

```js
function length(str) {
	return str.length;
}
```

**exersize link**
- [source link](https://edabit.com/challenge/4MSbtYFBiRtxHEkY8)

------
**49.Return a String as an Integer**

**javob**

```js
function stringInt(str) {
	return parseInt(str);
}
```
**exersize link**
-[source link](https://edabit.com/challenge/rGsgEswWuW339yNxY)
------
