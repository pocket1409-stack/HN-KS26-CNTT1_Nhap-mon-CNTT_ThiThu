# BÀI LÀM – THI THỬ HACKATHON 01

- **Mã đề:Thi thử
- **Họ tên:Trần Thiện Thuật
- **Lớp:CNTT1
- **Link repository:https://github.com/pocket1409-stack/HN-KS26-CNTT1_Nhap-mon-CNTT_ThiThu
- **Hệ điều hành (Windows/macOS):WIndows

## 4.2. Thao tác máy tính cơ bản bằng CLI

### Các lệnh đã chạy

```shell
# Ghi lần lượt các lệnh đã chạy, mỗi lệnh một dòng

```

### Kết quả liệt kê toàn bộ dự án (Windows: Get-ChildItem -Recurse -Force; macOS: ls -aR)

```text
PS C:\Users\HLC\Desktop\starter-kit\van-phong-pham-website> pwd
PS C:\Users\HLC\Desktop\starter-kit\van-phong-pham-website> ls -Force
```

## 4.3. Lọc log thủ công

### Lệnh đã chạy

```shell
# PS C:\Users\HLC\Desktop\starter-kit\van-phong-pham-website\logs> cd ..
```

### 2 dòng lỗi đầu tiên trong daily_report.txt
2025-10-28 08:24:28 [ERROR] Thanh toan bi tu choi
2025-10-28 08:30:28 [ERROR] Thanh toan bi tu choi
```text

```

## 4.4. Thao tác với tài liệu Markdown (README.md)

> README.md được chấm trực tiếp trên file `README.md` ở gốc dự án. Đánh dấu `[x]` vào các mục đã làm để tự kiểm tra.

- [x] Heading 1: tên dự án
- [x] Mô tả ngắn có cả **in đậm** và *in nghiêng*
- [x] Bảng `Thư mục | Nội dung`, ít nhất 3 dòng dữ liệu
- [x] Code block chứa lệnh PowerShell/Terminal liệt kê nội dung dự án
- [x] Task list ít nhất 2 công việc, có ít nhất 1 mục đã hoàn thành
- [x] Blockquote nhắc không upload `.env`

## 4.5. Chạy script auto_report (.ps1 hoặc .sh)

### Lệnh chạy (Windows: nếu dùng Phụ lục 2 thì ghi cả 2 lệnh)

```shell
# Ghi lệnh vào đây (xoá dòng này)
PS C:\Users\HLC\Desktop\starter-kit\van-phong-pham-website> # Script: auto_report.ps1
PS C:\Users\HLC\Desktop\starter-kit\van-phong-pham-website> # Tac gia: Thuat
PS C:\Users\HLC\Desktop\starter-kit\van-phong-pham-website> # Ngay tao: 23/10/2026
PS C:\Users\HLC\Desktop\starter-kit\van-phong-pham-website>
PS C:\Users\HLC\Desktop\starter-kit\van-phong-pham-website> Write-Host "Dang loc log..."
Dang loc log...
PS C:\Users\HLC\Desktop\starter-kit\van-phong-pham-website> "=== BAO CAO LOI ===" > logs/auto_report.txt
PS C:\Users\HLC\Desktop\starter-kit\van-phong-pham-website> Get-Content logs/shop.log | Select-String "ERROR" >> logs/auto_report.txt
PS C:\Users\HLC\Desktop\starter-kit\van-phong-pham-website> Write-Host "Hoan thanh!"
Hoan thanh!
```

### Nội dung file logs/auto_report.txt

```text


```

## 4.6. Đếm số dòng lỗi

### Lệnh

```shell
# PS C:\Users\HLC\Desktop\starter-kit\van-phong-pham-website> Get-Content logs/shop.log | Select-String "ERROR" | Measure-Object | Select-Object -ExpandProperty Count

```

### Kết quả đếm (Windows: giá trị Count; macOS: con số in ra)

```text
6

```

## 4.7. Báo cáo tổng hợp

### Các lệnh đã chạy

```shell
# Ghi lần lượt các lệnh đã chạy, mỗi lệnh một dòng (xoá dòng này)

```

### Nội dung file logs/tong_hop.txt

```text
(Dán kết quả vào đây – xoá dòng này)

```

## 4.8. Excel

> Phần Excel được chấm trực tiếp trên file `data/don_ban_thang_10.xlsx`, không cần ghi vào đây.
