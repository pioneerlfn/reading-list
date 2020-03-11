

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

