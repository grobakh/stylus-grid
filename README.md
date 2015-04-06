# stylus-grid
CSS Grid 960 with stylus generator

1. Add stylus support to your project
2. Download grid.styl
3. Edit grid.styl to adjust vertical line size, gap size
4. Rename grid column styles if you wnat
5. Generate css
6. Insert container and if needed decorator macros to your layout stylus
```
.decorator
  decorator(line, gap / 2)
  background white
  height 100%

.container
  container()
  height 100%
``` 
8. Use simple div structure (JADE example):
```
  body
    .decorator
      .container
        block content
```
7. Profit!!!
