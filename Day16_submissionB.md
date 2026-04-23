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
> **Giải pháp:** Một 'Tax Engine' sử dụng AI để đối soát đa nguồn thu nhập (Upwork, Paypal, Bank), tự động hóa việc làm sạch dữ liệu và tạo file quyết toán (XML) chuẩn 100%, giúp freelancer nộp thuế chỉ trong 3 phút thay vì 3 ngày.

---

## 2. Customer / Segment Card

- **Segment name:** Design freelancer (Global platforms focused)
- **Operational context:** Nhận thu nhập ngoại tệ từ các nền tảng (Upwork, Fiverr, Adobe Stock) về ví điện tử hoặc bank VN, phải tự đối soát phí platform và tỷ giá để khai thuế.
- **Recurring workflow:** Quyết toán thuế TNCN theo tháng/quý và quyết toán năm khi có nhiều nguồn thu nhập.
- **Pain moment:** Sợ hãi khi nhận được thông báo rà soát từ cục thuế vì không biết giải trình các khoản phí platform đã trừ như thế nào.
- **Why now:** Thuế Việt Nam đang tăng cường rà soát dòng tiền từ nước ngoài và các nền tảng số xuyên biên giới.
- **Access path:** Hợp tác với các cộng đồng Designer lớn và cung cấp công cụ kiểm tra "Sức khỏe tuân thủ thuế" miễn phí.

One-sentence description:
> Những người freelancer designer làm việc trên các nền tảng Global đang gặp khó khăn trong việc đối soát doanh thu thực tế và cần giải pháp chuẩn hóa dữ liệu thuế tự động.

---

## 3. Need Map (2–3 needs)

### Need #1 (priority)
- **Statement (JTBD):** Khi design freelancer đã hoàn thành nhiều job trên Global platforms, tôi muốn tự động bóc tách doanh thu net (sau khi trừ phí platform) sang tờ khai VN, để tôi có thể nộp thuế đúng mà không cần biết nghiệp vụ kế toán phức tạp.
- **Current workaround:** Tự tính tay trên Excel hoặc thuê kế toán ngoài (nhưng kế toán thường không hiểu phí platform).
- **Pain signal:** Sai lệch số liệu giữa tiền thực nhận về Bank và tiền ghi trên Invoice gốc của platform.
- **Evidence / proxy evidence:** Các thread thảo luận về "cách tính thuế khi làm Upwork" luôn nhận được tương tác cao nhất trong các group freelancer.
- **Why underserved:** Kế toán truyền thống thường chỉ xử lý hóa đơn nội địa, thiếu kiến thức về dòng tiền Global Gig Economy.

### Need #2
- **Statement (JTBD):** Khi quy định thuế thay đổi hoặc thu nhập của tôi chạm ngưỡng mới, tôi muốn được cảnh báo sớm về các nghĩa vụ pháp lý phát sinh, để tôi chủ động kế hoạch tài chính và tránh các khoản phạt truy thu bất ngờ.
- **Current workaround:** Chờ đến khi bị cục thuế gọi tên hoặc hỏi thăm đồng nghiệp.
- **Pain signal:** "Tê liệt hành động" vì không biết mình đang ở trạng thái tuân thủ hay vi phạm pháp luật.
- **Evidence / proxy evidence:** Tâm lý "thà trốn còn hơn khai" xuất phát từ việc không biết khai thế nào cho đúng và sợ bị phạt thêm.
- **Why underserved:** Chưa có công cụ nào cung cấp tính năng "Audit-ready Monitoring" liên tục cho cá nhân tại VN.

---

## 4. Strategy Statement

For **Design Freelancer làm việc trên các nền tảng Global**,
who struggle with **việc đối soát doanh thu thực tế (net) và phí trung gian khi khai thuế tại VN**,
our product helps them **tối ưu số thuế phải nộp và đảm bảo tính tuân thủ 100%**
through **công cụ Agentic-Tax tự động bóc tách doanh thu và tạo tờ khai XML chuẩn hóa**,
unlike **việc thuê kế toán ngoài (chậm, tốn kém, rò rỉ thông tin) hoặc tự mò mẫm (dễ sai sót)**,
because we can leverage **thuật toán đối soát dòng tiền đa quốc gia và tính bảo mật vượt trội của mô hình xử lý dữ liệu AI cục bộ**.

---

## 5. Moat Hypothesis

**Moat mechanism:** Cross-Border Reconciliation Logic (Càng nhiều case xử lý, thuật toán đối soát phí và tỷ giá càng chính xác).

If we deploy **50** times in **Global Design context**, the following improve:
1. **Precision:** Khả năng tự động nhận diện và phân loại các loại phí ẩn (Platform fees, Withdrawal fees) đạt độ chính xác tương đương chuyên gia.
2. **Speed to Compliance:** Thời gian từ lúc upload PDF/Excel đến lúc có file XML nộp thuế giảm xuống dưới 1 phút.
3. **Legal Edge:** Hệ thống RAG được cập nhật các kịch bản giải trình thuế thực tế từ hàng trăm trường hợp tương tự.

Why competitors cannot easily replicate this:
> Thuật toán đối soát dòng tiền Global-to-Local là một "black box" về nghiệp vụ cần sự kết hợp giữa kỹ thuật AI và hiểu biết sâu về quy trình thanh toán quốc tế. Các phần mềm kế toán đại trà khó có thể tinh chỉnh sâu cho ngách freelancer này.

---

## 6. Initial TAM / SAM / SOM view

| Layer | Estimate | Key assumptions | Confidence |
|---|---|---|---|
| TAM | Cá nhân kinh doanh Gig economy tại VN | Xu hướng làm việc remote/global tăng mạnh. | Medium |
| SAM | Freelancer nhận thu nhập từ các nền tảng quốc tế (Design, IT, Content) | Nhóm này có dòng tiền phức tạp nhất và nhu cầu nộp thuế cao nhất để minh bạch tài chính. | High |
| SOM | 10-15% freelancer trong các group cộng đồng Design lớn | Có thể chuyển đổi nhanh qua các chiến dịch "Health-check" miễn phí. | Medium |

**Top 3 unknowns requiring further research:**
1. Khả năng tích hợp kỹ thuật (hoặc hướng dẫn người dùng) để nộp file XML lên iCanhan mượt mà nhất.
2. Mức độ chấp nhận của cơ quan thuế đối với các bảng kê đối soát do AI tạo ra.
3. Giải pháp bảo mật "Zero-knowledge" để freelancer yên tâm cung cấp dữ liệu thu nhập.

**Judgment:**
- [x] Worth pursuing now
- [ ] Worth pursuing but not now (need to validate [...] first)
- [ ] Not worth pursuing as currently framed

---

## 7. Positioning Note (2 sentences)

**What we are:**
> Là công cụ "Audit-ready preparation" giúp freelancer chuẩn hóa dữ liệu thu nhập quốc tế thành hồ sơ thuế hợp lệ chỉ trong vài phút.

**What we are not / not yet:**
> Chúng tôi không thay thế trách nhiệm pháp lý cá nhân và không phải là cơ quan nộp thuế; chúng tôi là cầu nối kỹ thuật giúp việc tuân thủ trở nên dễ dàng.

---

## 8. Self-assessment before Day 17

Trong 6 mắt xích (Idea → Customer → Need → Strategy → Moat → Market Size), mắt xích nào team đang yếu nhất?

> **Strategy (Tích hợp & Niềm tin):** Cần làm rõ quy trình "Last-mile" để người dùng không cảm thấy bị bỏ rơi sau khi đã có file XML nhưng không biết bấm Submit thế nào.

Open questions chúng tôi muốn khám phá thêm ở Day 17:
1. Làm sao để xây dựng giải pháp bảo mật dữ liệu khiến người dùng tin tưởng 100%?
2. Có thể tự động bóc tách dữ liệu trực tiếp từ tài khoản ngân hàng (API/Statement) hay chỉ dừng lại ở Invoice?
3. Mô hình thu phí nào (Sub vs Transaction) phù hợp nhất với tâm lý "tiết kiệm" của freelancer?
