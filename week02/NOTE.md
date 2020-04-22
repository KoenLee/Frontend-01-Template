# 本周作业

## 正则

    写一个正则表达式 匹配所有 Number 直接量

    ```js
    let reg = /(^\d+(\.\d+)?$)|(^0[xX][0-9a-fA-F]+$)|(^(\d+\.)?\d+e\d+$)/

    ```

    写一个 UTF-8 Encoding 的函数

    ```js

    let utf8Encoding = (code,int) => {
      return String.fromCodePoint(code)
    }

    ```

    写一个正则表达式，匹配所有的字符串直接量，单引号和双引号


    ```js

    let regString = /^[\s\w\W]+$/

    ```
