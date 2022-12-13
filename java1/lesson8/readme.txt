Nội dung kiến thức:
-Cú phap Labda
-Java Swing
-Test assiment

------ chú ý: Trong trường hợp interface chỉ có 1 phương thức thôii lúc đấy nó sẽ hỗ trợ 
cú pháp dài dòng thành cú pháp ngắn gọn

 // item 2: - Tìm hiểu hàm tạo trong labda
        //Khởi tạo đối tượng từ interface-> IMessage
  c1:      // lop nay k tái sử dụng đc nên chỉ sử dụng được 1 lần 
        IMessage m = new IMessage() {
            @Override
            public void onMessage() {
                System.out.println("Hello word!!!!!");
            }
        };
        m.onMessage();

        
  c2:      //Khởi tạo đối tượng từ interface-> IMessage
        // lop nay k tái sử dụng đc nên chỉ sử dụng được 1 lần 
        IMessage m2 = () -> {
            System.out.println("Hello2  word2!!!!!");
        };
        m2.onMessage();



        2 cách trên đều giống nhau 