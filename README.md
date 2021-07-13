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