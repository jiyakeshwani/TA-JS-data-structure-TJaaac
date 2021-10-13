```js
let user = {
  name: "Arya",
  sibling: ["Robb", "Ryan", "John"],
};
let allBrothers = ["Robb", "Ryan", "John"];
let brothersCopy = user.sibling;
let usename = user.name;
let newUser = user;
```

1. Memory representation

- Create the memory representation of the above snippet on notebook.
- Take a photo/screenshot and add it to the folder `code`

<!-- To add this image here use ![name](./hello.jpg) -->

2. Answer the following with reason:

- `user == newUser;` // true because user.name is arya and newuser is user.name
- `user === newUser;`// true because user.name is arya and newuser is user.name
- `user.name === newUser.name;`// false because there in newuser there is no key named as name.
- `user.name == newUser.name;`// false because there in newuser there is no key named as name.
- `user.sibling == newUser.sibling;`// false because in newuser there is no key named as sibling.
- `user.sibling === newUser.sibling;`// false because in newuser there is no key named as sibling.
- `user.sibling == allBrothers;`// false because user.sibling points to the objrct address and stores the value there and allBrothers stores the value in variable.
- `user.sibling === allBrothers;`// false because user.sibling points to the objrct address and stores the value there and allBrothers stores the value in variable.
- `brothersCopy === allBrothers;`// false brotherscopy is equal to user.sibling which points to object address and stores the value there and allBrothers stores the value in the variable.
- `brothersCopy == allBrothers;`//false brotherscopy is equal to user.sibling which points to object address and stores the value there and allBrothers stores the value in the variable.
- `brothersCopy == user.sibling;`// true brothersCopy is equal to user.sibling
- `brothersCopy === user.sibling;`// true brothersCopy is equal to user.sibling
- `brothersCopy[0] === user.sibling[0];`// true brothersCopy is equal to user.sibling
- `brothersCopy[1] === user.sibling[1];` // true brothersCopy is equal to user.sibling
- `user.sibling[1] === newUser.sibling[1];`// false
