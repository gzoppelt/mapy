# mapy
Mastering Python
```
$ cd mapy
$ pip install zed --user
$ pip uninstall zed
$ python3
>>>

>>> help('functools.wraps')
or
>>> import functools
>>> help(functools.wraps)

>>> import sys
>>> sys.path
['', '/usr/lib/python3.4', '/usr/lib/python3.4/plat-x86_64-linux-gnu', '/usr/lib/python3.4/lib-dynload', '/usr/local/lib/python3.4/dist-packages', '/usr/lib/python3/dist-packages']
>>> sys.path.append('/home/g/code/python/myLib') #every time you open the interpreter

$ cd /home/g/code/python/myLib/demopackage/__init__.py:
  #__all__ = ['foo', 'bar', 'baz']

>>> import demopackage  

>>> from pkgutil import get_data
>>> get_data('demo1', 'data/data.txt')
b'Das ist ist data.text in dem demo1-Package.\n' #byte object
>>> get_data('demo1', 'data/data.txt').decode('utf8')
'Das ist ist data.text in dem demo1-Package.\n'  #string



```
up to video: 3.4 (start)
