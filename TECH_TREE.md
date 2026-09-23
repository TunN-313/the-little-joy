# 🌳 TECH TREE: THE LITTLE JOY LANDING PAGE
> **Dự án:** Landing Page "Giftbox Cá Nhân Hóa"  
> **Slogan:** *"Made from little moments, made for someone special"*  
> **Kiến trúc:** High-Converting Single Page Application (Lightweight, Mobile-First, Vanilla JS + Tailwind CSS)

---

## 1. Sơ Đồ Cây Công Nghệ (Mermaid Tech Tree Diagram)

```mermaid
graph TD
    %% Base Layer
    Root[🌸 THE LITTLE JOY - CORE SYSTEM] --> T0[Tier 0: Design System & Foundation]
    
    %% Tier 0: Foundation
    T0 --> T0_Colors[🎨 Palette Tokens: Terracotta, Alabaster, Espresso, Gold]
    T0 --> T0_Typography[🔤 Google Fonts: Playfair Display + Plus Jakarta Sans]
    T0 --> T0_Assets[🖼️ Asset Pipeline: Local Assets & Optimized Images]
    T0 --> T0_CSS[⚙️ Tailwind Engine + Custom Utility Classes]

    %% Tier 1: Hook & Brand Experience
    T0 --> T1[Tier 1: Emotional Hook & First Impression]
    T1 --> T1_Nav[🧭 Glassmorphism Sticky Header & Quick CTA]
    T1 --> T1_Hero[✨ Hero Section 2-Column Split Layout]
    T1 --> T1_Visual[🎁 Cinematic Unboxing Mockup & Floating Cards]
    T1 --> T1_Trust[⭐ Micro Social Proof: 2500+ Nụ cười, 4.9/5]

    %% Tier 2: Storytelling & Craftsmanship
    T1 --> T2[Tier 2: Storytelling & Emotional Resonance]
    T2 --> T2_Collections[📦 Curated Collections: Love, Birthday, Gratitude, Self-love]
    T2 --> T2_Craft[📜 Behind The Craft: 4-Step Interactive Timeline]
    T2 --> T2_Assurance[🛡️ Risk Reversal: Duyệt ảnh trước khi giao & 1 đổi 1]

    %% Tier 3: Core Interactive Engine
    T2 --> T3[Tier 3: Interactive Giftbox Customizer Engine]
    T3 --> T3_State[🔄 State Machine: Box Color, Items List, Custom Text]
    T3 --> T3_UI_Controls[🎛️ Step-by-Step Selector: Wood/Terracotta/Pink Box]
    T3 --> T3_LivePreview[👁️ Real-time Canvas/DOM Visual Preview]
    T3 --> T3_Validation[⚠️ Multi-select Limiter: Max 3 items rule]

    %% Tier 4: Closing Funnel & Trust
    T3 --> T4[Tier 4: Social Proof & Objection Handling]
    T4 --> T4_Stories[💌 Real Customer Unboxing Stories & Quotes]
    T4 --> T4_FAQ[❓ Interactive Accordion FAQ]
    T4 --> T4_Footer[🏡 Warm Artisanal Footer & Brand Identity]

    %% Tier 5: Conversion & Mobile Optimization
    T4 --> T5[Tier 5: Conversion Triggers & Omnichannel]
    T5 --> T5_Zalo[📲 Zalo Smart Deep-link & Dynamic Order Payload]
    T5 --> T5_StickyMobile[📱 Floating Mobile Bottom Bar: Tư vấn + Đặt quà]
    T5 --> T5_Tracking[📊 Event Tracking: CTA clicks, Scroll depth]

    %% Tier 6: DevOps, SEO & Distribution
    T5 --> T6[Tier 6: Deployment, SEO & CI/CD]
    T6 --> T6_SEO[🔍 Meta Tags, OpenGraph, Schema.org GiftShop]
    T6 --> T6_Git[🐙 Git Version Control & GitHub Pages / Vercel]
    T6 --> T6_Perf[⚡ 100/100 Lighthouse Performance & Lazy Loading]

    classDef core fill:#BD6B4D,stroke:#2C1E1A,stroke-width:2px,color:#fff;
    classDef foundation fill:#FAF7F2,stroke:#BD6B4D,stroke-width:2px,color:#2C1E1A;
    classDef feature fill:#F4DCD1,stroke:#BD6B4D,stroke-width:1px,color:#2C1E1A;
    classDef engine fill:#D4AF37,stroke:#2C1E1A,stroke-width:2px,color:#2C1E1A;
    
    class Root core;
    class T0,T1,T2,T4,T5,T6 foundation;
    class T3 engine;
```

---

## 2. Chi Tiết Các Tầng Công Nghệ (Tech Tree Breakdown)

### 🌿 TIER 0: NỀN TẢNG THIẾT KẾ & HỆ THỐNG TOKENS (FOUNDATION)
* **Design Tokens (CSS Variables & Tailwind Config):**
  * `Primary`: `#BD6B4D` (Terracotta mộc ấm) | `Primary Hover`: `#A45538`
  * `Secondary`: `#F4DCD1` (Blush pastel)
  * `Surface`: `#FAF7F2` (Alabaster nền kem ấm)
  * `Card`: `#FFFFFF`
  * `Text Main`: `#2C1E1A` (Espresso) | `Text Muted`: `#7A6B65`
  * `Accent`: `#D4AF37` (Champagne Gold)
* **Typography Stack:**
  * Headings / Serif: `'Playfair Display', serif`
  * Body / Sans: `'Plus Jakarta Sans', sans-serif`
* **Local Asset Pipeline:** Quản lý kho ảnh thực tế trong `./Images/` (Logo, hình sản phẩm, sáp niêm phong).

---

### 🌸 TIER 1: BRAND IDENTITY & GÂY ẤN TƯỢNG ĐẦU TIÊN (HOOK LAYER)
* **Glassmorphic Sticky Nav:**
  * Backdrop-blur header với độ trong suốt tinh tế.
  * Logo thương hiệu + navigation liên kết mượt (Smooth Scrolling) + Mini-CTA "Đặt làm ngay".
* **Hero Section (High-CRO Split):**
  * Typography nổi bật với badge cảm xúc *"✨ Hộp quà cá nhân hóa theo từng câu chuyện"*.
  * H1 Headline định vị: *"Gói ghém yêu thương từ những khoảnh khắc nhỏ nhất"*.
  * Bộ đôi CTA: Button chính (Primary Glow) + Button phụ ("Xem video unboxing").
  * Visual Hero: Mockup hộp quà mở nắp nghệ thuật kết hợp floating badge *"Thiệp viết tay riêng cho..."*.

---

### 🌿 TIER 2: NGHỆ THUẬT KỂ CHUYỆN & GIẢI TOẢ TÂM LÝ (STORYTELLING)
* **Curated Collections Grid:**
  * Phân nhóm theo nhu cầu: *Anniversary / Birthday Joy / Gratitude / Self-love*.
  * Micro-hover effect (zoom nhẹ, viền bóng mượt, hiển thị chi tiết tặng phẩm).
* **"Behind The Craft" - Hành Trình 4 Bước:**
  * Step 1: Lắng nghe & Khởi tạo ý niệm.
  * Step 2: Tuyển chọn tặng phẩm thủ công.
  * Step 3: Cá nhân hóa (In ảnh mini, khắc tên laser, viết thiệp sáp).
  * Step 4: Đóng gói 3 lớp chống sốc & niêm phong con dấu sáp.
* **Risk Reversal Badges:**
  * Cam kết gửi ảnh duyệt trước khi ship.
  * 1 đổi 1 lập tức nếu cấn móp trong quá trình vận chuyển.

---

### ⚡ TIER 3: TRÁI TIM TƯƠNG TÁC (CORE INTERACTIVE ENGINE)
* **Giftbox Customizer Widget (Vanilla JS Engine):**
  * **State Management:** Quản lý trạng thái hộp quà (Box color, selected gifts, recipient name, custom message).
  * **Interactive Selectors:**
    * Lựa chọn chất liệu/màu hộp (Gỗ mộc, Terracotta, Pastel Blush).
    * Giới hạn thông minh: Chọn tối đa 3 món quà (nến thơm, lọ trà hoa, sổ tay, khăn lụa, khung ảnh polaroid).
    * Ô nhập liệu trực tiếp tên người nhận và thông điệp.
  * **Live DOM Visualizer:** Tên người nhận và các món quà được hiển thị trực quan lên hộp quà mô phỏng theo thời gian thực (Real-time Preview).

---

### 💌 TIER 4: BẰNG CHỨNG XÃ HỘI & GIẢI TỎA LO ÂU (TRUST & PROOF)
* **Customer Joy Stories:**
  * Masonry / Grid hiển thị khoảnh khắc mở hộp thực tế từ khách hàng.
  * Quote trích dẫn cảm xúc ấm áp và đánh giá 5 sao.
* **Interactive Accordion FAQ:**
  * Trả lời 4 khúc mắc phổ biến: Thời gian giao hàng hỏa tốc, gửi ảnh cá nhân/mã Spotify, chính sách bảo hành khi vận chuyển, dịch vụ gửi tặng bí mật.

---

### 🚀 TIER 5: BỘ CHUYỂN ĐỔI & TỐI ƯU MOBILE (CONVERSION LAYER)
* **Smart Zalo Deeplink:**
  * Tự động tổng hợp cấu hình hộp quà mà khách vừa tạo (Màu hộp + Món đã chọn + Tên người nhận) thành nội dung tin nhắn gửi thẳng tới Zalo OA/Số hotline:
    `https://zalo.me/[SDT]?text=Chào%20The%20Little%20Joy,%20mình%20muốn%20đặt%20hộp%20quà...`
* **Mobile Sticky Bottom Bar:**
  * Thanh ghim đáy màn hình thông minh (chỉ hiện khi cuộn qua Hero Section).
  * 2 Action: Nút nhắn tin tư vấn nhanh + Nút Primary cuộn mượt đến bộ phối quà.
* **CRO Event Tracking:**
  * Gắn định danh cho các nút hành động (Hero CTA, Customizer Submit, Sticky Mobile).

---

### 🌐 TIER 6: SEO, DEPLOYMENT & QUẢN LÝ PHIÊN BẢN (DISTRIBUTION)
* **Git Version Control:** Khởi tạo repository Git, cấu hình `.gitignore` chuẩn.
* **SEO Metadata:** Meta tags chuẩn OpenGraph (OG Title, OG Image, OG Description) cho hiển thị đẹp khi chia sẻ link qua Zalo/Facebook.
* **Ready for Deployment:** Tương thích 100% với GitHub Pages, Vercel, Netlify (Zero-configuration static build).
