# exampleBasedProgramming
Toying with example based programming.



# Introduction to learners

learners are a new kind of function.
Instead of describing code logic, you describe expected use cases ('rules') and the learners learn how to resolve it.

## examples

A learner that take 2 variables in parameters and add them with a space

    learner addSpaceBeetweenWords() {
      ("hello", "world") => "hello world";
    }

A learner that extract a date from a timestamp

    learner yearFromTimeStamp() {
      (1435326791790) => 2015;
      (1435295687790) => 2014;
    }

A learner that remove odd numbers from array

    learner removeOddNumber() {
      ([0,1,2,3,4,5,6,7,8,9]) => [0,2,4,6,8];
    }


