## Deobfuscate

This tool using [babel-plugin-deobfuscate](https://github.com/mcountryman/babel-plugin-deobfuscate) to implement.


### babel-plugin-deobfuscate

Implemented as [Babel](http://babeljs.io) plugin. Written in TypeScript. Babel's core package "babel-core" and its helpers "babylon" (parser) and "babel-types" (AST) provide useful functions for AST manipulation. Babel is written in JavaScript. This allows some transformations to be implemented without the need to emulate JavaScript behaviour. For example, instead of emulating `==` expressions which is error-prone since they can result in surprisingly un-intuitive results, the expression can simply be evaluated on the de-obfuscator virtual machine. Because only JavaScript primitives are executed, this is not a security problem.

Given that Babel's core functionality involves transforming modern JavaScript, it is incentivised to keep the AST definition and the parser up-to-date with new language syntax.


## Javascript Obfuscator

 - [https://javascriptobfuscator.com/Javascript-Obfuscator.aspx](https://javascriptobfuscator.com/Javascript-Obfuscator.aspx)
 - [https://github.com/javascript-obfuscator/javascript-obfuscator](https://github.com/javascript-obfuscator/javascript-obfuscator)



## Related source

- [http://jsnice.org/](http://jsnice.org/)
- [crack.js](https://github.com/jscck/crack.js)

