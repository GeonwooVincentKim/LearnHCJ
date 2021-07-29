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

## Difference between `Non-attribute` CSS Tags (Selector) and `Class-Attribute` CSS Tags (Selector) and `Multiple-Class-Attribute` CSS Tags (Selector)

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

### `Multiple-Class-Attribute` CSS Tags
- `Mulitple-Class-Attribute` CSS Tags apply several attributes design into specified `Selector` tags by using `.`
- For the Example

```HTML
<p class='p_tag_font p_tag_color'></p>
```
```CSS
.p_tag_font{
    font-size: 10px;
    text-decoration: none;
}

.p_tag_color{
    color: green;
    background-color: GreenYellow;
}
```

### `*` Selector
- Select all elements, and set their `Property` to `Value`

```HTML
<html>
    <head>
        <title>Title</title>
    </head>

    <body>
        <h1>This is Main-Title <b>TEXT</b></h1>
        <h3>This is Sub-Title <b>TEXT</b></h3>
        <div class="div_property">
            <ul>
                <li>Prop1</li>
                <li>Prop2</li>
                <li>Prop3</li>
            </ul>
        </div>
    </body>
</html>
```
```CSS
*{
    margin: 0 auto;
    padding: 0;
}
```
