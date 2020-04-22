# 本周作业

## 总结

  1.对编程语言通识有了基本的认识，
  
  2.了解了编程语言分类
  
  编程语言按语法分类
    ·非形式语言
      中文，英文

    ·形式语言
      0型 无限制文法
      1型 上下文相关文法
      2型 上下文无关文法
      3型 正则文法

  产生式

  用尖括号括起来的名称来表示语法结构名
  语法结构分成基础结构和需要用其他语法结构定义的复合结构
    基础结构称终结符
    复合结构称非终结符
  引号和中间的自负表示终结符
  可以有括号

  类型系统
  动态类型系统与静态类型系统
  强类型与弱类型  

  2.JavaScript词法构成 （Atom）
  InputElement
  WhiteSpace
  LineTerminator
  Comment
  Token (JavaScript中一切有效的东西)
      IdentifierName
      Keywords
      Identifier
      Future reserved Keywords:enum
      Punctuator
      Literal

## 作业

### 1.写一个正则表达式 匹配所有 Number 直接量

```js
let reg = /(^\d+(\.\d+)?$)|(^0[xX][0-9a-fA-F]+$)|(^(\d+\.)?\d+e\d+$)/
```

### 2.写一个 UTF-8 Encoding 的函数

```js
let encodeUtf8 = (text) => text.split('').map(char => char.charCodeAt().toString(16)).join('')
```

### 3.写一个正则表达式，匹配所有的字符串直接量，单引号和双引号

```js
let regString = /^[\s\w\W]+$/
```
