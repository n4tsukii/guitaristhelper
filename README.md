# GuitaristHelper

Website hỗ trợ người chơi đàn guitar, được phát triển như một phần của đồ án giữa kỳ môn **Website Nâng Cao**. Ứng dụng cung cấp các công cụ hữu ích để hỗ trợ người học guitar từ cơ bản đến nâng cao.

## Tổng Quan Dự Án

**GuitaristHelper** là một website được xây dựng bằng Laravel, nhằm giúp người chơi guitar cải thiện kỹ năng thông qua các công cụ trực quan và dễ sử dụng. Dự án tập trung vào việc cung cấp trải nghiệm học tập hiệu quả và thân thiện với người dùng.

### Các Tính Năng Chính
1. **Tìm/Xem Hợp Âm**:
   - Tìm kiếm và xem các hợp âm guitar với sơ đồ bấm dây chi tiết.
   - Hiển thị hợp âm cho nhiều loại khác nhau (ví dụ: trưởng, thứ, 7).
2. **Xem Scale**:
   - Khám phá các scale guitar (ví dụ: trưởng, thứ, pentatonic) với hình ảnh phím đàn.
   - Lọc scale theo khóa hoặc loại để dễ dàng học tập.
3. **Metronome**:
   - Công cụ metronome trên trình duyệt để hỗ trợ luyện tập nhịp điệu.
   - Điều chỉnh tốc độ (BPM) và tùy chọn âm thanh.

## Công Nghệ Sử Dụng
- **Backend**: Laravel (framework PHP)
- **Frontend**: Blade templates, Bootstrap/Tailwind CSS, JavaScript
- **Cơ Sở Dữ Liệu**: MySQL (hoặc SQLite cho môi trường phát triển)
- **Thư Viện**:
  - Guitar.js (hiển thị hợp âm và scale)
  - Tone.js (âm thanh cho metronome)
- **Công Cụ**: Composer, NPM, Laravel Artisan