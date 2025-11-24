# ✈️ Travel Booking Website

> Hệ thống đặt tour du lịch trực tuyến, giúp kết nối khách hàng với các chuyến đi thú vị một cách nhanh chóng và tiện lợi. Đồ án cơ sở ngành Công nghệ Thông tin - Đại học Phenikaa.

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white)

## 📖 Giới thiệu
Dự án xây dựng một trang web thương mại điện tử chuyên về dịch vụ du lịch. Hệ thống cho phép người dùng tìm kiếm, xem chi tiết và đặt tour (Booking). Đồng thời cung cấp trang quản trị (Admin Dashboard) để quản lý tour, đơn hàng và khách hàng.

## 🚀 Tính năng chính

### 👤 Khách hàng (User)
* **Đăng ký/Đăng nhập:** Bảo mật thông tin người dùng.
* **Tìm kiếm Tour:** Lọc theo điểm đến, giá tiền, ngày khởi hành.
* **Đặt Tour (Booking):** Quy trình đặt vé và thanh toán trực tuyến.
* **Lịch sử:** Xem lại các tour đã đặt.

### 🛠 Quản trị viên (Admin)
* **Quản lý Tour:** Thêm, sửa, xóa thông tin tour du lịch.
* **Quản lý Đơn hàng:** Duyệt đơn, hủy đơn, xem doanh thu.
* **Quản lý Người dùng:** Phân quyền và quản lý tài khoản khách hàng.

## 🛠 Công nghệ sử dụng
* **Backend:** Java 17, Spring Boot (Spring MVC, Spring Data JPA, Spring Security).
* **Frontend:** HTML5, CSS3, JavaScript, Bootstrap, Thymeleaf.
* **Database:** MySQL.
* **Tools:** IntelliJ IDEA, Maven, Git, Postman.

## ⚙️ Cài đặt và Chạy dự án

**Yêu cầu:** JDK 17+, MySQL, Maven.

1.  **Clone dự án:**
    ```bash
    git clone [https://github.com/Tobii1707/Web-travel-booking.git](https://github.com/Tobii1707/Web-travel-booking.git)
    cd Web-travel-booking
    ```

2.  **Cấu hình Database:**
    * Tạo database tên `travel_booking` trong MySQL.
    * Mở file `src/main/resources/application.properties` và chỉnh sửa username/password của bạn:
    ```properties
    spring.datasource.url=jdbc:mysql://localhost:3306/travel_booking
    spring.datasource.username=root
    spring.datasource.password=your_password
    ```

3.  **Chạy ứng dụng:**
    ```bash
    mvn spring-boot:run
    ```
    Hoặc chạy file `TravelBookingApplication.java` trong IntelliJ IDEA.

4.  **Truy cập:**
    * Trang chủ: `http://localhost:8080`
    * Admin: `http://localhost:8080/admin`

## 🤝 Thành viên thực hiện
* **Dương Nhật Minh** (Leader): Fullstack, System Design.
* **Nguyễn Thị Kiều Loan:** Frontend, Testing.
* **Hà Nam Khánh:** Backend, Database Design.
* **Dương Văn Thắng:** Backend, Logic System.

---
*Created by Team Phenikaa Uni - 2025*
