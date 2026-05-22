# 📱 Impact of TikTok on ADHD Symptoms
*Computational Social Media Final Project - Fulbright University Vietnam*

## 📌 Giới thiệu dự án (Project Overview)
Dự án này là bài tập cuối kỳ của môn học **Computational Social Media** tại Đại học Fulbright Việt Nam, dưới sự hướng dẫn của **Giáo sư - Tiến sĩ Phan Thành Trung**. 

Nghiên cứu tập trung vào việc đánh giá tác động của việc sử dụng TikTok đối với các triệu chứng của Hội chứng Rối loạn Tăng động Giảm chú ý (ADHD), đặc biệt là **khả năng tập trung (attention span)** của thanh thiếu niên và người trưởng thành trẻ.

### 👥 Thành viên Nhóm 1 (Group 1)
- **Nguyễn Phan Quỳnh Như (240109)** - *Phân chia công việc, Viết phần Kết quả, Lập trình phân tích dữ liệu* 👩‍💻
- **Phạm Bảo Anh Thy (240192)** - *Quản lý nhóm, Viết Phương pháp nghiên cứu, Lập trình phân tích dữ liệu*
- **Phạm Thị Hoài An (220125)** - *Quản lý nhóm, Viết Mở đầu và xử lý dữ liệu*
- **Nguyễn Thục Anh (240126)** - *Viết Kết luận, Định dạng báo cáo*
- **Trịnh Trần Bảo Châu (230177)** - *Tổng quan tài liệu (Literature Review)*
- **Võ Hương Giang (240181)**

---

## 🎯 Mục tiêu nghiên cứu (Research Objectives)
Khi TikTok ngày càng trở nên phổ biến và gây nghiện, việc hiểu rõ tác động của nền tảng này đến sức khỏe tinh thần là cực kỳ cần thiết để xây dựng thói quen sử dụng lành mạnh. Mặc dù đã có nhiều nghiên cứu về mạng xã hội nói chung, nhưng vẫn thiếu các dữ liệu thống kê cụ thể về mối tương quan giữa Hội chứng ADHD và việc sử dụng TikTok. 

Dự án nhằm mục đích thu hẹp khoảng trống này bằng cách thu thập và phân tích dữ liệu thực tế về **thời lượng**, **thói quen tương tác** và **triệu chứng ADHD tự báo cáo** của người dùng.

---

## 🛠 Phương pháp nghiên cứu (Methodology)
- **Thu thập dữ liệu:** Khảo sát trực tuyến thu về **201 phản hồi** từ người dùng TikTok.
- **Tiền xử lý & Trực quan hóa dữ liệu:** - Loại bỏ các quan sát không hợp lệ (người không sử dụng TikTok).
  - Ánh xạ (mapping) thời lượng sử dụng và tần suất triệu chứng về các biến dạng số (ví dụ: quy đổi "Dưới 30 phút" thành 0.5 giờ).
  - Tính toán các chỉ số tổng hợp: `ADHD_score`, `attention_score`, `impulsivity_score`, và `impact_score`.
- **Phân tích thống kê:** Sử dụng thống kê mô tả, kiểm định phân tích phương sai (ANOVA), và kiểm định tương quan để tìm ra các mẫu (patterns) trong hành vi người dùng.

---

## 📊 Kết quả nổi bật (Key Findings)
- Việc sử dụng TikTok hàng ngày có liên hệ đáng kể với sự suy giảm khả năng tập trung và gia tăng các biểu hiện của triệu chứng ADHD.
- Khung thời gian người dùng lướt TikTok trong ngày cũng có tác động nhất định đến khoảng thời gian chú ý (attention span) của họ.
- **Hệ quả tương lai:** Cần thúc đẩy giáo dục về kiến thức truyền thông (media literacy), nâng cao nhận thức về thời gian sử dụng màn hình, và đưa ra các thiết kế ứng dụng (design nudges) khuyến khích việc sử dụng chừng mực.

---

## 📁 Cấu trúc Repository (Repository Structure)
- 📄 `CSM - GROUP 1 - FINAL PROJECT.ipynb`: File Jupyter Notebook chứa mã nguồn Python thực hiện toàn bộ các bước xử lý, phân tích thống kê và trực quan hóa dữ liệu.
- 📄 `Computational_Social_Media_Final_Report_Group 1.pdf`: Báo cáo nghiên cứu chi tiết (Final Paper).
- 📄 `CSM - GROUP 1 - FINAL PROJECT.pdf`: Slide thuyết trình dự án của nhóm (Presentation Deck).
- 📄 `ksatfile.xlsx` (Dataset - Ẩn do lý do bảo mật thông tin khảo sát): Dữ liệu thô được trích xuất từ Google Forms.

---

## 💻 Công nghệ sử dụng (Technologies Used)
- **Ngôn ngữ lập trình:** Python
- **Thư viện xử lý dữ liệu:** `pandas`, `numpy`
- **Thư viện trực quan hóa:** `seaborn`, `matplotlib`
- **Thư viện thống kê & Machine Learning:** `scipy`, `statsmodels`, `scikit-learn`
- **Môi trường:** Google Colab / Jupyter Notebook
