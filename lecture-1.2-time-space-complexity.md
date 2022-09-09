## Lecture 1.2

An algorithm is *correct* if it produces intended result for problem within specified construction.

### Lecture Slides
https://canvas.ubc.ca/courses/101869/pages/lesson-1-dot-2-2022-09-09-reasoning-about-code-intro?module_item_id=4805629

### Efficiency of Algorithms
* **Time** & **Space** are most common metrics
* Express **Time** as a positive function, non-decreasing (bigger the data size, longer the time)
* Form of the function depends on the structure of the algorithm
```javascript
T(n) // n: inputs are usually integers 
T(n) = 2n + 3 seconds // example of linear function, line increases with n
```

<img width="500" alt="image" src="https://user-images.githubusercontent.com/5387769/189448255-cd5eada0-7a0e-4861-9079-70f0ed4f174f.png">

* From the table above, you can see how much time is saved by using an ```n``` instead of an ```2^n``` algorithm
