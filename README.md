# 🏢 BlueMoon - Apartment Management System

![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Python](https://img.shields.io/badge/Python-3.8+-3776AB?style=for-the-badge&logo=python&logoColor=white)

🌍 **BlueMoon** là hệ thống quản lý chung cư hiện đại, được thiết kế để tối ưu hóa việc tương tác giữa Ban quản lý và Cư dân, giúp mọi quy trình từ thu phí đến tiếp nhận góp ý trở nên minh bạch và nhanh chóng.

> ⚠️ **Project Status**: Đây là một sản phẩm thuộc dự án học tập, hiện đang trong giai đoạn phát triển prototype.

---

## 🌟 Tính năng chính

Hệ thống được thiết kế với hai phân quyền người dùng chuyên biệt:

### 🛠️ Phân quyền Ban Quản Lý (Admin)
* 📊 **Thống kê Khoản thu**: Theo dõi tổng quan dòng tiền, số phiếu đã thu và tỷ lệ thanh toán theo từng tháng.
* 👥 **Quản lý Cư dân**: Quản lý danh sách hộ gia đình, thông tin nhân khẩu và căn hộ chi tiết.
* 🚗 **Phê duyệt Yêu cầu**: Hệ thống duyệt các yêu cầu thêm xe, thay đổi nhân khẩu gửi từ cư dân.
* 📢 **Quản lý Thông báo**: Tạo và gửi các thông báo quan trọng (bảo trì điện, nước, nhắc nợ) tới toàn tòa nhà.
* 💰 **Quản lý Quyên góp**: Ghi nhận và công khai các khoản đóng góp từ thiện, quỹ cộng đồng.

### 🏠 Phân quyền Cư dân (User)
* 📋 **Thông tin Hộ gia đình**: Xem diện tích căn hộ, danh sách thành viên và thông tin chủ hộ.
* 💳 **Phí & Thanh toán**: Tra cứu lịch sử hóa đơn và thực hiện thanh toán qua mã QR tích hợp sẵn.
* 📩 **Gửi Góp ý**: Gửi các kiến nghị về an ninh, hạ tầng trực tiếp đến Ban quản lý.
* 🔔 **Hộp thư Thông báo**: Cập nhật nhanh nhất các tin tức mới nhất từ Ban quản lý.

---

## ⚙️ Công nghệ sử dụng

* **Backend**: Node.js
* **Database**: MySQL
* **Languages**: JavaScript, Python, CSS
* **Version Control**: Git & GitHub

---

## 📸 Giao diện ứng dụng

### 🔹 Giao diện Ban Quản Lý (Admin)
| Thống kê tài chính | Danh sách hộ dân | Phê duyệt yêu cầu |
|---|---|---|
| ![Thống kê](bluemoon/images/Screenshot%202026-03-03%20223832.jpg) | ![Dân cư](images/Screenshot%202026-03-03%20223804.png) | ![Duyệt](images/Screenshot%202026-03-03%20223823.png) |

### 🔹 Giao diện Cư dân (User)
| Trang chủ User | Chi tiết hóa đơn | Hệ thống thông báo |
|---|---|---|
| ![User](images/Screenshot%202026-03-03%20223920.jpg) | ![Hóa đơn](images/Screenshot%202026-03-03%20223939.jpg) | ![Thông báo](images/Screenshot%202026-03-03%20223952.png) |
