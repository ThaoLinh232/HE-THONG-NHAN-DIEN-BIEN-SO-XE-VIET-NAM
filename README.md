# 🚗 Nghiên cứu và Xây dựng Hệ thống Nhận diện Biển số Xe Việt Nam

## 📘 Giới thiệu

Đề tài **"Nghiên cứu và xây dựng hệ thống nhận diện biển số xe Việt Nam"** tập trung vào việc ứng dụng **xử lý ảnh (OpenCV)** và **mô hình học sâu YOLOv8** để **phát hiện vị trí biển số xe**, sau đó sử dụng **mạng nơ-ron tích chập (CNN)** để **nhận dạng ký tự** trên biển số.  

Hệ thống được xây dựng bằng **Python**, triển khai và thử nghiệm trong môi trường **Google Colab** và **Localhost**, không bao gồm giao diện đồ họa.  
Mục tiêu chính của hệ thống là tự động phát hiện và đọc chính xác biển số xe Việt Nam trong ảnh hoặc video.

---

## 🎯 Mục tiêu đề tài

1. **Nghiên cứu cấu trúc và đặc điểm biển số xe Việt Nam.**  
2. **Phát hiện vùng chứa biển số** bằng mô hình **YOLOv8**.  
3. **Tiền xử lý ảnh biển số** bằng **OpenCV** (lọc nhiễu, cắt vùng, nhị phân hóa).  
4. **Nhận dạng ký tự (OCR)** bằng **mạng CNN** huấn luyện riêng.  
5. **Đánh giá độ chính xác, tốc độ xử lý và khả năng mở rộng** của hệ thống.

---

## 🧠 Công nghệ và thư viện sử dụng

| Thành phần | Công nghệ/Thư viện |
|-------------|--------------------|
| Ngôn ngữ lập trình | Python 3.10+ |
| Xử lý ảnh | OpenCV, NumPy |
| Phát hiện biển số | YOLOv8 (Ultralytics) |
| Nhận dạng ký tự | CNN (Keras/TensorFlow) |
| Môi trường thực thi | Google Colab / Localhost |
| Định dạng dữ liệu | JPG, PNG, MP4 |

---

## 🧩 Quy trình hoạt động
📷 Ảnh đầu vào
🔍 Phát hiện vùng chứa biển số xe (YOLOv8)
✂️ Tiền xử lý vùng biển số (OpenCV)
🔠 Nhận dạng ký tự bằng CNN
🧾 Xuất kết quả: chuỗi biển số, độ tin cậy
