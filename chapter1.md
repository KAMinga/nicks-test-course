---
title       : Insert the chapter title here
description : Insert the chapter description here

--- type:NormalExercise lang:r xp:100 skills:1 key:d1b81538fd
## Test exercise

*** =instructions

*** =hint

*** =pre_exercise_code
```{r}
```

*** =sample_code
```{r}
# Create a variable
x <- 1:5

# Create another variable
y <- rnorm(5)

# Create a thrid variable
z <- Sys.Date()
```

*** =solution
```{r}
# Create a variable
x <- 1:5

# Create another variable
y <- rnorm(5)

# Create a thrid variable
z <- Sys.Date()
```

*** =sct
```{r}
ex() %>% {
  check_object(., "x") %>% check_equal()
  check_object(., "y") %>% check_equal()
  check_object(., "z") %>% check_equal()
}
```
