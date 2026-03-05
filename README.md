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

### 🔹 Trang đăng nhập & Tổng quan
| Màn hình đăng nhập | Trang chủ hệ thống |
|---|---|
| ![Login](bluemoon/images/Screenshot%202026-03-03%20223739.png) | ![Dashboard](bluemoon/images/Screenshot%202026-03-03%20223754.png) |

### 🔹 Phân quyền Ban Quản Lý (Admin)
| Quản lý cư dân | Phê duyệt yêu cầu | Thống kê khoản thu | Góp ý từ cư dân |
|---|---|---|---|
| ![Dân cư](bluemoon/images/Screenshot%202026-03-03%20223804.png) | ![Duyệt](bluemoon/images/Screenshot%202026-03-03%20223823.png) | ![Thống kê](bluemoon/images/Screenshot%202026-03-03%20223832.png) | ![Góp ý](bluemoon/images/Screenshot%202026-03-03%20223839.png) |

### 🔹 Phân quyền Cư dân (User)
| Trang chủ User | Thông tin hộ gia đình | Phí & Thanh toán | Hệ thống thông báo |
|---|---|---|---|
| ![User](bluemoon/images/Screenshot%202026-03-03%20223920.png) | ![Hộ gia đình](bluemoon/images/Screenshot%202026-03-03%20223932.png) | ![Hóa đơn](bluemoon/images/Screenshot%202026-03-03%20223939.png) | ![Thông báo](bluemoon/images/Screenshot%202026-03-03%20223952.png) |
