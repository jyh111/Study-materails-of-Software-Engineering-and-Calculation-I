2013期末试卷总结
第一题：
6道选择，考察重点是java语法规范
记得的有命名，异常，线程（这个一定要注意,好像考了两道，整个卷子我唯一不会做的就是这一道）
关键字，标识符，final ,static块的初始化。
第二题：
概念理解题：
一道是有关面向对象和结构化设计的区别
一道是有关版本控制的理解
（目测这种题每年都会变，注意老师最后一节课划重点过程中会透露信息，一定要注意老师强调的内容，尤其是他说可能考概念的都考了）
第三题：简答题，
1.是取自于PPT的一道难度大同小异的有关初始化顺序的题目，只要弄懂PPT中那个动物的例子就可以
2.同样是看程序写结果题，注意PPT上出现过的这类。
3.
第四题：同样是简答题
1.是一道画出选课系统一个用例图的题目
2.是描述选课系统各个对象之间的关系，建议使用语言+UML
3.写一个junit测试用例，并且叙述测试。（只需要会写最基本的即可，复习时不用花太多时间）
这几道考察面向对象思想的简答题是很基本的，只要把PPT上相关内容（或者那几个期末总结的文档看下，基本没问题）
其次，注意大作业，考前建议用大作业进行类图，juint，用例图的练习。
第五题：
写代码
具体难度见11年试卷，估计不会再出新的题，最多是变个主题，框架是不会变的。
再难一点的化可能会是headFirstJava上的那个小动画，或者是dailyAdvice个人估计不会更难了。
第六题：
此题为附加题，主要以考察较高级的面向对象思想为主，需要基本掌握继承，多态，和接口设计
1.给出一段代码（类似于）
public void excuate(int commandNum){
switch(commandNum){ 
    case 1://do task
    case 2:
    case 3:
    ....
    case 45:
  }
}
是实现网络的一种方式，即把命令进行编码，在服务器端进行译码。
问题：这样写看似不错，但是不易应对变更，多加命令，好几处需要修改。使用多态，改进设计
Answer：我的答案是：
一个Command抽象类，有一个excuate方法，每一个command建立一个子类，继承Command,实现excuate方法，
用Command command1=new Command1();这样的方式创建对象，即可实现动态绑定。
（虽说不咋地，但是肯定给分了）
2.一道与接口有关的题目。
考察的是OO基本原则，面向接口编程而不是面向实现编程