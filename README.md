# Debugging-DOM-issues


This project focuses on identifying and fixing bugs in a JavaScript script that interacts with the DOM.  
The given code had multiple errors related to DOM selection, method names, and property usage.

## 📌 Task Requirements

### ✔ 1. Change Text
- Clicking **"Change Text"** should update the `<p>` element with id `message` to:
  **"New Message"**

### ✔ 2. Change Background Color
- Clicking **"Change Background"** should change the `<div>` with id `box` to a **blue** background.

---

## 🐞 Fixed Issues

### ❌ Wrong id in querySelector  
```js
document.querySelector('#massage')
