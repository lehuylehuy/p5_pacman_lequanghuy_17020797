# p5_pacman_lequanghuy_17020797
1. cần hoàn thiện train trong perceptron.py 
duyệt mỗi lần và update weight dựa các classification errors.
CT:wy=wy+f ,wy′=wy′−f 
trong đó y là mylable,y' là trọng số của lable, f là featurebetter

2. hoàn thiện hàm findhighWeifeatures trả về 100 features của weight cao nhất
-sd câu lệnh python dataClassifier.py -c perceptron -w  trong câu hỏi
 để hiển thị 100 pixel với weight lớn nhất 
-so sánh ta đc a là kq và trả lời trong answer.py

3.trainAndTune trong mira.py. Phương pháp này sẽ đào tạo một trình phân loại MIRA bằng 
cách sử dụng từng giá trị của C trong Cgrid.
các weights mang lại độ chuẩn xác cao nhất trên validationData
Mira sử dụng tou để điều chỉnh lượng thay đổi
vì tou quá lớp thì sẽ k tối chúng ta sẽ đặt ra 1 giới hạn là c để tou không vượt quá c


4.thiết kế và cải thiện features hiện có
các feature đặc biệt:
số lượng vùng trắng mà các pixel đó liên tiếp nhau
Số thượng chuyển trạng thái pixel từ trắng sang đen trên đường kẻ giwuax màn hình
số lượng chuyển trạng thái pixel từ trắng sang đen trên đường kẻ dọc giwuax màn hình 

5. hoàn thiện phương thức train trong perceptron_pacman.py
cài đặt giống phương thức train khác 

6.thiết kế feature của riêng mình 
các feature chúng ta có thể sử dụng: win, lose, score,...
