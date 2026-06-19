# AI_WORKFLOW_FOR_BS_THU_v1.1

**Phiên bản:** 1.1  
**Mục tiêu:** Chuẩn hóa cách dùng AI trong dự án truyền thông Bác sĩ Thu để nghiên cứu, lên ý tưởng, viết nội dung, kiểm duyệt và tái sử dụng.

---

# 1. Vai trò của AI trong dự án

AI không thay thế bác sĩ.

AI hỗ trợ:

- Tổ chức ý tưởng.
- Viết nháp.
- Gợi ý hook.
- Chuyển bài dài thành video.
- Chuyển video thành bài dài.
- Kiểm tra tone và safety.
- Tái sử dụng nội dung.
- Phân tích hiệu quả.

Bác sĩ Thu vẫn cần duyệt:

- Chuyên môn.
- Giọng nói thật.
- Ranh giới y khoa.
- Tính phù hợp với ca bệnh thực tế.

---

# 2. Bộ chat nên có trong Project

## Chat 1 — Brand Strategy
Dùng cho:
- Định vị.
- Chân dung khách hàng.
- Chiến lược kênh.
- Kế hoạch 3–6–12 tháng.

## Chat 2 — Content Pillars
Dùng cho:
- Lên lịch 7 ngày/30 ngày.
- Tạo series.
- Chọn góc tiếp cận.

## Chat 3 — Scripts
Dùng cho:
- Full Script.
- Teleprompter.
- Cue Card.
- Caption.
- Text overlay.

## Chat 4 — Facebook Long-form
Dùng cho:
- Bài dài.
- Bài phân tích.
- Case ẩn danh.
- Doctor POV dài.

## Chat 5 — Medical Safety Review
Dùng cho:
- Kiểm tra cam kết quá mức.
- Kiểm tra chẩn đoán online.
- Kiểm tra phác đồ/thông số.
- Làm mềm câu chữ.

## Chat 6 — Performance & Repurpose
Dùng cho:
- Phân tích chỉ số.
- Tái sử dụng nội dung thắng.
- Tạo biến thể hook.

---

# 3. Prompt tạo ý tưởng 30 ngày

```text
Dựa trên toàn bộ tài liệu trong Project Bác Sĩ Thu - Truyền Thông, hãy đề xuất lịch nội dung 30 ngày cho thương hiệu cá nhân Bác sĩ Thu.

Yêu cầu:
- Ưu tiên xây trust và authority, không bán hàng lộ.
- Mỗi ngày có 1 ý tưởng video ngắn.
- Mỗi tuần có 1 bài Facebook dài.
- Có tỷ lệ cân bằng:
  1. Mụn — thâm — sẹo
  2. Nám/sắc tố
  3. Laser an toàn
  4. Đỏ da/PDL
  5. Bạch biến/bớt
  6. Chăm sóc sau thủ thuật
  7. Da và Cuộc Sống
  8. Doctor POV

Mỗi ý tưởng gồm:
- Chủ đề
- Người xem
- Nỗi đau/cảm xúc
- Hiểu lầm
- Hook emotion-first
- Góc nhìn bác sĩ
- CTA an toàn
- Format phù hợp
```

---

# 4. Prompt viết video 3 tầng

```text
Viết kịch bản video ngắn cho Bác sĩ Thu với chủ đề:

[Chủ đề]

Yêu cầu:
- Thời lượng 45–60 giây.
- Bác sĩ nói trực tiếp trước camera.
- Không bắt đầu bằng định nghĩa bệnh nếu có thể bắt đầu bằng tình huống đời sống.
- Người xem phải cảm thấy "Bác sĩ hiểu mình" trước khi cảm thấy "Bác sĩ hiểu bệnh".
- Không cam kết khỏi 100%.
- Không bán hàng lộ.
- Không đưa phác đồ/thông số nội bộ.
- CTA an toàn.

Cấu trúc đầu ra:
1. Insight bệnh nhân
2. Full Script
3. Prompt Teleprompter 100–120 từ
4. Cue Card gạch đầu dòng
5. Text overlay
6. Caption
7. Gợi ý cảnh quay
8. Lưu ý kiểm duyệt y khoa
```

---

# 5. Prompt viết Facebook long-form

```text
Viết bài Facebook long-form cho Bác sĩ Thu về chủ đề:

[Chủ đề]

Yêu cầu:
- Mở bài bằng tình huống đời sống hoặc cảm xúc bệnh nhân.
- Sau đó mới giải thích chuyên môn.
- Giọng văn ấm áp, rõ ràng, có góc nhìn bác sĩ.
- Không quảng cáo lộ.
- Không cam kết khỏi 100%.
- Không đưa phác đồ/thông số nội bộ.
- Có CTA an toàn cuối bài.

Cấu trúc:
1. Tình huống bệnh nhân thường gặp
2. Cảm xúc/nỗi lo phía sau
3. Góc nhìn bác sĩ
4. Giải thích bản chất vấn đề
5. Người bệnh nên làm gì
6. CTA an toàn
```

---

# 6. Prompt kiểm duyệt an toàn

```text
Hãy kiểm tra nội dung dưới đây theo tiêu chuẩn truyền thông y khoa an toàn cho thương hiệu cá nhân Bác sĩ Thu.

Nội dung:
[Dán nội dung]

Kiểm tra:
1. Có câu nào cam kết quá mức không?
2. Có câu nào dễ bị hiểu là chẩn đoán online không?
3. Có tiết lộ phác đồ, thông số, liều lượng hoặc quy trình nội bộ không?
4. Có quảng cáo lộ quá không?
5. Có gây sợ hãi quá mức không?
6. Có hạ thấp bác sĩ/phòng khám khác không?
7. CTA đã an toàn chưa?
8. Đề xuất bản chỉnh sửa tự nhiên hơn.

Giữ giọng văn gần gũi, không làm nội dung quá khô cứng.
```

---

# 7. Prompt tái sử dụng nội dung

```text
Dưới đây là một video/bài viết đã đăng:

[Nội dung]

Chỉ số:
- View:
- Like:
- Comment:
- Share:
- Save:
- Inbox:
- Ghi chú:

Hãy phân tích:
1. Vì sao nội dung này hiệu quả/chưa hiệu quả?
2. Hook có đủ mạnh không?
3. Insight bệnh nhân có rõ không?
4. Có đúng định vị Bác sĩ Thu không?
5. Có thể tái sử dụng thành nội dung nào?
6. Đề xuất:
   - 5 hook mới
   - 3 video follow-up
   - 1 bài Facebook dài
   - 1 carousel outline
   - 3 câu hỏi story
```

---

# 8. Prompt tạo Doctor POV

```text
Tạo 10 ý tưởng Doctor POV cho Bác sĩ Thu về chủ đề:

[Chủ đề]

Yêu cầu:
- Mỗi ý tưởng phải thể hiện cách bác sĩ suy nghĩ, cân nhắc hoặc từ chối.
- Không bán hàng.
- Không cam kết kết quả.
- Có cảm xúc bệnh nhân.
- Có hook ngắn.
- Có CTA an toàn.

Đầu ra:
1. Hook
2. Tình huống bệnh nhân
3. Góc nhìn bác sĩ
4. Một câu giải thích y khoa
5. CTA
```

---

# 9. Prompt chuyển nội dung bệnh học sang emotion-first

```text
Hãy chuyển nội dung dưới đây từ kiểu "giải thích bệnh học" sang kiểu "emotion-first".

Nội dung gốc:
[Dán nội dung]

Yêu cầu:
- Không bắt đầu bằng định nghĩa.
- Mở đầu bằng tình huống đời sống thật.
- Gọi tên cảm xúc bệnh nhân.
- Sau đó mới giải thích y khoa.
- Giữ tone của Bác sĩ Thu: chuyên môn, ấm áp, điềm tĩnh.
- Không làm quá cảm xúc.
- Không cam kết kết quả.
```

---

# 10. Quy trình AI hàng tuần

## Thứ 2
AI lên 10 ý tưởng từ bình luận/câu hỏi.

## Thứ 3
Chấm điểm ý tưởng, chọn 3–5 chủ đề.

## Thứ 4
AI viết script 3 tầng.

## Thứ 5
Bác sĩ Thu duyệt, AI chỉnh tone.

## Thứ 6/7
Quay batch.

## Sau khi đăng
AI phân tích hiệu quả và đề xuất follow-up.

---

# 11. Quy tắc kiểm soát chất lượng AI

Không dùng trực tiếp nội dung AI nếu chưa kiểm tra:

- Chuyên môn.
- Claim.
- CTA.
- Tone.
- Ranh giới tư vấn cá nhân.
- Phù hợp hình ảnh Bác sĩ Thu.
