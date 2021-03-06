
# Big O Notation

## Description
Big O is the language and metric we use to describe the efficiency of algorithms. It can be used to categorize "time complexity" and "space complexity".

    - **Time**: The maximum amount of time it would take the algorithm to solve a problem.

    - **Space**: The maximum amount of computer memory, or RAM, the algorithm needs to run.
    
https://www.bigocheatsheet.com/

## Prerequisite Fundamentals
* Primitive data types
* Arrays and objects

<!--## Before Getting Started
Things to have installed or set up before diving into the code 
(eg. create-react-app globally, mongoDB, python3 etc.)
* Primitive data types
* Arrays and objects  -->
---

| Label | Name | Description |
|--|--|--|
| O(1) | Constant |  |
| O(log n) | Logarithmic |  |
| O(n) | Linear |  |
| O(n^2) | Quadratic |  |
|  |  |  |
| O(2n^n) | Exponential |  |
| O(n^n) | ?? |  |
| O(n!) | Factorial |  |

---

```javascript
    // O(1)
    const s = 4 + 3

    // O(n)
    for(let i = 0; i < n; i++) {

    }

    // O(n)
    let s = 0
    for(let i = 0; i < n; i++) {
        // O(1)
        s += i
    }

    // O(n^2)
    for(let i = 0; i < n; i++) {
        for(let j = 0; j < y;j++) {

        }
    }

    // O(n)
    for(let i = 0; i < n; i++) {}
    for(let i = 0; i < n; i++) {}
    for(let i = 0; i < n; i++) {}
    for(let i = 0; i < n; i++) {}

    // O(log n)
    while(n > 0) {
        n /= 2
    }

    100
    50
    25
    12.4
    6.25

    // O(nlog n)

    // O(n)
    for(let i = 0; i < n; i++) {
        // O(log n)
        while(n > 0) {
            n /= 2
        }
    }
```


## Extra Things to Note
Users should keep these things in mind. Let them know things won't work unless they have done these
* In order to visualize the database you nee to have a frontend with this
* You need an API key for this
* Superusers should have this permission to do that
