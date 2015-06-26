# exampleBasedProgramming
Toying with example based programming.



# Introduction to mutators

Mutator are a new kind of function.
Instead of describing code logic, you describe expected use cases. ('rules')

## examples

A 'function' that take 2 variables in parameters and add them with a space

  mutator addSpaceBeetweenWords() {
    ("hello", "world") => "hello world";
  }

A function that extract a date from a timestamp

  mutator yearFromTimeStamp() {
    (1435326791790) => 2015;
    (1435295687790) => 2014;
  }

A function that remove odd numbers from array

  mutator removeOddNumber() {
    ([0,1,2,3,4,5,6,7,8,9]) => [0,2,4,6,8];
  }


