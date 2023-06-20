## Multi_Label_Image_Classification_For_Hanois_Scenic_Spots
Project này với mục đích phân biệt, trả về các địa danh của Hà Nội có trong ảnh
- Có 10 địa danh được huấn luyện trong mô hình trên: Hồ Gươm, Hồ Tây, Tháp Rùa, Cầu Thê Húc, Bưu Điện, Vườn Hoa, Khách Sạn, Đền Quán Thánh, Chùa Trấn Quốc, Công Viên Nước
- Mô hình được Pretrain từ mô hình ResNet50 với đầu ra Classification được sửa đổi, layer cuối cùng sử dụng hàm Sigmoid để đánh giá điểm của từng nhãn
- Mô hình trên mình xây dựng trên Driver để sử dụng Google Colab:
  https://drive.google.com/drive/folders/12EUJgDoP1y-dZK92tZT7snk9DoaSLxKn?usp=sharing
  - File Train: Resnet_miml
  - File Test: Test_Resnet
