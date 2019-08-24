# CSS Cheat sheet

## Sets style to elements using the id

```css
#id-name : {
    margin: 8px 6px 4px 2px; /*starts 8px top and ends 2px left*/
    width : 50%; /*Sets the width to 50% of the parent container*/
};
```

## Sets style to elements using classes

```css
.class-name : {
    width : 100px;
    height : 100px;
    color : red;
    margin : 5px 10px; /*top-bottom 5, left-right 10*/
    padding : 3px;
};
```

## Use an image as background

```css
.class-name {
    background : url('imageUrl') no-repeat center center;
    background-size: cover;
}
```

## Media Breakpoints

```css
@media(min-width:992px) {
    body {
        background:red;
    }
}
@media(max-width:576px) {
    body {
        background:gray;
    }
}
```

## Display Modes

---

```block``` : Expands to the size of its parent container.

```inline``` : It's placed inline with other elements.

```none``` : Element is removed
