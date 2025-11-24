# ✈️ Travel Booking Website

> Hệ thống đặt tour du lịch trực tuyến trọn gói (Fullstack Project).

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white)

## 📖 Giới thiệu
Đây là dự án cá nhân (Personal Project) mô phỏng một sàn thương mại điện tử du lịch hoàn chỉnh. Hệ thống được tôi xây dựng từ con số 0, bao gồm cả thiết kế giao diện (Frontend), xử lý nghiệp vụ (Backend) và thiết kế cơ sở dữ liệu.

Mục tiêu của dự án là áp dụng kiến thức **Spring Boot** và mô hình **MVC** để giải quyết bài toán đặt vé trực tuyến thực tế.

## 🚀 Chức năng chính tôi đã xây dựng

### 👤 Phân hệ Người dùng (Client)
* **Authentication:** Đăng ký, Đăng nhập, Quên mật khẩu (Spring Security).
* **Booking Flow:** Tìm kiếm tour -> Xem chi tiết -> Chọn lịch trình -> Đặt vé -> Thanh toán.
* **Profile:** Quản lý thông tin cá nhân và lịch sử đặt tour.

### 🛠 Phân hệ Quản trị (Admin Dashboard)
* **CRUD Management:** Quản lý toàn bộ Tour, Danh mục, User và Bài viết.
* **Order Processing:** Duyệt đơn đặt tour, xử lý hủy đơn và hoàn tiền.
* **Statistics:** Thống kê doanh thu theo tháng/quý (Biểu đồ).

## 🛠 Công nghệ sử dụng
* **Core:** Java 17.
* **Backend Framework:** Spring Boot 3.0 (Spring MVC, Spring Data JPA, Spring Security).
* **Frontend:** Thymeleaf Template Engine, HTML5, CSS3, Bootstrap 5, JavaScript.
* **Database:** MySQL.
* **Tools:** IntelliJ IDEA, Maven, Git, Postman.

## ⚙️ Cài đặt và Chạy

**Yêu cầu:** JDK 17+, MySQL, Maven.

1.  **Clone dự án:**
    ```bash
    git clone [https://github.com/Tobii1707/Web-travel-booking.git](https://github.com/Tobii1707/Web-travel-booking.git)
    cd Web-travel-booking
    ```

2.  **Cấu hình Database:**
    * Tạo database tên `travel_booking` trong MySQL.
    * Cập nhật `application.properties`:
    ```properties
    spring.datasource.url=jdbc:mysql://localhost:3306/travel_booking
    spring.datasource.username=root
    spring.datasource.password=your_password
    ```

3.  **Chạy ứng dụng:**
    ```bash
    mvn spring-boot:run
    ```

4.  **Truy cập:**
    * Trang chủ: `http://localhost:8080`
    * Admin: `http://localhost:8080/admin` (Tài khoản: admin/123456)

---
*Developed by Hà Nam Khánh*
