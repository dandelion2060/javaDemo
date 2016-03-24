模拟课程管理系统的关系连接部分：
- 从数据文件CourseManagementSystem.xml中把数据读取出来并写入到数据库中形成关系链。
- 显示每门课程的最好成绩和平均成绩

分析部分：
- 观察xml文件结构
- 先把难点或者不清楚的技术关键点做一个先期试验
    - readMultiNode.java
- 建领域模型，即对象建模
    - Teacher: id, name
    - Student: id, name
    - Course: id, name
    - TechCourse: Teacher, Course
    - Score: Course, Student, score
- 根据对象关系形成数据库表结构

- 写程序
    - 先写出骨架
    - 一步步实现，实现一点就测试一点。保证这一点没问题
    - 数据库中文插入乱码问题(http://my.oschina.net/zhenguoguan/blog/138704)
    - 查询出数据封装成对象
    - 构造函数
    - toString
- 检验