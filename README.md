# 🚀 SEO Agent Skills — by SaoLabs

> Hệ thống AI Agent chuyên biệt cho SEO, kiến trúc **hai tầng phân vai** (Strategist → Executor), tự động hóa toàn bộ quy trình từ hoạch định chiến lược Data-Driven đến thực thi nội dung chuẩn SEO Rank Math 100/100 với văn phong tự nhiên như con người.

---

## 📖 Mục lục

- [1. Triết lý Thiết kế](#1-triết-lý-thiết-kế)
- [2. Kiến trúc Hai tầng](#2-kiến-trúc-hai-tầng)
- [3. SEO Master Agent — Chuyên gia Hoạch định](#3-seo-master-agent--chuyên-gia-hoạch-định)
- [4. Copywriter Agent — Cỗ máy Thực thi](#4-copywriter-agent--cỗ-máy-thực-thi)
- [5. Bảng Kế hoạch 13 Cột](#5-bảng-kế-hoạch-13-cột)
- [6. Hướng dẫn Sử dụng](#6-hướng-dẫn-sử-dụng)
- [7. Cấu trúc Dự án](#7-cấu-trúc-dự-án)

---

## 1. Triết lý Thiết kế

Hệ thống giải quyết bài toán "AI Content máy móc" bằng quy tắc ưu tiên tối thượng:

1. **Văn phong Con người** — Ngôn từ có nhịp điệu, cảm xúc. Loại bỏ hoàn toàn "văn mẫu AI" sáo rỗng.
2. **Chiều sâu Nội dung (E-E-A-T)** — Giải quyết đúng Search Intent, bảo chứng sự thật từ nguồn uy tín.
3. **Kỹ thuật SEO Tuyệt đối** — Tối ưu AEO/SGE, Rank Math 100/100, Topic Cluster chuẩn chỉnh.

---

## 2. Kiến trúc Hai tầng

| Tầng | Agent | Vai trò | Chức năng |
| :--- | :--- | :--- | :--- |
| **Strategist** | SEO Master Agent | SEO Director | Nghiên cứu, lập roadmap, bóc tách từ khóa, thiết kế bản vẽ kỹ thuật (Bảng 13 cột) |
| **Executor** | Copywriter Agent | Senior Copywriter | Thực thi viết bài, tối ưu on-page, chèn media, tự kiểm duyệt chất lượng |

**Luồng dữ liệu:** Master Agent xuất **Bảng Kế hoạch 13 cột** → Copywriter Agent nhận từng dòng dữ liệu → Xuất **Báo cáo thực thi nội dung SEO**.

---

## 3. SEO Master Agent — Chuyên gia Hoạch định

> **Prompt:** [`SEO-MASTER-AGENT.md`](./SEO-MASTER-AGENT.md)

SEO Master Agent đóng vai trò là "bộ não" của toàn bộ chiến dịch. Thay vì chỉ lên danh sách từ khóa một cách cơ học, Agent được trang bị tư duy của một **Giám đốc SEO (SEO Director)** với khả năng phân tích dữ liệu thực chứng và thiết lập "bản vẽ kỹ thuật" không tì vết cho đội ngũ nội dung.

### 3.1 Tư duy SEO bao quát (Nhánh chính & Nhánh phụ)

Agent không chỉ nhắm vào các từ khóa bán hàng trực tiếp (Sản phẩm/Dịch vụ) mà còn có khả năng tự suy luận để đào sâu vào **"nguyên nhân gốc rễ" (Root Cause)** của khách hàng:

- **Nhánh chính:** Sản phẩm/Dịch vụ trực tiếp (VD: "niềng răng").
- **Nhánh phụ:** Nguyên nhân gốc rễ, kiến thức giáo dục bao quanh (VD: "tại sao răng hô, lệch khớp cắn").

Việc phân bổ nội dung để giải quyết các vấn đề nhánh phụ giúp website xây dựng **Topical Authority** vững chắc và thu phễu tự nhiên từ giai đoạn nhận thức.

### 3.2 Thuật toán Bóc tách Từ khóa "Bảo toàn ngữ nghĩa"

Đây là tính năng giải quyết mâu thuẫn lớn nhất giữa công cụ SEO (cần từ khóa ngắn) và văn phong tự nhiên (cần câu hoàn chỉnh). Quy trình 3 bước:

- **Bước 1:** Sử dụng dữ liệu thực để tìm ra truy vấn tốt nhất (có thể dài 2-7 từ). Xóa sạch dấu câu.
- **Bước 2:** Bóc tách lấy "cụm từ lõi" ngắn gọn (2-5 từ), ưu tiên cụm danh từ để tương thích Rank Math/Yoast SEO. **⚠️ Nếu cắt gọt làm sai nghĩa → BẮT BUỘC giữ nguyên bản gốc.**
- **Bước 3:** Đẩy phiên bản từ khóa dài (đầy đủ ngữ cảnh) xuống Cột 13 dưới dạng các **"Câu văn mẫu"**, giúp Copywriter Agent viết câu chuẩn ngữ pháp tiếng Việt mà không bị tối nghĩa.

> ❌ **Ví dụ lỗi:** "Niềng răng có đau không" → cắt thành "niềng răng có đau" = nghĩa khẳng định tiêu cực, sai Search Intent.
> ✅ **Cách đúng:** Giữ nguyên "niềng răng có đau không".

### 3.3 Phân bổ Topic Cluster Động (Dynamic Allocation)

Tránh việc rập khuôn tỷ lệ cứng nhắc. Agent tự tính toán tỷ trọng nội dung cho 3-4 cụm chủ đề trong từng Phase:

| Phase | Mục tiêu | Phân bổ |
| :--- | :--- | :--- |
| **Phase 1** | Bao phủ & Lên top | 40-50% Cluster chủ đạo; 50-60% bổ trợ + nhánh phụ |
| **Phase 2** | Củng cố | 40% chuyên sâu E-E-A-T; 60% rải đều |
| **Phase 3** | Mở rộng | 50-60% ngách mới/nhánh phụ; 40% duy trì cũ |
| **Phase 4** | Cập nhật | Refresh nội dung cũ + Hot trend |

### 3.4 Kỷ luật Bảng dữ liệu thép

Agent xuất ra Bảng Kế hoạch 13 cột và Bảng Brief đa ngôn ngữ với lệnh cấm kỵ tuyệt đối: **Không được xuống dòng trong ô bảng**. Mọi danh sách dùng dấu `;` hoặc `,`. Điều này bảo vệ cấu trúc Markdown khi trích xuất sang Google Sheets/Excel.

### 3.5 Kiến trúc Đa ngôn ngữ (Bilingual Architecture)

Bảng 13 cột phân luồng ngôn ngữ:
- **Cột 3-7:** BẮT BUỘC dùng ngôn ngữ mục tiêu của chiến dịch.
- **Cột 8-13:** BẮT BUỘC dùng tiếng Việt (riêng truy vấn trong Cột 13 vẫn dùng ngôn ngữ mục tiêu).

### 3.6 Khóa chuẩn E-E-A-T & YMYL

Với chủ đề nhạy cảm (Y tế, Tài chính, Luật...), bắt buộc tham chiếu nguồn chính thống: PubMed, WHO, NIH, Dược thư Quốc gia. Cấm bịa đặt.

### 3.7 Quy trình 6 Giai đoạn

| GĐ | Tên | Output | Dừng |
| :--- | :--- | :--- | :---: |
| 1 | Khảo sát Thị trường & Đánh giá Nội tại | Báo cáo Self-Audit, Chân dung KH, Timeline động | 🛑 |
| 2 | Giải phẫu Đối thủ & Nghiên cứu Từ khóa | SWOT, Phân nhóm từ khóa, Content Gap, Striking Distance | 🛑 |
| 3 | Lộ trình Chiến lược (Roadmap 4 Phase) | Bảng Roadmap + Topic Matrix | 🛑 |
| 4 | **Kế hoạch Nội dung** (quan trọng nhất) | **Bảng KH 13 cột**, Bảng Internal Link, Brief tài nguyên | 🛑 |
| 5 | Dàn ý | H1-H3 + Meta Data | 🛑 |
| 6 | Audit | Kiểm tra SEO & gợi ý Content Refresh | — |

---

## 4. Copywriter Agent — Cỗ máy Thực thi

> **Prompt:** [`COPYWRITER-AGENT.md`](./COPYWRITER-AGENT.md)

Nếu Master Agent là bản vẽ, thì Copywriter Agent là **thợ xây bậc thầy**. Agent được thiết lập với nguyên tắc tối thượng: **(1) Văn phong tự nhiên → (2) Chất lượng nội dung → (3) Tối ưu kỹ thuật SEO**. Tuyệt đối không đánh đổi sự tự nhiên để nhồi nhét SEO.

### 4.1 Cơ chế Anti-Context Bleeding (Làm sạch bộ nhớ)

Để khắc phục lỗi AI bị "râu ông nọ cắm cằm bà kia" khi xử lý hàng loạt bài viết, Agent được lệnh **chỉ ghi nhớ dữ liệu của yêu cầu hiện tại** và xóa bỏ các đoạn hội thoại bài viết cũ. Chỉ nhận làm **1 bài/lần** và cung cấp 3 Option xuất file.

### 4.2 Động cơ Hành văn (Human-like Engine)

- **Bộ lọc chống "văn mẫu AI":** Loại bỏ hoàn toàn các từ sáo rỗng ("Trong thời đại hiện nay...", "Giải pháp hoàn hảo"...).
- **Nhịp câu đan xen:** Trộn lẫn câu ngắn (2-5 chữ) với câu dài, dùng từ chuyển ý mượt mà.
- **Phiên dịch chuyên môn:** Có khả năng biến kiến thức hàn lâm, y khoa chuyên sâu thành ngôn ngữ đại chúng, gần gũi với người đọc bình thường.
- **Cân bằng E-E-A-T & đại chúng:** Giải thích thuật ngữ chuyên ngành bằng ví dụ thực tế, hình ảnh so sánh sinh động.

### 4.3 Văn phong theo Phễu (Funnel-Aware)

Tự động nhận diện Phễu từ Cột 8 để tùy chỉnh giọng điệu:
- **TOFU:** Khách quan, giáo dục, đi sâu nguyên nhân gốc rễ.
- **MOFU:** Phân tích chuyên sâu, so sánh đối chiếu đa chiều.
- **BOFU:** Thuyết phục, chuyển đổi mạnh mẽ (kết hợp CTA từ Cột 9).

**Độ dài linh hoạt:** Không khóa cứng số từ. Khung tham khảo: Bài tiêu chuẩn ~1200 từ, Cluster ~2000 từ, Pillar ~3000 từ.

### 4.4 Tối ưu SEO Rank Math 100/100

- **AEO (AI Search):** Tự động tạo cấu trúc **Answer-first 40-80 từ** ngay dưới H1 để nhắm mục tiêu AI Overview.
- **Lắp ghép từ khóa thông minh:** Nhận cụm từ lõi (Cột 6) để rải mật độ 0.6-1.5%. Đọc "Câu văn mẫu" từ Cột 13 để phát triển thành H2, H3, FAQ mượt mà, đúng chuẩn ngữ pháp.
- **Kỷ luật Link:** Được phép linh động tạo thêm Internal/External Link nếu thiếu, nhưng bắt buộc cú pháp `[Anchor text](URL)`. Tuyệt đối không lộ URL trần.
- **Kỷ luật Media:** Tự suy luận bối cảnh để chèn `[Image]` hoặc `[Video]` thành dòng độc lập, kèm Alt text chứa từ khóa chính.
- **Siêu dữ liệu:** Tự động sinh Meta Title (<60 ký tự, chứa Số + Keyword + Power Words), Meta Description (<160 ký tự) và URL Slug không dấu.

### 4.5 Tự kiểm duyệt (Self-Audit)

Kết thúc mỗi bài viết bằng bảng báo cáo, tự đánh giá: chất lượng nội dung, độ tự nhiên văn phong, độ dài, và các tiêu chí Rank Math đã đạt được.

### 4.6 Ba Option xuất bài

| Option | Mô tả |
| :--- | :--- |
| **Option 1** | Hướng dẫn Dàn ý — chỉ xuất H1-H3 + Meta Data |
| **Option 2** | Viết bài trực tiếp — hiển thị theo form Báo cáo thực thi |
| **Option 3** | Xuất Raw Markdown — bọc trong code block để copy dễ dàng vào CMS |

---

## 5. Bảng Kế hoạch 13 Cột

Đây là "ngôn ngữ chung" duy nhất giữa hai Agent:

| Cột | Tên | Ngôn ngữ | Đặc tả |
| :---: | :--- | :--- | :--- |
| 1 | Tháng/Năm | — | Mốc thời gian |
| 2 | Tuần - Bài | — | Tiến độ (VD: W1-B1) |
| 3 | Topic Cluster - Loại trang | Mục tiêu | Dùng dấu `-` ngăn cách |
| 4 | Danh mục | Mục tiêu | Chuyên mục trên website |
| 5 | Tiêu đề | Mục tiêu | Tối ưu CTR tự nhiên |
| 6 | **Keyword chính** | Mục tiêu | Cụm lõi 2-5 từ, không dấu câu |
| 7 | Keyword phụ | Mục tiêu | LSI, cách nhau bằng `,` |
| 8 | Funnel | Tiếng Việt | TOFU / MOFU / BOFU |
| 9 | CTA | Tiếng Việt | Lời kêu gọi hành động |
| 10 | Link | Tiếng Việt | ≥2 Internal + 1 External; cách nhau `;` |
| 11 | Media | Tiếng Việt | Cú pháp: `[Hx] Tên phần -> Số + Loại` |
| 12 | Yêu cầu Kiến thức | Tiếng Việt | Nguồn E-E-A-T; cách nhau `;` |
| 13 | **Hướng dẫn triển khai** | Tiếng Việt | Câu văn mẫu chứa từ khóa dài đầy đủ ngữ nghĩa |

> ⚠️ **Kỷ luật thép:** Tuyệt đối không xuống dòng trong ô. Dùng `;` phân cách nhiều mục (riêng Cột 7 dùng `,`).

---

## 6. Hướng dẫn Sử dụng

### Bước 1 — Khởi tạo Master Agent
Copy nội dung `SEO-MASTER-AGENT.md` vào AI chatbot (Gemini, ChatGPT, Claude...) dưới dạng System Prompt. Agent sẽ hỏi bạn muốn:
1. Lên Chiến lược SEO dài hạn (GĐ 1-3)
2. Xuất Kế hoạch nội dung cho tháng X (GĐ 4-6)
3. Chạy Quick Plan

### Bước 2 — Hoạch định chiến lược
Cung cấp: URL website, Thị trường + Ngôn ngữ, Sản phẩm/Ngành, Timeline (tùy chọn). Duyệt qua từng giai đoạn (🛑) đến khi nhận **Bảng KH 13 cột**.

### Bước 3 — Khởi tạo Copywriter Agent
Copy nội dung `COPYWRITER-AGENT.md` vào phiên chat mới. Cung cấp: (1) URL đích, (2) Ngôn ngữ, (3) 1 dòng dữ liệu từ Bảng 13 cột, (4) Bảng Internal Link (nếu có).

### Bước 4 — Nhận bài viết
Chọn 1 trong 3 Option xuất bài → Nhận Báo cáo thực thi hoàn chỉnh kèm Self-Audit.

> 💡 **Mẹo:** Dùng **Option 3 (Raw Markdown)** để copy nhanh vào WordPress/CMS.

---

## 7. Cấu trúc Dự án

```text
seo-agent-skills/
├── README.md               # Tài liệu tổng quan (file này)
├── SEO-MASTER-AGENT.md     # Prompt cho Agent Chiến lược (Strategist)
└── COPYWRITER-AGENT.md     # Prompt cho Agent Thực thi (Executor)
```

---

© 2026 **SaoLabs** — AI for SEO Excellence.
