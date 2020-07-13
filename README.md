# create-unique-id

A small package to create a unique id.

![npm](https://img.shields.io/npm/v/create-unique-id) [!install size](https://packagephobia.com/result?p=create-unique-id) ![npm](https://img.shields.io/npm/dm/create-unique-id)

## Useage

You can generate a unique string between 2 and 22 digits long. The function accepts one parameter `createUID(Number)` where `Number` is any digit between 2 and 22. The function will round down to the closest whole, even number if you put something like 9.25.

```
import createUID from 'create-unique-id';

console.log(createUID(2));  // xu
console.log(createUID(4));  // f4b5
console.log(createUID(10)); // psaskfdy9d
console.log(createUID(22)); // klnt41nhfau5wz4n30pq

console.log(`uid-${createUID(6)}`); // uid-feyz4s
```

## Issues & Ideas

If you run into an issue or have an idea to make this better please don't hesitate to file and issue.
