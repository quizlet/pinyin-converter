Pinyin Converter
================

A simple Javascript plugin to convert pinyin with numbers to tone marks. 

`PinyinConverter.convert('ni3hao3') // returns 'nǐhǎo'`

This plugin powers the Pinyin conversion on Quizlet.com and was conceived during one of our 
[hacknights](http://quizlet.com/inside-quizlet/hacknight-better-mandarin-support-in-quizlet)

Getting Started
===============

Just add the pinyin_converter.js script to your site. There are no external dependencies.

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
