

# BÀI LÀM – HACKATHON 01

[](https://github.com/haianhvotam08-creator/HNKS26CNTT3_NHAPMONCNTT_hackathon01/blob/main/bai_lam.md#b%C3%A0i-l%C3%A0m--hackathon-01)

-   **Mã đề:** 17
-   **Họ tên:_Nguyễn Hải Anh
-   **Lớp:_CNTT3_
-   **Link repository:**
-   **Hệ điều hành (Windows/macOS):_Windows_

## 4.2. Thao tác máy tính cơ bản bằng CLI

[](https://github.com/haianhvotam08-creator/HNKS26CNTT3_NHAPMONCNTT_hackathon01/blob/main/bai_lam.md#42-thao-t%C3%A1c-m%C3%A1y-t%C3%ADnh-c%C6%A1-b%E1%BA%A3n-b%E1%BA%B1ng-cli)

### Các lệnh đã chạy

[](https://github.com/haianhvotam08-creator/HNKS26CNTT3_NHAPMONCNTT_hackathon01/blob/main/bai_lam.md#c%C3%A1c-l%E1%BB%87nh-%C4%91%C3%A3-ch%E1%BA%A1y)

pwd
ls -Force
mv .\nguon_hang.txt .\docs\
mv .\logo_trai_cay_sach.PNG .\media\
 cp .\media\logo_trai_cay_sach.PNG .\backup\
 rm -r *.tmp
 cd .\logs\
cat .\fruit.log
cd ..

### Kết quả liệt kê toàn bộ dự án (Windows: Get-ChildItem -Recurse -Force; macOS: ls -aR)

[](https://github.com/haianhvotam08-creator/HNKS26CNTT3_NHAPMONCNTT_hackathon01/blob/main/bai_lam.md#k%E1%BA%BFt-qu%E1%BA%A3-li%E1%BB%87t-k%C3%AA-to%C3%A0n-b%E1%BB%99-d%E1%BB%B1-%C3%A1n-windows-get-childitem--recurse--force-macos-ls--ar)

```
 Directory:
    C:\Users\admin\Downloads\starter-kit\starter-kit\trai-cay-website


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----        10/28/2026  10:59 AM                backup
d-----        10/28/2026  10:51 AM                data
d-----        10/28/2026  10:53 AM                docs
d-----        10/28/2026  10:51 AM                logs
d-----        10/28/2026  10:54 AM                media
------        10/27/2026   1:32 AM             70 .env
-a----        10/27/2026   1:32 AM           2228 bai_lam.md


    Directory: C:\Users\admin\Downloads\starter-kit\starter-kit\trai-cay-we
    bsite\backup


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/27/2026   1:32 AM           7054 logo_trai_cay_sach.PNG


    Directory:
    C:\Users\admin\Downloads\starter-kit\starter-kit\trai-cay-website\data


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/27/2026   1:32 AM           6095 ban_trai_cay_thang_7.xlsx


    Directory:
    C:\Users\admin\Downloads\starter-kit\starter-kit\trai-cay-website\docs


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/27/2026   1:32 AM             66 nguon_hang.txt


    Directory:
    C:\Users\admin\Downloads\starter-kit\starter-kit\trai-cay-website\logs


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/27/2026   1:32 AM           1041 fruit.log


    Directory:
    C:\Users\admin\Downloads\starter-kit\starter-kit\trai-cay-website\media


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/27/2026   1:32 AM           7054 logo_trai_cay_sach.PNG


PS C:\Users\admin\Downloads\starter-kit\starter-kit\trai-cay-website>


```

## 4.3. Lọc log thủ công

[](https://github.com/haianhvotam08-creator/HNKS26CNTT3_NHAPMONCNTT_hackathon01/blob/main/bai_lam.md#43-l%E1%BB%8Dc-log-th%E1%BB%A7-c%C3%B4ng)

### Lệnh đã chạy

[](https://github.com/haianhvotam08-creator/HNKS26CNTT3_NHAPMONCNTT_hackathon01/blob/main/bai_lam.md#l%E1%BB%87nh-%C4%91%C3%A3-ch%E1%BA%A1y)

# Ghi lệnh vào đây (xoá dòng này)
cat .\logs\fruit.log | Select-String "ERROR" > .\logs\daily_report.txt

### 2 dòng lỗi đầu tiên trong daily_report.txt

[](https://github.com/haianhvotam08-creator/HNKS26CNTT3_NHAPMONCNTT_hackathon01/blob/main/bai_lam.md#2-d%C3%B2ng-l%E1%BB%97i-%C4%91%E1%BA%A7u-ti%C3%AAn-trong-daily_reporttxt)

```
2026-07-28 10:04:32 [ERROR] Thanh toan bi tu choi
2026-07-28 10:16:32 [ERROR] Het thoi gian cho (timeout)


```

## 4.4. Thao tác với tài liệu Markdown (README.md)

[](https://github.com/haianhvotam08-creator/HNKS26CNTT3_NHAPMONCNTT_hackathon01/blob/main/bai_lam.md#44-thao-t%C3%A1c-v%E1%BB%9Bi-t%C3%A0i-li%E1%BB%87u-markdown-readmemd)

> README.md được chấm trực tiếp trên file `README.md` ở gốc dự án. Đánh dấu `[x]` vào các mục đã làm để tự kiểm tra.

-   Heading 1: tên dự án
-   Mô tả ngắn có cả **in đậm** và _in nghiêng_
-   Bảng `Thư mục | Nội dung`, ít nhất 3 dòng dữ liệu
-   Code block chứa lệnh PowerShell/Terminal liệt kê nội dung dự án
-   Task list ít nhất 2 công việc, có ít nhất 1 mục đã hoàn thành
-   Blockquote nhắc không upload `.env`

## 4.5. Chạy script auto_report (.ps1 hoặc .sh)

[](https://github.com/haianhvotam08-creator/HNKS26CNTT3_NHAPMONCNTT_hackathon01/blob/main/bai_lam.md#45-ch%E1%BA%A1y-script-auto_report-ps1-ho%E1%BA%B7c-sh)

### Lệnh chạy (Windows: nếu dùng Phụ lục 2 thì ghi cả 2 lệnh)

[](https://github.com/haianhvotam08-creator/HNKS26CNTT3_NHAPMONCNTT_hackathon01/blob/main/bai_lam.md#l%E1%BB%87nh-ch%E1%BA%A1y-windows-n%E1%BA%BFu-d%C3%B9ng-ph%E1%BB%A5-l%E1%BB%A5c-2-th%C3%AC-ghi-c%E1%BA%A3-2-l%E1%BB%87nh)

.\auto_report.ps1

### Kết quả hiển thị

[](https://github.com/haianhvotam08-creator/HNKS26CNTT3_NHAPMONCNTT_hackathon01/blob/main/bai_lam.md#k%E1%BA%BFt-qu%E1%BA%A3-hi%E1%BB%83n-th%E1%BB%8B)

```
Dang loc log ...
Hoan thanh!


```

## 4.6. Đếm số dòng lỗi

[](https://github.com/haianhvotam08-creator/HNKS26CNTT3_NHAPMONCNTT_hackathon01/blob/main/bai_lam.md#46-%C4%91%E1%BA%BFm-s%E1%BB%91-d%C3%B2ng-l%E1%BB%97i)

### Lệnh

[](https://github.com/haianhvotam08-creator/HNKS26CNTT3_NHAPMONCNTT_hackathon01/blob/main/bai_lam.md#l%E1%BB%87nh)

 (cat .\logs\fruit.log | select-string "ERROR").count

### Kết quả đếm (Windows: giá trị Count; macOS: con số in ra)

[](https://github.com/haianhvotam08-creator/HNKS26CNTT3_NHAPMONCNTT_hackathon01/blob/main/bai_lam.md#k%E1%BA%BFt-qu%E1%BA%A3-%C4%91%E1%BA%BFm-windows-gi%C3%A1-tr%E1%BB%8B-count-macos-con-s%E1%BB%91-in-ra)

```
5


```

## 4.7. Báo cáo tổng hợp

[](https://github.com/haianhvotam08-creator/HNKS26CNTT3_NHAPMONCNTT_hackathon01/blob/main/bai_lam.md#47-b%C3%A1o-c%C3%A1o-t%E1%BB%95ng-h%E1%BB%A3p)

### Các lệnh đã chạy

[](https://github.com/haianhvotam08-creator/HNKS26CNTT3_NHAPMONCNTT_hackathon01/blob/main/bai_lam.md#c%C3%A1c-l%E1%BB%87nh-%C4%91%C3%A3-ch%E1%BA%A1y-1)

“=== TONG HOP LOG ===“ > .\logs\tong_hop.txt
 cat .\logs\fruit.log | Select-String “WARNING” >> .\logs\tong_hop.txt
  (cat .\logs\fruit.log | Select-String “ERROR”).count >> .\logs\tong_hop.txt

### Nội dung file logs/tong_hop.txt

[](https://github.com/haianhvotam08-creator/HNKS26CNTT3_NHAPMONCNTT_hackathon01/blob/main/bai_lam.md#n%E1%BB%99i-dung-file-logstong_hoptxt)

```
(Dán kết quả vào đây – xoá dòng này)


```

## 4.8. Excel

[](https://github.com/haianhvotam08-creator/HNKS26CNTT3_NHAPMONCNTT_hackathon01/blob/main/bai_lam.md#48-excel)

> Phần Excel được chấm trực tiếp trên file `data/ban_trai_cay_thang_7.xlsx`, không cần ghi vào đây.
