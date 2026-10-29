# WHEN NOBODY'S WATCHING — bản thiết kế 70 cụm (29/10/2026)

**Yêu cầu người dùng (29/10/2026):** dùng skill `viet-kich-ban-drama-phuong-tay`, nhịp dồn dập kiểu phim mì ăn liền, cho khán giả **người Mỹ gốc Phi**, dài **khoảng 35 phút**, nhiều cú ngoặt, thoại và hành động kịch tính; **không ẩn ý, dễ xem dễ hiểu, không lòng vòng**; áp `emotional-loop-framework-western-short-drama.md` (vòng M1–M6, S1–S13, R1–R10, nhịp 3 tập đảo nhỏ, 8–10 tập lộ lớn). Video mẫu: https://youtu.be/55-IE6JdYKM (60 phút, phim Trung "mẹ chồng tỷ phú giả nghèo").

**Hai lưu ý của người dùng:**
1. Giữ chủ đề **cải trang / lật thân phận** (CTR cao) nhưng đưa **cú ngoặt bất ngờ sớm hơn**: có nhân vật phát hiện sự thật giữa chừng, có kế hoạch đối phó ngầm.
2. **Cân bằng thắt nút – mở nút**: nhân vật phản ứng linh hoạt ở giữa phim, không dồn hết giải toả về cao trào cuối.

**Soát 29/10:** `_nguon_kb/soat.py` 0 lỗi (70 cụm, 35:00, 316 câu thoại, ≤ 12 từ/câu, 2–6 câu/cụm) · `content_filter.py --strict` 0 CẤM / 0 CẢNH BÁO / 0 THÔNG TIN.

**Cổng sản xuất:** 70 cụm × 30 giây = 35:00 · 23 tập (22 tập × 3 cụm + tập cuối 4 cụm) · 16:9 · Seedance qua tool Bigup · thoại tiếng Anh ASCII, ≤ 12 từ/câu, 3–6 câu/cụm · kể thẳng theo thời gian, không hồi tưởng, không chữ trên màn hình (luật dựng F13).

---

## 0. Video mẫu — học được gì, đổi gì

Đã đọc transcript tới phút 46/60 (trình duyệt đã đóng sau khi đọc).

| Video mẫu (Trung Quốc) | Giữ | Đổi trong phim này |
|---|---|---|
| Mẹ chồng chủ tịch giả bà già nghèo vào tiệm áo cưới thử con dâu tương lai | Cải trang thử lòng, bị sỉ nhục công khai | Salon tóc cao cấp của chính công ty bà (tóc = bản sắc người da đen), bà là nhà sáng lập hãng dưỡng tóc tỷ đô |
| Con dâu tương lai (khách VIP) gạt chân, làm rách váy, đòi 160.000 tệ | Gạt chân + đòi tiền vô lý | Gạt chân làm rơi bộ tóc giả 9.000 đô vào bồn gội, đòi 9.000 đô |
| Bà lên cơn tim; cô nhân viên tốt bụng cứu, bị đuổi | Người tốt cứu người lạ, mất việc | Cô thợ tết tóc kiêm CNA nhận ra hạ đường huyết, đưa nước cam |
| Bà gọi giám đốc tới, mua cả tiệm ghi doanh số cho cô gái, đuổi cửa hàng trưởng | Clapback sớm (phút 4) | Chánh văn phòng tới, lộ log tắt camera, đuổi quản lý, cô gái lên làm quản lý |
| Bí mật: cô gái mới là người hiến máu cứu con trai; con dâu cướp công | Công ơn bị cướp | Cô gái làm CPR cứu con trai ở giải chạy; con dâu cướp công và nổi tiếng nhờ câu chuyện đó |
| Tiệc đính hôn: con trai núp trên lầu xem, camera vạch mặt | Vạch mặt bằng bằng chứng | Bằng chứng là cuộc gọi 911 có giọng và tên cô gái — lộ ở **giữa phim** |
| Con dâu livestream bịa có thai, cổ phiếu rớt; mẹ giả vờ đồng ý | Phản đòn mạng + giả khuất phục | Giữ, rồi thêm 4 lớp: ảnh siêu âm song thai lấy từ blog, mẹ cô ta dùng tiền tống tiền mua nợ thuế nhà bà nội cô gái, quản lý cũ quay lại phe thiện, trợ lý livestream phản chủ |

**Ba chỗ làm khác hẳn MOTHER OF THE GROOM (phim gần nhất cùng mô-típ):** không đám cưới, không hắt nước, không sổ "ba cơ hội"; phản diện **biết sự thật từ phút 6** và đổi chiến thuật; nhân vật chính **biết thân phận bà từ đầu** (lộ ở phút 5).

---

## 1. Concept một trang

- **Tên phim:** WHEN NOBODY'S WATCHING
- **Logline:** Bà trùm hãng dưỡng tóc tỷ đô giả làm bà già nghèo để xem cô dâu tương lai của con trai đối xử ra sao khi không ai nhìn — và cô thợ tết tóc duy nhất ra tay giúp bà hoá ra chính là người đã cứu sống con trai bà, còn cô dâu kia đã cướp công suốt hai năm.
- **Câu poster (tiếng Anh):** *"She dressed like nobody to see who you really are."*
- **Câu thoại poster (cụm 66):** *"You were only kind when somebody was watching. Tonight, everybody was."*
- **Lời hứa hình ảnh:** bộ tóc giả 9.000 đô trôi trong bồn gội; bà tỷ phú ngồi bệt dưới sàn salon của chính mình; tấm séc ký tên Beverly Thornton nằm trong túi kẻ ác; chiếc nhẫn đính hôn lăn trên bàn ăn; dạ tiệc ven sông với màn hình LED phát lại từng lời nói dối; bà nội 77 tuổi đội mũ dạ tiệc ngồi trước cửa nhà mình bị thay khoá.
- **Thể loại:** Hidden Identity (chính) + Secret Savior / Stolen Credit (phụ) — framework G1 + S2 + R5.
- **Địa chỉ đời thực:** Prince George's County, Maryland (quận da đen giàu nhất nước Mỹ) + National Harbor, cuối tháng 4/2026, mùa đỗ quyên.

### 1.1 Bậc thang phản diện (mỗi bậc một loại receipt khác nhau)

| Bậc | Ai | Bị hạ ở | Receipt |
|---|---|---|---|
| 1 · Tay sai ngoài cùng | **Latasha** — quản lý Velour, xoá camera giúp Bianca | Cụm 8 (phút 4) — bị đuổi; cụm 46–48 quay sang phe thiện | Log hệ thống: camera tắt bằng tài khoản của chị ta 10 phút trước |
| 2 · Tay chân | **Tamia** — trợ lý quay phim của Bianca | Cụm 54 phản chủ (để livestream chạy) | Livestream đang bật |
| 3 · Người nhà phản diện | **Charlene** — mẹ Bianca, nợ một tay cho vay ở Suitland | Cụm 63–64, 67 | Sao kê chuyển khoản: tiền cọc tống tiền → mua nợ thuế nhà bà Earnestine; thay khoá trái phép |
| 4 · Trùm | **Bianca** — influencer 2,1 triệu người theo dõi, nổi tiếng nhờ câu chuyện "tôi làm CPR cứu người yêu" | Cụm 58–66 (3 tầng) | Video màn hình camera (Latasha), sao kê ngân hàng (không có khoản rút 9.000), cuộc gọi 911, ảnh siêu âm song thai trên blog 2021, livestream tự thú |
| 5 · "Kẻ thử" ẩn | **Bà Earnestine** — hoá ra chính là người cho Beverly vay 200 đô năm 1988, và đã âm thầm thử lại Beverly | Cụm 69–70 (cú lật ấm áp + móc phần sau) | Tấm ảnh 1988 hai phụ nữ tết tóc trên ghế bếp |

### 1.2 Thanh tẩy 3 tầng (cụm 63–67)
- **TIỀN:** tiền cọc 250.000 đô bị phong toả làm vật chứng; nhà tài trợ huỷ hợp đồng ngay trên livestream; tấm séc 2 triệu trao cho Ayanna, không phải Bianca.
- **LUẬT:** thám tử Imes bắt Bianca + Charlene vì tống tiền và khai báo gian dối; việc thay khoá nhà bà Earnestine là trái phép, trả chìa khoá tại chỗ.
- **DANH DỰ:** Bianca xin Darius → bị từ chối ("You showed me who you are. Twice."); Charlene xin bà Earnestine → "Bless your heart."

### 1.3 Bản đồ cú ngoặt (trả lời lưu ý 1 — ngoặt sớm, ngoặt dày)

| Phút | Cụm | Cú ngoặt | Ai phát hiện / đối phó |
|---|---|---|---|
| 00:45 | 2 | Bà già nghèo là bà Thornton, đang thử cô dâu | Khán giả biết ngay (trớ trêu kịch tính) |
| 05:00 | 11 | **Ayanna biết bà là ai từ lúc bà bước vào** | Beverly phát hiện |
| 06:20 | 13 | **Bianca đọc tên trên tấm séc → biết bà già là Beverly** | Phản diện phát hiện sớm |
| 06:30 | 14 | Bianca đổi kế hoạch: tới trước, khóc trước, đổ cho Ayanna | Kế hoạch đối phó ngầm của phản diện |
| 07:10 | 15 | Bianca KHÔNG phải người làm CPR cứu Darius | Khán giả biết, Darius chưa |
| 10:30 | 21–22 | Chuyện Ayanna "biết bà là ai" bị lật thành bằng chứng cô đào mỏ | Phản diện dùng sự thật làm vũ khí |
| 13:50 | 28 | **Ayanna mới là người làm CPR** | Ayanna phát hiện; Darius không tin |
| 16:20 | 33 | Cuộc gọi 911 → Bianca thú nhận, trả nhẫn | **Giải toả lớn giữa phim** |
| 17:45 | 36 | Bianca livestream: "có thai, bị đuổi vì con thợ tết tóc" | Phản đòn của phản diện |
| 19:20 | 39 | Beverly nhận lời tống tiền: "Done." | Kế hoạch đối phó ngầm của phe thiện |
| 20:15 | 41 | Ảnh siêu âm có HAI thai, lấy từ blog 2021 | Ayanna (nghề CNA) |
| 21:00 | 43 | Charlene nắm nợ thuế nhà bà Earnestine | Leo thang vào gia đình nữ chính |
| 22:45 | 46 | Latasha giữ bản quay đầy đủ, quay sang phe thiện | Tay sai đổi phe |
| 26:30 | 54 | Tamia không tắt livestream | Tay chân phản chủ (khán giả biết trước Bianca) |
| 32:00 | 65 | Tấm séc 2 triệu "chưa bao giờ nói là cho ai" | Beverly |
| 34:00 | 69 | Bà Earnestine là người cho vay 200 đô năm 1988 — và đã thử Beverly ngược lại | Cú lật cuối |

### 1.4 Giải toả rải đều (trả lời lưu ý 2)
Phút 3:45 Latasha bị đuổi · 4:15 Ayanna lên quản lý · 5:00 Ayanna "I treated nobody like somebody" · 9:45 đoạn ghi âm "Move, old lady" · 11:00 Beverly "My house. My table. Sit." · 12:45 bà Earnestine trị thám tử bằng một câu đùa · **16:20 Bianca tự thú, trả nhẫn** · 20:15 lộ ảnh siêu âm giả · 23:00 Latasha đổi phe · 27:00 Bianca tự thú trước 1,8 triệu người mà không biết · 28:30–35:00 bậc thang vạch mặt. Không quãng nào quá 3 phút không có ít nhất một cú phản đòn nhỏ.

### 1.5 Đặt – trả

| Đặt | Cụm đặt | Trả |
|---|---|---|
| Ayanna liếc tường hũ kem có chân dung Beverly | 3 | 11 — "Your face is on every jar in here." |
| Bianca nhét tấm séc vào túi: "I'm not even looking at that." | 9 | 13 — Tamia đọc tên trên séc; 61 — "I didn't even look at it!" bị lặp lại |
| Chấm đỏ ĐANG QUAY trên điện thoại ở ghế số 4 | 12 | 20 — đoạn ghi âm "Move, old lady." |
| Beverly kể "một bà cho tôi vay 200 đô năm 1988" | 10 | 69–70 |
| Bà Earnestine nhìn Beverly: "Have we met?" | 19 | 69 |
| Tấm ảnh 1988 hai phụ nữ trên ghế bếp ở phòng khách nhà Ellis | 30 | 69 |
| Vết sẹo lông mày trái của Darius | 16 | 27–28 |
| "Stay with me, runner." — Bianca lặp lại câu Darius nhớ | 18 | 29, 32 (giọng thật trong cuộc gọi 911) |
| Hình xăm nhịp tim trên cổ tay Ayanna | 2 | 28, 34 |
| Bianca: "Nobody asked you, Tamia. Keep filming." | 14 | 52 "furniture with a phone" → 54 → 62 |
| Charlene "lấy đâu ra 40.000 tiền mặt vào thứ Tư" | 44 | 63 — tiền cọc của Beverly |
| Bianca: "Prove it." | 1 | 58 — chính video chứng minh |
| Chiếc đĩa bánh của bà Earnestine | 19 | 27 — Darius mang trả; 70 — "You bring the dish back." |

---

## 2. Địa chỉ đời thực (references/14)

**Prince George's County, Maryland** (~63% dân da đen, quận da đen giàu nhất nước) và **National Harbor** (khu ven sông Potomac thuộc Oxon Hill, cùng quận). Thời gian: **thứ Năm 23/4/2026 → thứ Bảy 2/5/2026**, mùa xuân, đỗ quyên nở.

- Biệt thự Thornton ở **Woodmore / Mitchellville** — khu golf có cổng, nhà colonial gạch lớn sảnh hai tầng (tầng 4, giàu thật, quiet luxury).
- Nhà bà Earnestine ở **Capitol Heights** — nhà gạch một tầng (brick rambler) xây 1958, sát ranh DC, trả hết nợ năm 1994 bằng tiền tết tóc (tầng 1–2).
- Salon **Velour Hair Lounge** ở **National Harbor** — salon của chính hãng Rosewood (tầng 3).
- Rosewood Hair Company: bắt đầu năm 1988 trên một chiếc ghế bếp ở **Seat Pleasant**; nay ~1,4 tỷ đô.
- Tay cho vay của Charlene ở **Suitland**.
- Dạ tiệc ở một khách sạn ven sông National Harbor.
- Tên khu là thật; tên salon, công ty, khách sạn, giải chạy ("Harbor 5K") đều hư cấu.

**Dấu hiệu người trong cuộc:** "Big Mama"; bữa tối Chủ nhật sau lễ nhà thờ mang **bánh khoai lang** (không phải bánh bí ngô); đòi lại đĩa bánh (trả đĩa không để rỗng: "From the store. But you didn't bring it back empty." — "Your mama raised you right."); mũ nhà thờ rộng vành; "Yes, ma'am"; "Bless your heart" kiểu miền Nam; slang DC "bama" (đúng một lần, miệng Tamia); "snatched me bald"; hộp bánh quy thiếc đựng giấy tờ trên nóc tủ lạnh; ghế bếp đặt giữa phòng khách làm ghế tết tóc; bonnet satin ở nhà; quạt giấy nhà thờ; mẹ nuôi cháu, cháu làm CNA ca sáng và tết tóc buổi tối. Không TV, radio, nhạc có lời, tên bài hát, tên hãng.

---

## 3. Nhân vật

> **Ảnh thắng chữ (30/10/2026):** tạo hình dưới đây đã sửa theo bộ ảnh tham chiếu tác giả duyệt ở `09_media/xuong/anh/` (dự án ảnh `09_media/xuong/du_an.json`, tạo bằng `tao_anh.py` theo khuôn phim cũ). Mỗi mã trang phục có bảng nhân vật 2 ô `SHEET_<TÊN>_<MÃ>` (ô trái cận mặt cổ trần, ô phải toàn thân).

Tên đã đối chiếu `_nguon`/`kich_ban.md` của mọi phim cũ trong `phim\` (không trùng Vivian, Deja, Brielle, Otis, Kendra, Brooks, Whitfield, Reginald…). Nhận diện bất biến nhắc trong mọi shot cận / trung của người đó.

| Mã | Vai | Nhận diện bất biến | Giọng (VOICE LOCK) |
|---|---|---|---|
| **BEVERLY** | **Beverly Thornton**, 64 — sáng lập & CEO Rosewood Hair Company; goá chồng; thông minh, khô, hài ngầm, thử lòng người | Da nâu sâu (Monk 8) ánh đồng; mặt góc cạnh, trán cao, cổ dài, **tàn nhang sẫm trên gò má**; **sisterlocks bạc rất mảnh vấn thành vương miện cao, cài MỘT khoen vàng trên một lọn ở thái dương**; **khe hở nhỏ giữa hai răng cửa**; **nốt ruồi nhỏ trên gò má TRÁI**; khuyên tai đồng điêu khắc · ảnh `CHAR_BEVERLY_FACE` | Contralto ấm, chậm, mềm bên ngoài cứng bên trong; không bao giờ cao giọng |
| **AYANNA** | **Ayanna Ellis**, 29 — CNA ca sáng ở viện dưỡng lão + thợ tết tóc ghế số 4 ở Velour; để dành mở tiệm tết tóc riêng; nhẫn nhịn nhưng có xương sống, nói thẳng, không nhận tiền bố thí | Da mật ong-caramel ánh vàng, **tàn nhang nhẹ trên mũi và má**; nụ cười hơi lệch; **tóc tết Fulani** (một đường cornrow giữa đỉnh, hai bên cornrow vòng quanh tai, phần còn lại bím vừa qua vai, cài khoen vàng và hạt gỗ); **lúm đồng tiền má PHẢI**; **khuyên mũi vàng nhỏ bên phải**; **hình xăm nét nhịp tim mặt trong cổ tay TRÁI** · ảnh `CHAR_AYANNA_FACE` | Alto trong, điềm tĩnh, càng giận càng nói chậm; giọng vùng DMV nhẹ |
| **DARIUS** | **Darius Thornton**, 34 — con trai Beverly, COO Rosewood, sắp lên CEO; hai năm trước ngừng tim ở giải Harbor 5K; tử tế, trung thành tới mức cả tin | Da nâu sâu (Monk 8), trông trẻ ~31; cao vai rộng, dáng người chạy bộ; **kính tròn gọng vàng mảnh**; **tóc 360 waves cắt sát, lineup sắc**; **râu ngắn đen tỉa gọn**; sống mũi hơi gồ; **vết sẹo mảnh xuyên lông mày TRÁI**; đồng hồ bạc mặt tròn tay trái · ảnh `CHAR_DARIUS_FACE` | Baritone trầm, nói ít, chậm |
| **BIANCA** | **Bianca Pierce**, 30 — influencer tóc & phong cách sống 2,1 triệu người theo dõi; nổi tiếng nhờ clip "tôi làm CPR cứu người yêu"; khách VIP của Velour | Da nâu vàng sáng (Monk 5); mặt nhỏ như búp bê, cằm nhọn, mắt mèo; **nốt ruồi duyên trên khoé môi trái**; son nâu anh đào bóng, mi giả dày; **tóc vàng mật thẳng dài tới eo, mái bằng dày ngang lông mày**; **móng hạnh nhân dài bạc chrome**; **dáng đồng hồ cát đầy đặn** (theo yêu cầu tác giả) · ảnh `CHAR_BIANCA_FACE` (cắt từ `NV-BIA-04`) | Mezzo ngọt khi có máy quay, rít và nhanh khi không |
| **CHARLENE** | **Charlene Pierce**, 56 — mẹ Bianca, tự xưng "nhà đầu tư bất động sản", thật ra nợ một tay cho vay ở Suitland; đầu não phía ác | Da nâu mật ong ánh đỏ; **người đầy đặn**, mặt tròn, cằm đôi; lông mày kẻ mảnh cong, nốt ruồi má phải, son đỏ; **tóc ngắn nhuộm đỏ đồng, cạo một bên kẻ vạch**; **kính phi công tròng hồng cài trên đầu**; **hoa tai vòng vàng to, vòng tay vàng xếp chồng**; móng đỏ · ảnh `CHAR_CHARLENE_FACE` | Khàn, nhanh, gọi ai cũng "honey/sweetheart" |
| **TAMIA** | **Tamia**, 26 — trợ lý quay phim của Bianca, cầm điện thoại gắn gimbal; bị coi như đồ vật; phản chủ ở cụm 54 | Da nâu sâu (Monk 8); nhỏ, gầy; **tóc xoăn tự nhiên cắt sát nhuộm đồng cam**; **kính gọng trong to tròn**; **khuyên vách mũi bạc**, sẹo nhỏ ở cằm; **tai nghe chụp tai đen đeo cổ**; không trang điểm · ảnh `CHAR_TAMIA_FACE` | Giọng DC trẻ, nhanh, hay chêm |
| **LATASHA** | **Latasha Greene**, 46 — quản lý Velour, em họ Charlene; xoá camera giúp Bianca; bị đuổi; quay lại nói sự thật | Da nâu hạt dẻ (Monk 7); mềm, hơi tròn; mặt tròn, nụ cười gượng hơi hô; **tóc pixie nâu mật, kính đọc cài trên tóc**; **bút chì vàng cài tai phải**; dây đeo thẻ trống · ảnh `CHAR_LATASHA_FACE` | Nói nhanh, hay chữa thẹn |
| **NADINE** | **Nadine Cole**, 51 — chánh văn phòng của Beverly 20 năm; khô, sắc, hài ngầm | Da nâu sâu (Monk 8); cao gầy, mặt dài góc cạnh; **tóc húi cua muối tiêu kẻ vạch ngôi**; **kính gọng vuông đen bản to**; **khuyên bạc nhỏ ở vành tai trái**; luôn cầm máy tính bảng · ảnh `CHAR_NADINE_FACE` | Rõ, gọn, không cảm xúc |
| **EARNESTINE** | **Earnestine Ellis "Big Mama"**, 77 — bà nội nuôi Ayanna; về hưu sau 32 năm làm nhân viên bưu điện; "mother" của nhà thờ Baptist; năm 1988 tết tóc trên ghế bếp ở Seat Pleasant | Da nâu rất sâu (Monk 9), đồi mồi, nếp cười sâu; nhỏ người, thẳng lưng, mặt dài; **tóc bạc ép uốn sóng kiểu xưa (finger waves)**; **kính mắt mèo gọng vàng có dây hạt**; **một răng bên bọc vàng khi cười**; **dây chuyền thánh giá vàng mảnh** · ảnh `CHAR_EARNESTINE_FACE` | Khàn ấm, chậm, hài, câu nào cũng như đóng dấu |
| **IMES** (PHU+) | **Thám tử Leon Imes**, 48 — cảnh sát quận Prince George's, tội phạm tài chính; công bằng, khô | Da nâu hạt dẻ (Monk 7); cao to; **đầu cạo bóng**; **ria mép chữ V muối tiêu**; **khuyên vàng nhỏ ở tai trái**; mắt sâu mệt nhưng hiền; phù hiệu vàng kẹp thắt lưng, không thấy vũ khí · ảnh `CHAR_IMES_FACE` | Trầm, đều, không phán xét |
| DRIVER (PHU) | Tài xế của Beverly, cụm 3 (có 1 câu thoại) | da nâu sâu, ~50, tóc ngắn điểm bạc lineup gọn, râu dê muối tiêu; vest đen · ảnh `SHEET_DRIVER_DR1` | trầm, lịch sự |
| OFFICER (PHU) | Cảnh sát mặc đồng phục, cụm 64–66 | ~32, hàm vuông, fade thấp; đồng phục navy, phù hiệu bạc, không súng · ảnh `SHEET_OFFICER_OF1` | không thoại |
| LOCKSMITH (PHU) | Thợ khoá, cụm 49 | ~45, chắc nịch, râu muối tiêu, mũ len xám; đồng phục xám, hộp đồ nghề · ảnh `SHEET_LOCKSMITH_LK1` | không thoại |

### 3.1 Trang phục (tầng 0–4, `doc_ra` = khán giả phải đọc ra)

| Mã | Tầng | Mô tả | Khán giả phải đọc ra |
|---|---|---|---|
| **BV0** | 0 | Khăn trùm đầu vải ô liu bạc màu buộc dưới cằm (giấu hết tóc), kính gọng nhựa nâu dày trầy xước, cardigan nâu quá khổ xù lông ở khuỷu và **thiếu một khuy**, váy mặc nhà hoa bạc màu dài qua bắp chân, tất dày màu be, giày chỉnh hình đen mòn mũi, túi nilon trắng nhàu, **gậy gỗ quấn băng keo đen ở tay cầm**; không trang điểm, không trang sức, không gì trông mới | một bà cụ nghèo đi lạc vào salon sang |
| BV1 | 4 | Cardigan cashmere kem dáng choàng ngoài áo lụa tím mận, quần ống rộng kem, locs bạc vấn vương miện cao, hoa tai kim cương nhỏ, kính đọc đeo dây hạt | bà chủ thật ở nhà |
| BV2 | 4 | Vest quần xám than may đo, áo lụa xanh ngọc lục bảo, vòng tay vàng bản to | CEO trong ngày khủng hoảng |
| BV3 | 4 | Đầm satin xanh nửa đêm dáng cột, cape ngắn đính hạt bạc ở vai, locs bạc vấn vương miện, hoa tai giọt sapphire | nữ hoàng của dạ tiệc |
| **AY1** | 1 | Tạp dề thợ tóc đen nhiều túi (không chữ) ngoài áo thun đen trơn, jean đen lưng cao, giày thể thao trắng sờn, tóc tết Fulani búi cao buộc ruy băng satin đen, lược đuôi chuột cài sau búi | thợ tóc làm công |
| AY1M | 1 | AY1 + thẻ quản lý đeo dây ở cổ | thợ tóc vừa lên quản lý |
| AY2 | 1 | Scrubs xanh nhạt, thẻ nhân viên cuộn dây ở thắt lưng, giày thể thao trắng, tóc tết Fulani buộc đuôi ngựa thấp, túi vải đeo vai | CNA đi ca sáng |
| AY3 | 2 | Đầm wrap vàng mù tạt dài qua gối, hoa tai vòng vàng nhỏ, giày cao gót vuông nâu, tóc tết Fulani xoã qua vai | đồ đi lễ Chủ nhật |
| AY4 | 1 | Hoodie xám trơn, legging đen, dép lê, tóc tết Fulani buộc thấp | ở nhà |
| AY5 | 2 | Jumpsuit đen tay dài cổ tròn, đai da đeo hông có túi đựng lược và kẹp, giày bệt đen, tóc tết Fulani vấn vương miện | thợ làm tóc đang làm việc ở dạ tiệc |
| DA1 | 3 | Áo quarter-zip navy ngoài áo thun trắng, quần kaki xám, giày lười da nâu | con nhà giàu đi làm |
| DA2 | 3 | Blazer len màu lạc đà, áo len cổ lọ đen, quần đen | bữa tối Chủ nhật |
| DA3 | 4 | Tuxedo đen, nơ đen, khăn cài túi trắng | dạ tiệc |
| BI1 | 3 | Váy bodycon dệt kim gân kem cổ cao tay dài, ngắn trên gối, ôm sát dáng đồng hồ cát; blazer kem quá khổ khoác vai, dây chuyền vàng mảnh, giày mũi nhọn trắng, túi xách da trắng | phông bạt, khách VIP |
| BI2 | 2 | Hoodie xám quá khổ, legging đen, giày thể thao trắng, tóc buộc rối, mặt mộc | "nạn nhân" đến khóc |
| BI3 | 3 | Đầm satin tím lilac tay phồng dài qua gối, giày quai mảnh bạc | cô dâu tương lai ra mắt |
| BI6 | 3 | Đầm blazer trắng cài khuy vàng, giày cao gót nude | đến ăn tối thứ Hai |
| BI4 | 2 | Áo len kem quá khổ, quần jean xanh nhạt, tóc xoã, không trang điểm | livestream đáng thương |
| BI5 | 3 | Đầm đuôi cá sequin bạc trễ vai, nhẫn đính hôn | tưởng mình là nữ hoàng đêm nay |
| BI5C | 3 | BI5, hai tay còng bạc ra sau, có cảnh sát giữ khuỷu tay | sa cơ |
| CH1 | 3 | Áo wrap hoạ tiết da báo cổ kín, quần ống rộng đen, giày cao gót đen, hoa tai vòng vàng to | phông bạt |
| CH2 / CH2C | 3 | Đầm sequin đỏ dài + khăn choàng lông giả trắng / CH2 còng tay ra sau | phông bạt dạ tiệc / sa cơ |
| TA1 | 1 | Hoodie xám quá khổ, quần đạp xe đen, giày thể thao hầm hố, điện thoại gắn gimbal | trợ lý quay phim |
| TA2 | 1 | Váy slip đen, áo khoác jean, điện thoại gắn gimbal | trợ lý đi làm ở dạ tiệc |
| LA1 | 2 | Blazer đen ngoài áo thun đen, quần âu đen, dây đeo thẻ + chùm chìa khoá | quản lý salon |
| LA2 | 1 | Áo khoác jean, áo thun trắng, quần jean | thất nghiệp |
| LA3 | 2 | LA2 + blazer đen khoác ngoài (dạ tiệc) | tới để nói sự thật |
| NA1 / NA2 | 3 | Vest quần navy, sơ mi trắng / vest quần đen, áo lụa trắng | chánh văn phòng |
| EA1 | 1 | Áo choàng mặc nhà (duster) tím hoa cà có hàng khuy bấm, dép vải, bonnet satin tím | bà ở nhà |
| EA2 | 2 | Vest váy xanh hoàng gia, **mũ nhà thờ rộng vành cùng màu cắm lông vũ**, găng trắng ngắn | đi lễ Chủ nhật |
| EA3 | 2 | Bộ hai mảnh ren màu sâm panh, mũ nhỏ fascinator cùng màu, ví cầm tay | bà đi dạ tiệc |
| IM1 | 2 | Vest xám, sơ mi trắng, phù hiệu vàng kẹp thắt lưng, sổ tay nhỏ | thám tử |
| DR1 | 2 | Vest đen, sơ mi trắng, cà vạt đen (tài xế) | tài xế nhà giàu |
| OF1 | 1 | Đồng phục cảnh sát navy, phù hiệu bạc không chữ, thắt lưng không súng | cảnh sát |
| LK1 | 1 | Đồng phục xám không chữ, ủng đen, hộp đồ nghề đen, mũ len xám | thợ khoá |

---

## 4. Bối cảnh (≤ 2 bối cảnh / cụm; bốn bức tường theo chiều kim đồng hồ)

| Mã | Của ai · ở đâu · tầng | Bốn bức tường / panel | Dấu hiệu người trong cuộc · người nền · tiếng nền · chặn |
|---|---|---|---|
| **VELOUR** | Salon của Rosewood ở National Harbor · tầng 3 | `VELOUR_FRONT` cửa kính đôi + mặt tiền kính nhìn ra lối gỗ ven sông · `VELOUR_DESK` quầy lễ tân, **tường hũ kem Rosewood in chân dung người phụ nữ tóc locs bạc (không chữ)**, góc chờ có tủ lạnh nhỏ đựng nước trái cây · `VELOUR_BOWLS` hàng 4 bồn gội đá đen + giá đầu tượng + cửa kho · `VELOUR_STATIONS` ghế nhung hồng phấn, gương, đèn vòng, **ghế số 4 có giá ba chân kẹp điện thoại** | kệ bonnet satin + bàn chải "edges" ở quầy, khăn đen gấp chồng, máy sấy chụp · ~6 khách nữ da đen nhiều độ tuổi mặc áo choàng cắt tóc đen + 3 thợ tạp dề đen, im lặng · máy sấy, kéo, nước chảy, chuông cửa · không TV / loa / chữ |
| VELOUR_BOARDWALK | Lối đi lát gỗ ven sông trước salon | SUV đen đậu ở lề, cửa kính salon phía sau | gió sông, chim hải âu xa |
| **THORNTON** | Biệt thự colonial gạch của Beverly, Woodmore · tầng 4 | `THORNTON_FOYER` cửa gỗ đôi · cầu thang cong gỗ óc chó · bàn console với **hũ Rosewood đầu tiên năm 1988 trong lồng kính** + cửa sổ · lối vào phòng ăn. `THORNTON_DINING` cửa từ sảnh · tủ búp phê · cửa sổ lớn nhìn ra sân golf · tường tranh. `THORNTON_STEPS` bậc thềm gạch, cột trắng, đèn hiên, lối xe vòng | quạt giấy nhà thờ trên bàn cạnh cửa, ảnh cưới đen trắng (không rõ mặt), bình mộc lan · không người nền · đồng hồ treo tường, máy lạnh · không vàng chói, không cột La Mã |
| **ELLIS** | Nhà gạch một tầng 1958 của bà Earnestine, Capitol Heights · tầng 1–2 | `ELLIS_PORCH` cửa lưới + cửa trước · đầu hiên trái có **ghế xích đu kim loại sơn xanh** · nhìn ra đường, hàng rào lưới, nhà đối diện · đầu hiên phải **bụi đỗ quyên hồng**. `ELLIS_LIVING` cửa trước · sofa + **ảnh 1988 hai phụ nữ trẻ tết tóc trên ghế bếp** · lối vào bếp (tủ lạnh có **hộp bánh quy thiếc** trên nóc) · giá mũ nhà thờ + **ghế bếp gỗ đặt giữa phòng làm ghế tết tóc** | quạt giấy nhà thờ, ảnh Ayanna tốt nghiệp CNA, hộp lược · 2–3 hàng xóm da đen đứng bên kia đường (cụm 25) · chim, cửa lưới cót két, xe xa · không bọc nhựa sofa, không đồ lưu niệm châu Phi |
| **BIANCA_CONDO** | Căn hộ thuê tầng cao ở National Harbor · tầng 3 phông bạt | sofa bouclé trắng · hai đèn vòng + tường hoa hồng giả làm phông quay · thùng hàng PR chất góc · cửa kính nhìn ra sông và vòng đu quay lớn | không người nền · tiếng thành phố xa |
| **GALA** | Phòng tiệc khách sạn ven sông National Harbor | `GALA_STAGE` sân khấu thấp + màn hình LED lớn · `GALA_FLOOR` ~120 khách da đen ăn mặc dạ tiệc ĐỨNG quanh bàn tròn khăn trắng có hoa mộc lan, không ai ăn uống · `GALA_DOORS` cửa đôi phía sau · `GALA_SIDE` cửa bên trái + bàn điều khiển màn hình. `GALA_BACKSTAGE` phòng thay đồ: gương viền bóng đèn tròn, bàn trang điểm, giá treo váy, cửa ra hành lang | tiếng người xì xào nhỏ, không nhạc, không micro / bục phát biểu (Beverly nói không cần micro) |

### 4.1 Bảng 4 góc đã tạo (ảnh thắng chữ — 30/10/2026)

Mỗi bảng vẽ một lượt rồi cắt 4 panel (`09_media/xuong/anh/`); panel theo thứ tự trên-trái, trên-phải, dưới-trái, dưới-phải:

| Bảng | Panel |
|---|---|
| `VELOUR_BANG` | `VELOUR_FRONT` · `VELOUR_DESK` · `VELOUR_BOWLS` · `VELOUR_STATIONS` |
| `THORNTON_FOYER_BANG` | `THORNTON_FOYER` (cửa đôi) · `THORNTON_FOYER_STAIRS` · `THORNTON_FOYER_CONSOLE` · `THORNTON_FOYER_ARCH` |
| `THORNTON_DINING_BANG` | `THORNTON_DINING` · `THORNTON_DINING_BUFFET` · `THORNTON_DINING_WINDOW` · `THORNTON_DINING_ART` |
| `ELLIS_LIVING_BANG` | `ELLIS_LIVING` (cửa trước) · `ELLIS_LIVING_SOFA` · `ELLIS_LIVING_KITCHEN` · `ELLIS_LIVING_HATS` |
| `ELLIS_PORCH_BANG` | `ELLIS_PORCH` (cửa lưới) · `ELLIS_PORCH_GLIDER` · `ELLIS_PORCH_STREET` · `ELLIS_PORCH_AZALEA` |
| `BIANCA_CONDO_BANG` | `BIANCA_CONDO` (sofa) · `BIANCA_CONDO_LIGHTS` · `BIANCA_CONDO_BOXES` · `BIANCA_CONDO_WINDOW` |
| `GALA_BANG` | `GALA_STAGE` · `GALA_FLOOR` · `GALA_DOORS` · `GALA_SIDE` |
| `GALA_BACKSTAGE_BANG` | `GALA_BACKSTAGE` (gương bóng đèn) · `GALA_BACKSTAGE_RACK` · `GALA_BACKSTAGE_DOOR` · `GALA_BACKSTAGE_BENCH` |

Ảnh đơn: `LOC_VELOUR_BOARDWALK` (lối gỗ ven sông trước salon, SUV đen), `LOC_THORNTON_STEPS` (bậc thềm, cột trắng, lối xe vòng). Chú ý: bàn console trong ảnh không có quạt giấy nhà thờ nổi bật; phòng ăn có đồng hồ treo tường và ảnh cưới trên tủ búp phê.

## 5. Đạo cụ

`PROP_WIG` bộ tóc giả vàng mật 30 inch · `PROP_CANE` gậy gỗ quấn băng keo · `PROP_FLIP_PHONE` điện thoại nắp gập cũ của Beverly · `PROP_OJ` chai nước cam · `PROP_CHECK` tờ séc cá nhân viết tay · `PROP_JAR` hũ kem Rosewood in chân dung · `PROP_JAR_1988` hũ đầu tiên trong lồng kính · `PROP_TRIPOD_PHONE` điện thoại Ayanna trên giá ba chân + đèn vòng · `PROP_PIE_DISH` đĩa thuỷ tinh bánh khoai lang · `PROP_FOLDER` tập hồ sơ thuế · `PROP_RING` nhẫn đính hôn · `PROP_SONOGRAM` ảnh siêu âm đen trắng · `PROP_NOTICE` tờ thông báo dán cửa · `PROP_PHOTO_1988` ảnh cũ hai phụ nữ trên ghế bếp · `PROP_BIG_CHECK` tấm séc lớn trên sân khấu · `PROP_KEYS` chùm chìa khoá mới · `PROP_LAPTOP` · `PROP_TABLET` (Nadine) · `PROP_GIMBAL_PHONE` (Tamia) · `PROP_CUFFS` còng bạc · `PROP_CARDS` xấp danh thiếp đặt lịch hồng (cụm 37). Ảnh: `09_media/xuong/anh/PROP_*.png`.

Mọi màn hình / giấy tờ / livestream / video / sao kê = INSERT, chữ và hình **ghép lúc dựng**. Không chữ đọc được trên đồ vật.

---

## 6. Bản đồ nhịp & vòng cảm xúc (23 tập)

| Tập | Cụm | Thời gian | Vòng (framework) | Cán cân quyền lực | Căng | Móc cuối tập |
|---|---|---|---|---|---|---|
| 1 · NINE THOUSAND DOLLARS | 1–3 | 00:00–01:30 | M4 · M1 pha 1 · S2 đặt | Bianca ↑↑, Beverly ↓ dưới sàn | 8 | Ayanna bị đuổi |
| 2 · WHO YOU CALLING? | 4–6 | 01:30–03:00 | M2 nén · S1 | Ayanna chắn trước Beverly; Bianca hất văng điện thoại | 8 | Nadine bước vào |
| 3 · VELOUR IS OURS | 7–9 | 03:00–04:30 | S3 nhỏ · S1 · M1 pha 2 | Lật: Latasha bị đuổi, Ayanna lên quản lý | 7 | Tờ séc nằm trong túi Bianca |
| 4 · I KNEW YOUR FACE | 10–12 | 04:30–06:00 | R1 · M6 | Ayanna ngang hàng Beverly | 7 | Chấm đỏ ĐANG QUAY |
| 5 · THE NAME ON THE CHECK | 13–15 | 06:00–07:30 | R1 · S7 đặt · R2 | Bianca biết sự thật → lên kế hoạch | 8 | Bianca không cứu Darius |
| 6 · SHE CRIED FIRST | 16–18 | 07:30–09:00 | M6 · S4 | Bianca thắng Darius | 8 | Bianca cười sau lưng Darius |
| 7 · SWEET POTATO PIE | 19–21 | 09:00–10:30 | S4 · M3 | Ghi âm lật một bậc → Bianca lật lại bằng hồ sơ | 7 | "Did you know who my mother was?" |
| 8 · SIT DOWN | 22–24 | 10:30–12:00 | R2 · M1 mini | Beverly đè cả bàn; thuê Ayanna | 8 | Bianca gọi mẹ nộp đơn tố cáo |
| 9 · A COP ON THE PORCH | 25–27 | 12:00–13:30 | S10 ngược · M2 · hài | Ayanna bị điều tra → bà Earnestine gỡ | 7 | Vết sẹo của Darius |
| 10 · STAY WITH ME, RUNNER | 28–30 | 13:30–15:00 | R5 · M5 ngọt→đau | Ayanna nói thật, Darius không tin | 8 | Cuộc gọi 911 |
| 11 · THE 911 CALL | 31–33 | 15:00–16:30 | S4 · R9 | Bianca sụp: tự thú, trả nhẫn | 9 | Bianca bỏ đi |
| 12 · PLAN B | 34–36 | 16:30–18:00 | M5 ngọt hơn · S10 ngược (midpoint) | Bianca lật lên bằng livestream | 9 | Hai triệu người xem |
| 13 · TWO MILLION | 37–39 | 18:00–19:30 | M6 · S11 | Charlene tống tiền; Beverly "Done." | 7 | Vì sao Beverly đồng ý? |
| 14 · TWO BABIES | 40–42 | 19:30–21:00 | S13 · S7 đặt bẫy | Phe thiện nắm bài | 7 | Tiền cọc sẽ đi đâu |
| 15 · BIG MAMA'S HOUSE | 43–45 | 21:00–22:30 | Leo thang gia đình · M5 | Charlene nắm nhà bà Earnestine | 8 | Charlene gọi thợ khoá: "Saturday. Noon sharp." |
| 16 · INSURANCE | 46–48 | 22:30–24:00 | Đổi phe (anti-fatigue 5) · S4 | Latasha sang phe thiện | 7 | Charlene bắt gặp Latasha rời salon |
| 17 · LOCKED OUT | 49–51 | 24:00–25:30 | M2 im lặng · đáy vực | Bà Earnestine bị khoá ngoài nhà | 9 | Bianca bước vào phòng thay đồ |
| 18 · FURNITURE WITH A PHONE | 52–54 | 25:30–27:00 | S7 để kẻ ác tự đi | Bianca tưởng thắng; Tamia không tắt live | 8 | "Is there a baby?" |
| 19 · THAT'S THE BABY | 55–57 | 27:00–28:30 | False victory · S8 dựng sân khấu | Bianca đỉnh cao, bút chạm séc | 9 | Màn hình LED sáng |
| 20 · THE FIRST VIDEO | 58–60 | 28:30–30:00 | S8 · S3 · M1 pha 2 | Sụp bậc 1–2 | 9 | "Which one?" |
| 21 · EVERYBODY WAS WATCHING | 61–63 | 30:00–31:30 | S10 lật · đổi phe | Tamia lật; tiền lộ đường đi | 10 | Còng tay |
| 22 · RECEIPTS | 64–66 | 31:30–33:00 | S3 luật · S9 · S11 | 3 tầng thanh tẩy | 10 | Séc cho ai? |
| 23 · TWO HUNDRED DOLLARS | 67–70 | 33:00–35:00 | M2 dư âm · R5 · G1 | Gia đình mới; Earnestine nắm phần sau | 8 | "With interest. Since 1988." |

Đường cong không xuống dưới 7 (luật ≥ 5); đỉnh cuối 10 > midpoint 9. Mỗi tập đổi cán cân ≥ 1 lần; không hai tập liền cùng một cảm xúc chủ đạo (phẫn nộ → hả hê → ấm → sợ → hy vọng → sốc → nhẹ nhõm xoay vòng).

---

## 7. Luật viết đã áp (từ skill + kinh-nghiem-news)

1. Cụm 1 mở bằng trung cảnh thấy mặt hành động chính (không mở bằng INSERT); người có mặt trong cụm đứng sẵn từ khung đầu; ai rời cảnh thì đi ra cửa trên hình.
2. Thoại không gọi TÊN người vắng mặt trong cụm (tool tự gắn ảnh theo tên) — dùng "my fiancée", "the manager", "her mother"…; ngoại lệ duy nhất là cụm 13 (tên trên tấm séc — đánh `bo_qua_biet_danh: ["BEVERLY"]`).
3. Gọi điện = người đó đứng một mình trong khung, chỉ người trong khung nói. Không thoại trong khoang xe (mọi câu nói cạnh xe đều đứng ngoài xe).
4. Màn hình, livestream, sao kê, ảnh siêu âm, video LED = INSERT ghép lúc dựng; âm thanh phát từ thiết bị (ghi âm, cuộc gọi 911) ghép lúc dựng.
5. Người nền luôn là người da đen, có số lượng, im lặng; tiệc thì đứng, không ai ăn uống (G8).
6. Không "kill / sell / sold / buy / bought / sale / hell / damn / insane / boy / hit / died"; không từ bạo lực trong thoại. "Xoá camera" viết "wiped". Tránh cả chữ dễ làm Seedance lỗi: "hold" (khung đứng hình), "frozen", "you're fired" (kiểm duyệt đầu ra), "pregnant" đứng cạnh động từ mạnh. Không slur, không tục.
7. Không cái tát nào cả phim. Hành động vật lý (sửa theo yêu cầu tác giả 29–30/10): cú gạt chân thấy rõ + ném bộ tóc giả ướt + đá văng gậy (cụm 1, và trên video ở cụm 46, 58), ném xấp tiền lẻ (cụm 3), Bianca hất văng điện thoại (cụm 5), làm rơi bánh khoai lang (cụm 19), ném nhẫn xuống bàn (cụm 33), hất xấp danh thiếp (cụm 37), còng tay (cụm 64–66). Không ai quỳ cầu xin (Ayanna ngồi xổm chăm người bệnh). Nên render thử cụm 1 trước vì có cảnh người già bị gạt ngã.
8. Không nhắc nước mắt / mắt đỏ / má đỏ (A1, A17, G7) — tả cảm xúc bằng hàm, môi, giọng, tay.
9. Không chữ trên màn hình, không thẻ tên (luật dựng F13); mốc thời gian đi qua thoại và trang phục.
10. Mỗi cụm 3–6 câu, ≤ 12 từ/câu, ASCII, câu nằm trong giây 1–28.

## 8. Checklist (framework mục 9 + skill)
- [x] 3 giây đầu có xung đột (bộ tóc trong bồn, bà cụ dưới sàn)
- [x] Mỗi tập kết bằng móc, không tập nào tự khép
- [x] Nữ chính chủ động: tự cứu người, tự tìm cuộc gọi 911, tự lật Latasha, tự phát hiện ảnh siêu âm, từ chối tiền bố thí, tự đòi 51%
- [x] Người yêu là cộng sự, không phải cứu tinh (Ayanna từ chối tiền của Darius ở cụm 45)
- [x] Không mâu thuẫn kiểu "một câu nói là xong" — mỗi lần nói thật đều bị bẻ bằng một lời nói dối có lý
- [x] Cược ngoài tình yêu: việc làm, căn nhà của bà, danh tiếng, công lý
- [x] Hậu quả vĩnh viễn: bị bắt, mất nhà tài trợ, mất tiền cọc
- [x] Không ẩn ý: mọi động cơ nói thẳng bằng lời (Bianca tự nói kế hoạch ở cụm 14, Charlene nói mục đích ở cụm 35, Beverly giải thích kế hoạch ở cụm 40)

## 9. Bước tiếp theo (chờ người dùng duyệt kịch bản)
1. Chuyển 70 cụm sang `_nguon\1_cum_NNN.json` (trường `kb` + `dien` 8–11 shot/cụm theo khuôn MOTHER OF THE GROOM) → `content_filter.py` 0 CẤM → `kiem_doi_thuc.py` hết cảnh báo.
2. Tạo ảnh qua cổng Bigup (`scripts/tao_anh.py … anh`): 10 nhân vật chính × bộ đồ, 5 bảng 4 góc bối cảnh, ~20 đạo cụ → QC ≥ 7/10 → bài kiểm tra tắt tiếng.
3. Viết tay bài tiếng Trung từng cụm (`_zh\prompt\cum_NNN.txt`) theo references/13, nhớ ghi `黑人` vào mọi câu người nền (G8).
4. `gui_video.py --nap` → `--thu` → gửi thật khi người dùng bảo.
