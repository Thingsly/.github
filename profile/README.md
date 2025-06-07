# Thingsly IoT Platform

👉 English version: [README\_EN.md](./README_EN.md)

## 🧭 Sơ lược

**Thingsly** (Things (Mọi vật) + ly ) là nền tảng IoT mã nguồn mở do người Việt phát triển, được xây dựng và vận hành bởi đội ngũ Thingsly.

Nền tảng hỗ trợ nhà phát triển phần mềm và thiết bị IoT dễ dàng theo dõi và quản lý dự án qua **Web Dashboard** và ứng dụng **iOS/Android**. Ngoài ra, bộ thư viện do **Thingsly** phát triển giúp kết nối và quản lý thiết bị IoT một cách đơn giản và hiệu quả.

### 🔌 Các loại plugin chính:

- **Device Template**: Gắn kết model thiết bị với plugin giao thức.
- **Protocol Plugin**: Giải pháp cho việc truy cập thiết bị trực tiếp.
- **Kanban Card**: Mở rộng khả năng hiển thị dữ liệu trên dashboard.
- **Visualization Plugin**: Mở rộng giao diện hiển thị dữ liệu theo thời gian thực.

---

## 🚀 Sản phẩm

- **Unified Equipment Management**
- **IoT Middle Platform**
- **Backend quản lý thiết bị cho nhà cung cấp thiết bị**

---

## ✅ Ai nên dùng?

- **Maker/Enthusiast**: Kiến trúc mở khơi dậy sáng tạo.
- **System Integrator**: Một nền tảng cho mọi giải pháp.
- **Solution Provider**: Tiết kiệm thời gian/chi phí để nhanh chóng triển khai sản phẩm.
- **Thiết bị Vendor**: Tập trung làm phần cứng, Thingsly lo phần mềm.
- **End Customer**: Truy cập mọi thiết bị từ một nền tảng trung tâm.

---

## ✨ Điểm nổi bật

- **Ease of Use**: Đơn giản hóa IoT cho người phát triển.
- **Compatibility**: Hỗ trợ nhiều loại giao thức thiết bị.
- **Component-Based Architecture**: Thiết kế mở, dễ tùy biến và mở rộng.

---

## 🎯 Giá trị cốt lõi

### 🚀 Tăng hiệu suất

- Tăng hiệu quả phát triển **2–10 lần** nhờ plugin tái sử dụng.
- Rút ngắn thời gian triển khai **từ tháng xuống tuần**.
- Khuôn mẫu tiêu chuẩn giúp **giảm 80% công việc lặp lại**.

### 💰 Giảm chi phí

- **Giảm hơn 50%** chi phí nhân lực.
- **Tiết kiệm >70%** chi phí vận hành/bảo trì.

---

## ⚙️ Chức năng chính

- **Multi-Tenant**: Quản trị hệ thống, tài khoản, thiết bị của từng tenant.
- **Device Access**: Quản lý dự án, nhóm thiết bị.
- **Monitoring Dashboard**: Tạo nhiều dashboard, đặt làm menu/trang chủ.
- **Device Model**: Định nghĩa model thiết bị, sơ đồ, export JSON.
- **Equipment Map**: Lọc theo dự án, nhóm, loại thiết bị.
- **Visualization**: Giao diện kéo thả, hỗ trợ 3D (Three.js), loosely-coupled với hệ thống.
- **Automation**: Scene linkage, trigger theo thời gian/sự kiện.
- **Alarm Information**: Xem và lọc cảnh báo theo nhóm, thời gian.
- **Notification**: Gửi SMS, Email,...
- **System Log**: Ghi nhận IP, thao tác thiết bị.
- **User Management**: Casbin, phân quyền trang, phân vai trò, quản lý theo dự án.
- **System Settings**: Đổi logo, tiêu đề, giao diện.
- **IoT Mobile App**: Uniapp, quét mã thêm thiết bị, giám sát, điều khiển, chuyển dự án,...

---

## 🧠 Công nghệ

- **Golang**: Hiệu năng concurrency cao, tiết kiệm tài nguyên, hỗ trợ edge device.
- **Vue.js (v3)**: Dễ dùng, hiện đại.
- **Node.js (v16.13)**: Cross-platform, open-source.

### 📦 Cơ sở dữ liệu

- **PostgreSQL**: Rộng rãi, chi phí thấp.
- **TimescaleDB**: Plugin time-series cho PostgreSQL.

### 📡 Message Queue & Broker

- **GMQTT**: Message Queue hiệu suất cao.
- **VerneMQ**: MQTT Broker phân tán.

### ⚡ Khác

- **Redis**: NoSQL cache.
- **Nginx**: Web server hiệu suất cao.
