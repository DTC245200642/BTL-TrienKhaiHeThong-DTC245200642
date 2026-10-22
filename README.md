# BTL Triển khai và Quản trị Hệ thống - Đề 3

Bài tập lớn học phần Triển khai và Quản trị hệ thống phần mềm.  
Đề tài: Triển khai website quảng bá sản phẩm (WordPress), đóng gói container và giám sát hệ thống (Prometheus, Grafana, Loki).

* **Sinh viên thực hiện:** Nguyễn Ngọc Anh
* **MSSV:** DTC245200642
* **Lớp:** CNTT K23G
* **Giảng viên hướng dẫn:** Thầy Vũ Việt Dũng

---

## Các bước chạy dự án

### 1. Yêu cầu máy chủ
* Đã cài đặt Docker và Docker Compose trên máy/Ubuntu.

### 2. Khởi chạy hệ thống

Tải code về máy:
```bash
git clone https://github.com/DTC245200642/BTL-TrienKhaiHeThong-DTC245200642.git
cd BTL-TrienKhaiHeThong-DTC245200642
cp .env.example .env
chmod 600 .env
docker-compose up -d
docker ps
