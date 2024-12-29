Bản TN từ 2.3 trở xuống là không mã hoá dữ liệu; từ 2.4 trở lên là mã hoá dữ liệu.
=> Qua lại giữa các bản mã hoá và không mã hoá cần format data.

## Đối với bản 2.6 trở lên:
- Đăng kí quyền Flash TN theo hướng dẫn: Tại đây.
-  Cài driver cho PC (Cách nhanh nhất là cài MiSuite). 
- Đưa máy về chế độ fastboot -> Giải nén rom .7z trong PC -> Chạy file "TNFlash.exe" (Không chạy quyền Admin) -> Gõ "2" nếu giữ dữ liệu, gõ "1" nếu Format data -> Nhấn Enter và chờ báo thành công đồng thời điện thoại khởi động lại.

Lưu ý: Vào recovery để format data và khởi động lại hoặc chạy lại rom qua fastboot 1 lần nữa nếu không boot được.

## Đối với bản 2.5 trở xuống:
1. Cài qua Recovery:

a. Flash đè: Nếu đang dùng MiuiTN  (không mất dữ liệu)

- Wipe cache, dalvik cache -> Flash rom -> Flash current recovery trong Advance  (dành cho máy phân vùng A/B) -> Reboot system.

b. Flash sạch: Nếu đang dùng ROM khác (mất dữ liệu)

- Wipe cache, dalvik cache -> Flash rom -> Flash current recovery trong Advance (dành cho máy phân vùng A/B) -> Format data -> Reboot recovery và Format data lại lần nữa (dành cho máy phân vùng A/B) -> Reboot system.

Ghi chú:

- Bỏ qua lỗi mount nếu có.

- Nếu vẫn không boot được, bạn hãy Miflash về ROM gốc China và thử lại.

2. Cài đặt qua Fastboot:

- Đưa máy về chế độ fastboot -> Cài driver cho PC 
(cách nhanh nhất là cài Misuite) -> Giải nén rom .zip trong PC -> Chạy file "MiuiTN_Install_Fastboot.bat" (Không chạy quyền Admin) -> Gõ "y" nếu giữ dữ liệu, gõ "n" nếu Format data -> Nhấn Enter và chờ báo thành công đồng thời điện thoại khởi động lại.

Lưu ý: Vào recovery để format data và khởi động lại hoặc chạy lại rom qua fastboot 1 lần nữa nếu không boot được.
