# Sentiment Analysis with RNN-based Models on IMDB Dataset
Dự án này triển khai và so sánh các mô hình mạng neural hồi tiếp (Recurrent Neural Networks) để phân loại cảm xúc của các bài đánh giá phim từ tập dữ liệu IMDB. Các mô hình được sử dụng gồm:

RNN cơ bản

LSTM (Long Short-Term Memory)

GRU (Gated Recurrent Unit)

Bi-directional LSTM

Mục tiêu
Phân loại cảm xúc của bài đánh giá phim thành Tích cực (Positive) hoặc Tiêu cực (Negative).

So sánh hiệu năng giữa các loại mạng hồi tiếp khác nhau.

Trực quan hóa kết quả huấn luyện và đánh giá.

Công nghệ sử dụng
Python 3.x

TensorFlow 

NumPy, Matplotlib

Tập dữ liệu IMDB (có sẵn)

# Cài đặt
git clone https://github.com/dangphank4/RNN.git
# Cách chạy
Chạy mô hình với lựa chọn:
Sử dụng google colab
Các tùy chọn khác:
--epochs 10         # Số vòng lặp huấn luyện
--batch_size 64     # Kích thước batch
--embedding_dim 128 # Kích thước vector từ

# Các mô hình hỗ trợ
Mô hình	Tham số --model
Simple RNN	rnn
LSTM	lstm
GRU	gru
Bi-directional LSTM	bilstm

# Kết quả mẫu
Mô hình	Độ chính xác kiểm tra
RNN	~51.81%
LSTM	~77.29%
GRU	~86.20%
Bi-directional LSTM	~82.11%

# Biểu đồ minh họa 
SimpleRNN

![image](https://github.com/user-attachments/assets/311b9c95-fe68-4ab9-854a-a002361112c0)
![image](https://github.com/user-attachments/assets/0233a779-e2e9-4115-98e6-4ee8639770f2)

LSTM

![image](https://github.com/user-attachments/assets/24f5e2ae-1da1-4fb0-8d92-d1c5d8bc817f)
![image](https://github.com/user-attachments/assets/6b1ba032-3ec2-412e-be70-70868725a4a9)

Bi-directional LSTM

![image](https://github.com/user-attachments/assets/040c01ef-9365-401b-844d-76b792645a64)
![image](https://github.com/user-attachments/assets/689a2038-dca4-4d09-b3b8-0e3c8fc4b9ec)

GRU

![image](https://github.com/user-attachments/assets/9400634d-e117-45be-8b40-74775282291d)
![image](https://github.com/user-attachments/assets/50008f90-99ff-440b-9fd6-cb9a5f022e88)



Định hướng mở rộng
Thêm Attention Mechanism

Thử nghiệm với Embedding pre-trained (GloVe, FastText)

Áp dụng mô hình Transformer

Đánh giá mô hình trên tập dữ liệu khác (Amazon reviews, Yelp, v.v.)

# Tác giả
Tên: Phan Lê Hải Đăng

Email: phanlehaidanghsht@gmai.com

Github: https://github.com/dangphank4
