# 🚀 SEO Agent Skills — by SaoLabs

> Hệ thống AI Agent chuyên biệt cho SEO, kiến trúc **hai tầng phân vai** (Strategist → Executor), tự động hóa toàn bộ quy trình từ hoạch định chiến lược Data-Driven đến thực thi nội dung chuẩn SEO với văn phong tự nhiên và cung cấp Information Gain sâu sắc.

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
2. **Information Gain & E-E-A-T** — Cung cấp thông tin giá trị mới, bảo chứng sự thật từ nguồn uy tín.
3. **Kỹ thuật SEO Tuyệt đối** — Tối ưu AEO (AI Search), Topic Cluster chuẩn chỉnh, thiết lập cấu trúc liên kết và media thông minh.

---

## 2. Kiến trúc Hai tầng

| Tầng | Agent | Vai trò | Chức năng |
| :--- | :--- | :--- | :--- |
| **Strategist** | SEO Master Agent | SEO Director | Lên Báo cáo chiến lược, nghiên cứu Content Gap, thiết lập Bảng Kế hoạch 13 cột |
| **Executor** | Copywriter Agent | Senior Copywriter | Nhận dữ liệu Bảng 13 cột để viết bài, chèn media/link, tự đánh giá nhị phân |

**Cơ chế bảo vệ ngữ cảnh:** Mỗi Agent hoạt động trong một luồng (phiên chat) riêng biệt để chống "ảo giác" (hallucination) và rò rỉ ngữ cảnh (context bleeding).

---

## 3. SEO Master Agent — Chuyên gia Hoạch định

> **Prompt:** [`SEO-MASTER-AGENT.md`](./SEO-MASTER-AGENT.md)

SEO Master Agent được trang bị tư duy của một **Giám đốc SEO**, phân tích dữ liệu đa ngôn ngữ để xuất ra Báo cáo Tổng thể hoặc Kế hoạch Tháng chi tiết.

### 3.1 Quy trình 5 Bước Chọn Từ Khóa Tối Ưu

Hệ thống tuân thủ một quy trình tư duy nghiêm ngặt để chọn từ khóa:
1. Quét bối cảnh & thị trường.
2. Giải phẫu đối thủ trực tiếp & phân tích top ranking.
3. Phân tích Content Gap (lỗ hổng nội dung).
4. Lọc & loại trừ tuyệt đối từ khóa chứa Brand đối thủ / sai Intent.
5. Chốt cụm từ khóa (2-5 từ). **⚠️ Nguyên tắc tối thượng:** Bảo toàn ngữ nghĩa. Nếu cắt gọt làm sai nghĩa, giữ nguyên gốc và lưu trữ phiên bản dài vào dạng "Câu văn mẫu" (Cột 13).

### 3.2 Kỷ Luật Bảng Định Dạng Thép

Nhằm tương thích 100% khi copy sang Google Sheets, Master Agent bị khóa chặt bởi các lệnh cấm kỵ:
- **Cấm xuống dòng** bên trong ô.
- **Cấm tự động đánh số** trước tên cột.
- **Cấm dùng ký tự pipe (`|`)** trong nội dung.
- Phải **hiển thị bảng Markdown trực tiếp**, không được bọc trong code block.

### 3.3 Cấu Trúc Vận Hành (3 Chế Độ)

Master Agent tự động chuyển đổi giữa 3 chế độ tùy thuộc lệnh của người dùng:

- **Chế độ A (Trò chuyện mặc định):** Giải đáp thắc mắc, phân tích NLP không xuất bảng.
- **Chế độ B (Option 1 - Chiến lược Tổng thể):** Xuất Báo cáo gồm Phân tích thị trường, Chân dung khách hàng, SWOT (Nội tại & Đối thủ), Content Gap, cùng **Bảng Roadmap 4 Phase** và danh sách 40 từ khóa tham khảo.
- **Chế độ C (Option 2 - Kế hoạch Nội dung Tháng):** Kế thừa chiến lược dài hạn để xuất ra 4 Bảng thực thi: Topic Matrix, Bảng 13 Cột, Bảng Gợi ý Link, Bảng Brief Tài nguyên.

---

## 4. Copywriter Agent — Cỗ máy Thực thi

> **Prompt:** [`COPYWRITER-AGENT.md`](./COPYWRITER-AGENT.md)

Copywriter Agent là **thợ xây bậc thầy** chuyên xử lý ngôn ngữ tự nhiên, biến dữ liệu thô thành bài viết chuẩn SEO và giàu Information Gain.

### 4.1 Làm sạch bộ nhớ & Tương tác

Để tránh lỗi "râu ông nọ cắm cằm bà kia", Copywriter Agent chỉ thực thi **duy nhất 1 bài viết/lần** và sẽ dọn sạch trí nhớ bài viết cũ trước khi nhận yêu cầu mới.

Cung cấp 3 Option xuất file:
- **Option 1:** Dàn ý (H1-H3 + Meta).
- **Option 2:** Viết bài trực tiếp (Hiển thị văn bản đọc trực tiếp).
- **Option 3:** Xuất Raw Markdown (Bọc code block copy vào CMS).

### 4.2 Tối ưu AEO & Kỹ thuật SEO

- **AEO (AI Search / SGE / Gemini):** Tự động tạo cấu trúc **Answer-first 40-80 từ** ngay dưới H1 để nhắm mục tiêu AI Overview.
- **Lắp ghép từ khóa dị/dài:** Sử dụng các "Câu văn mẫu" từ Cột 13 của Master Agent để tích hợp các cụm từ khó nhằn vào bài mà không làm sượng ngữ pháp tiếng Việt.
- **Kỷ luật External Deep Link:** Mọi External Link tự sinh bắt buộc phải trỏ sâu (Deep Link) vào các tài liệu chuyên ngành, **tuyệt đối không trỏ về trang chủ**. URL trần phải được ẩn dưới định dạng `[Anchor text](URL đích)`.
- **Kỷ luật Media Placeholder:** Agent bắt buộc phải viết 1-2 câu "chuyển ý" dẫn dắt trước khi chèn ảnh/video, đồng thời ghi lại **chính xác mô tả chi tiết** để team Design nắm được ý đồ thiết kế.

### 4.3 Self-Checklist Nhị Phân

Kết thúc mỗi bài viết, Agent tự chạy **Checklist Nhị phân 6 tiêu chí (Có/Không)** để đảm bảo đạt chuẩn SEO:
1. Keyword ở 50 chữ đầu (Answer-first)?
2. Keyword trong H2/H3?
3. Xử lý "từ khóa dị" bằng câu mẫu Cột 13?
4. In đậm keyword phụ?
5. Ẩn URL trần thành Deep Link chuẩn Markdown?
6. Có câu dẫn dắt trước thẻ Media Placeholder?

---

## 5. Bảng Kế hoạch 13 Cột

Đây là "ngôn ngữ chung" duy nhất giữa hai Agent (Tuân thủ kỷ luật Bảng Thép & Đa ngôn ngữ):

| Cột | Tên | Ngôn ngữ | Đặc tả |
| :---: | :--- | :--- | :--- |
| 1 | Tháng/Năm | Tiếng Việt | Mốc thời gian |
| 2 | Tuần - Bài | Tiếng Việt | Tiến độ (VD: W1-B1) |
| 3 | Topic Cluster - Loại trang | Mục tiêu | Dùng dấu `-` ngăn cách |
| 4 | Danh mục | Mục tiêu | Chuyên mục trên website |
| 5 | Tiêu đề | Mục tiêu | Tối ưu CTR tự nhiên |
| 6 | **Keyword chính** | Mục tiêu | Cụm lõi 2-5 từ, không dấu câu |
| 7 | Keyword phụ | Mục tiêu | LSI, cách nhau bằng `,` |
| 8 | Funnel | Tiếng Việt | TOFU / MOFU / BOFU |
| 9 | CTA | Tiếng Việt | Lời kêu gọi hành động |
| 10 | Link | Tiếng Việt | `Loại Link` và `Tên bài` ; Không chứa URL trần |
| 11 | Media | Tiếng Việt | Cú pháp: `[Hx] Tên phần -> Số lượng + Loại: [Mô tả chi tiết]` |
| 12 | Yêu cầu Kiến thức | Tiếng Việt | Nguồn E-E-A-T; Số liệu thô khách cấp |
| 13 | **Hướng dẫn triển khai** | Tiếng Việt | Câu văn mẫu chứa từ khóa dị đầy đủ ngữ nghĩa |

---

## 6. Hướng dẫn Sử dụng

### Bước 1 — Khởi tạo Master Agent
Copy nội dung `SEO-MASTER-AGENT.md` vào AI chatbot.
Cung cấp **đủ 4 thông tin cốt lõi**:
1. Thương hiệu.
2. Sản phẩm / Dịch vụ.
3. Ngôn ngữ / Thị trường nhắm tới.
4. Website (URL).
*(Nếu thiếu, Agent sẽ chặn lại và yêu cầu cung cấp thêm)*

### Bước 2 — Chọn Chế độ Hoạch định
Yêu cầu Agent chạy **Option 1** (Báo cáo Tổng thể) để vạch định chiến lược dài hạn, sau đó chạy **Option 2** để xuất Bảng Kế hoạch Nội dung 13 cột chi tiết cho tháng hiện tại.

### Bước 3 — Khởi tạo Copywriter Agent
Copy nội dung `COPYWRITER-AGENT.md` vào **một phiên chat mới hoàn toàn**.
Cung cấp 1 dòng dữ liệu của Bảng 13 cột + Bảng Link/Brief (nếu có).
Chọn hình thức xuất bài (Dàn ý / Viết trực tiếp / Raw Markdown).

### Bước 4 — Đánh giá & Publish
Kiểm tra chéo với Self-Checklist Nhị phân ở cuối bài viết trước khi đưa lên CMS.

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
