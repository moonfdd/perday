##2020-03-25：快排、堆排和归并都是O(nlog n)的算法，为何JDK选择快速排序？
***
口诀如下： 
冒选插希快 堆归计桶基（冒泡，选择，插入，希尔，快速，堆，归并，计数，桶，基数）  
冒线 平平 稳常小  
选平 平平 不常小  
插线 平平 稳常序  
希线 四组 不常组  
快四 四平 不对大  
堆四 四四 不常大  
归四 四四 稳线大  
计加 加加 稳k空  
桶加 加平 稳加空  
基乘 乘乘 稳加空  

上述口诀是算法名称，最好时间复杂度，平均时间复杂度，最坏时间复杂度，是否稳定，空间复杂度，备注。  
线：线性阶。  
平：平方阶。  
四：线性平方阶。  

[评论](https://user.qzone.qq.com/136234428/blog/1585098900)  