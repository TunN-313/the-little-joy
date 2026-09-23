# CHIẾN LƯỢC THIẾT KẾ LANDING PAGE & BỘ PROMPT ĐA GIAI ĐOẠN
**Dự án:** Landing Page "Giftbox Cá Nhân Hóa"  
**Thương hiệu:** The Little Joy  
**Slogan cốt lõi:** *"Made from little moments, made for someone special"*  
**Vai trò:** Senior UX/UI & Conversion Rate Optimization (CRO) Lead

---

## PHẦN 1: HỆ THỐNG THƯƠNG HIỆU & KIẾN TRÚC TRẢI NGHIỆM (UX/CRO)

### 1. Phân tích nhận diện thương hiệu (Từ Logo & Tư liệu)
* **Tên thương hiệu:** The Little Joy
* **Tinh thần cốt lõi (Brand Persona):** Ấm áp, tinh tế, thủ công tỉ mỉ (artisanal), lưu giữ ký ức và truyền tải tình cảm chân thành.
* **Bảng màu chủ đạo (Brand Color Palette):**
  * **Primary Color (Màu nhận diện):** Terracotta Warm / Mộc ấm (`#C87A5B` hoặc `#BD6B4D`) – khơi gợi cảm xúc yêu thương, sự trân trọng.
  * **Secondary / Accent (Màu bổ trợ):** Soft Peach / Creamy Blush (`#F7EDE2` & `#F4DCD1`) – tạo cảm giác nhẹ nhàng, dễ chịu cho mắt.
  * **Neutral Background (Nền chủ đạo):** Warm Alabaster / Nền kem mộc (`#FAF7F2`) – không dùng trắng tinh khiết `#FFFFFF` để tránh cảm giác công nghiệp, lạnh lẽo.
  * **Deep Text / Contrast (Màu chữ & viền):** Deep Espresso / Nâu hạt dẻ sẫm (`#2C1E1A`) – tương phản cao, dễ đọc, sang trọng hơn màu đen than thông thường.
  * **Luxury Highlight:** Muted Champagne Gold (`#D4AF37`) cho các badge quà tặng đặc biệt hoặc tem niêm phong sáp.

---

### 2. Hành trình tâm lý khách hàng (Customer Journey Map)

```
[ GIAI ĐOẠN 1: AWARENESS & HOOK ]
       │  "Chiếc hộp này dành cho ai? Tại sao lại chạm đến cảm xúc?"
       ▼
[ GIAI ĐOẠN 2: EMPATHY & SHOWCASE ]
       │  "Những khoảnh khắc nhỏ được đóng gói như thế nào?"
       ▼
[ GIAI ĐOẠN 3: PROCESS & CRAFTSMANSHIP ]
       │  "Từng công đoạn được chăm chút thủ công ra sao? Sự an tâm & tỉ mỉ"
       ▼
[ GIAI ĐOẠN 4: INTERACTIVE SELECTION ]
       │  "Tự tay tôi có thể chọn gì vào hộp? Trải nghiệm làm người tặng quà"
       ▼
[ GIAI ĐOẠN 5: SOCIAL PROOF & RISK REVERSAL ]
       │  "Người nhận mở hộp cảm thấy thế nào? Cam kết đóng gói & giao hàng"
       ▼
[ GIAI ĐOẠN 6: CONVERSION / HIGH-URGENCY CTA ]
       ▼  "Tạo hộp quà kỷ niệm ngay hôm nay"
```

---

### 3. Cấu trúc trang (Information Architecture - 7 Modules)

1. **Header & Sticky Mini-CTA:** Logo The Little Joy, cam kết giao hỏa tốc/đóng gói thủ công, nút "Tự thiết kế hộp quà".
2. **Hero Section (First Impression):**
   * Slogan trung tâm: *"Made from little moments, made for someone special"*.
   * Split Layout: Bên trái là tiêu đề đánh trúng tâm lý quà tặng độc bản; bên phải là hình ảnh/video mở hộp cinematic (Unboxing moment).
   * Primary CTA: **"Tạo hộp quà cho người đặc biệt"** + Micro-copy: *Gói ghém thủ công trong 24h*.
3. **Curated Collections (Sản phẩm tiêu biểu theo dịp):**
   * Phân loại trực quan: Tình yêu (Anniversary/Love), Sinh nhật (Birthday Joy), Tri ân (Thank you/Gratitude), Tự thưởng (Self-love).
4. **Behind The Craft (Hành trình tạo nên sản phẩm - The Core Process):**
   * Step 1: Lắng nghe câu chuyện & lời nhắn nhủ.
   * Step 2: Tuyển chọn tặng phẩm tinh tế (nến thơm, trà hoa, sổ tay, khăn lụa, ảnh in mini).
   * Step 3: Khắc tên, in thiệp viết tay & đóng sáp niêm phong thủ công.
   * Step 4: Đóng gói chống va đập 3 lớp an toàn tuyệt đối.
5. **Interactive Giftbox Customizer Preview (Bộ demo trực quan):**
   * 3 bước chọn đơn giản: Chọn hộp -> Chọn quà bên trong -> Điền lời chúc & ảnh kỷ niệm.
6. **Customer Joy Stories (Bằng chứng cảm xúc):**
   * Video ngắn/hình ảnh unboxing thực tế từ người nhận, cảm xúc rơi nước mắt/mỉm cười hạnh phúc.
7. **FAQ & Final Sticky Conversion:**
   * Giải đáp: Thời gian giao hàng, bảo quản, đổi trả nếu móp méo, dịch vụ giữ bí mật tạo bất ngờ.

---

## PHẦN 2: CHIẾN LƯỢC CHIA LỆNH ĐA GIAI ĐOẠN (CHỐNG ẢO GIÁC CHO AI AGENT)

Khi giao việc cho AI Agent (như Cursor, v0, Devin, Claude Code), việc quăng một prompt dài hàng nghìn chữ sẽ gây ra:
* Bỏ sót tính năng (component hallucination).
* Màu sắc bị lệch chuẩn CSS (vỡ palette).
* Giao diện mobile bị vỡ bố cục do quá tải token.

**Quy trình 5 Giai Đoạn chuẩn hóa:**
* **Giai đoạn 1:** Thiết lập Design System Tokens & Base Theme (HTML/Tailwind config).
* **Giai đoạn 2:** Xây dựng Hero Section, Value Proposition & Header.
* **Giai đoạn 3:** Xây dựng Module "Hành trình chế tác & Quy trình thủ công" (Crafting Journey).
* **Giai đoạn 4:** Xây dựng Bộ xem trước cá nhân hóa (Interactive Gift Builder) & Showcase sản phẩm.
* **Giai đoạn 5:** Xây dựng Social Proof, FAQ, Sticky Mobile Bar & Tinh chỉnh CRO.

---

## PHẦN 3: BỘ PROMPT CHUẨN ĐỂ ĐƯA VÀO AGENT

---

### PROMPT 1: Khởi tạo Design System & Tokens (Giai đoạn 1)

```text
[BỐI CẢNH & VAI TRÒ]
Bạn là Senior Creative Front-end Developer và Design System Lead. Bạn đang xây dựng một landing page duy nhất (Single Page) cho thương hiệu hộp quà cá nhân hóa "The Little Joy" với slogan: "Made from little moments, made for someone special".

[NHIỆM VỤ GIAI ĐOẠN 1]
Thiết lập cấu trúc HTML5 cơ bản, tích hợp Tailwind CSS qua CDN, phông chữ và các biến CSS Tokens đồng bộ tuyệt đối với nhận diện thương hiệu logo "The Little Joy".

[QUY TẮC MÀU SẮC & TOKENS]
Hãy cấu hình `tailwind.config` hoặc CSS Variables với bảng mã màu sau:
- primary: '#BD6B4D' (Terracotta mộc ấm)
- primary-hover: '#A45538'
- secondary: '#F4DCD1' (Blush pastel)
- surface: '#FAF7F2' (Alabaster kem mộc ấm áp, dùng cho background body)
- card: '#FFFFFF' (Trắng ấm nhẹ cho các card khối)
- text-main: '#2C1E1A' (Nâu sẫm espresso sang trọng, thay cho đen thuần)
- text-muted: '#7A6B65' (Nâu khói mềm mại)
- accent-gold: '#D4AF37' (Champagne Gold nhấn nhá)

[FONTS]
- Heading: 'Playfair Display' hoặc 'Cinzel' (Google Fonts) thể hiện sự trang nhã, thi vị, cá nhân hóa.
- Body: 'Plus Jakarta Sans' hoặc 'Inter' (Google Fonts) đảm bảo dễ đọc trên mobile.

[YÊU CẦU ĐẦU RA]
Chỉ xuất phần khung HTML bao gồm thẻ <head>, nạp font, script tailwind config, style reset, và thẻ <body> với màu nền `#FAF7F2`. Chưa viết phần nội dung body, tạo sẵn cấu trúc thẻ <header> rỗng và container chính. Giữ code thật sạch và sẵn sàng cho Giai đoạn 2.
```

---

### PROMPT 2: Xây dựng Navigation & Hero Section Tối Ưu Chuyển Đổi (Giai đoạn 2)

```text
[BỐI CẢNH & VAI TRÒ]
Tiếp tục từ Giai đoạn 1 của landing page "The Little Joy". Bạn sẽ lập trình phần Header và Hero Section tập trung tối đa vào cảm xúc và chuyển đổi tức thì (High-CRO).

[DỮ LIỆU ĐẦU VÀO]
- Tên: The Little Joy
- Slogan: "Made from little moments, made for someone special"
- CTA chính: "Tự tay thiết kế hộp quà"
- CTA phụ: "Khám phá bộ sưu tập sẵn"

[YÊU CẦU GIAO DIỆN HERO SECTION]
1. Header:
   - Sticky bar kính mờ (backdrop-blur-md) với nền kem trong suốt nhẹ.
   - Bên trái: Logo text "The Little Joy" font serif thanh lịch kèm icon nhỏ hình nơ/tim tối giản.
   - Giữa: Menu cuộn mượt (Bộ sưu tập, Quy trình chế tác, Câu chuyện người nhận, Đánh giá).
   - Bên phải: Nút CTA nhỏ "Đặt làm ngay" (Màu primary, bo góc tròn sang trọng).

2. Hero Banner:
   - Layout 2 cột trên Desktop (50/50), xếp chồng cân đối trên Mobile.
   - Cột trái (Copywriting & CTA):
     * Badge nhỏ trên tiêu đề: "✨ Hộp quà cá nhân hóa theo từng câu chuyện"
     * Tiêu đề chính H1: "Gói ghém yêu thương từ những khoảnh khắc nhỏ nhất"
     * Subtitle: "Made from little moments, made for someone special. Từng tấm thiệp viết tay, chiếc nơ lụa và món quà bên trong đều mang dấu ấn riêng của bạn."
     * CTA Group: 1 nút Primary nổi bật hiệu ứng hover scale nhẹ + 1 nút viền mềm "Xem video unboxing thực tế".
     * Trust Elements (Social Proof nhỏ bên dưới nút): 3 avatar khách hàng chồng lên nhau + Dòng chữ "Hơn 2,500+ nụ cười đã được trao đi trong năm nay ★★★★★ (4.9/5)".
   - Cột phải (Visual Mockup):
     * Khung hình hộp quà mở nắp nghệ thuật, bên trong có: Nến thơm khắc tên, sổ tay mini, ảnh chụp kỷ niệm polaroid kẹp gỗ, hoa khô và sáp niêm phong đỏ terracota.
     * Thêm 1 floating card nhỏ trôi nhẹ: "Thiệp viết tay riêng cho: Em yêu 💌" để làm bật tính cá nhân hóa.

[QUY TẮC KỸ THUẬT]
- Sử dụng đúng mã màu tokens từ Giai đoạn 1.
- Mobile First: Đảm bảo tiêu đề không bị gãy chữ xấu trên màn hình 375px.
```

---

### PROMPT 3: Hành Trình Chế Tác "Behind The Craft" & Quy Trình 4 Bước (Giai đoạn 3)

```text
[BỐI CẢNH & VAI TRÒ]
Bạn đang tiếp tục triển khai phần cốt lõi của landing page: "Quy trình tạo ra sản phẩm" để giải quyết câu hỏi lớn nhất của người mua quà: "Hộp quà này được làm như thế nào và có thực sự đặc biệt không?".

[YÊU CẦU NỘI DUNG & UX GIAI ĐOẠN 3]
Xây dựng Section: "Hành trình từ khoảnh khắc nhỏ đến món quà độc bản" (Behind The Crafting).

1. Thiết kế dòng thời gian (Timeline / Stepper Flow) gồm 4 bước:
   - Bước 1: Lắng nghe & Khởi tạo ý niệm (Bạn chọn phong cách, dịp tặng và chia sẻ câu chuyện/lời chúc riêng tư).
   - Bước 2: Tuyển chọn tặng phẩm thủ công (Mỗi món quà như nến sáp đậu nành, trà hoa mộc, phụ kiện lụa đều được kiểm tra tỉ mỉ).
   - Bước 3: Cá nhân hóa từng chi tiết (In ảnh kỷ niệm lấy ngay, khắc tên laser lên hộp gỗ/thủy tinh, viết thiệp thủ công mực nâu vintage).
   - Bước 4: Đóng gói niêm phong sáp cổ điển (Thắt ruy băng lụa cao cấp, đóng dấu sáp dập nổi logo The Little Joy, bọc 3 lớp chống sốc bảo vệ khi vận chuyển).

2. Yêu cầu UI/Visual:
   - Mỗi bước có: Số thứ tự to mờ nghệ thuật phía sau, icon minh họa mềm mại, tiêu đề bước và mô tả ngắn ấm áp.
   - Thẻ hiển thị dạng Card nền trắng kem có viền bo tròn nhẹ, shadow mịn như giấy mỹ thuật cao cấp.
   - Điểm nhấn giữa Section: Một CTA trung gian kích thích: "Bạn đã sẵn sàng gửi gắm yêu thương? -> Bắt đầu chọn quà".

[QUY TẮC CRO]
- Đưa vào các bảo chứng ngay tại quy trình: "Cam kết gửi ảnh chụp thành phẩm duyệt trước khi giao", "Bảo hành 1 đổi 1 ngay lập tức nếu hộp bị va đập khi ship".
```

---

### PROMPT 4: Trải Nghiệm Tự Tay Chọn Hộp (Interactive Giftbox Customizer Preview) (Giai đoạn 4)

```text
[BỐI CẢNH & VAI TRÒ]
Để biến người xem từ "chỉ đọc lướt" thành "người hành động", bạn hãy xây dựng một mô phỏng tương tác (Interactive Simulation) trực quan ngay trên landing page bằng JavaScript thuần (Vanilla JS) tích hợp sẵn trong file.

[TÍNH NĂNG TƯƠNG TÁC]
Tạo một widget demo có tên: "Tự phối thử Giftbox của bạn trong 30 giây":
1. Bên trái: Bộ điều khiển (Step Controls):
   - Bước 1: Chọn màu hộp (Hộp Gỗ Mộc, Hộp Terracotta Warm, Hộp Pastel Pink).
   - Bước 2: Chọn 3 món quà yêu thích (Toggle checkbox các thẻ: Nến thơm Amber & Vanilla, Lọ trà hoa cúc mật ong, Khăn lụa hoa, Sổ tay da khắc tên, Khung ảnh gỗ Mini).
   - Bước 3: Nhập tên người nhận quà và thông điệp ngắn.
2. Bên phải: Khung hiển thị trực quan (Live Visual Preview Box):
   - Thay đổi màu hộp theo lựa chọn.
   - Hiển thị danh sách các món quà đã chọn bên trong hộp.
   - Tên người nhận tự động render trực tiếp lên nhãn hộp quà theo thời gian thực (Real-time).
3. Nút hành động chuyển đổi (Conversion Trigger):
   - Nút: "Gửi cấu hình này qua Zalo / Đặt hàng ngay" (Kèm tự động tạo link Zalo hoặc modal pop-up thu thập thông tin đơn hàng).

[YÊU CẦU KỸ THUẬT]
- Code JS gọn gàng, tương thích hoàn toàn không cần thư viện ngoài (dùng Vanilla JS).
- Giao diện mượt mà, có hiệu ứng chuyển động nhẹ nhàng khi click chọn.
```

---

### PROMPT 5: Social Proof, FAQ, Sticky Mobile Bottom Bar & Tối Ưu Đóng Trang (Giai đoạn 5)

```text
[BỐI CẢNH & VAI TRÒ]
Hoàn thiện các phần cuối cùng của Landing page "The Little Joy", gia cố niềm tin khách hàng và chốt đơn (Final Closing).

[CÁC SECTION CẦN HOÀN THIỆN]
1. Section "Khoảnh Khắc Hạnh Phúc" (Real Emotional Proof):
   - Grid 3 cột dạng masonry hoặc card ảnh chân thực: Ảnh người nhận cười rạng rỡ khi mở hộp, tin nhắn cảm ơn xúc động trên Instagram/Zalo.
   - Quote khách hàng: "Khoảnh khắc bạn ấy mở chiếc thiệp viết tay và ngửi thấy mùi nến thơm yêu thích, cả căn phòng như bừng sáng."

2. Section FAQ (Accordion mở rộng):
   - 4 câu hỏi thường gặp nhất:
     * 1. Tôi ở xa có được duyệt ảnh chụp hộp quà trước khi gửi không?
     * 2. Thời gian làm và giao hàng mất bao lâu? Có ship hỏa tốc không?
     * 3. Nếu quà tặng bị lỗi hoặc hộp bị móp do bên vận chuyển thì sao?
     * 4. Tôi muốn thêm ảnh cá nhân và bài hát kỷ niệm (mã QR Spotify) có được không?

3. Footer ấm cúng:
   - Nhắc lại slogan: "The Little Joy — Made from little moments, made for someone special".
   - Thông tin cửa hàng, hotline tư vấn, chính sách bảo hành quà tặng nguyên vẹn 100%.

4. Mobile Sticky Bottom Bar (Thanh chốt đơn cố định trên điện thoại):
   - Luôn hiển thị ở mép dưới màn hình khi cuộn qua Hero Section.
   - Gồm 2 nút:
     * Nút gọi/nhắn tư vấn nhanh (Zalo Icon).
     * Nút Primary to: "Tự tạo hộp quà riêng" (Click cuộn mượt đến bộ widget customizer).

[YÊU CẦU TỔNG THỂ CUỐI CÙNG]
Kiểm tra lại toàn bộ file code: Đúng màu chủ đạo của logo, không vỡ layout trên màn hình dọc (mobile responsive 100%), hình ảnh placeholder dùng Unsplash với từ khóa quà tặng/nến thơm cao cấp.
```

---

## PHẦN 4: HƯỚNG DẪN THỰC THI THỰC TẾ (BEST PRACTICES)

1. **Chuẩn bị hình ảnh:**
   * Thay thế các link placeholder ảnh bằng ảnh thật đã có trong file `.zip` (ảnh chụp hộp quà thực tế, ảnh cận cảnh tem niêm phong sáp, ảnh chụp nơ lụa).
2. **Thiết lập liên kết Zalo/Hotline:**
   * Thay link liên hệ Zalo theo cú pháp chuẩn: `https://zalo.me/[SỐ_ĐIỆN_THOẠI]` để khi khách click vào CTA trên mobile, ứng dụng Zalo sẽ mở ngay lập tức kèm lời chào mẫu: *"Chào The Little Joy, mình muốn tư vấn một hộp quà cá nhân hóa..."*.
3. **Đo lường chuyển đổi (Tracking):**
   * Gắn sự kiện `onclick` trên 3 nút CTA:
     * `CTA_Hero_CreateBox`
     * `CTA_Widget_Submit`
     * `CTA_Sticky_Mobile`
   * Đo lường tỷ lệ người dùng cuộn đến phần *Quy trình chế tác* để đánh giá mức độ hấp dẫn của câu chuyện thương hiệu.