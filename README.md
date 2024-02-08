# Piano-HTML-CSS
Practice of responsive web design by building a piano

Key learning came at the end when configuring @media queries.

```css
@media (max-width: 768px) {
    #piano {
        width: 358px;
    }
    .keys {
        width: 318px;
    }
    .logo {
        width: 150px;
    }
}

@media (min-width: 769px) and (max-width: 1199px) {
    #piano {
        width: 675px;
    }
    .keys {
        width: 633px;
    }
}
```

Here I am setting up the rules for the width of the diffent div elements.
TIL that you can use logical operator like ```and``` to define specific range of widths.