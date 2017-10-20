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
