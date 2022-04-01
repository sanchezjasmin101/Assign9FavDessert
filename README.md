# Assign9FavDessert
My favorite desserts
---
title: "FavDessert"
output: html_document
---

```{r}
FavDes <- read.csv("~/Desktop/FavDessert.csv")
summary(FavDes$Favorite.Dessert)

summary(FavDes$Rating)

summary(FavDes$Rating)

library(ggplot2)

ggplot(FavDes, aes(Favorite.Dessert, Quantity, color = Rating))+ geom_point(shape = 8)+theme_classic()
```

