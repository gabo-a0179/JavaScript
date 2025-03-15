# 3. String

## Concat strings:
```js
'some' + 'text'
// 'sometext'
```

## Type of variable
```js
typeof 'text'
// string
```

## Type coercion
```js
'hello' + 3
// 'hello3'

'text' + 3 + 2
// 'text32'
```

## 3 ways to create a string
```js
// 1
'text'

// 2
"text"

// 3
`text` // template strings
```

## Template strings
- Interpolation: Insert value directly into a string
```js
// ${} = Insert value directly into a string

`Text ${1+1}`
// 'Text 2'
```
- Multi-line string:
```js
`some
text`
```