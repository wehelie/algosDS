### Defining Classes
- What is it ?
- What does it have ?
- What does it do ?

### Constructor Function

```javascript
function Building(floors) {
  this.what = 'building';
  this.floors = floors;
}

// per instance
var House = new Building(3);

```


### Methods (for all instances)

```javascript
Building.ClassName.prototype.countFloors = function() {
  console.log('I have', this.floors, 'floors');
};
```


#### Exercise Time!
```javascript
var Dome = function(doors) {
  this.doors = doors;
  this.floors = floors;
}
Dome.prototype.countFloors = function() {
  if(this.door > 10) {
    .console.log("Building is too big");
  }
}
var stadium = new Dome(4);
```

- - -

## Stacks & Queues
- - -
#### Ingredients to Learn DS

1. Learn Data Structure Concept
  - Draw it
  - Create the API/operation methods
2. Build the Data Structure
  - Pseudocode the implementation
  - Code the data Structure Constructor
3. Utilize the data Structure
  - put your data structure to work
  - Pair it with an algorithm if needed
4. Understand Data Structure
  - What is the time complexity? (coming soon)
  - How can you optimize ?

  - - -

  ### "LIFO"
  Stacks are elementary data structure where the Last item added Into the stack
  will be the First one taken Out of the stack.

  "added Into" (aka Pushed onto)
  "taken Out" (aka Popped off)
