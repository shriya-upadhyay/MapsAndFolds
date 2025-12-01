# Maps and Folds (An Overview)

Maps and folds are both **higher-order functions** which means they fulfill one or both of the following criteria:

1. receive a function as a parameter
2. return a function 


## Definitions

A **map** is a function that takes another function and a list as arguments and returns that function applied to the list ([Wikipedia](https://en.wikipedia.org/wiki/Map_(higher-order_function))). It can be considered an “apply-to-all”. 


A **fold** is also a function that takes another function and a list as arguments, combines the results of applying the function to each of the elements of the list recursively, and then returns that result ([Wikipedia](https://en.wikipedia.org/wiki/Fold_(higher-order_function))). 

Maps are relatively straightforward but folds are tricky because the function can be applied either from the right of the list to the left OR from the left of the list to the right and the result will be **different** in each case.
