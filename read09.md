Functional programming is a programming paradigm — a style of building the structure and elements of computer programs — that treats computation as the evaluation of mathematical functions and avoids changing-state and mutable datA

If a function reads external files, it’s not a pure function — the file’s contents can change.

Any function that relies on a random number generator cannot be pure.

toLowerCase: converts the string to all lower case
trim: removes whitespace from both ends of a string
split and join: replaces all instances of match with replacement in a given string

This article is kind of confusing in some places. About half way through it talks about `sum(5, 8)` equaling 13 adn then somehow equaling 16???? 

https://canvas.instructure.com/courses/1986811/discussion_topics/8781240

Functions as first-class entities can:
  refer to it from constants and variables
  pass it as a parameter to other functions
  return it as result from other functions  