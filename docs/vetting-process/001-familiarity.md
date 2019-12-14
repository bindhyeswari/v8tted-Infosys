# Familiarity with Objects and Arrays
- Slicing and dicing objects and arrays
- Object.prototype and Object methods (e.g. `Object.keys`, `Object.values`, `Object.create`, etc)
- Array.prototype methods (e.g. `forEach`, `slice`, `map`, `reduce` etc.)

## Code snippets

### Example 1: Sales Data
 - Write a module to perform the following operation, given a [sales json object](monthlySalesbyCategoryMultiple.json.md):
    - Print all the available categories (category names only)  `snippet`
    - For each category, print the highest sales by date `snippet 2`
    - For each category, print all the months ordered by the sales data `snippet 3`
```sh
// output from snippet 1
> Categories available: Furniture, Technology
``` 
    
```sh
// output from snippet 2
> June (200) saw the highest sales in Furniture. 
> April (250) saw the highest sales in Technology. 
```
   
```sh
// output from snippet 3
> Furniture: `Apr, Sep, Oct, Nov, Dec, Jan, Feb, Mar, Jun, May, Jul, Aug`
> Technology: `Apr, Sep, Oct, Nov, Dec, Jan, Feb, Mar, Jun, May, Jul, Aug`
```
    

