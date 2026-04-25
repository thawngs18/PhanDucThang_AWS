---
title: "Tuần 1 - Làm quen với AWS và các dịch vụ AWS cơ bản"
weight: 1
---

## Mục tiêu

- Tìm hiểu quy định, văn hóa doanh nghiệp, hoàn tất thủ tục với giảng viên hướng dẫn và thiết lập quy trình làm việc chung với nhóm FCJ.
- Nắm bắt các chính sách của AWS Free Tier 2025, nhận diện các dịch vụ dễ phát sinh chi phí và xây dựng phương án kiểm soát ngân sách an toàn.
- Xây dựng hệ thống quản lý định danh (IAM) bảo mật cao, áp dụng nguyên tắc "Quyền tối thiểu" (Least Privilege) và hạn chế sử dụng tài khoản Root.
- Nắm vững kiến thức nền tảng về kiến trúc mạng đám mây (VPC, Subnet, IGW, NAT Gateway) và các lớp bảo mật mạng (Security Group, Network ACLs).
- Thực hành xây dựng hạ tầng mạng ảo (VPC) độc lập và triển khai máy chủ EC2 trên AWS.

## Công việc đã thực hiện

### Ngày 17/04/2026

- Gặp gỡ, làm quen và tạo mối quan hệ với các thành viên trong đơn vị.
- Đọc kỹ các quy định, văn hóa doanh nghiệp và nội quy làm việc tại đơn vị thực tập.
- Tài liệu tham khảo: [https://rules.fcjuni.com/1-regulations/](https://rules.fcjuni.com/1-regulations/)

### Ngày 20/04/2026

- Liên hệ và chính thức xác nhận thông tin thực tập với GVHD.
- Chủ động kết nối, lập nhóm và phân chia vai trò với các thành viên FCJ.
- Thống nhất kênh liên lạc và công cụ quản lý công việc.

### Ngày 21/04/2026

- Đọc tài liệu cập nhật về AWS Free Tier 2025.
- Lên danh sách và ghi chú các dịch vụ có nguy cơ phát sinh chi phí cao để phòng tránh.
- Đăng ký tài khoản AWS và hoàn tất 5 task cơ bản để nhận $200 Credit.
- Thiết lập hệ thống cảnh báo chi phí để kiểm soát ngân sách an toàn.
- Tài liệu tham khảo: [https://000001.awsstudygroup.com/](https://000001.awsstudygroup.com/)

### Ngày 22/04/2026

- Thiết lập bộ ba User, Group và Role.
- Sử dụng Policy để định nghĩa hành động được phép hoặc bị cấm dựa trên nguyên tắc "Quyền tối thiểu".
- Không dùng tài khoản Root cho việc hằng ngày và bắt buộc kích hoạt xác thực đa yếu tố cho tài khoản Admin.
- Triển khai Switch Role để OperatorUser chuyển sang Admin tạm thời khi cần xử lý hệ thống.
- Khởi tạo thành công AdminGroup, AdminUser, OperatorUser và gán AllowSwitchAdminPolicy để hoàn tất lab.
- Tài liệu tham khảo: [https://000002.awsstudygroup.com/](https://000002.awsstudygroup.com/)

### Ngày 23/04/2026

- Tìm hiểu về Subnets, Route Table, Internet Gateway và NAT Gateway.
- Tìm hiểu cách hoạt động của Security Group, Network ACLs và công cụ VPC Resource Map.
- Tài liệu tham khảo: [https://000003.awsstudygroup.com/](https://000003.awsstudygroup.com/)

### Ngày 24/04/2026

- Đã tạo VPC, Subnet, Internet Gateway, Route Table, Security Group và bật giám sát VPC Flow Logs.
- Triển khai EC2: Khởi tạo máy chủ và kiểm tra kết nối thành công từ VSCode vào máy chủ.
- Tài liệu tham khảo: [https://000003.awsstudygroup.com/](https://000003.awsstudygroup.com/)

## Các lab đã thực hiện

<div class="row g-3">
  <div class="col-md-4">
    <div class="card h-100 shadow-sm">
      <div class="card-body">
        <h5 class="card-title">Lab 001 - AWS Free Tier</h5>
        <p class="card-text">Kích hoạt tài khoản AWS, hoàn tất 5 task để nhận credit, cấu hình AWS Budgets cảnh báo chi phí và thu hồi tài nguyên sau thực hành.</p>
      </div>
    </div>
  </div>

  <div class="col-md-4">
    <div class="card h-100 shadow-sm">
      <div class="card-body">
        <h5 class="card-title">Lab 002 - AWS IAM</h5>
        <p class="card-text">Tạo User/Group/Role, áp dụng Policy theo nguyên tắc Quyền tối thiểu, bật MFA, kiểm tra Switch Role và xác nhận cơ chế Deny &gt; Allow.</p>
      </div>
    </div>
  </div>

  <div class="col-md-4">
    <div class="card h-100 shadow-sm">
      <div class="card-body">
        <h5 class="card-title">Lab 003 - Amazon VPC</h5>
        <p class="card-text">Xây dựng VPC với Public/Private Subnet, cấu hình IGW/NAT Gateway, Route Table, Security Group, Network ACL và xác thực kết nối EC2 thành công.</p>
      </div>
    </div>
  </div>
</div>

## Kết quả

- Đã xác nhận xong thông tin thực tập, hoàn thiện cơ cấu nhóm FCJ, phân chia rõ vai trò và thống nhất công cụ quản lý, liên lạc.
- Đăng ký thành công tài khoản AWS, hoàn tất 5 task cơ bản để nhận $200 Credit và thiết lập Billing Alarm.
- Khởi tạo thành công IAM (AdminGroup, AdminUser, OperatorUser), bật MFA cho Admin và cấu hình Switch Role (AllowSwitchAdminPolicy).
- Triển khai hạ tầng mạng gồm VPC, Subnet, Internet Gateway, Route Table, Security Group và kích hoạt VPC Flow Logs.
- Khởi tạo thành công máy chủ EC2 và kiểm tra kết nối thành công từ VSCode.
