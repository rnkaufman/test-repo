# Markdown syntax parsing error example for typescript optional chaining

- Lorem ipsum dolor sit amet, consectetur adipiscing elit.
- Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
- Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
- Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
- Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
- [MDN Web Docs](https://developer.mozilla.org/)
- [W3C](https://www.w3.org/)

```js
const user = {
  name: "John Doe",
  address: {
    city: "New York",
  },
};

console.log(`Hello, ${user.name}!`);
console.log(`City: ${user.address.city ?? "Unknown"}`);
console.log(`Street: ${user.address.street ?? "Unknown"}`);
```

## This section has syntax parsing issues on GitHub now because of the above code block

It does work fine with a ts code block though, so that's an easy workaround

- Lorem ipsum dolor sit amet, consectetur adipiscing elit.
- Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
- Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
- Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
- Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
- [MDN Web Docs](https://developer.mozilla.org/)
- [W3C](https://www.w3.org/)
