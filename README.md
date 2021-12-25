作业2
一、实验目的
1.掌握对象传值的影响 2.熟悉掌握实例化和构造方法的用法

二、业务要求
基本要求
实例化多个Lake对象
同一Fish对象均setFish其中
通过调用输出方法
查看weight的变化情况
在gitee的readme中给出结论 ##
三、解题思路 1.首先定义二个类，分别为Fish和Lake，再在Fish类中定义weight属性，在lake类中定义fish属性，setfish和eat方法 
2.实例化湖的类两个对象分别为西湖和太湖，实例化鱼的类一个对象泥鳅 
3.分别用西湖和太湖调用setfish方法，方法中用泥鳅作为参数。 
4.用太湖调用eat方法后，输出太湖、西湖、和泥鳅的重量 
5.同理用西湖在运行一遍
四、关键代码
1.将鱼放入湖中
void setFish(Fish s) {
        fish = s;
    }
1.让鱼的重量增加
    void eat(int n) {
        fish.weight = fish.weight + n;
    }
