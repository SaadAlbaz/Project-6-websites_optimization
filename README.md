
# How to start
1. opne index.html in broweser
2. open views/pizza.html in browser 

### Optimization Made on index.html
- Inline CSS
- Added async javascript for external js
- Added media='print' for print.css
- Inline javascript
- Deleted external resource for google font
- compressed images

### Optimization Made on main.js
- Deleted determineDx() method
- No more read layout then write style in changePizzaSize()
- All the layouts read are done outside loops
- compressed image