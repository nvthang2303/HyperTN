## Phiên bản 2.6:

- Hỗ trợ HyperOS 2.

- Chỉ hỗ trợ cài đặt qua Fastboot. Cần đăng kí số serial để có quyền flash rom.

- Fix Integrity (2 dòng) cho Ví Google và bank như ABBank, KPlus...

- Fix lỗi Thư viện chiếm dung lượng bộ nhớ cao do tự động tải ảnh gốc.

- Fix lỗi không có ngôn ngữ tiếng Việt trong bản Miui các thiết bị MTK.

- Fix lỗi Trung tâm điều khiển thông báo bị trong suốt bất thường trên Mũi.

- Thêm Circle Search (Cập nhật app Google, xoá dữ liệu nếu không dùng được). Cách dùng: chọn nút Circle Search trong Trung tâm điều khiển khi muốn dùng. Với HyperOS2 thì thêm tùy chọn nhấn giữ thanh điều hướng để dùng (Cần chọn Ứng dụng Trợ lí kĩ thuật số mặc định là Google).

- Thêm tùy chọn bật eSIM cho các thiết bị có hỗ trợ.

- Thêm tùy chọn 120Hz cho các máy có 144Hz.

- Tắt hạn chế FPS, độ sáng khi nhiệt cao.

- Cập nhật các ứng dụng mod mới như Bảo mật (HyperOS2), App Vault, Trình khởi chạy, Chủ đề.

## Phiên bản 2.5:

- Phiên bản 2.5 sẽ có tình trạng dữ liệu là mã hoá. (Vì vậy có thể update từ HyperTN 2.4, đối với các phiên bản khác cần format data).

- Pass Strong Integrity (3 dòng).

- Fix VieID báo lỗi Thiết bị Không an toàn (chỉ Android 14), xoá dữ liệu app nếu update từ V2.4.

- Thêm 1 bản chỉ thêm ngôn ngữ Việt cho rom mượt hơn. Nên sử dụng bản này nếu bạn sử dụng ngôn ngữ Việt, Anh, Trung.

- Cập nhập bộ spoof mới, unlock fps, đồ hoạ cho nhiều game hơn.

- Thêm tùy chọn bật Tối đa FPS và tránh tụt FPS trong cài đặt Bảo mật.

- Thêm tùy chọn Tần số làm mới 1 Hz, chọn nó nếu muốn tất cả các ứng dụng có tần số quét ở mức cao nhất.

- Bật tính năng điều chỉnh chế độ tối cho từng ứng dụng.

- Sử dụng Thư viện (fix đồng bộ tự động lấy ảnh từ Google về), Thời tiết Global để tránh còn tiếng Trung cũng như bản đồ có đường lưỡi bò.

- Fix lỗi hiển thị thông báo toàn màn hình, lỗi thông báo cuộc gọi Whatapps.

- Cập nhập strings ngôn ngữ mới từ EU, fix lỗi không chuyển ngôn ngữ ở một số ứng dụng.

- Sử dụng font Roboto trong bản Multilingual để fix lỗi font ở một số ngôn ngữ.

- Fix lỗi crash Màn hình chính khi khởi động lại và thỉnh thoảng khi đang dùng.

- Fix lỗi reset cài đặt màn hình khoá khi sử dụng Chủ đề bên thứ 3.

- Unlock tính năng chụp ảnh màn hình cho mọi ứng dụng.

- Fix script flash rom, hạn chế việc flash lỗi khi chuyển nền rom, đồng thời không cần flash lại twrp khi flash bằng twrp.

- Giữ lại việc báo tình trạng đã Unlock để tránh hiểu lầm.

- Sử dụng Bảo mật mod mới, có hiển thị sức khoẻ pin thực tế.

## Phiên bản 2.4:

- Sử dụng code build mới phù hợp với các máy đời mới.

- Phiên bản đầu cho HyperOS.

- Fix lỗi chứng nhận Google Play (Play Integrity) cho tất cả các thiết bị.

- Bản HyperTN là mã hoá (cần format cho lần cài đầu). Bản MIUITN vẫn là đã giải mã (Có thể update từ bản MIUITN cũ)

- Fix thông báo cho HyperOS.

- Sử dụng nguồn strings ngôn ngữ mới, dịch ứng dụng nhiều hơn.

- Có thể cài các APK mod trực tiếp. (Cần sign).

- Cập nhập mới các app mod.

## Phiên bản 2.3:

- Fix lỗi chứng nhận Google Play Protect (Play Integrity) để dùng được Google Pay, cũng như một số ngân hàng khác. Một số thiết bị không pass nhưng vẫn sẽ dùng được Google Play.

- Fix lỗi crash trong tùy chọn chế độ đọc sách, Lịch, Bảo mật...

- Fix hao pin trong chế độ chờ.

- Việt hóa thêm một vài ứng dụng.

- Xóa tùy chỉnh FPS thông minh trong Tiết kiệm pin (Tránh giảm FPS trong game và một số app như Tik Tok, Youtube...)

- Thêm sẵn Trình chỉnh sửa ảnh để fix lỗi một vài thiết bị không tự tải được.

- Dùng Chủ đề mod mới có thêm tùy chọn thay đổi vùng từ @kakashi.

- Dùng trình cài đặt Google mod từ @kakashi.

- Update phiên bản mới cho Bảo mật, Thư viện, Realme Search, Thời tiết, Joyose, Ví thẻ Mi.

## Phiên bản 2.2:

- Fix lỗi chứng nhận Google Play Protect (Play Integrity) do Google vừa thay đổi API.

- Giữ lại Ví thẻ thông minh của Xiaomi. (Để chép thẻ thang máy, thẻ giữ xe...).

- Fix lỗi mất trình cài đặt gói trên một số thiết bị.

- Thêm tùy chọn Bật max hiệu suất (Tạm thời mình đặt nó ở cài đặt Màn hình chính) . Khi bật nó sẽ tăng max hiệu suất, FPS trong game và các ứng dụng video như TikTok, Youtube. Nên tắt tùy chọn này khi không dùng tới để tiết kiệm pin.

- Xóa một số dịch vụ Google không cần thiết để tiết kiệm pin.

- Fix lỗi không hiển thị tùy chọn của một số ngôn ngữ.

- Fix lỗi báo Trình trạng Unlock sai.

- Fix lỗi thanh trượt khi hẹn giờ DND.

- Thêm overlay việt hoá cho Taplus, Không gian thứ 2, Getapps  và string mới cho một vài ứng dụng khác.

- App MiuiHome mod từ @HolyBearHome (Tính năng ở đây) và đã được sửa đổi để fix một số lỗi như thỉnh thoảng lag, crash khi chọn một số tùy chọn, khám phá Google trong màn hình -1.

- App Vault mod từ @kakashi với một vài tính năng mới rất hay (Tính năng ở đây) (chuyển được dùng Tiện ích EU để không có Tiện ích tiếng Tàu, Nhóm Tiện ích trong màn hình -1...). 

- App Bảo mật HyperOS mod từ @SatanMods (Tính năng ở đây), có lại tính năng Thời gian xem màn hình cho mọi máy.

- App Thư viện HyperOS mod từ @SatanMods (Tính năng ở đây) cho Android 13, có mod thêm xóa Dịch vụ bản đồ có đường lưỡi bò. (Cho phép bật đồng bộ từ Google Photo).

- Sử dụng một số ứng dụng từ HyperOS như Trinhf cài đặt gói, Thời Tiết, Ghi chú, Trình dọn dẹp, Ghi màn hình.

## Phiên bản 2.1:

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

## Phiên bản 2.0:

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

## Phiên bản 1.9:

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

## Phiên bản 1.8:

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

## Phiên bản 1.7:

- Sử dụng phông chữ Helvetica sửa đổi bởi @ Hiends29.

- Sửa lỗi bootloop cho Android 10.

- Sửa lỗi Vowifi, Cuộc gọi video.

- Sử dụng mod Launcher của Sipollo + IOS mới nhất của Kashi.

- Sử dụng mod bảo mật của Kashi (Thêm thanh bên, Hộp công cụ video, Game Turbo, FPS động, Tác vụ tự động, Xóa bộ hẹn giờ cảnh báo bảo mật, Sạc tối ưu, Tăng tốc độ sạc)

- Quay lại bản mod ứng dụng Chủ đề Trung Quốc để có đầy đủ chức năng.

- Tắt một số chức năng trong cài đặt hiển thị, wifi để tối ưu hóa pin.

- Cải thiện bàn phím cho Gboard. (Dành cho Android 10, 12).

- Xóa mod Google Photo Unlimited vì nó không hoạt động.

## Phiên bản 1.6:

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

## Phiên bản 1.5:

- Sử dụng App Vault 5.x của EUXiaomi cho tất cả các phiên bản rom. (Như vậy sẽ có widget mới của miui 13 cho cả miui 12 và 12.5).

- Sửa lỗi Powerkeeper không hoạt động trên android 10, 11. (Sửa lỗi thông báo ứng dụng)

- Thêm tùy chọn 90Hz cho các thiết bị có tần số quét >= 120Hz.

- Nâng bàn phím lên cho Gboard.

- Có thể xóa Getapps bằng cách thông thường. (Nếu sử dụng Getapps vui lòng không cập nhật Chủ đề, Âm nhạc và Máy tính).

- Tắt tự động khôi phục các ứng dụng Trung Quốc sau khi định dạng dữ liệu.


