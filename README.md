# Module 5 Week 4 Day 2 Demo - Nodes and Data Structure with Big O

**Course:** WEB 403 / WEB 603 - Full Stack Web Development  
**Student:** Migo Sea  
**Assignment:** In-Class Exercise / Demo (Week 4 Day 2)  

---

## Project Overview

This repository contains the exercises for **Module 5 Week 4 Day 2**, focusing on DOM Node Traversal, Data Structures, Big O Notation, and Object manipulation in JavaScript:

1. **Demo 1 (`demo1.html`) - DOM Traversal & Styling:**
   - Traversing the DOM tree using `p.parentNode`, `p.parentNode.parentNode`, and `ul.childNodes`.
   - Iterating over elements using `for...of` loops (`ul.children` and `p.childNodes`).
   - Dynamically applying inline styles (`background = 'yellow'` and `document.body.children[3].lastElementChild.style.background = 'purple'`).

2. **Demo 2 (`demo2.html`) - Quicksort & O(log n) Complexity:**
   - Implemented `smArr = [37, 29, 30]` and `bigArr = [43, 59, 29, 18]`.
   - Sorted numerical arrays in ascending order using recursive quicksort.

3. **Demo 3 (`demo3.html`) - Factorial & O(n!) Factorial Complexity:**
   - Recursive factorial function demonstrating exponential/factorial time complexity.
   - Tested with `factorial(1)`, `factorial(10)`, and `factorial(12)`.

4. **Demo 4 (`demo4.html`) - Linear O(n) Complexity:**
   - Implemented `exampleLinear(10)` demonstrating standard linear loop complexity printing numbers `0` to `9`.

5. **Demo 5 (`demo5.html`) - Deleting Object Properties:**
   - Demonstrated object manipulation and property deletion using the `delete` keyword (`delete person.age`), showing `undefined` behavior upon subsequent property access.

6. **Bonus / Handout: Certificate Signing Request (CSR):**
   - Generated CSR file: `mywebsite-csr.txt` (2048-bit RSA key for `www.mywebsite.com`).
   - Complete step-by-step guide: `CSR_Generation_Guide.md`.

---

## Screenshots

All output screenshots are documented in the `screenshots/` directory:
- `screenshots/demo1.png` - Shark World DOM manipulation & console
- `screenshots/demo1_purple.png` - DOM element color change to purple
- `screenshots/demo2.png` - Quicksort console output (`smArr`, `bigArr`)
- `screenshots/demo3.png` - Factorial console outputs
- `screenshots/demo4.png` - Linear loop console output
- `screenshots/demo5.png` - Object property deletion displaying `undefined`

---

## File Structure

```
m5-w4-d2-demo/
├── README.md
├── .gitignore
├── demo1.html
├── demo2.html
├── demo3.html
├── demo4.html
├── demo5.html
├── mywebsite-csr.txt
├── CSR_Generation_Guide.md
└── screenshots/
    ├── demo1.png
    ├── demo1_purple.png
    ├── demo2.png
    ├── demo3.png
    ├── demo4.png
    └── demo5.png
```
