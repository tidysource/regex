# regex
Regex notes and snippets

## All characters INCLUDING new line
```javascript
/[\s\S]/

//Or

/[^]/
```

## Prevent gready match
```javascript
//? after quantifier makes it non-greedy
/a*?/
```