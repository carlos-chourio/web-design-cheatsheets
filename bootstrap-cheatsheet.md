# Bootstrap Cheat sheet

## Background Colors

---

| Name | Color | Hexadecimal |
| ---- | ----- | ----------- |
| Primary | Blue. | 157efb |
| Secondary  | Gray | 6c757c
| Success  | Green | 30a64a |
| Danger  | Red | da3849 |
| Warning | Amber (Yellow) | fdc02f |
| Info | Cyan (Light blue) |25a2b7 |
| Dark | Dark | 343a40 |
| White | White | ffffff |
| Light | Light Gray | f8f9fa
| Transparent | Transparent | Transparent |

- *bg-color* : Sets Background to that color.
- *text-color* : Sets text to that color.

## Containers and Rows

---

```container``` : Sets some padding and margin to the element so it no longer occupies the whole screen from edge to edge. (These padding and margin are responsive) and change with breakpoints

```container-fluid``` : Occupies the entire viewport from edge to edge. (Does not use media breakpoints, but their content resize smoothly)

```row``` : row enables you the usage the grid system. It's mandatory to do responsive design in bootstrap.

## Breakpoints in Bootstrap 4

---

| property  |   value   |   name  |
|-----------|-----------|---------|
| min-width | 1200px    |   XL    |
| min-width | 996px     |   LG    |
| min-width | 768px     |   MD    |
| min-width | 576px     |   SM    |
| max-width | 575.98px  |         |

What col-xx-size does is to place the content of the element inside a column of size **size** and stack the elements once the breakpoint **xx** is hit.

```(where name is xx the name name of the breakpoint and size is the column size between 1-12)```

We can change the order of the columns by using order-xx where xx is the index of the column (like if it were a 1-based array)

## Alignment

---

```align-items-xxxx``` : (It's used along with the row class) Aligns the elements inside a row and places them on the xxxx (center-start-end) of the parent element.

```align-self-xxxx``` : It's used in a child of the row element and it places the element itself on the xxxx (center-start-end) of the parent element.

```justify-content-xxx```: (It's used in along with the row class) and it justifies the content of the element to the position xxxx (center-right-left-around-between).

```col-offset-xx-size```: moves the current element *size* columns to the right when the viewport is in the xx breakpoint. Example -> ```col-offset-md-4```

## Margin, Padding & Display

---

- ```margin``` : m-x
- ```padding``` : p-x
- ```display``` : d-xxxx

```x``` : value in pixels of the margin/padding.

```suffixes``` : t -> top, b -> bottom, r -> right, l -> left, x-> left and right, y -> top and bottom, blank -> all the way around. Examples: mr-2 my-3 pb-5...

```xxxx``` : display mode (inline, block)



