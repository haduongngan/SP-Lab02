# SP-Lab02
Trong bài tập này, em thực hiện nhận dạng các khẩu lệnh đơn lẻ.
Các yêu cầu bao gồm: 
- Sử dụng dữ liệu đã thu (theo nhóm), trích xuất đặc trưng MFCC (39 đặc trưng, gồm cả MFCC, delta, deltadelta) của từng khẩu lệnh / con số
- Viết chương trình sử dụng DTW để nhận dạng khẩu lệnh đơn lẻ (mỗi từ/khẩu lệnh dùng khoảng 2-3 mẫu)
- Viết chương trình sử dụng HMM (segmental K-means) để nhận dạng khẩu lệnh đơn lẻ (sử dụng HMM với Mixture of Gaussians, sử dụng toàn bộ bộ dữ liệu đã thu).

Cấu trúc tổ chức các file trong github:
- Thư mục src chứa code của các chương trình: xử lý dữ liệu và trích xuất đặc trưng, cài đặt sử dụng DTW để nhận dạng khẩu lệnh, 2 tệp sử dụng HMM (khác nhau về số nhãn sử dụng) để nhận dạng khẩu lệnh
- Thư mục data chứa các file âm thanh đã cắt
- Thư mục MFCC chứa các list đặc trưng MFCC đã trích xuất
- Thư mục model chứa các model đã huấn luyện và lưu lại

Sau đây là đoạn video demo ngắn về bài tập của em:
