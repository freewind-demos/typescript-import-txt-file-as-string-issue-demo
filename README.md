TypeScript Import Txt File as String (Issue) Demo
=================================================

```
npm install
npm run demo
```

It will print error:

```
console.log(`Hello, ${username_txt_1.default.trim()}!`);
                                             ^

TypeError: Cannot read property 'trim' of undefined
```

How to fix?

Update:
-------

With the help of https://stackoverflow.com/a/52488349/342235, it's fixed now, thanks!
