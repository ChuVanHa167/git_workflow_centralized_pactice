# git_workflow_centralized_pactice
thực hành Centralized Workflow

**_Giả sử dự án:_**
Một nhóm nhỏ gồm 3 lập trình viên đang phát triển một website giới thiệu công ty.

Nhóm sử dụng Git theo mô hình Centralized Workflow.

_**Trong mô hình này:**_
Chỉ tồn tại một nhánh chính duy nhất _main_

Tất cả lập trình viên commit trực tiếp vào main
- Không có branch feature
- Không có branch release
- Không có branch hotfix

_**Workflow đơn giản:**_
```
Developer → commit → push → main
```
_**Mục đích của repo này:**_
Repo này dùng để minh họa cách hoạt động của Centralized Workflow.

_**Quy trình thực hành:**_
Clone repository
Tạo file code
Commit trực tiếp vào main
Push lên GitHub

**_Workflow:_**
```
Developer A
      \
Developer B -----> main
      /
Developer C
```
Tất cả thay đổi đều đi thẳng vào main.

_**Ưu điểm:**_
- Rất đơn giản
- Dễ học cho người mới
- Không cần quản lý nhiều branch

_**Nhược điểm**_
- Dễ gây conflict
- Không phù hợp dự án lớn
- Không có môi trường test riêng
