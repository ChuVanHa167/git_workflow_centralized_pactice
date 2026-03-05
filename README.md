# git_workflow_centralized_pactice
thực hành Centralized Workflow

Giả sử dự án:
Một nhóm nhỏ gồm 3 lập trình viên đang phát triển một website giới thiệu công ty.
Nhóm sử dụng Git theo mô hình Centralized Workflow.

Trong mô hình này:
Chỉ tồn tại một nhánh chính duy nhất: main
Tất cả lập trình viên commit trực tiếp vào main
Không có branch feature
Không có branch release
Không có branch hotfix

Workflow đơn giản:
Developer → commit → push → main

Mục đích của repo này:
Repo này dùng để minh họa cách hoạt động của Centralized Workflow.

Quy trình thực hành:
Clone repository
Tạo file code
Commit trực tiếp vào main
Push lên GitHub

Workflow
Developer A
      \
Developer B -----> main
      /
Developer C
Tất cả thay đổi đều đi thẳng vào main.

Ưu điểm
Rất đơn giản
Dễ học cho người mới
Không cần quản lý nhiều branch

Nhược điểm
Dễ gây conflict
Không phù hợp dự án lớn
Không có môi trường test riêng
