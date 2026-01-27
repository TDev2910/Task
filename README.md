TaskFlow là một nền tảng quản lý công việc hiện đại, được thiết kế để tối ưu hóa quy trình làm việc nhóm. Dự án tập trung vào việc áp dụng các công nghệ mới nhất của hệ sinh thái Laravel (2025) và các Best Practices trong lập trình.

🌟 Key Features
Role-based Access Control (RBAC): Phân quyền chi tiết (Admin, Leader, Member) sử dụng Middleware và Policies.

Real-time Collaboration: Thông báo tức thời khi có thay đổi hoặc gán task nhờ Laravel Reverb.

Interactive Dashboard: Trực quan hóa dữ liệu công việc với Chart.js/ApexCharts.

Advanced Task Engine: Quản lý trạng thái phức tạp, gán người phụ trách và theo dõi deadline thông minh.

Activity Logs: Truy vết lịch sử thay đổi (Audit Trail) cho từng đầu việc.

🏗️ Technical Stack
Backend: Laravel 11 (PHP 8.3+)

Frontend: Vue.js 3 (Composition API) + Inertia.js

Real-time: Laravel Reverb

Database: MySQL 8 & Redis (Caching/Queue)

DevOps: Docker (PHP-FPM, Nginx, MySQL, Redis)

Testing: Pest/PHPUnit (Feature & Unit Testing)

📐 Architecture & Best Practices
Dự án không chỉ là CRUD cơ bản mà áp dụng các mô hình chuyên sâu để dễ dàng mở rộng:

Action & Service Pattern: Tách biệt logic nghiệp vụ khỏi Controller.

Custom Builders: Tối ưu hóa các câu lệnh truy vấn (Eloquent) phức tạp.

Clean Code: Tuân thủ nguyên tắc SOLID và DRY.
