# Python里的OS模块常用函数说明

------

Python的标准库中的os模块包含普遍的操作系统功能。如果你希望你的程序能够与平台无关的话，这个模块是尤为重要的。即它允许一个程序在编写后不需要任何改动，也不会发生任何问题，就可以在Linux和Windows下运行。

下面列出了一些在os模块中比较有用的部分。它们中的大多数都简单明了。

os.sep可以取代操作系统特定的路径分隔符。windows下为 “\\”

os.name字符串指示你正在使用的平台。比如对于Windows，它是'nt'，而对于Linux/Unix用户，它是'posix'。

os.getcwd()函数得到当前工作目录，即当前Python脚本工作的目录路径。

os.getenv()获取一个环境变量，如果没有返回none

os.putenv(key, value)设置一个环境变量值

os.listdir(path)返回指定目录下的所有文件和目录名。

os.remove(path)函数用来删除一个文件。

os.system(command)函数用来运行shell命令。

os.linesep字符串给出当前平台使用的行终止符。例如，Windows使用'\r\n'，Linux使用'\n'而Mac使用'\r'。

os.path.split(p)函数返回一个路径的目录名和文件名。

os.path.isfile()和os.path.isdir()函数分别检验给出的路径是一个文件还是目录。

os.path.existe()函数用来检验给出的路径是否真地存在

os.curdir:返回当前目录（'.')
os.chdir(dirname):改变工作目录到dirname

os.path.getsize(name):获得文件大小，如果name是目录返回0L

os.path.abspath(name):获得绝对路径
os.path.normpath(path):规范path字符串形式

os.path.splitext():分离文件名与扩展名
os.path.join(path,name):连接目录与文件名或目录
os.path.basename(path):返回文件名
os.path.dirname(path):返回文件路径

