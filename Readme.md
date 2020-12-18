# Installation:

```
npm i sorting-array
yarn add sorting-array
```

# How to use ?

```
const sortArray = require('sorting-array');
or
import sortArray from 'sorting-array';

// By default it sort data in Ascending Order.
// For :
//     Ascending Order: asc
//     Descending Order: desc

// With object name sortArray(arrayData,sortType,objectName)

  sortArray(
    [
      { name: "akash", age: 25 },
      { name: "ravi", age: 28 },
      { name: "rajan", age: 25 },
    ],
    "desc",
    "name"
  );


// Without object name sortArray(arrayData,sortType)

sortArray([1, 2, 4, 3, 5], "desc");
```

# Other Similler
 for array filter visit: https://www.npmjs.com/package/npm-array-filter,  
 for array find visit: https://www.npmjs.com/package/npm-array-find


