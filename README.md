linux系统----一个根目录（安全级别比较高）/且不能修改----操作通过命令行
    常用命令  ---pwd显示当前的工作目录
             ----ls查看当前目录的所有信息
             ----cd  改变当前目录
             ----cd +空格 回到主目录
             
             
java类型------8个类型
         ----int 4位  整形（整数），有范围+21亿到-21亿，会有益出现象，超出变负值。。。Java默认是整形类型  中等
         ----long 8位  长整形，有范围-百亿到+百亿，结尾必须加上l或者L才能表示是长整形                    比较大
         ----double 8位  浮点数，。。。java默认是double类型，
         ----float 4 位  浮点数，结尾加上f或者F
         ----char 由两部分组成，字符+码   char是一个16位无符号的Unicode码
             转义字符 ‘\n'回车
                     '\r'换行
         -----boolean  逻辑运算 true和false
         -----byte 1位   范围在-128（-2^7）  最小的
         -----shor                        较小
         
         double>float>long>int>short>byte(char==int)
         类型转换：
           1 自动类型转：从小类型到大类型自动转换
           2 强制转换：（类型）变量   ----从大类型到小类型
           
           byte,short,char参与运算时直接转换位int型
     java循环：
          while 循环-
          do…while 循环
          for 循环
          
          for(声明语句 : 表达式)
            {
               声明新的局部变量，该变量的类型必须和数组元素的类型匹配。其作用域限定在循环语句块，其值与此时数组元素的值相等。
               表达式：表达式是要访问的数组名，或者是返回值为数组的方法。
            }
          break 主要用在循环语句或者 switch 语句中，用来跳出整个语句块
          continue 适用于任何循环控制结构中。作用是让程序立刻跳转到下一次循环的迭代。

     java数组：
          声明数组    dataType[] arr={3,5,7,7,8}----直接给数组arr赋值
                     dataType[] arr= new dataType[5] -----声明一个长度为5的数组，没有赋值默认每一项是0，
                     dataType[] arr=new dataType{1，2，5，6，8，7}-----声明一个数组直接赋值
                     
                     
          数组排序    java方法
                        import java.utils.Array
                        Array.sort 
                     冒泡排序
                       for(var i=0;i<=arr.length;i++){
                           for(var j=0;j<=arr.length-1-i;j++){
                               if(arr[j]>arr[j+1]){
                                   int t=arr[j]
                                   arr[j+1]=arr[j]
                                   arr[j]=t
                               
                               }
                           }
                       }
                     
            

           
    
             
