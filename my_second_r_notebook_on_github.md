---
title: "My second rmarkdown on Github"
output:
  html_document:
    df_print: paged
    keep_md: TRUE
---




Here is a ggplot chart


```r
mtcars %>%
        ggplot(aes(x = wt, y = mpg, color = as.factor(cyl))) +
        geom_point() +
        geom_smooth() +
        ggtitle("My First Plot")
```

```
## `geom_smooth()` using method = 'loess' and formula 'y ~ x'
```

![](my_second_r_notebook_on_github_files/figure-html/unnamed-chunk-2-1.png)<!-- -->

