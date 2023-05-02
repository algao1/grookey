# Grookey

Grookey is a toy interpreter (wip) for the [Monkey](https://monkeylang.org/) language.

<div align="center">
	<img src="./.media/monkey_logo_cropped.png">

*This image is generated using Midjourney.*
</div>

This interpreter is built following the examples in ["Writing An Interpreter In Go"](https://interpreterbook.com/) by Thorsten Ball. 

Here's what a toy example looks like:
```
>> let add = fn(a, b) { a + b };
>> let sub = fn(a, b) { a - b };
>> let applyFunc = fn(a, b, func) { func(a, b) };
>> applyFunc(2, 2, add);
4
>> applyFunc(10, 2, sub);
8
```