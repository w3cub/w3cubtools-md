# w3cubtools-md
Tools descriptions



## File Name Rule
we automatically require the directory file.

```javascript
const files = require.context("@md/", false, /\.md$/);
const modules = {};
files.keys().forEach(key => {
  modules[key.replace(/\.\//, "/").replace(/(\.md)/g, "")] = files(key).default;
});
```


  Url     =>  File Name  

  /gomoku =>  gomoku.md






## License

Copyright (c) Terry Cai. Licensed under the MIT license.



