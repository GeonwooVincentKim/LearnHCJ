# LearnHCJ

This is the project that learns how to use `HTML`, `CSS`, `JAVASCRIPT`

## How does `CSS` tags are composed

### RuleSet
- A CSS rule consists of a `Selector` and `declaration block`

### Declaration Block
- Declaration Block consists `Declaration`
- Contains one or more `Declarations` separated by semicolons

### Declaration
- Declaration consists `Property` and `Value`
- Each Declaration includes a `CSS Property name` and `value`, Separated by a `colon` -> `:`

### Property
- Property defines which kind of feature that the specified tags have
- For the example, `color`, `text-align`

### Value
- Value defines the `Property's` detail feature
- For the example, `red`, `center`


```CSS
/*
    RuleSet -> Includes from `Selector` to the end of `closure tag`
    p -> `Selector`
    { } -? `Declaration Block`
    color, text-align -> `Property`
    red, center -> `Value`
*/
p{
    color: red;
    text-align: center;
}
```

## Difference between `Non-attribute` CSS Tags and `Class-Attribute` CSS Tags

### `Non-Attribute` CSS Tags
- `Non-Attribute` CSS Tags apply attribute design into every same `Selector` tags
- For the Example

```HTML
<p>P Tag Text</p>
```
```CSS
/*
    In this case every `p` tags CSS Desigh has same one
*/
p{
    color: blue;
    text-align: right;
}
```

### `Class-Attribute` CSS Tags
- `Class-Attribute` CSS Tags apply attribute design into specified `Selector` tags by using `.`
- For the Example

```HTML
<p class='p_tag_attribute'>P Tag Text</p>
```
```CSS
.p_tag_attribute{
    color: blue;
    text-align: right;
}
```
