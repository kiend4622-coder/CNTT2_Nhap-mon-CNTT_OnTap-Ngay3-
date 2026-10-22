# Quản lý Trung tâm Tiếng Anh TTA

## Giới thiệu dự án
Trung tâm ngoại ngữ TTA cung cấp các khóa học chất lượng cao. Dự án này giúp **tự động hóa** việc quản lý học viên và *tối ưu hóa* quy trình tính học phí cho bộ phận kế toán.

## Cấu trúc thư mục
| Thư mục / File | Nội dung |
| :--- | :--- |
| `data/` | Chứa các file Excel dữ liệu khóa học và đăng ký |
| `docs/` | Tài liệu hướng dẫn sử dụng hệ thống |
| `logs/` | Lưu trữ nhật ký hệ thống và vận hành |

## Quy trình đăng ký học tại TTA
1. Học viên chọn khóa học phù hợp tại trung tâm.
2. Nhân viên tiếp nhận thông tin và tạo lượt đăng ký mới.
3. Kế toán tính toán tổng học phí và xác nhận hoàn tất.

## Lệnh liệt kê nội dung dự án
```powershell
Get-ChildItem -Path . -Recurse
