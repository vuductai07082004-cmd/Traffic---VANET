# Dự Án Dự Đoán Tắc Nghẽn Giao Thông Trong Mạng VANET (Vehicular Ad-Hoc Networks)

Dự án này áp dụng các thuật toán Học máy (Machine Learning) để dự báo trạng thái giao thông và các mức độ tắc nghẽn mạng trong mạng lưới kết nối xe cộ (VANET). Bằng cách phân tích các thông số vận hành của phương tiện và môi trường, mô hình giúp đưa ra cảnh báo sớm về các điểm nghẽn giao thông và mật độ xe, từ đó tối ưu hóa lộ trình và nâng cao hiệu quả giao thông thông minh.

---

## 📌 Mô Tả Dự Án
Trong mạng VANET, mật độ xe cộ cao và sự di chuyển nhanh chóng của các phương tiện thường dẫn đến tình trạng tắc nghẽn cục bộ, làm giảm hiệu suất truyền gói tin và gây ùn tắc giao thông. Dự án này tận dụng sức mạnh của phân tích dữ liệu và mô hình dự báo Machine Learning để dự đoán trước các kịch bản tắc nghẽn dựa trên tập dữ liệu mô phỏng mạng VANET.

## 🛠️ Các Thư Viện Cần Cài Đặt (Prerequisites)
Để chạy được dự án này, máy tính của bạn cần cài đặt ngôn ngữ lập trình Python (khuyến nghị phiên bản 3.8 trở lên) và các thư viện hỗ trợ xử lý dữ liệu, học máy sau.

Bạn có thể cài đặt nhanh tất cả các thư viện này bằng cách sao chép và chạy lệnh dưới đây trong Terminal / Command Prompt:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn notebook

Bước 1: Tải mã nguồn về máy cục bộ
Mở Terminal (trên Linux/macOS) hoặc Command Prompt/PowerShell (trên Windows) và gõ lệnh
git clone [https://github.com/vuductai07082004-cmd/Traffic---VANET/edit/main/README.md](https://github.com/vuductai07082004-cmd/Traffic---VANET/edit/main/README.md)
cd your-repo-name
Bước 2: Chuẩn bị dữ liệu
Hãy đảm bảo file dữ liệu mô phỏng VANET của bạn (ví dụ: vanet_traffic_data.csv) đã được đặt cùng trong thư mục chứa dự án.

Bước 3: Khởi chạy Jupyter Notebook
Tại thư mục dự án trên Terminal, gõ lệnh sau để mở giao diện Jupyter Notebook trên trình duyệt web:
jupyter notebook
Bước 4: Chạy các khối code (Cells)
Trên giao diện trình duyệt Jupyter, click vào file dự án có định dạng đuôi .ipynb (ví dụ: traffic_congestion_prediction.ipynb).

Chạy lần lượt các ô code (Cells) bằng cách nhấn tổ hợp phím Shift + Enter (hoặc nhấn nút Run trên thanh công cụ) để xem các biểu đồ trực quan hóa dữ liệu và kết quả huấn luyện mô hình.
