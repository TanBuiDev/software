# Nhóm 17

## 👥 Danh sách thành viên (Team Members)

| STT | MSSV       | Họ và Tên             | Vai trò (Role) | Tài khoản GitHub |
|:---:|:----------:|-----------------------|----------------|------------------|
| 1   | 2280602879 | **Bùi Lê Hoàng Tấn** | 👑 Team Lead   | [@TanBuiDev](https://github.com/TanBuiDev) |
| 2   | 2280602841 | **Nguyễn Thành Tâm** | Developer      | [@NguyenThanh-Tam](https://github.com/NguyenThanh-Tam) |
| 3   | 2280603258 | **Nguyễn Chánh Tín** | Developer      | [@ChanhTin3258](https://github.com/ChanhTin3258) |
| 4   | 2280609812 | **Nguyễn Lê Minh Khôi**| Developer      | [@KhoiNguyen0102](https://github.com/KhoiNguyen0102) |
| 5   | 2280606102 | **Lê Thành Đạt** | Developer      | [@KevinDat59](https://github.com/KevinDat59) |
| 6   | 2280606052 | **Đỗ Văn Đạt** | Developer      | [@Dat890369](https://github.com/Dat890369) |
| 7   | 2280601287 | **Đỗ Gia Hưng** | Developer      | [@Hungboong](https://github.com/Hungboong) |

## 🚀 Quy trình làm việc (Git Workflow)

Nhóm áp dụng mô hình **Git Flow** với các quy tắc nghiêm ngặt:

### 1. Nhánh (Branches)
* `main`: Mã nguồn sản phẩm chính thức (Production-ready).
* `develop`: Nhánh phát triển chung (Integration branch).
* `feature/<tên-chức-năng>`: Nhánh phát triển tính năng riêng của từng thành viên.
* `hotfix/<tên-lỗi>`: Nhánh sửa lỗi khẩn cấp trên main.

### 2. Quy tắc Commit (Convention)
* `feat`: Tính năng mới.
* `fix`: Sửa lỗi.
* `docs`: Thêm/Sửa tài liệu.
* `style`: Chỉnh sửa format, giao diện.

### 3. Quy trình Merge
1.  Code trên nhánh `feature/...` -> Push lên GitHub.
2.  Tạo **Pull Request** vào nhánh `develop`.
3.  Yêu cầu thành viên khác **Review** và **Approve**.
4.  Merge vào `develop`.
5.  Release: Merge `develop` -> `main` khi hoàn tất.

## 🛠 Cài đặt & Sử dụng

```bash
# Clone dự án về máy
git clone [https://github.com/TanBuiDev/software.git](https://github.com/TanBuiDev/software.git)

# Di chuyển vào thư mục
cd software

# Kiểm tra danh sách nhánh
git branch -a
