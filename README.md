# Deep_Learning_DS201
Đếm số người và phát hiện vi phạm khoảng cách cộng đồng từ CCTV


- **Mô tả bài toán :**

  - Bài toán của chúng tôi đưa ra sẽ là phát hiện số người từ frame của camera an
ninh từ đó đếm số lượng người có mặt bằng cách sử dụng YOLOv4. Sau khi đã
có các đối tượng thì thực hiện đo khoảng cách giữa các đối tượng để chỉ những
vị phạm về khoảng cách.
  
  - Trong đồ án này, tập dữ liệu dùng để nhận dạng người được thu thập bằng hai
cách đó là lấy một phần bộ dữ liệu có sẵn và tự thu thập:

    – Đối với hướng đầu tiên, thu thập dữ liệu có sẵn, việc thu thập dữ liệu sẽ
nhanh và hiệu quả hơn hướng thứ hai. Cụ thể ở phần này, chúng tôi đã trích
ra 2000 ảnh trong Dataset Scut Head.

    – Đối với hướng thứ hai, thu thập dữ liệu bằng cách thủ công, việc thu thập
dữ liệu sẽ bổ sung được những dữ liệu khó nhận dạng như ảnh mờ, trời
mưa,. . . Cụ thể ở phần này, chúng tôi đã thu thập được 2329 ảnh trên các
wedsite thông dụng như Google, Bing,. . .


- **Mô tả file :**
  - **File pdf :**Nội dung chi tiết quá trình thực hiện.
  - **person.jpynb :**File thực hiện quá trình train YOLO V4.
  - **Detector.ipynb :**File thực hiện đếm số người dưới dạng video.
  - **File media :**Video trước và sau khi áp dụng mô hình.


- **Kết luân :**
Qua bài toán tôi đúc kết được kiến thức cơ bản về deep learning, hiểu được về một số mạng deep learning cơ bản như:**CNN**,**RNN**,...
