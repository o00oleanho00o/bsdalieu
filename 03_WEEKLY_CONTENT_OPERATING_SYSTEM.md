# 03 - Hệ thống vận hành nội dung hàng tuần

## 1. Mục tiêu

Mỗi tuần, Anh cung cấp input từ Bác sĩ Thu. AI sẽ biến input đó thành:

- Lịch đăng Facebook cá nhân, TikTok, YouTube Shorts.
- Chủ đề dự trữ cho YouTube long-form.
- Script video ngắn 3 tầng.
- Bài Facebook/case diary nếu có case thật.
- Kế hoạch quay batch.
- KPI cần theo dõi sau 7 ngày.

Không làm theo kiểu “hôm nay đăng gì”, mà làm theo câu hỏi:

> **Tuần này Bác sĩ Thu cần được nhớ đến vì điều gì?**

---

## 2. Input hàng tuần cần lấy từ Bác sĩ Thu

Bác sĩ Thu không cần viết content hoàn chỉnh. Chỉ cần gửi input thô theo form:

```text
Tuần: [ngày/tháng]

1. Case nhớ nhất trong tuần:
- Case 1:
  - Vấn đề da:
  - Tuổi/nhóm người bệnh:
  - Câu chuyện/ngữ cảnh:
  - Điều phụ huynh/bệnh nhân lo nhất:
  - Bác sĩ đã giải thích điều gì:
  - Có hình ảnh/video không:
  - Consent: Có/Không/Chưa rõ
  - Mức độ có thể chia sẻ: công khai/ẩn danh/chỉ làm insight

2. Câu hỏi thật bệnh nhân/phụ huynh hỏi:
- Câu hỏi 1:
- Câu hỏi 2:
- Câu hỏi 3:

3. Hiểu lầm gặp nhiều:
- Hiểu lầm 1:
- Hiểu lầm 2:

4. Chủ đề bác sĩ muốn nói:
- Chủ đề:
- Vì sao muốn nói:

5. Ràng buộc tuần này:
- Có quay được không:
- Quay ngày nào:
- Có ảnh/case nào không được dùng không:
```

---

## 3. Quy trình xử lý input

```text
Input thô
↓
Ẩn danh và lọc safety
↓
Phân loại pillar
↓
Chấm điểm ưu tiên
↓
Chọn 3–5 chủ đề tuần
↓
Phân bổ nền tảng
↓
Viết nội dung
↓
Lập shotlist quay batch
↓
Đăng và theo dõi KPI
↓
Rút kinh nghiệm sau 7 ngày
```

---

## 4. Phân loại input

| Loại input | Chuyển thành gì? |
|---|---|
| Case thật có cảm xúc mạnh | Facebook case diary + TikTok Doctor POV + YouTube Shorts |
| Câu hỏi thật | TikTok FAQ + YouTube Shorts + Facebook caption ngắn |
| Hiểu lầm phổ biến | Myth-busting video + bài Facebook giải thích |
| Case có hành trình dài | Series Facebook + seed YouTube long-form |
| Comment chất lượng | Video reply + FAQ bank |
| Chủ đề chuyên môn sâu | YouTube long-form outline |

---

## 5. Thang điểm chọn ý tưởng

Chấm theo 100 điểm:

| Tiêu chí | Điểm |
|---|---:|
| Nỗi đau/cảm xúc rõ | 20 |
| Có insight thật/case thật | 15 |
| Giá trị chuyên môn | 20 |
| Có Doctor POV | 15 |
| Hợp định vị Bác sĩ Thu | 15 |
| Dễ sản xuất trong tuần | 10 |
| An toàn truyền thông/y khoa | 5 |
| **Tổng** | **100** |

Quyết định:

| Điểm | Hành động |
|---:|---|
| 85–100 | Ưu tiên quay/đăng ngay |
| 70–84 | Làm được, cần chỉnh hook/tone |
| 55–69 | Để sau hoặc đổi angle |
| <55 | Bỏ hoặc lưu kho |

Điểm trừ đặc biệt:

| Vấn đề | Trừ |
|---|---:|
| Nội dung chỉ quay máy/thủ thuật, không có bác sĩ giải thích | -15 |
| Pema/logo/dịch vụ là nhân vật chính | -10 |
| Dùng từ “bay màu”, “sạch hoàn toàn”, “đẹp kịp Tết” | -10 |
| Before/after thiếu kỳ vọng thực tế | -10 |
| Hình ảnh trẻ em/case nhạy cảm thiếu privacy | -15 |

---

## 6. Output hàng tuần AI cần trả cho Anh

Mỗi tuần, sau khi nhận input, AI cần xuất theo cấu trúc:

```text
1. Nhận định nhanh tuần này
- Tài sản nội dung mạnh nhất:
- Chủ đề nên ưu tiên:
- Chủ đề nên để sau:
- Rủi ro safety cần chú ý:

2. Bảng chấm điểm ý tưởng
- Chủ đề
- Pillar
- Người xem
- Nỗi đau
- Doctor POV
- Điểm /100
- Quyết định

3. Lịch đăng 7 ngày
- Ngày
- Nền tảng
- Chủ đề
- Format
- Hook
- CTA
- Ghi chú quay/dựng

4. Gói nội dung chi tiết
- Script video ngắn 3 tầng
- Caption TikTok/Shorts
- Bài Facebook nếu có
- Metadata YouTube Shorts

5. Kế hoạch quay batch
- Shotlist
- Bối cảnh
- Trang phục
- Props/hình ảnh minh họa
- Ghi chú âm thanh/ánh sáng

6. KPI theo dõi sau 7 ngày
- Facebook
- TikTok
- YouTube Shorts
- Long-form seed
```

---

## 7. Lịch làm việc tuần mẫu

| Ngày | Việc | Người phụ trách |
|---|---|---|
| Thứ 2 | Nhận input từ Bác sĩ Thu, lọc safety, chọn chủ đề | Anh + AI |
| Thứ 3 | Viết script 3 tầng, caption, bài Facebook | AI |
| Thứ 4 | Bác sĩ Thu duyệt chuyên môn, chỉnh giọng nói | Bác sĩ Thu + Anh |
| Thứ 5 | Quay batch 3–5 video | Anh + Bác sĩ Thu |
| Thứ 6 | Dựng, đóng gói metadata, lên lịch đăng | Anh/Editor + AI |
| Thứ 7 | Đăng TikTok/Shorts, theo dõi phản hồi sớm | Anh |
| Chủ nhật | Ghi lại comment/câu hỏi mới, chuẩn bị tuần sau | Anh + AI |

---

## 8. Lịch đăng tuần mẫu

| Ngày | Facebook cá nhân | TikTok | YouTube Shorts | Ghi chú |
|---|---|---|---|---|
| Thứ 2 | Bài case diary/Doctor POV |  |  | Xây trust đầu tuần |
| Thứ 3 |  | Video FAQ 1 |  | Test hook |
| Thứ 4 | Bài ngắn kéo lại chủ đề |  | Shorts từ video FAQ 1 | Tối ưu title search |
| Thứ 5 |  | Video Doctor POV |  | Một ý chính |
| Thứ 6 | Bài FAQ/caption dài |  | Shorts từ Doctor POV | Đẩy lưu/share |
| Thứ 7 |  | Video myth-busting/comment reply |  | Lấy comment tuần sau |
| Chủ nhật | Bài nhẹ đời sống nghề nếu có |  |  | Không bắt buộc |

---

## 9. Quy tắc chọn chủ đề cho YouTube long-form

Một chủ đề được đưa vào YouTube long-form khi đạt ít nhất 2 trong 4 điều kiện:

1. Có nhiều câu hỏi thật lặp lại.
2. Có video ngắn retention/share/comment tốt.
3. Có case/hành trình đủ chiều sâu nhưng vẫn an toàn privacy.
4. Có giá trị authority lâu dài, người xem có thể tìm lại sau 6–12 tháng.

Ví dụ đạt chuẩn:

- “Bớt Ota và bớt rượu vang ở trẻ: phụ huynh cần hiểu gì?”
- “Mụn — thâm — sẹo: nên xử lý theo thứ tự nào?”
- “Laser có làm da mỏng không?”
- “Nám vì sao không nên hứa sạch vĩnh viễn?”

---

## 10. Báo cáo sau đăng 7 ngày

Mỗi nội dung cần ghi lại:

| Trường | Nội dung |
|---|---|
| Ngày đăng | |
| Nền tảng | |
| Chủ đề | |
| Pillar | |
| Hook | |
| View/reach | |
| Like | |
| Comment | |
| Share | |
| Save | |
| Follow/subscriber tăng | |
| Inbox/câu hỏi thật | |
| Nhận xét chất lượng | |
| Có nên repurpose không | Có/Không |
| Follow-up nên làm | |
