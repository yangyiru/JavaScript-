## JavaScript专题之类型判断
  + ### [typeof] 是一元操作符，放在其单个操作数的前面，操作数可以是任意类型。返回值为表示操作数类型的一个字符串
  + 如何检测Object的细分类型：Array/Function/Date/RegExp/Error
    use Object.prototype.toString
    e.g:
    ```
    Object.prototype.toString.call(new Date()) // "[object Undefined]"
    Object.prototype.toString.call(new Error()) // "[object Error]"
    ```
  + type API  封装type函数以便检测各个类型的值
    ```
      var 
    ```
