### MIUITN
- Sửa đổi bởi Thang Nguyen.
- Dựa trên ROM China gốc.
### Download rom:
- Tìm "Codename" thiết bị của bạn (có thể sử dụng tìm kiếm Google hoặc [Tại đây](https://xiaomiui.net/all-xiaomi-codenames-5137))
- Vào thư mục "MIUITN -> Codename" và tải rom về.

### Hướng dẫn cài rom: 
1. Cài qua Recovery:

a. Flash đè: Nếu đang dùng MiuiTN/HyperTN  (không mất dữ liệu)
- Wipe cache, dalvik cache -> Flash rom -> Flash current recovery trong Advance  (dành cho máy phân vùng VAB) -> Reboot system.

b. Flash sạch: Nếu đang dùng ROM khác (mất dữ liệu)
- Wipe cache, dalvik cache -> Flash rom -> Flash current recovery trong Advance (dành cho máy phân vùng VAB) -> Format data -> Reboot recovery và Format data lại lần nữa (dành cho máy phân vùng VAB) -> Reboot system.

Ghi chú:
- Bỏ qua lỗi mount nếu có.
- Nếu vẫn không boot được, bạn hãy Miflash về ROM gốc China và thử lại.

2. Cài đặt qua Fastboot:

- Đưa máy về chế độ fastboot -> Cài driver cho PC 
(cách nhanh nhất là cài Misuite) -> Giải nén rom .zip trong PC -> Chạy file "MiuiTN_Install_Fastboot.bat" -> Gõ "y" nếu giữ dữ liệu, gõ "n" nếu Format data -> Enter và chờ báo thành công.

Lưu ý: Vào recovery để format data và khởi động lại hoặc chạy lại rom qua fastboot 1 lần nữa nếu không boot được.

### Hỗ trợ:
- Miui 12, 12.5, 13, 14 - Android 10, 11, 12, 13.
- Tất cả các thiết bị có ROM China.
### Link Telegram: 
- [Channel](http://t.me/MiuiTNChannel)
- [Group support](http://t.me/MiuiTNGroup)
### Tính năng: (So với Rom China)
- Mặc định: Không root, đã RW (chỉ cho phân vùng dùng EXT4), không mã hoá.
- Pass Play Integrity: Fix lỗi chứng nhận Google Play Protect (Play Integrity) để dùng được Google Pay, cũng như một số ngân hàng khác. Một số thiết bị không pass nhưng vẫn sẽ dùng được Google Play. Khi Google fix vui lòng cài đặt APK mới nhất tại thư mục FixIntegrity và khởi động lại. (Áp dụng con Ver 2.3 trở lên).
- Chuyển rom A12+ sang dạng hybrid, tất cả các thiết bị flash TWRP hoặc fastboot đều được, thời gian flash twrp sẽ rất nhanh.
- Đa ngôn ngữ như rom EU.
- Gỡ bỏ các dịch vụ và ứng dụng không cần thiết.
- Sử dụng font Helvetica được chỉnh sửa bởi @ Hiends29.
- Sửa lỗi thông báo ứng dụng.
- Sửa lỗi OK Google trong Trợ lí Google.
- Sửa lỗi âm thanh thông báo, hiển thị ở màn hình khóa cho tất cả các ứng dụng.
- Vô hiệu hóa xác thực chữ ký, bạn có thể cài đặt APK mod (đã sign) theo cách thông thường, không cần Core Patch.. (Camera, Theme, MiuiHome mod...)
- Thêm tìm kiếm Realme thay thế tìm kiếm Xiaomi, chọn Trình tìm kiếm là Xiaomi trong cài đặt màn hình chính, vuốt lên để có.
- Mod bo tròn giao diện bảng tùy chọn cho một sốapp.
- Có thể tắt các ứng dụng hệ thống.
- Mở khóa FPS, tính năng cho một số game. (Danh sách)
- Dung lượng không giới hạn Google Photo.
- Thêm bàn phím nâng cao cho Gboard, Laban key.
- Sửa lỗi trễ khi bấm Nguồn và kích hoạt khởi chạy Google Assistant bằng nút Nguồn. (Dành cho android 11+).
- Bật tính năng Phối màu nâng cao trong cài đặt hiển thị.
- Kích hoạt tùy chọn 90hz cho Tốc độ làm mới, tốc độ làm mới thông minh.
- Bật làm sạch loa trong cài đặt.
- Có sẵn app Google Play (Dịch vụ Google trong cài đặt)
- Tắt tự động khôi phục các app China sau khi format dữ liệu.
- Sửa tùy chọn Force Darkmode trong Miui 13, 14.
- Sửa lỗi Dòng thời gian trong Google Maps.
- Thêm ứng dụng Music, Video, Caculator từ @XiaomiEU.
- Thêm GoogleCalendarSync, Android Auto.
- App MiuiHome mod từ @HolyBearHome (Tính năng ở đây) vđã được sửa đổi để fix một số lỗi như thỉnh thoảng lag, crash khi chọn một số tùy chọn, khám phá Google trong màn hình -1.
- App Vault mod từ @kakashi với một vài tính năng mới rất hay (Tính năng ở đây) (chuyển được dùng Tiện ích EU để không có Tiện ích tiếng Tàu, Nhóm Tiện ích trong màn hình -1...). 
- App Bảo mật mod từ @SatanMods (Tính năng ở đây), có lại tính năng Thời gian xem màn hình cho mọi máy.
- App Thư viện mod từ @SatanMods (Tính năng ở đây) cho Android 13, có mod thêm xóa Dịch vụ bản đồ. (Cho phép bật đồng bộ từ Google Photo).
- App Ghi màn hình mod từ @Hemal_bear (Tính năng ở đây) cho phép ghi màn hình ở nhiều mức fps và âm thanh từ nhiều nguồn.
- App Chủ đề mod từ @kakashi (Tính năng ở đây)
- App SystemUIPlugin từ @PlugInUpdates (Tính năng ở đây), có phím nguồn mở rộng và bảng âm lượng dạng Mipad.
- App Joyose mod từ Satan (Tính năng ở đây) unlock Gpu Tuner cho mọi thiết bị.
- MiuiPackageInstaller mod có thể cài đặt ứng dụng hệ thống.
- Sửa camera Munch, Apollo.
### Donate:
- Zalopay/Momo/Viettelpay: 0356144996
- Techcombank: 14025025164011
- [Paypal](http://paypal.me/nvthang2303)
### Credits:
- Hais team (For tool build).
- 4PDA (For some mods).
- @Hiends29 (For font).
- @XiaomiEU (For string language, some mods and apps). 
- @Hemal_bear (For MiuiHome, App Vault, Themes, Gallery, Screen Recorder)
- @kakashi (For MiuiHome, Themes)
- @PlugInUpdates (For MiuiSystemUIPlugin).
### Changelog:

[x] Phiên bản 2.2:
- Giữ lại Ví thẻ thông minh của Xiaomi. (Để chép thẻ thang máy, thẻ giữ xe...).
- Fix lỗi mất trình cài đặt gói trên một số thiết bị.
- Thêm tùy chọn Bật max hiệu suất (Tạm thời mình đặt nó ở cài đặt Màn hình chính) . Khi bật nó sẽ tăng max hiệu suất, FPS trong game và các ứng dụng video như TikTok, Youtube. Nên tắt tùy chọn này khi không dùng tới để tiết kiệm pin.
- Xóa một số dịch vụ Google không cần thiết để tiết kiệm pin.
- Fix lỗi không hiển thị tùy chọn của một số ngôn ngữ.
- Fix lỗi báo Trình trạng Unlock sai.
- Dịch TapPlus sang tiếng Việt.
- App MiuiHome mod từ @HolyBearHome (Tính năng ở đây) và đã được sửa đổi để fix một số lỗi như thỉnh thoảng lag, crash khi chọn một số tùy chọn, khám phá Google trong màn hình -1.
- App Vault mod từ @kakashi với một vài tính năng mới rất hay (Tính năng ở đây) (chuyển được dùng Tiện ích EU để không có Tiện ích tiếng Tàu, Nhóm Tiện ích trong màn hình -1...). 
- App Bảo mật HyperOS mod từ @SatanMods (Tính năng ở đây), có lại tính năng Thời gian xem màn hình cho mọi máy.
- App Thư viện HyperOS mod từ @SatanMods (Tính năng ở đây) cho Android 13, có mod thêm xóa Dịch vụ bản đồ. (Cho phép bật đồng bộ từ Google Photo).
- Sử dụng một số ứng dụng từ HyperOS như Thời Tiết, Ghi chú, Trình dọn dẹp, Ghi màn hình.

[x] Phiên bản 2.1:
- Pass SafetyNet mặc định -> Tất cả app ngân hàng sẽ hoạt động ok (Nếu bạn root chỉ cần ẩn 2 mục com.google.android.gms và com.google.android.gms.unstable của Dịch vụ Google Play thì sẽ pass SafetyNet, không cần sử dụng module fix SafetyNet).
- Fix lỗi phải dùng file magisk for erofs để root trên các thiết bị erofs. Giờ đây các bạn có thể dùng bất cứ file magisk nào để root.
- Bỏ Trình cài đặt Pixel ban đầu để tránh lỗi không dùng được wifi để cài đặt.
- Fix lỗi bị reset theme ở một số thiết bị.
- Update app Music để fix lỗi không chạy nền.
- Việt hoá thêm một số ứng dụng.
- Unlock tính năng, FPS thêm một số game (List game ở đây).
- Dùng app Bảo mật, Trình cài đặt gói tốt hơn.
- Bỏ một số tính năng không cần thiết để pin tốt hơn.
- Fix lỗi không boot ở một vài thiết bị chip MTK.

[x] Phiên bản 2.0:
- Thêm Đa ngôn ngữ như EU Rom.
- Cập nhập font Helvetica mới đẹp hơn (Thanks @hiends)
- Sửa lỗi  check bảo mật của một app ngân hàng (xóa prop fake trạng thái unlock -> Không pass safetynet nhưng hầu hết các app ngân hàng sẽ hoạt động tốt). Nếu root thì chỉ cần Hide app ngân hàng trong Magisk Delta là nó sẽ hoạt động bình thường.
- Sửa lỗi OK Google trong Trợ lí Google (Nhớ update app Google trong CHPlay).
- Tắt tính năng tắt tạm thời Bluetooth trên thanh  trạng thái.
- Đổi Cài đặt ban đầu sang Pixel -> Không cần bật Dịch vụ Google để có Google Play nữa.
- Sửa lỗi lỗi màu chữ trùng với màu nền khung tùy chọn một số app. (Thanks @hiends)
- MiuiHome, App vault mod mới (Fix lỗi tự reset widget , màn hình khóa sau một thời gian)
- Sử dụng App Chủ đề mod vùng Global của @Kashi
- Xóa Dịch vụ bản đồ Baidu có đường lưỡi bò trong Thư viện
- App bảo mật mới từ @Hemal.
- Trình ghi màn hình mod từ @Hemal thêm tùy chọn FPS cao.
- Xóa tùy chỉnh FPS thông minh trong Tiết kiệm pin (Tránh giảm FPS trong game và một số app như Tik Tok, Youtube...)
- Sửa lỗi dịch vụ in.
- Thêm Công cụ hình ảnh Al trong cài đặt hiển thị.
- Thêm âm lịch cho màn hình khoá.
- Dùng Trình cài đặt gói của EU.
- Xóa trình Update trong A13.
- Xóa Getapps để tránh cập nhập mất app mod.
- Sửa lỗi Camera cho F4 (munch), Mi 10T (Apollo) (Cần test).
- Sửa lỗi font trong Google Maps ở 1 số thiết bị.

[x] Phiên bản 1.9:
- Hỗ trợ cho các thiết bị erofs.
- Convert rom A12+ sang hybrid, tất cả các máy đều có thể flash ở TWRP hoặc fastboot, thời gian flash ở twrp sẽ rất nhanh.
- Vô hiệu hóa xác thực chữ ký, bạn có thể cài đặt APK mod bằng cách thông thường.
- Sửa thông báo nhiều hơn.
- Sửa lỗi SafetyNet theo mặc định.
- Thêm tìm kiếm Realme thay thế tìm kiếm Xiaomi, vuốt lên để lấy.
- Bo tròn trong một số giao diện ứng dụng.
- Sửa biểu tượng hoàn nguyên về kiểu cũ trong v1.8.
- Sửa lỗi thanh ngang ở bàn phím nâng cao.
- Miuihome mới, App Vault (Thêm biểu tượng siêu, widget miễn phí).
- Giữ Joyose, để tiết kiệm pin.
- Có thể vô hiệu hóa các ứng dụng hệ thống.

[x] Phiên bản 1.8:
- Thay đổi logo MiuiTN.
- Vượt qua mạng lưới an toàn theo mặc định.
- Tiếp tục sửa thông báo ứng dụng.
- Sửa âm thanh thông báo, hiển thị trên màn hình khóa cho tất cả ứng dụng.
- Sử dụng ứng dụng Vault của Miui 14, có widget mới.
- Kích hoạt VoLTE, Vowifi, Cuộc gọi video.
- Sử dụng launcher iOS mod mới (Kết hợp Sipollo và Kashi, dịch sang tiếng Việt)
- Sử dụng mod ứng dụng China Themes với ngôn ngữ toàn cầu và đầy đủ chức năng.
- Sử dụng mod ứng dụng Security cuối cùng của Ram mod và dịch sang tiếng Việt.
- Sử dụng MiuiSystemUIPlugin cuối cùng của @PlugInUpdates cho kiểu MIUI Pad, - đồng thời bật Tùy chọn khởi động lại mở rộng.
- Bật tốc độ làm mới thông minh trong cài đặt hiển thị.

[x] Phiên bản 1.7:

- Sử dụng phông chữ Helvetica sửa đổi bởi @ Hiends29.
- Sửa lỗi bootloop cho Android 10.
- Sửa lỗi Vowifi, Cuộc gọi video.
- Sử dụng mod Launcher của Sipollo + IOS mới nhất của Kashi.
- Sử dụng mod bảo mật của Kashi (Thêm thanh bên, Hộp công cụ video, Game Turbo, FPS động, Tác vụ tự động, Xóa bộ hẹn giờ cảnh báo bảo mật, Sạc tối ưu, Tăng tốc độ sạc)
- Quay lại bản mod ứng dụng Chủ đề Trung Quốc để có đầy đủ chức năng.
- Tắt một số chức năng trong cài đặt hiển thị, wifi để tối ưu hóa pin.
- Cải thiện bàn phím cho Gboard. (Dành cho Android 10, 12).
- Xóa mod Google Photo Unlimited vì nó không hoạt động.

[x] Phiên bản 1.6:

- Thay đổi phông chữ thành phông chữ HarmonyOS.
- Thêm Mở rộng PowerMenu, sửa lỗi PowerMenu bị trễ và bật khởi chạy Google Assistant bằng nút Nguồn.
- Thêm Cài đặt Google. (Vui lòng quản lý ứng dụng trong cài đặt-> hiển thị tất cả ứng dụng-> tìm kiếm Cài đặt Android -> Kích hoạt nó)
- Sử dụng Themes mod của @Kashi (Có thể nhập chủ đề, ngôn ngữ chung)..
- Thêm Google Feed + Sửa lỗi Ẩn ứng dụng cho trình khởi chạy.
- Thêm MiuiPackageInstaller Global.
- Lưu trữ ảnh Google không giới hạn.
- Sử dụng Security mod v4 của Ram mod (Thêm Sidebar, Game Turbo, Dynamic FPS, Tác vụ tự động, Xóa bộ hẹn giờ cảnh báo bảo mật)
- Kích hoạt nhiều chức năng trong cài đặt hiển thị (Bảng màu nâng cao, Chống nhấp nháy, Công cụ hình ảnh AI, Tốc độ làm mới thông minh...). Một số tính năng sẽ bị thiếu trong Android 10, 11.
- Kích hoạt tính năng sạc tối ưu hóa, tăng tốc độ sạc.
- Kích hoạt tính năng tiết kiệm pin cực độ.
- Thêm Dual Wifi cho các thiết bị không được hỗ trợ.
- Kích hoạt tính năng tải trước AI trong MiuiLab.
- Sửa camera cho Munch.

[x] Phiên bản 1.5:

- Sử dụng App Vault 5.x của EUXiaomi cho tất cả các phiên bản rom. (Như vậy sẽ có widget mới của miui 13 cho cả miui 12 và 12.5).
- Sửa lỗi Powerkeeper không hoạt động trên android 10, 11. (Sửa lỗi thông báo ứng dụng)
- Thêm tùy chọn 90Hz cho các thiết bị có tần số quét >= 120Hz.
- Nâng bàn phím lên cho Gboard.
- Có thể xóa Getapps bằng cách thông thường. (Nếu sử dụng Getapps vui lòng không cập nhật Chủ đề, Âm nhạc và Máy tính).
- Tắt tự động khôi phục các ứng dụng Trung Quốc sau khi định dạng dữ liệu.