### cheet sheet
[Python Cheat Sheet](https://www.pythonsheets.com/)

### shell
- [使用Python创建你自己的Shell(上)](http://www.codeceo.com/article/create-your-own-shell-in-python-part-1.html)
- [使用Python创建你自己的Shell(下)](http://www.codeceo.com/article/create-your-own-shell-in-python-part-2.html)


### package、moudle以及import

- [Absolute vs Relative Imports in Python(realpython)](https://realpython.com/absolute-vs-relative-python-imports/)

    python解释器查找module(也就是py文件)的顺序是
    ```bash
    sys.modules --> built-in --> sys.path
    ```
    sys.path[0]是解释器被调用来执行的py文件所在的目录。如果是以交互方式启动，那sys.path[0] 就是' '. 

### str, unicode
- [How Python saves memory when storing strings](https://rushter.com/blog/python-strings-and-memory/)
- [Unicode HOWTO¶](https://docs.python.org/3/howto/unicode.html)
- [The Absolute Minimum Every Software Developer Absolutely, Positively Must Know About Unicode and Character Sets (No Excuses!)](https://www.joelonsoftware.com/2003/10/08/the-absolute-minimum-every-software-developer-absolutely-positively-must-know-about-unicode-and-character-sets-no-excuses/)

### logging
- [Good logging practice in Python](https://fangpenlin.com/posts/2012/08/26/good-logging-practice-in-python/)
- [日志 HOWTO¶](https://docs.python.org/zh-cn/3/howto/logging.html)

    logging的日志级别从上到下为:
    ```python
    CRITICAL = 50
    FATAL = CRITICAL
    ERROR = 40
    WARNING = 30
    WARN = WARNING
    INFO = 20
    DEBUG = 10
    NOTSET = 0
    ```
    
    如果将级别设置为某一档，则只会打印大于等于该档的日志。  
    低于该档的日志将不会打印。

    比如`level=logging.ERROR`, 则只会打印 `ERROR和FATAL` 这两个级别的日志。


### socket programming
- [Socket Programming in Python (Guide)](https://realpython.com/python-sockets/)




