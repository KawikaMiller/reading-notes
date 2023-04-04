# Data Structures and Algorithms

## Dicussion Questions

1. **What is 1 of the more important things you should consider when deciding which data structure is best suited to solve a particular problem?** I think the scale of the data you will be using is probably the key determining factor here. Is the amount of data always going to be a certain size? Or is the amount of data expected to grow indefinitely?

2. **How can we ensure that we’ll avoid an infinite recursive call stack?**
By including a 'base case' - which is just a fancy way of saying including a condition that determines whether the recursion should execute or not.

Example:
```
const recursiveFunc = () => {
    if (base case condition) {
        // don't do recursion
        return
    } else {
        // do recursion
        recursiveFunc();
    }
}
```

## Things I Want To Know More About
n/a