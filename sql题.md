场景题如何构造微博那种关注和被关注的数据结构，我回答用图，然后就是图怎么构造，矩阵和邻接表分别适合哪种图

场景题：互相关注表设计

 **题目**：

 场景题：需求：谁关注了我，我关注了谁，谁与我互相关注。表该如何设计，索引怎么建。查询语句怎么写

 **思路**：

 个人见解，表可以有：id、粉丝id、被追随者id 三个字段，索引可以建两个，分别是粉丝 id 和被追随者 id。


sql题：
classId studentId courseId score
1. 求1班总分最高的前三名
2. 求每个班总分最高的前三名
