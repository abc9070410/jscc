# jscc

- A javascript library for converting Simplified Chinese characters to Traditional Chinese characters and vice versa
- 提供簡體中文轉繁體中文，或繁體中文轉簡體中文。

## How to Use

- Simplified Chinese to Traditional Chinese (簡體中文轉繁體中文)  
```javascript
jscc.toTC("一秒钟几十万上下"); // 一秒钟几十万上下 -> 一秒鐘幾十萬上下
```
  
- Traditional Chinese to Simplified Chinese (繁體中文轉簡體中文)    
```javascript
jscc.toSC("一秒鐘幾十萬上下"); // 一秒鐘幾十萬上下 -> 一秒钟几十万上下
```

## Installation

- include the following js file in the header  
```html
<script type="text/javascript" charset="utf-8" src="jscc.min.js"></script>
```

## License

- The MIT License (http://opensource.org/licenses/MIT)

