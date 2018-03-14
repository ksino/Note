作者：[星辰](https://www.zhihu.com/question/30145645/answer/119778117)


### 基础
### 必不可少，web码农的基本知识（7）
1.了解http1.1八种方法，
- （常用：GET，POST）小公司写API，大公司封装API
  
2.熟悉Python数据结构，三类（注意逗号和顿号）：列表-list、元组-tuple、字符串-str，字典-dict，集合-set（常用：dict，list
- 搞清楚json和字典

3.了解一个请求到底包含了什么（用Django框架来解释，你可以简单理解为view的第一个参数，一般用request表示）
  
- 知道request.method（是GET，还是POST） - 这就是前面为什么要了解http1.1
- 知道request.is_ajax()（判断此次请求是否ajax）
- 知道return的格式，可以是json（Django框架里的JsonResponse），可以是最普通的render过的html（Django框架里的HttpResponse），等等

4.了解两个常用的数据库。

- 一个nosql（常用：mysql和mongodb）了解mongoengine

5.了解一些常用的前端库（以下几个足矣）
-  bootstrap，uikit(很轻量，用腻了前者可以尝试一下，没有学习成本哦) - 布局，常用组件（按钮，菜单等）
-  moment.js - 处理人类的时间逻辑
-  ECharts，highcharts，d3... - 画图表（入门先echarts，百度的，文档好理解，很活跃发展很快，一通百通，就像你选择了Python一样）
-  SweetAlert - 很好看的alert，后面补一个图结尾（好看很重要，真的）

6.了解常用的设计模式，一两个即可，工作的时候尽量往上靠，这个靠悟性（最常用：工厂方法）

7.算法呢，说真的会快速排序即可，当然多了不咬人

## 进阶
### 真正成为一名软件工程师（4）
1. 了解测试驱动开发（毕竟Python是动态语言，不过还是了解即可），懂得画简单的流程图，做事有条理

2. 了解需求，懂得甘特图的意义（最难的部分），懂得估算时间，懂得说出困难，而不是快失败了再怪别人没有给够你资源、时间
3. 懂得什么是特性，其他人看的是特性，代码的精妙只是你的精神食量，是你的小棉袄，你会理解的
4. 懂得什么是交付，交付的意义是什么
