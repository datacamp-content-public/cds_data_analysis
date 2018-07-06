---
  title: "Template Chapter 1"
  description: "This is a template chapter."
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

This is the assignment text. It should help provide students with the background information needed.
The instructions that follow should be in bullet point form with clear guidance for what is expected.

`@instructions`
- Instruction 1
- Instruction 2
- Instruction 3
- Instruction 4

`@hint`
- Here is the hint for this setup problem. 
- It should get students 50% of the way to the correct answer.
- So don't provide the answer, but don't just reiterate the instructions.
- Typically one hint per instruction is a sensible amount.

`@pre_exercise_code`
```{r}
# Load datasets and packages here.
```
`@sample_code`
```{r}
# Your
# sample
# code
# should
# be
# ideally
# 10 lines or less,
# with a max
# of 16 lines.
```
`@solution`
```{r}
# Answer goes here
# Make sure to match the comments with your sample code
# to help students see the differences from solution
# to given.
```
`@sct`
```{r}
# Update this to something more informative.
success_msg("Some praise! Then reinforce a learning objective from the exercise.")
```






---
## Load the data for our regression example

```yaml
type: NormalExercise

xp: 100

key: 1f9e4c449e



```

First we need to load the regression data for this chapter. 

`@instructions`
* Load the ggplot2 package using the library() function
* Load the diamonds data using the load() function

`@hint`



`@sample_code`
```{r}
### Load ggplot2 library using library()


### Load diamonds data using load()
```
`@solution`
```{r}
library(ggplot2)
data("diamonds")
```
`@sct`
```{r}
library(testwhat)
library(dplyr)
ex() %>% test_object("diamonds") 
success_msg("Great job!")

```




