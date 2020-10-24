---
title: sumTillSingleDigit
tags: math,beginner
---

Does Sum all the digits of a number unless the number becomes a single digit numbers

- If a number is divisible by `9` i.e `num%9==0` sum of its digits unless you can a single digit will always be `9` else sum of its digits unless you can a single digit will be the remainder when the number is divided by `9` i.e `number%9`

```js
function sumTillSingleDigit(num) {
	sum = 0
	if (num % 9 == 0)
		sum = 9
	else
		sum = num % 9
	return sum
}
```

```js
sumTillSingleDigit(93); // 3
sumTillSingleDigit(81); // 9
sumTillSingleDigit(51298); // 7
```
