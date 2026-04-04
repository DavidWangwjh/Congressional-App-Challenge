## CSS Syntax
```
selector {
  property: value;
}
```

### Example
```
p {
  color: red;
  font-size: 20px;
}
```
Explanation:
- p → selects all paragraph elements
- color → what you are changing
- red → value you set

## CSS Selectors

### 1. Element Selector
Targets all elements of a type:
```
p {
  color: blue;
}
```
This changes all `<p>` tags.

### 2. Class Selector
Used when you want to style specific elements.

#### HTML:
```
<p class="highlight">Important text</p>
```
#### CSS:
```
.highlight {
  color: red;
  font-weight: bold;
}
```

### 3. ID Selector
Used for one specific element.

#### HTML:
```
<h1 id="title">My Website</h1>
```
#### CSS:
```
#title {
  color: green;
  font-size: 30px;
}
```

### 4. Multiple Selectors
```
h1, p {
  color: purple;
}
```
Applies to both `<h1>` and `<p>`.

## CSS Demo
Check out demo.html

## HTML + CSS Challenge
Recreate challenge.html