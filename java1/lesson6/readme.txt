Nội dung kiến thức :
- chữa bt 
-COLLection(List , ArrayList, Vector)
-Public/Protected/Private/Friendly
-Final +Static+.........
    -Final
        -biến
        -hàm
 

-Stringbulder và buffer =>>>>>>>>>>>>>>>>>>>>>>>> Nên dùng builder
    -trong java có 2 loại biến
        -Biến char , float, int...........gọi là biến nguyên thủy 
        -String ;à 1 class object
    -StringBuilder
        // xu ly chuỗi lớn hay cộng chuỗi thì dùng 
        StringBuilder builder = new StringBuilder();
        builder.append("ads");
        builder.append("1334");
        builder.append("đâss");
        builder.append("0988");
        //in ra dùng tostring
        System.out.println(builder.toString())

        ==================================================    KHÁC NHAU          ==============
            -Stringbuilder và Stringbuffer khác nhau ở hàm append,to string 
                -Stringbuffer CÓ Synchronized
                    +Synchronized liên quan đến hệ thống làm việc đa luông,lập trình song song,  giúp đồng bộ luồng, kiểm soát bộ nhớ tốt
                