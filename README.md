#结构化数据
<br>
      之前学习了如何声明和定义变量，使之包含各种类型的数据，如整数，浮点数和字符等。学习了如何创建这些类型的数组和数组指针，这些指针指向包含可用数据类型内存位置。这些很有用，但是许多应用程序还需要一些更灵活的功能。<br>
      例如要编写一个处理马匹数据的程序，就需要每匹马的名字、出生日期、颜色、高度和它的父母等。在这些数据中，一些项是字符串，一些项是数值。因此，必须为每一种数据类型建立数组并储存它们。但是这是有限制的，例如不能方便地引用Dobbin的生日或者Trigger的身高。必须通过一个通用索引将数据项关联起来，使数组同步，C语言在这方面提供了相当好的方法。
