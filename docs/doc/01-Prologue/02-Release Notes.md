### Phiên bản hỗ trợ

| Cms Version |  PHP Support  |  Release   |     Support     |
|:-----------:|:-------------:|:----------:|:---------------:|
|      7      | 8.2.x - 8.3.x | 10/08/2024 |   Đang hỗ trợ   |
|      6      | 8.0.x - 8.1.x | 25/07/2022 | Cập nhật vá lỗi |
|      5      | 8.0.x - 8.1.x | 10/12/2021 | `Dừng hỗ trợ `  |
|      4      | 7.0.x - 7.3.x | 29/09/2020 |  `Dừng hỗ trợ`  |
|      3      |      5.6      | 18/09/2019 |  `Dừng hỗ trợ`  |

### version 7.0.4 - public beta - 20.08.2024

<span class="badge text-bg-red">Fix</span> lỗi lưu post không có kết nối với danh mục <span class="badge text-bg-yellow">Trang</span>

<span class="badge text-bg-red">Fix</span> lỗi url chuyển hướng trong auth nếu user đã đăng nhập

<span class="badge text-bg-green">Add</span> Thêm hooks user_form_profile

<span class="badge text-bg-blue">Change</span> Optimize code

### version 7.0.3 - public beta - 18.08.2024

<span class="badge text-bg-red">Fix</span> lỗi logout khi redirect lưu cache trình duyệt

<span class="badge text-bg-red">Fix</span> lỗi review image <span class="badge text-bg-yellow">Châu Thạch</span>

<span class="badge text-bg-blue">Change</span> Đổi service lấy danh sách fonts google

<span class="badge text-bg-green">Add</span> Thêm hooks admin_pre_user_update, admin_pre_user_update_meta, admin_user_update_success

### version 7.0.2 - public beta - 15.08.2024

<span class="badge text-bg-red">Fix</span> lỗi route khi bật đa ngôn ngữ  <span class="badge text-bg-yellow">Dương</span>

<span class="badge text-bg-red">Fix</span> <span class="badge text-bg-pink">Location</span> lỗi thư viện Location lấy sai tên full_name  <span class="badge text-bg-yellow">Trang</span>

<span class="badge text-bg-red">Fix</span> <span class="badge text-bg-pink">Widget</span> lỗi widget kéo thả không cập nhật thứ tự  <span class="badge text-bg-yellow">Dương</span>

<span class="badge text-bg-red">Fix</span> <span class="badge text-bg-pink">Theme menu</span> lỗi khi edit menu không hiện data đã lưu <span class="badge text-bg-yellow">Dương</span>

### version 7.0.1 - public beta - 13.08.2024

<span class="badge text-bg-red">Fix</span> lỗi không vào được trang update phiên bản bằng button upload  

<span class="badge text-bg-red">Fix</span> <span class="badge text-bg-pink">Theme menu</span> lỗi thêm menu không xóa cache củ <span class="badge text-bg-yellow">Dương</span>

<span class="badge text-bg-blue">Change</span> <span class="badge text-bg-pink">Cache</span> Đổi class CacheHandler thành class SkillDo\Cache  

<span class="badge text-bg-blue">Change</span> <span class="badge text-bg-pink">Mail</span> Đổi class Mail thành class SkillDo\Mail

<span class="badge text-bg-green">Add</span> Thêm class SkillDo\Location xử lý thông tin địa chỉ

<span class="badge text-bg-green">Add</span> Thêm class SkillDo\ServiceLocation lấy thông tin địa chỉ từ service

