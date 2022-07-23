# Challenge-3
```shell
We have a nested object, we would like a function that you pass in the object and a key and get back the value.
```
```shell
Nested Object has three uniquekeys: 
id - whose value is a number
date - whose value is a string
data -whose value is an object nested within it.

While structures can quickly becomes complex, we can still use the same notations to access the information we need.
```

## Code
```shell
let userActivity = {
  id: 78945612378,
  date: 'July 23, 2001',
  data: {
    totalUsers: 98,
    online: 87
  }
};

// change code below this line

// change code below this line 

console.log(userActivity);
```

## Output
```shell
{ id :78945612378,
  date: 'July 23, 2001',
  date: { totalUsers: 98, online: 87 } }
```

## Case-1 Code modified 
```shell
Here we've defined an object, "userActivity", which includes another object nested within it.
You can modify properties on this nested object in the same way you modified properties in the last challenge.
Set the value of "online" key to "97".
```

```shell
let userActivity = {
  id: 78945612378,
  date: 'July 23, 2001',
  data: {
    totalUsers: 98,
    online: 87
  }
};

// change code below this line

// change code below this line 

console.log(userActivity.data);
```

## Output
```shell
 { totalUsers: 98, online: 87 } }
```

## Case-2 Code modified like

```shell
let userActivity = {
  id: 78945612378,
  date: 'July 23, 2001',
  data: {
    totalUsers: 98,
    online: 87
  }
};

// change code below this line
userActivity.data.online = 97;
// change code below this line 

console.log(userActivity);
```

## Output
```shell
{ id :78945612378,
  date: 'July 23, 2001',
  date: { totalUsers: 98, online: 97 } }
```
