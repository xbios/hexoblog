---
title: Js (Javascript)
date: 2020-05-17 14:47:15
tag: [js]
---

# [TypeScript, Looping through a dictionary](https://stackoverflow.com/questions/16174182/typescript-looping-through-a-dictionary)

To loop over the key/values, use a `for in` loop:

```js
for (let key in myDictionary) {
  let value = myDictionary[key];
  // Use `key` and `value`
}
```

<!-- {% codeblock lang:javascript  %}
alert("Hello");
var myVar = "Hello"
{% endcodeblock %} -->

<!-- {% youtube I07XMi7MHd4?t=296  %} -->

# [eslint] Delete 'cr' [prettier/prettier]

Try setting the "endOfLine":"auto" in your .prettierrc file (inside the object)
Or set

```
"prettier/prettier": ["error", {
..
"endOfLine":"auto"
..
}],
```
