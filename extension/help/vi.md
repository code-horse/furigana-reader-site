---
layout: bare
title: Furigana Reader — Hướng dẫn sử dụng
lang: vi
---

# Furigana Reader — Hướng dẫn sử dụng

> Phiên bản: v1.4.1

## Giới thiệu

Furigana Reader là tiện ích trình duyệt dành cho người học tiếng Nhật. Chạy bằng bộ phân tích hình thái WASM (Lindera + IPAdic) có dự phòng JavaScript, tiện ích thêm furigana (chú đọc) chính xác cho chữ kanji trên trang web và trong PDF. Nó còn có từ điển tiếng Nhật tích hợp, đọc văn bản và dịch — giúp bạn học phát âm tiếng Nhật dễ hơn.

---

## Tính năng chính

- **Chế độ furigana toàn trang** — Một cú nhấp để thêm furigana cho mọi kanji trên trang
- **Từ điển khi di chuột** — Di qua ký tự đã gắn chú để xem nghĩa JMdict (hơn 180 nghìn mục), cách đọc, huy hiệu cấp JLPT (N5–N1) và nút phát âm; chọn chế độ Từ điển, Chỉ đọc hoặc Tắt
- **Trình đọc PDF** — Trình đọc PDF tích hợp với furigana, từ điển, đọc và dịch; kéo thả, mở bằng URL và phát hiện PDF tự động với chuyển hướng thông minh
- **Ba kiểu hiển thị đọc** — Hiragana, katakana và romaji
- **Tách okurigana** — Tách chính xác okurigana (送り仮名) khỏi phần kanji
- **Hỗ trợ jukujikun** — Đọc đúng cho hợp chữ nhiều kanji có cách đọc đặc biệt (熟字訓)
- **Đọc văn bản (TTS)** — Nhấn nút loa để nghe phát âm tiếng Nhật
- **Đọc vùng chọn và karaoke** — Chọn bất kỳ văn bản tiếng Nhật nào; thanh công cụ nhỏ xuất hiện với nút đọc và dịch; khi đọc, từng từ hoặc ký tự được làm nổi theo thời gian thực (hiệu ứng karaoke) đồng bộ với âm thanh
- **Dịch vùng chọn** — Chọn bất kỳ văn bản nào, nhấn nút dịch trên thanh công cụ để dịch ngay qua Bing Translate hoặc Google Translate, hiển thị trong bong bóng nội tuyến
- **Phím tắt** — Truy cập nhanh các tính năng cốt lõi qua phím tắt tùy chỉnh
- **Giao diện đa ngôn ngữ** — Hỗ trợ 38 ngôn ngữ giao diện

---

## Cách sử dụng

### Bước 1: Cài tiện ích

Cài **Furigana Reader** từ [Chrome Web Store](https://chromewebstore.google.com/), hoặc tải cục bộ ở chế độ nhà phát triển.

### Bước 2: Mở trang web bất kỳ

Truy cập trang có nội dung tiếng Nhật.

### Bước 3: Bật furigana

Nhấn biểu tượng tiện ích trên thanh công cụ. Bật «Bật furigana», sau đó bật «Furigana toàn trang» để chú thích mọi kanji. Bạn cũng có thể dùng nút nổi góc dưới bên phải.

### Bước 4: Xem furigana

Di chuột qua ký tự để xem chú thích furigana với cách đọc và nghĩa từ điển. Nhấn biểu tượng loa để nghe phát âm.

### Bước 5: Đọc và dịch văn bản đã chọn

Chọn văn bản tiếng Nhật bằng chuột. Gần vùng chọn xuất hiện thanh công cụ nhỏ với hai nút:
- **🔊 Đọc** — Đọc to văn bản đã chọn với làm nổi kiểu karaoke
- **🌐 Dịch** — Hiển thị bong bóng dịch nội tuyến phía dưới thanh công cụ

Bạn cũng có thể chuột phải và chọn «Furigana Reader > Đọc to vùng chọn» hoặc «Furigana Reader > Dịch vùng chọn».

> **Mẹo:** Nhấn biểu tượng tiện ích để mở bảng cài đặt và chỉnh kiểu furigana, chế độ khi di chuột, tốc độ đọc, công cụ dịch, v.v.

---

## Từ điển khi di chuột

Tiện ích có từ điển tiếng Nhật tích hợp dựa trên JMdict (hơn 180.000 mục). Trong cài đặt bạn có thể chọn nhiều chế độ khi di chuột:

| Chế độ | Hành vi |
|--------|---------|
| **Từ điển** | Di chuột hiển thị cách đọc + nghĩa + cấp JLPT + nút phát âm |
| **Chỉ đọc** | Di chuột hiển thị cách đọc + nút phát âm (không nghĩa) |
| **Tắt** | Không có hiệu ứng khi di chuột |

Ở chế độ **Từ điển**, chú thích hiển thị:
- Từ và cách đọc (furigana)
- Nút phát âm (nhấn để nghe)
- Nghĩa tiếng Nhật từ JMdict
- Huy hiệu JLPT (N5–N1) khi có

> **Mẹo:** Dữ liệu từ điển tải theo nhu cầu khi bật chế độ Từ điển và được gỡ khi chuyển sang chế độ khác để tiết kiệm bộ nhớ.

---

## Trình đọc PDF

Furigana Reader có trình đọc PDF tích hợp: furigana, từ điển, đọc và dịch — giống trên trang web, nay áp dụng cho PDF.

### Mở PDF

**Cách 1: Từ popup**  
Nhấn biểu tượng tiện ích, rồi «Mở trình đọc PDF». Kéo thả file PDF hoặc nhấn «Chọn tệp» để mở PDF cục bộ. Bạn cũng có thể dán URL PDF.

**Cách 2: Menu ngữ cảnh**  
Chuột phải liên kết `.pdf` trên trang và chọn «Mở PDF bằng Furigana Reader».

**Cách 3: Phát hiện tự động**  
Khi bật «Phát hiện PDF thông minh» trong cài đặt, tiện ích tự chuyển hướng URL `.pdf` sang trình đọc tích hợp. Khi PDF được phát hiện nhưng không chuyển hướng (ví dụ trình xem của Chrome), bạn sẽ thấy thông báo và lời nhắc mở bằng Furigana Reader.

### Tính năng trình đọc PDF

- **Chú thích furigana** — Mọi tính năng furigana hoạt động trên văn bản PDF, gồm toàn trang và chú thích khi di chuột
- **Năm chế độ furigana** — Hiragana, katakana, romaji, chỉ khi di chuột và Tắt
- **Từ điển bằng nhấp** — Nhấp từ để xem nghĩa JMdict (trên PDF dùng nhấp thay vì di chuột để đọc tập trung hơn)
- **Thanh công cụ vùng chọn** — Chọn văn bản để đọc, dịch hoặc sao chép
- **Thanh bên** — Mục lục và hình thu nhỏ trang
- **Tìm kiếm** — Tìm toàn văn trong PDF
- **Chủ đề** — Tối, sáng và sepia
- **Thu phóng** — Nhiều mức, gồm furigana thích ứng theo mức zoom
- **Phím tắt** — Phím mũi tên điều hướng, +/- thu phóng, Ctrl/Cmd+F tìm kiếm

---

## Đọc vùng chọn và karaoke

Tính năng đọc vùng chọn cho phép chọn bất kỳ văn bản tiếng Nhật nào và đọc to một cú nhấp — phù hợp luyện phát âm câu và đọc.

**Cách 1: Thanh công cụ vùng chọn**  
Chọn văn bản tiếng Nhật bằng chuột. Gần vùng chọn xuất hiện thanh nhỏ với nút 🔊 đọc và 🌐 dịch. Nhấn đọc. Khi đọc, từng từ hoặc ký tự được làm nổi theo thời gian thực (karaoke) để bạn theo dõi.

**Cách 2: Menu chuột phải**  
Sau khi chọn văn bản tiếng Nhật, chuột phải và chọn «Furigana Reader > Đọc to vùng chọn».

**Cách 3: Phím tắt**  
Chọn văn bản và nhấn `Alt+Shift+S` (Mac: `Ctrl+Shift+S`).

> **Mẹo:** Hiệu ứng karaoke hoạt động tốt nhất khi trình duyệt hỗ trợ sự kiện ranh giới từ TTS. Nếu không, tiện ích dùng phương án dựa thời gian để làm nổi mượt.

---

## Dịch

Chọn bất kỳ văn bản nào trên trang và dùng tính năng dịch để có bản dịch tức thì.

**Cách 1: Thanh công cụ vùng chọn**  
Chọn văn bản, nhấn nút 🌐 dịch trên thanh công cụ. Bong bóng dịch hiện bên dưới với kết quả và nút sao chép.

**Cách 2: Menu chuột phải**  
Chọn văn bản, chuột phải và chọn «Furigana Reader > Dịch vùng chọn».

**Cách 3: Phím tắt**  
Chọn văn bản và nhấn `Alt+Shift+T` (Mac: `Ctrl+Shift+T`).

**Công cụ dịch:**
- **Bing Translate** (mặc định) — Microsoft Translator
- **Google Translate** — Google

Cả hai hỗ trợ **108 ngôn ngữ đích**.

Bạn có thể đổi công cụ dịch và ngôn ngữ đích trong cài đặt tiện ích. Ngôn ngữ đích tự nhận từ ngôn ngữ trình duyệt.

> **Mẹo:** Nhấn ra ngoài thanh công cụ hoặc bong bóng để đóng.

---

## Phím tắt

| Phím tắt | Phím tắt Mac | Hành động |
|----------|--------------|-----------|
| `Alt+Shift+F` | `Ctrl+Shift+F` | Bật/tắt chú thích furigana |
| `Alt+Shift+S` | `Ctrl+Shift+S` | Đọc văn bản đã chọn |
| `Alt+Shift+T` | `Ctrl+Shift+T` | Dịch văn bản đã chọn |

> **Mẹo:** Tùy chỉnh phím tắt trong Chrome tại `chrome://extensions/shortcuts`.

---

## Hướng dẫn cài đặt

| Cài đặt | Mô tả |
|---------|-------|
| **Bật furigana** | Công tắc chính bật/tắt chú thích furigana |
| **Furigana toàn trang** | Khi bật, hiển thị furigana cho mọi kanji (có thể ảnh hưởng bố cục trang) |
| **Chế độ khi di chuột** | Chọn: Từ điển (đọc + nghĩa + JLPT + âm thanh), Chỉ đọc (đọc + âm thanh), hoặc Tắt |
| **Kiểu furigana** | Hiragana, katakana hoặc romaji |
| **Tốc độ đọc** | Điều chỉnh tốc độ đọc câu |
| **Công cụ dịch** | Bing Translate hoặc Google Translate |
| **Ngôn ngữ đích** | Ngôn ngữ dịch đích (tự nhận từ trình duyệt) |
| **Phát hiện PDF thông minh** | Khi bật, tự chuyển URL PDF sang trình đọc tích hợp và hiển thị thông báo khi phát hiện PDF |

---

## Câu hỏi thường gặp

**H: Tại sao không hoạt động trên một số trang?**  
Đ: Vì lý do bảo mật, tiện ích không chạy trên trang đặc biệt như `chrome://`, cài đặt trình duyệt hoặc Chrome Web Store.

**H: Furigana không chính xác thì sao?**  
Đ: Một số từ hiếm hoặc cách đọc đặc biệt (熟字訓) có thể sai. Chúng tôi liên tục cải thiện. Vui lòng gửi ví dụ cụ thể.

**H: Không có âm thanh TTS?**  
Đ: Kiểm tra âm lượng hệ thống và gói giọng tiếng Nhật. Hỗ trợ đọc khác nhau theo trình duyệt và hệ điều hành.

**H: Chế độ toàn trang ảnh hưởng bố cục?**  
Đ: Furigana cần thêm không gian, có thể làm lệch bố cục. Nếu khó đọc, tắt toàn trang và dùng chú thích khi di chuột.

**H: Dịch không hoạt động?**  
Đ: Dịch cần internet. Nếu Bing Translate lỗi, thử Google Translate trong cài đặt. Một số mạng có thể chặn dịch vụ dịch.

**H: Làm sao mở PDF bằng Furigana Reader?**  
Đ: Nhấn «Mở trình đọc PDF» trong popup, chuột phải liên kết PDF và chọn «Mở PDF bằng Furigana Reader», hoặc bật «Phát hiện PDF thông minh» để tự chuyển hướng.

**H: Đã bật phát hiện PDF thông minh nhưng một số PDF không chuyển?**  
Đ: Tự chuyển áp dụng cho URL kết thúc `.pdf`. PDF không có đuôi hoặc mở trong trình xem Chrome sẽ có thông báo và huy hiệu nhắc mở bằng Furigana Reader.

**H: Dùng từ điển ngoại tuyến được không?**  
Đ: Có. Từ điển JMdict (hơn 180.000 mục) được đóng gói trong tiện ích. Mọi tra cứu thực hiện cục bộ, không cần mạng.

---

## Liên kết liên quan

- [Chính sách quyền riêng tư](../privacy-policy)
- [Hỗ trợ & phản hồi](../support)

---
