---
title: 'Chapter Title Here'
description: 'Chapter description goes here.'
---

## Example coding exercise

```yaml
type: NormalExercise
key: e8c1edbe67
lang: python
xp: 100
skills: 2
```

This is an example exercise. More characters needed?	

`@instructions`
Do stuff here. More characters more characters.

`@hint`


`@pre_exercise_code`
```{python}

```

`@sample_code`
```{python}
abc = 123
```

`@solution`
```{python}
abc = 123
abc *= 2

```

`@sct`
```{python}
Ex().check_object('abc').has_equal_value()
```

---

## Exercise Test 1

```yaml
type: MultipleChoiceExercise
key: 771ec2d640
xp: 50
```

This is a sample question. Enter the right answer, dude.

`@possible_answers`
- var += 2
- [var *= 2]
- var /= 2

`@hint`


`@pre_exercise_code`
```{python}
var = 123

```

`@sct`
```{python}

```
