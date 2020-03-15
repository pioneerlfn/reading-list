## vim

删除光标到行末的内容: `d$`

## linux-command-line

### find

`find . -type d -iname "__pycache__" | xargs rm -rf`

这行命令的执行的任务是:
找到当前目录及其子目录下名为`__pycache__`的目录，并且删除.

举个例子🌰，假设我执行了一个python项目，导致生成了一些cache文件，目录树🌲变成下面这样:

```bash
.
├── shell.py
└── yosh
    ├── __init__.py
    ├── __pycache__
    │   ├── __init__.cpython-36.pyc
    │   └── constants.cpython-36.pyc
    ├── buildins
    │   ├── __init__.py
    │   ├── __pycache__
    │   │   ├── __init__.cpython-36.pyc
    │   │   └── cd.cpython-36.pyc
    │   ├── cd.py
    │   └── exit.py
    ├── constants.py
    └── test_dir

```
在执行完上面这行目录之后，目录树又可以变成最开始的样子:
```bash
.
├── shell.py
└── yosh
    ├── __init__.py
    ├── buildins
    │   ├── __init__.py
    │   ├── cd.py
    │   └── exit.py
    ├── constants.py
    └── test_dir

```

