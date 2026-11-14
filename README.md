# Week 7 – JavaScript Best Practices

**Student:** Carlos Adenge  
**Repository:** iyf-s12-week-07-carlosadenge

## Live Demo
[View To-Do List](https://carlosadenge.github.io/iyf-s12-week-07-carlosadenge)  
[View Shopping Cart](https://carlosadenge.github.io/iyf-s12-week-07-carlosadenge/cart/)

## About This Project
This is my Week 7 project for the IYF Wecan Academy 
I refactored my Week 5 To-Do List into clean modules, added localStorage persistence, ESLint, Prettier, and unit tests.  
I also built a Shopping Cart that uses the same state + persistence pattern.

## Features

### To-Do List
- Add, toggle, delete, and edit tasks
- Filters: All / Active / Completed
- Survives page refresh (localStorage)
- Clear completed tasks
- Modular architecture (storage, logic, state, UI, app)

### Shopping Cart
- Add products to cart
- Change quantity
- Remove items
- Live total and item count
- Cart persists after refresh

## Project Structure
iyf-s12-week-07-carlosadenge/

├── index.html

├── styles.css

├── js/

│   ├── app.js

│   ├── state.js

│   ├── storage.js

│   ├── todo-logic.js

│   └── ui.js

├── tests/

│   └── todo-logic.test.js

├── cart/

│   ├── index.html

│   ├── cart.css

│   └── cart.js

├── eslint.config.js

├── .prettierrc

├── package.json

└── README.md
