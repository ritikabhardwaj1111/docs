---
Title: '.has()'
Description: 'Returns a boolean reflecting whether an entry with a given key exists in a Map object.'
Subjects:
  - 'Web Development'
  - 'Computer Science'
Tags:
  - 'Map'
  - 'Object'
CatalogContent:
  - 'introduction-to-javascript'
  - 'paths/front-end-engineer-career-path'
---

Returns a boolean reflecting whether an entry with a given key exists in a `Map` object.

## Syntax

The `.has()` method accepts a `key` as a parameter:

```js
map.has(key);
```

If the `key` exists in `map`, `.has()` returns `true`. Otherwise, it returns `false`.

## Example

Checking whether a key is in `fruits` map can be done using the `.has()` method:

```js
const fruits = new Map([
  ['Apples', 5],
  ['Oranges', 8],
]);

console.log(fruits.has('Apples')); // Output: true
console.log(fruits.has('Bananas')); // Output: false
```

The first `.has()` statement checks that there are `'Apples'` in `fruits`, which returns `true`. The second statement finds that there are no `'Bananas'` in `fruits` and `false` is returned.