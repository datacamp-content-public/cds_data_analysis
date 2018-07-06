---
  title: "This is my first exercise"
  description: "This is my first exercise example"
  v2: true

---
## An exercise title written in sentence case

```yaml
type: NormalExercise
lang: r
xp: 100
skills: 1
key: 96c7a96fea


```

First we are going to load the data sets we need

`@instructions`
- Load the ggplot2 library
- Load the diamonds data set

`@hint`
- Use the library() command to load ggplot2
- Use the load() command to load the diamonds data set.

`@pre_exercise_code`
```{r}
# Load datasets and packages here.
library(ggplot2)
```
`@sample_code`
```{r}
## Load ggplot2

## Load diamonds

```
`@solution`
```{r}
## Load ggplot2
library(ggplot2)
## Load diamonds
data(diamonds)

```
`@sct`
```{r}
# Update this to something more informative.
success_msg("Some praise! Then reinforce a learning objective from the exercise.")
```



