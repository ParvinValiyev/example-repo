# CSS - Cascading Style Sheets

## DOM - Document Object Model

## CSS OM - CSS object Model

## CSS in HTML

- Inline CSS

`style=""` attribute

- Internal CSS 

`<style></style>` tag

- External CSS

`<link rel="stylesheet" href="file.css"` />

## CSS SELECTORS

- tag selector

```css
body {
    font-size: 45px;
}
```
- CLASS SELECTOR

```<div class="greeting">Hello world</div>```
```css
.greeting {
    font-size: 22px;
}
```

- ID selector

```html
<div id="friend">hello friend</div>
```
```css
#friend {
    background: purple;
}
```

- ATTRIBUTE SELECTOR

```html
<span title="Hello JOhn doe">Hello John</span>
<p data-status="success">John</p>
```

```css
[title] {
    color: green;
}

[data-status='success'] {
    color: red;
}
```

- PSEUDO ELEMENT & PSEUDO CLASS SELECTOR

```html
<input placeholder="enter your name"> 
```

```css
::placeholder {
    color: red;
}
```
## SPECIFITY