pinyin-converter
================

Javascript object which adds accents to pinyin. PinyinConverter.convert('ni3hao3') => nǐhǎo

Getting Started
===============

Just add the pinyin_converter.js script to your site.

Usage
=====

PinyinConverter only has 1 method: `PinyinConverter.convert(text)`

```js
var pinyin = PinyinConverter.convert("san1ren2xing2bi4you3wo3shi1");
// returns "sānrénxíngbìyǒuwǒshī"

// ü can be typed by using v
var pinyin = PinyinConverter.convert("lv4");
// returns "lǜ"

// works with uppercase chars too
var pinyin = PinyinConverter.convert("WO3 HEN3 XI3HUAN QUIZLET!");
// returns "WǑ HĚN XǏHUAN QUIZLET!"
```

Enjoy!
