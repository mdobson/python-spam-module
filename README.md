## Example native python extension written in C

This is a sample python extension written in C. This is the result of two tutorials for python 2.7:

1. [Building an extension in C](http://docs.python.org/2/extending/extending.html)
2. [Using distutils to make a build file](http://docs.python.org/2/extending/building.html#building)

Simply run `python setup.py build` and `python setup.py install`. This will expose the `spam` module. From there use `spam.system()` to execute shell commands. E.x `spam.system("ls -l")`.
