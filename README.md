# stylus-grid
###CSS Grid 960 with stylus macros and generators. 
Customizable gap and unit size.
No padding magic in container. No 'row' div markup.

1) Add stylus support to your project

2) Download grid.styl

3) Edit grid.styl to adjust vertical line size, gap size

4) Rename grid column styles if you want

5) Insert container and if needed decorator macros to your layout stylus
```
.decorator
  decorator(line, gap / 2)
  background white
  height 100%

.container
  container()
  height 100%
``` 
6) Use simple div structure (JADE example):
```
  body
    .decorator
      .container
        block content
          .grid12_4 leftpanel
          .grid12_8 rightpanel
```
7) Profit!!!
