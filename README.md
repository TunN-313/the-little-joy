# 🌸 The Little Joy — Giftbox Cá Nhân Hóa

> *"Made from little moments, made for someone special"*

Landing Page tối ưu tỷ lệ chuyển đổi (CRO) và trải nghiệm người dùng (UX) dành cho thương hiệu hộp quà thủ công cao cấp **The Little Joy**.

---

## 📌 Tổng Quan Dự Án

* **Thương hiệu:** The Little Joy
* **Sản phẩm cốt lõi:** Hộp quà thiết kế riêng, thiệp viết tay, nến thơm, khắc tên, đóng sáp niêm phong thủ công.
* **Mục tiêu:** Mang lại trải nghiệm tặng quà ấm áp, cá nhân hóa sâu sắc và thúc đẩy tỷ lệ chốt đơn (CRO) cao qua Zalo và tư vấn trực tiếp.
* **Cây công nghệ:** Xem chi tiết tại [TECH_TREE.md](TECH_TREE.md).
* **Kế hoạch & Chiến lược:** Xem tài liệu [landing_page_strategy_staged_prompts.md](landing_page_strategy_staged_prompts.md).

---

## 🎨 Nhận Diện Thương Hiệu & Bảng Màu

| Tên màu | Mã Hex | Ý nghĩa |
| :--- | :--- | :--- |
| **Terracotta Warm** | `#BD6B4D` | Màu nhận diện chủ đạo, mộc ấm, khơi gợi cảm xúc |
| **Soft Peach / Blush** | `#F4DCD1` | Màu phụ nhẹ nhàng, tôn nét nữ tính, ngọt ngào |
| **Warm Alabaster** | `#FAF7F2` | Nền kem ấm tự nhiên (không dùng trắng tinh công nghiệp) |
| **Deep Espresso** | `#2C1E1A` | Chữ và chi tiết viền sang trọng, tương phản mềm |
| **Champagne Gold** | `#D4AF37` | Điểm nhấn tem niêm phong sáp, badge đặc biệt |

* **Typography:** `Playfair Display` (Tiêu đề nghệ thuật) + `Plus Jakarta Sans` (Nội dung dễ đọc).

---

## 🌳 Cấu Trúc Thư Mục

```text
The Little Joy/
├── Images/                                 # Kho hình ảnh sản phẩm thực tế & Logo
│   ├── LOGO.png
│   ├── 32.png, sau 1.png
│   └── trước 2 (*).png
├── index.html                              # Trang Landing Page chính (Single Page)
├── TECH_TREE.md                            # Cây công nghệ và kiến trúc hệ thống
├── landing_page_strategy_staged_prompts.md # Bộ prompt 5 giai đoạn chuẩn hóa
├── .gitignore                              # Cấu hình bỏ qua tệp tạm
└── README.md                               # Hướng dẫn dự án
```

---

## 🚀 Hướng Dẫn Đẩy Lên GitHub (Push to GitHub)

1. Tạo một repository mới trên [GitHub](https://github.com/new) (ví dụ đặt tên: `the-little-joy-landingpage`).
2. Mở terminal tại thư mục này và chạy các lệnh:

```bash
# Đổi nhánh chính thành main
git branch -M main

# Liên kết với repository GitHub của bạn (thay URL của bạn vào)
git remote add origin https://github.com/<YOUR-USERNAME>/the-little-joy-landingpage.git

# Đẩy code lên GitHub
git push -u origin main
```

---

## 📦 Triển Khai Trực Tuyến (Deployment)

Dự án được tối ưu hóa dạng **Zero-Configuration Static Web**:
* **GitHub Pages:** Vào `Settings > Pages` trên GitHub repository > Chọn nhánh `main` > Save.
* **Vercel / Netlify:** Import repository trực tiếp để có link truy cập ngay lập tức với SSL miễn phí.
