# pxt-hebrew
---
This library make it possible to show characters of Hebrew.
A fork from the Katakana extension.

## Basic Usage
---
Import extension from https://github.com/shahart/heb-microbit

Method
```
hebrew.showString(string)
הצג מחרוזת
```

- string: characters to show

the only argument is the characters to show. The default is blank. 

You can use the characters below and space.
```
 אבגדהוזחטיךכלםמןנסעףפץצקרשת-,.､｡!?｢｣[]()<>#$%&'abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ^`_･*+ｰ=\\/:;@
```

## Example
---

It works.
```
hebrew.showString("שלום !")

Hebrew is written from right to left, so, only in the text input block, note for rtl issue in the end of the line, i.e. other symboles than Hebrew, are shown on the right side, rather than left.
```

## License
MIT

## Supported targets

* for PXT/microbit
