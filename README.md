# jquery-rectangle-boundary-utils
A small plugin to test the boundary between the source and target elements

## Methods

- **isInside()** returns boolean
- **isColliding()** returns boolean
- **isContaining()** returns boolean
- **union()** returns {top, left, width, height}
- **intersect()** returns {top, left, width, height}

## Examples

```javascript
 $('.box1').isInside('.box2')
 $('.box1').isColliding('.box2')
 $('.box1').isContaining('.box2')
 $('.box1').union('.box2')
 $('.box1').intersect('.box2')
```
