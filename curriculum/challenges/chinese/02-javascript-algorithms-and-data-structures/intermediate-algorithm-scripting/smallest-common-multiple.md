---
id: ae9defd7acaf69703ab432ea
title: 最小公倍数
challengeType: 5
forumTopicId: 16075
---

# --description--

在这道题目中，我们需要写一个函数，它接收一个包含两个数字的数组参数`arr`，它的返回值为这两个数字范围内所有数字（包含这两个数字）的最小公倍数。

注意，较小数不一定总是出现在数组的第一个元素。

比如，传入`[1, 3]`，那么函数的返回结果应为 1、2、3 的最小公倍数，即为 6。

如果你遇到了问题，请点击[帮助](https://forum.freecodecamp.one/t/topic/157)。

# --hints--

`smallestCommons([1, 5])`应该返回一个数字。

```js
assert.deepEqual(typeof smallestCommons([1, 5]), 'number');
```

`smallestCommons([1, 5])`应该返回 60。

```js
assert.deepEqual(smallestCommons([1, 5]), 60);
```

`smallestCommons([5, 1])`应该返回 60。

```js
assert.deepEqual(smallestCommons([5, 1]), 60);
```

`smallestCommons([2, 10])`应该返回 2520。.

```js
assert.deepEqual(smallestCommons([2, 10]), 2520);
```

`smallestCommons([1, 13])`应该返回 360360。

```js
assert.deepEqual(smallestCommons([1, 13]), 360360);
```

`smallestCommons([23, 18])`应该返回 6056820。

```js
assert.deepEqual(smallestCommons([23, 18]), 6056820);
```

# --solutions--

