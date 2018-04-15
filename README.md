# python_foundation 
basic knowledge python （python 3）
chapter 1 数字和字符串
1.1.1 常见计算符号
    加号：+
    减号：-
    乘号：*
    除号：/
    乘方：**
    数学括号：()
    余数：%
1.1.2 代码风格
   https://www.python.org/dev/peps/pep-0008/
1.2 整数和浮点数
    int() float()
1.3 出现错误
    Traceback（回溯）表示“程序出错而停止时正在执行的内容”
    错误与异常：
    https://docs.python.org/3/tutorial/errors.html
1.4 变量
    VARIABLE NAME = VALUE
    注意：
    1）Python 中没有某些语言中关于变量赋值的关键字，没有必要指定变量的类型 —— 只需直接使用等号为变量赋值即可。
    2）如果要使用变量名，则必须首先为其赋值！
    3）如果要访问该值，仅需使用变量名。
    * print 是 Python 的一个内置函数。Python 中的函数调用始终带有一对括号，如果有参数，那么参数放在括号内。 
    变量赋值：
    1）有一些不能用于变量名的保留字，如 False 和 class。https://docs.python.org/3/reference/lexical_analysis.html#keywords
    2）虽然在变量名中使用任何内置的标识符（e.g.int）不会立即导致错误，但我们也不建议使用。
    3) 再一次赋值时，旧数据被新值取而代之
    4）重新赋值运算符：e.g. +=, -=, *= ... 
       manila_pop += 1675 是 manila_pop = manila_pop + 1675 的简写。
1.5 布尔值和和比较运算符
    bool: True False
    运算符名称	符号
    小于	<
    大于	>
    小于等于	<=
    大于等于	>=
    等于	==
    不等于	!=
1.6 字符串和文本
    可以使用引号创建一个字符串 —— 单引号或双引号均可。
    可以使用 + 将字符串放在一起 —— 我们将其称为连接字符串。
    引号中的引号
1.7 内置函数
    len()
1.8 类型和类型转换
    type()
1.9 字符串方法
    处理值的三种方式：运算符，函数，方法(method)
    e.g. .title(), .islower()
    https://docs.python.org/3/library/stdtypes.html#string-methods
    e.g. .count(), .format()



