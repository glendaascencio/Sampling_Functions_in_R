#### This repository contains all sampling functions in R

Creating sample data is a common task performed in many different scenarios.

R has several base functions that make the sampling process quite easy and fast.

Below is an explanation of the main functions used in the current set of exercices:

1. set.seed() – Although R executes a random mechanism of sample creation, set.seed() function allows us to reproduce the exact sample each time we execute a random-related function.

2. sample() – Sampling function. The arguments of the function are:
x – a vector of values,
size – sample size
replace – Either use a chosen value more than once or not
prob – the probabilities of each value in the input vector.

3. seq()/seq.Date() – Create a sequence of values/dates, ranging from a ‘start’ to an ‘end’ value.

4. rep() – Repeat a value/vector n times.

5. rev() – Revert the values within a vector.
