# Day 16 Submission — Team FreeTax AI

## Members
- Trần Khánh Bằng 2A202600458 
- Nguyễn Đức Mạnh 2A202600151 
- Nguyễn Bá Khánh 2A202600135 
- Hoàng Quang Thắng 2A202600069

---

## 1. Idea reframed

Original idea:
> Freelancer thường rơi vào trạng thái mệt mỏi khi đối mặt với thủ tục thuế vì ngôn ngữ luật khó hiểu và nỗi sợ bị phạt hành chính. Họ thà mất tiền thuê bên thứ ba hoặc "trốn" thuế (rủi ro cao) còn hơn tự làm.

Reframed as a product opportunity:
> **Tên dự án:** **FreeTax AI** – Trợ lý ảo chuyên biệt cho thuế Freelancer. 
> **Giải pháp:** Một nền tảng tập trung sử dụng AI để tự động hóa quy trình từ lúc nhận tiền (Invoice) đến khi có mã giao dịch nộp thuế thành công, kết hợp tư vấn luật dựa trên RAG.

---

## 2. Customer / Segment Card

- **Segment name:** Design freelancer
- **Operational context:** Phải khai thuế hàng tháng đối với từng khoản thu nhập và thường xuyên phải cập nhật các bộ luật mới phức tạp.
- **Recurring workflow:** Mỗi khi phát sinh thu nhập mới từ các nguồn local hoặc global đều phải thực hiện khai thuế.
- **Pain moment:** Bị cơ quan thuế phạt hành chính khi không khai hoặc khai sai, đồng thời gặp khó khăn trong việc thực hiện các thủ tục hoàn thuế.
- **Why now:** Bộ luật mới về thuế ở Việt Nam đang được siết chặt và thực hiện gắt gao hơn hẳn các năm trước.
- **Access path:** Cung cấp hệ thống hỗ trợ với chi phí tối ưu hơn nhiều so với việc thuê công ty luật hoặc kế toán riêng.

One-sentence description:
> Những người freelancer, designer làm việc tự do có nhiều nguồn thu nhập (Local & Global) đang gặp khó khăn trước các quy định thuế mới và cần giải pháp tự động hóa thủ tục minh bạch.

---

## 3. Need Map (2–3 needs)

### Need #1 (priority)
- **Statement (JTBD):** Khi design freelancer đã hoàn thành nhiều job, muốn tiết kiệm thời gian khai thuế, để có thể tập trung nhận thêm job khác và cải thiện thu nhập.
- **Current workaround:** Thuê công ty luật hoặc bên thứ 3 giải quyết thủ công.
- **Pain signal:** Tốn 2-3 ngày làm việc mỗi tháng, dễ sai sót thông tin, quy trình nộp tờ khai iCanhan không rõ ràng.
- **Evidence / proxy evidence:** Hàng loạt bài đăng hỏi đáp về thủ tục thuế trên các cộng đồng "Freelance Việt Nam", "Cộng đồng Designer".
- **Why underserved:** Chi phí thuê dịch vụ ngoài quá cao so với thu nhập cá nhân, dễ gặp rủi ro bị scam hoặc rò rỉ dữ liệu tài chính.

### Need #2
- **Statement (JTBD):** Khi đối mặt với các văn bản luật thuế mới khô khan, tôi muốn được giải đáp thắc mắc bằng ngôn ngữ bình dân, để hiểu rõ nghĩa vụ mà không bị "tê liệt hành động".
- **Current workaround:** Tự tra cứu trên mạng hoặc hỏi người quen (không đảm bảo tính chính xác).
- **Pain signal:** Nỗi sợ mơ hồ về pháp lý dẫn đến việc trì hoãn hoặc trốn thuế (rủi ro cao).
- **Evidence / proxy evidence:** Tâm lý chung "thà mất tiền thuê còn hơn tự làm" do ngôn ngữ luật quá khó hiểu.
- **Why underserved:** Chưa có công cụ AI chuyên biệt nào tại Việt Nam được huấn luyện sâu về luật thuế dành riêng cho cá nhân/Gig economy.

---

## 4. Strategy Statement

For **Design Freelancer với nhiều nguồn thu nhập**
who struggle with **việc khai thuế từ nhiều nguồn và luật thuế mới thay đổi liên tục**,
our product helps them **tiết kiệm thời gian, giảm sai sót và minh bạch hóa hồ sơ tài chính**
through **ứng dụng AI tự động điền tờ khai thuế mẫu 02/KK-TNCN và tư vấn luật trực tuyến**,
unlike **việc thuê công ty luật chi phí cao hoặc tự mò mẫm thủ công đầy rủi ro**,
because we can leverage **tốc độ phản hồi tức thì, chi phí cực thấp và khả năng cá nhân hóa cao dựa trên dữ liệu thu nhập đặc thù**.

---

## 5. Moat Hypothesis

**Moat mechanism:** Data compounding (Càng nhiều người dùng, AI càng hiểu sâu các loại invoice ngành Design).

If we deploy **50** times in **Design vertical**, the following improve:
1. **Personalization:** Hệ thống tự ghi nhớ các loại chi phí và nguồn thu đặc trưng để gợi ý khai báo chính xác hơn.
2. **Response time:** Quy trình xử lý invoice thành tờ khai XML được tối ưu hóa theo thời gian thực.
3. **Better answers:** RAG system được tinh chỉnh từ hàng nghìn câu hỏi thực tế của cộng đồng designer.

Why competitors cannot easily replicate this:
> Công cụ càng dùng càng trở nên cá nhân hóa theo luồng thu nhập của người dùng, tạo ra chi phí chuyển đổi (switching cost) cao. Đồng thời, bộ dữ liệu invoice đặc thù của ngành sáng tạo là rào cản lớn cho các bên làm kế toán tổng quát.

---

## 6. Initial TAM / SAM / SOM view

| Layer | Estimate | Key assumptions | Confidence |
|---|---|---|---|
| TAM | Toàn bộ cá nhân kinh doanh tự do (Gig economy) tại VN | Kinh tế Gig tăng trưởng mạnh, nhà nước siết chặt quản lý thuế cá nhân. | Medium |
| SAM | Freelancer lĩnh vực sáng tạo & công nghệ (Design, Dev, Content) | Nhóm này có trình độ số hóa cao, thu nhập đa dạng và nhạy bén với công nghệ AI. | High |
| SOM | 10-15% thị phần freelancer có nhu cầu thuế trong năm đầu | Tiếp cận hiệu quả qua các cộng đồng chuyên môn lớn và social media. | Medium |

**Top 3 unknowns requiring further research:**
1. Độ tin cậy của việc nộp file XML tự động lên cổng dịch vụ công của Tổng cục Thuế.
2. Khả năng bảo mật tuyệt đối dữ liệu thu nhập của người dùng để xây dựng Trust.
3. Mức độ chi trả (Willingness to pay) của freelancer cho gói dịch vụ định kỳ.

**Judgment:**
- [x] Worth pursuing now
- [ ] Worth pursuing but not now (need to validate [...] first)
- [ ] Not worth pursuing as currently framed

---

## 7. Positioning Note (2 sentences)

**What we are:**
> Là trợ lý ảo thông minh giúp freelancer tự động hóa quy trình khai thuế TNCN và giải đáp các thắc mắc pháp lý một cách nhanh chóng, chính xác.

**What we are not / not yet:**
> Chúng tôi không phải là cơ quan nhà nước và không hỗ trợ bất kỳ hành vi trốn thuế hay lách luật trái phép nào.

---

## 8. Self-assessment before Day 17

Trong 6 mắt xích (Idea → Customer → Need → Strategy → Moat → Market Size), mắt xích nào team đang yếu nhất?

> **Strategy (Chiến lược thâm nhập sâu):** Cần làm rõ hơn cách thức tích hợp kỹ thuật với hệ thống thuế điện tử hiện tại để đảm bảo trải nghiệm "seamless".

Open questions chúng tôi muốn khám phá thêm ở Day 17:
1. Làm sao để xây dựng niềm tin (Trust) tuyệt đối cho người dùng khi họ cung cấp dữ liệu thu nhập?
2. Quy trình nộp file XML lên iCanhan có thể tự động hóa đến mức nào bằng AI?
3. Cách thức xử lý các loại hóa đơn (Invoice) từ Global Platforms (Upwork, Fiverr) về thuế TNCN tại VN.
