# 05 — PROMPT TẠO HÌNH / VIDEO

> Ghi **mọi lần thử**, kể cả lần hỏng. Chuỗi *thử → chọn → sửa* chính là bằng chứng đóng góp sáng tạo: Nghị định 134/2026/NĐ-CP coi việc **thiết lập prompt, đánh giá, lựa chọn, chỉnh sửa kết quả** là đóng góp của con người.
> File kết quả đặt tên trùng **mã** của lần thử (vd `C01-03.mp4`) và lưu trong `09_media/ai-tao-ra/`.

**Tác phẩm:** WHEN_NOBODYS_WATCHING

## Tạo hình nhân vật — Bước 1: ảnh nhận diện (chốt khuôn mặt)

> Prompt do Claude soạn theo yêu cầu tác giả (30/10/2026), dựa trên `THIET_KE.md` mục 3 (nhận diện bất biến) và mục 3.1 (trang phục). Tác giả chạy prompt, soát, chọn và quyết định ảnh chốt.

**Cách làm**
1. Chạy theo thứ tự ưu tiên: Beverly → Ayanna → Darius → Bianca → Earnestine → Charlene → Nadine → Tamia → Latasha → Imes. Ảnh lưu vào `09_media/ai-tao-ra/`, đặt tên đúng mã lần thử.
2. Soát theo dòng **Soát trước khi chốt**. Lỗi AI hay mắc: **lật trái/phải** (nốt ruồi, sẹo, lúm đồng tiền, hình xăm, khuyên mũi), **làm sáng màu da**, **làm trẻ người già**, **biến locs thành bím**, **tự chèn chữ vào ảnh**.
3. Sai một chi tiết thì yêu cầu công cụ **chỉ sửa đúng chi tiết đó** trên ảnh vừa tạo (giữ nguyên khuôn mặt), đừng tạo lại từ đầu. Mỗi lần sửa là **một mã mới** (NV-BEV-02, -03…), không ghi đè file cũ.
4. Ảnh đạt: ghi **Giữ** + lý do. Đó là **ảnh chốt** của nhân vật — làm tham chiếu cho mọi trang phục (Bước 2) và cho Seedance.

Cả 10 prompt dùng chung nền xám, ánh sáng và bố cục ba góc nhìn để bộ ảnh chốt đồng bộ. Tóc để xoã trong ảnh nhận diện để thấy rõ độ dài, màu; kiểu búi theo từng cảnh làm ở Bước 2.

### NV-BEV-01 · BEVERLY THORNTON, 64
- **Ngày:** 30/10/2026
- **Công cụ / model:** gpt-image-2.5, gửi qua Xưởng Phim Bigup 1.0.23 (`xuong.py tao-anh`) · **Gói:** trả phí qua cổng studio
- **Thiết lập:** 1536x1024 (ngang), 1 ảnh/lần, model mặc định của cổng
- **Tư liệu đầu vào:** không (lần tạo đầu)
- **Mô tả (VN):** bà 64 tuổi, da nâu sâu ánh đồng; sisterlocks bạc dài ngang vai (xoã); khe hở răng cửa khi cười; nốt ruồi gò má trái; mặc BV1 — cardigan cashmere kem dáng choàng, áo lụa tím mận, quần ống rộng kem, hoa tai kim cương nhỏ, kính đọc đeo dây hạt.
- **Prompt:**

```text
Photorealistic character reference sheet for a live-action drama. One landscape image showing the SAME person three times side by side, with a perfectly consistent face and identity: left - front-facing head-and-shoulders portrait; middle - three-quarter view head-and-shoulders portrait; right - full-body standing pose facing the camera. Plain light-gray seamless studio background, soft even studio lighting, natural skin texture, accurate skin tone, sharp focus, realistic proportions, dignified and natural look. No text, no letters, no numbers, no labels, no logos, no watermark anywhere in the image.

The person: a 64-year-old African American woman, the self-made founder and CEO of a large hair-care company; composed, sharp, quietly witty, never raises her voice.
Skin: deep brown skin with a warm copper glow (Monk skin tone 8), natural age lines around the eyes and mouth, not airbrushed.
Hair: silver-gray sisterlocks (very fine, uniform micro-locs), worn down, shoulder length.
Must be clearly visible: a small gap between her two upper front teeth - she smiles gently in the front view so the gap shows; a small mole on her LEFT cheekbone (her own left side, which appears on the right side of the image in the front view).
Wardrobe, identical in all three views: a cream cashmere wrap cardigan over a plum silk blouse, wide-leg cream trousers, small diamond stud earrings, reading glasses hanging on a beaded chain.
Expression: warm but watchful eyes, the quiet authority of a matriarch.
```

- **Kết quả:** `09_media/ai-tao-ra/NV-BEV-01.png`
- **Soát trước khi chốt:** ☐ khe hở răng cửa · ☐ nốt ruồi gò má TRÁI (nằm bên PHẢI ảnh khi nhìn thẳng) · ☐ locs bạc mảnh, không thành bím hay dreadlocks to · ☐ trông đúng 64 tuổi · ☐ da nâu sâu ánh đồng, không bị làm sáng
- **Claude soát (gợi ý, tác giả quyết):** đạt khe răng cửa, nốt ruồi đúng má trái, tuổi và màu da; locs hơi to so với sisterlocks (mảnh) — chấp nhận được, hoặc sửa riêng tóc.
- **Đánh giá & quyết định:**

### NV-AYA-01 · AYANNA ELLIS, 29
- **Ngày:** 30/10/2026
- **Công cụ / model:** gpt-image-2.5, gửi qua Xưởng Phim Bigup 1.0.23 (`xuong.py tao-anh`) · **Gói:** trả phí qua cổng studio
- **Thiết lập:** 1536x1024 (ngang), 1 ảnh/lần, model mặc định của cổng
- **Tư liệu đầu vào:** không (lần tạo đầu)
- **Mô tả (VN):** cô 29 tuổi, da nâu ánh vàng ấm; bím knotless dài tới eo, nâu sẫm, đuôi màu mật ong (xoã); lúm đồng tiền sâu má phải; khuyên mũi vàng nhỏ bên phải; hình xăm nét nhịp tim mặt trong cổ tay trái; mặc AY1 — tạp dề thợ tóc đen nhiều túi không chữ, áo thun đen, jean đen lưng cao, giày thể thao trắng sờn.
- **Prompt:**

```text
Photorealistic character reference sheet for a live-action drama. One landscape image showing the SAME person three times side by side, with a perfectly consistent face and identity: left - front-facing head-and-shoulders portrait; middle - three-quarter view head-and-shoulders portrait; right - full-body standing pose facing the camera. Plain light-gray seamless studio background, soft even studio lighting, natural skin texture, accurate skin tone, sharp focus, realistic proportions, dignified and natural look. No text, no letters, no numbers, no labels, no logos, no watermark anywhere in the image.

The person: a 29-year-old African American woman, a certified nursing assistant by day and a hair braider by night; steady, plain-spoken, kind, with a strong backbone.
Skin: medium-deep brown with warm golden undertones (Monk skin tone 7).
Hair: waist-length knotless box braids, dark brown with honey-blonde ends, worn down.
Must be clearly visible: a deep dimple in her RIGHT cheek - she smiles slightly in the front view; a small gold nose stud on her RIGHT nostril; a thin fine-line heartbeat (EKG line) tattoo on the inside of her LEFT wrist - in the three-quarter view she rests her left hand near her collarbone with the inner wrist facing the camera so the tattoo shows.
Wardrobe, identical in all three views: a black multi-pocket stylist apron with no text or logo over a plain black T-shirt, high-waisted black jeans, worn white sneakers.
Expression: calm, grounded, quietly confident; warm eyes.
```

- **Kết quả:** `09_media/ai-tao-ra/NV-AYA-01.png`
- **Soát trước khi chốt:** ☐ lúm đồng tiền má PHẢI · ☐ khuyên mũi bên PHẢI · ☐ hình xăm nhịp tim cổ tay TRÁI · ☐ bím knotless dài tới eo, đuôi màu mật ong · ☐ tạp dề không chữ, không logo
- **Claude soát (gợi ý, tác giả quyết):** đạt bím dài đuôi mật ong, khuyên mũi bên phải, hình xăm nhịp tim ở cổ tay, tạp dề không chữ; lúm đồng tiền má phải chưa rõ — nên sửa riêng chi tiết này.
- **Đánh giá & quyết định:**

### NV-DAR-01 · DARIUS THORNTON, 34
- **Ngày:** 30/10/2026
- **Công cụ / model:** gpt-image-2.5, gửi qua Xưởng Phim Bigup 1.0.23 (`xuong.py tao-anh`) · **Gói:** trả phí qua cổng studio
- **Thiết lập:** 1536x1024 (ngang), 1 ảnh/lần, model mặc định của cổng
- **Tư liệu đầu vào:** không (lần tạo đầu)
- **Mô tả (VN):** anh 34 tuổi, cao ~1m90, vai rộng; da nâu sâu; tóc fade thấp, xoắn ngắn trên đỉnh; râu quai nón đầy tỉa gọn; vết sẹo mảnh xuyên lông mày trái; đồng hồ bạc mặt tròn tay trái; mặc DA1 — quarter-zip navy, áo thun trắng, kaki xám, giày lười da nâu.
- **Prompt:**

```text
Photorealistic character reference sheet for a live-action drama. One landscape image showing the SAME person three times side by side, with a perfectly consistent face and identity: left - front-facing head-and-shoulders portrait; middle - three-quarter view head-and-shoulders portrait; right - full-body standing pose facing the camera. Plain light-gray seamless studio background, soft even studio lighting, natural skin texture, accurate skin tone, sharp focus, realistic proportions, dignified and natural look. No text, no letters, no numbers, no labels, no logos, no watermark anywhere in the image.

The person: a 34-year-old African American man, the chief operating officer of his family's hair-care company; kind, loyal, a little too trusting; a former distance runner.
Build: tall (about 6 feet 3 inches), broad-shouldered, athletic.
Skin: deep brown (Monk skin tone 8).
Hair: low fade with short twists on top; a full beard, neatly trimmed.
Must be clearly visible: a thin pale scar cutting vertically through his LEFT eyebrow (his own left side, which appears on the right side of the image in the front view); a silver watch with a round face on his left wrist.
Wardrobe, identical in all three views: a navy quarter-zip sweater over a white T-shirt, gray chinos, brown leather loafers.
Expression: reserved and earnest, gentle eyes, a man of few words.
```

- **Kết quả:** `09_media/ai-tao-ra/NV-DAR-01.png`
- **Soát trước khi chốt:** ☐ sẹo xuyên lông mày TRÁI (nằm bên PHẢI ảnh khi nhìn thẳng) · ☐ đồng hồ bạc mặt tròn tay TRÁI · ☐ cao, vai rộng · ☐ râu quai nón đầy, tỉa gọn
- **Claude soát (gợi ý, tác giả quyết):** đạt sẹo lông mày trái, đồng hồ tay trái, râu, tóc, vóc dáng.
- **Đánh giá & quyết định:**

### NV-BIA-01 · BIANCA PIERCE, 30
- **Ngày:** 30/10/2026
- **Công cụ / model:** gpt-image-2.5, gửi qua Xưởng Phim Bigup 1.0.23 (`xuong.py tao-anh`) · **Gói:** trả phí qua cổng studio
- **Thiết lập:** 1536x1024 (ngang), 1 ảnh/lần, model mặc định của cổng
- **Tư liệu đầu vào:** không (lần tạo đầu)
- **Mô tả (VN):** cô 30 tuổi, da nâu sáng; tóc body wave vàng mật dài tới eo, rẽ ngôi giữa; mi giả dày, son nude bóng, móng hạnh nhân dài bạc chrome; mặc BI1 — váy bodycon gân kem dài qua gối, blazer kem quá khổ khoác vai, dây chuyền vàng bản to, giày mũi nhọn trắng, túi da trắng.
- **Prompt:**

```text
Photorealistic character reference sheet for a live-action drama. One landscape image showing the SAME person three times side by side, with a perfectly consistent face and identity: left - front-facing head-and-shoulders portrait; middle - three-quarter view head-and-shoulders portrait; right - full-body standing pose facing the camera. Plain light-gray seamless studio background, soft even studio lighting, natural skin texture, accurate skin tone, sharp focus, realistic proportions, dignified and natural look. No text, no letters, no numbers, no labels, no logos, no watermark anywhere in the image.

The person: a 30-year-old African American woman, a glamorous hair-and-lifestyle influencer with two million followers; sweet and polished on camera, cold and sharp off it.
Skin: light brown (Monk skin tone 5).
Hair: sleek, glossy, waist-length honey-blonde body-wave hair with a center part.
Must be clearly visible: thick false eyelashes, glossy nude lips, long almond-shaped silver chrome nails - in the three-quarter view she lifts one hand near her face so the nails are clearly visible.
Wardrobe, identical in all three views: a below-the-knee ribbed cream bodycon dress, an oversized cream blazer draped over her shoulders, a chunky gold chain necklace, white pointed-toe heels, a white leather handbag.
Expression: camera-ready poise with a cool, slightly arrogant look in the eyes.
```

- **Kết quả:** `09_media/ai-tao-ra/NV-BIA-01.png`
- **Soát trước khi chốt:** ☐ tóc vàng mật, sóng lớn, rẽ ngôi giữa, dài tới eo · ☐ móng hạnh nhân dài màu bạc chrome · ☐ da nâu sáng (Monk 5), không bị biến thành da trắng · ☐ blazer khoác vai, không xỏ tay
- **Claude soát (gợi ý, tác giả quyết):** đạt tóc, móng bạc chrome, blazer khoác vai, màu da; cổ váy khoét sâu — cân nhắc kín hơn để tránh kiểm duyệt khi gen video.
- **Đánh giá & quyết định:**

### NV-EAR-01 · EARNESTINE ELLIS "BIG MAMA", 77
- **Ngày:** 30/10/2026
- **Công cụ / model:** gpt-image-2.5, gửi qua Xưởng Phim Bigup 1.0.23 (`xuong.py tao-anh`) · **Gói:** trả phí qua cổng studio
- **Thiết lập:** 1536x1024 (ngang), 1 ảnh/lần, model mặc định của cổng
- **Tư liệu đầu vào:** không (lần tạo đầu)
- **Mô tả (VN):** bà 77 tuổi, da nâu rất sâu; tóc xoăn ngắn bạc trắng; kính mắt mèo gọng vàng; dây chuyền thánh giá vàng mảnh; mặc EA2 — vest váy xanh hoàng gia, găng trắng ngắn; tay cầm mũ nhà thờ rộng vành cắm lông vũ (không đội, để lộ tóc).
- **Prompt:**

```text
Photorealistic character reference sheet for a live-action drama. One landscape image showing the SAME person three times side by side, with a perfectly consistent face and identity: left - front-facing head-and-shoulders portrait; middle - three-quarter view head-and-shoulders portrait; right - full-body standing pose facing the camera. Plain light-gray seamless studio background, soft even studio lighting, natural skin texture, accurate skin tone, sharp focus, realistic proportions, dignified and natural look. No text, no letters, no numbers, no labels, no logos, no watermark anywhere in the image.

The person: a 77-year-old African American grandmother, retired after 32 years at the post office, a respected church mother at her Baptist church; slow-spoken, funny, unshakable.
Skin: very deep brown (Monk skin tone 9), soft natural age lines, not airbrushed.
Hair: short, tightly curled, snow-white natural hair.
Must be clearly visible: gold cat-eye eyeglasses; a thin gold cross necklace.
Wardrobe, identical in all three views: a royal-blue skirt suit and short white gloves; she holds a wide-brimmed royal-blue church hat with a feather in her gloved hands (not wearing it), so her hair is visible.
Expression: warm, sly, a knowing half-smile.
```

- **Kết quả:** `09_media/ai-tao-ra/NV-EAR-01.png`
- **Soát trước khi chốt:** ☐ kính mắt mèo gọng vàng · ☐ dây chuyền thánh giá vàng mảnh · ☐ tóc xoăn ngắn bạc trắng · ☐ trông đúng 77 tuổi · ☐ da nâu rất sâu (Monk 9), không bị làm sáng
- **Claude soát (gợi ý, tác giả quyết):** đạt kính mắt mèo, thánh giá, tóc bạc, mũ cầm tay, tuổi; da có thể sẫm thêm một chút cho đúng Monk 9.
- **Đánh giá & quyết định:**

### NV-CHA-01 · CHARLENE PIERCE, 56
- **Ngày:** 30/10/2026
- **Công cụ / model:** gpt-image-2.5, gửi qua Xưởng Phim Bigup 1.0.23 (`xuong.py tao-anh`) · **Gói:** trả phí qua cổng studio
- **Thiết lập:** 1536x1024 (ngang), 1 ảnh/lần, model mặc định của cổng
- **Tư liệu đầu vào:** không (lần tạo đầu)
- **Mô tả (VN):** bà 56 tuổi, da nâu; tóc pixie nhuộm đỏ đồng; hoa tai vòng vàng to; kính râm cài trên đầu; móng đỏ; mặc CH1 — áo wrap da báo, quần ống rộng đen, giày cao gót đen.
- **Prompt:**

```text
Photorealistic character reference sheet for a live-action drama. One landscape image showing the SAME person three times side by side, with a perfectly consistent face and identity: left - front-facing head-and-shoulders portrait; middle - three-quarter view head-and-shoulders portrait; right - full-body standing pose facing the camera. Plain light-gray seamless studio background, soft even studio lighting, natural skin texture, accurate skin tone, sharp focus, realistic proportions, dignified and natural look. No text, no letters, no numbers, no labels, no logos, no watermark anywhere in the image.

The person: a 56-year-old African American woman, a flashy self-styled real-estate investor who is secretly deep in debt; brassy, fast-talking, scheming.
Skin: medium brown (Monk skin tone 6).
Hair: short pixie cut dyed copper-red.
Must be clearly visible: large gold hoop earrings; sunglasses pushed up on top of her head; red nail polish.
Wardrobe, identical in all three views: a leopard-print wrap top, black wide-leg trousers, black high heels.
Expression: a smug, calculating smile.
```

- **Kết quả:** `09_media/ai-tao-ra/NV-CHA-01.png`
- **Soát trước khi chốt:** ☐ pixie đỏ đồng · ☐ hoa tai vòng vàng to · ☐ kính râm cài trên đầu · ☐ áo wrap da báo
- **Claude soát (gợi ý, tác giả quyết):** đạt tóc đỏ đồng, hoa tai, kính râm, áo da báo, móng đỏ; da hơi sáng so với Monk 6; cổ áo khoét sâu.
- **Đánh giá & quyết định:**

### NV-NAD-01 · NADINE COLE, 51
- **Ngày:** 30/10/2026
- **Công cụ / model:** gpt-image-2.5, gửi qua Xưởng Phim Bigup 1.0.23 (`xuong.py tao-anh`) · **Gói:** trả phí qua cổng studio
- **Thiết lập:** 1536x1024 (ngang), 1 ảnh/lần, model mặc định của cổng
- **Tư liệu đầu vào:** không (lần tạo đầu)
- **Mô tả (VN):** bà 51 tuổi, da nâu sâu; tóc tự nhiên cắt ngắn muối tiêu; kính gọng vuông đen bản to; luôn cầm máy tính bảng; mặc NA1 — vest quần navy, sơ mi trắng.
- **Prompt:**

```text
Photorealistic character reference sheet for a live-action drama. One landscape image showing the SAME person three times side by side, with a perfectly consistent face and identity: left - front-facing head-and-shoulders portrait; middle - three-quarter view head-and-shoulders portrait; right - full-body standing pose facing the camera. Plain light-gray seamless studio background, soft even studio lighting, natural skin texture, accurate skin tone, sharp focus, realistic proportions, dignified and natural look. No text, no letters, no numbers, no labels, no logos, no watermark anywhere in the image.

The person: a 51-year-old African American woman, chief of staff to a powerful CEO for twenty years; dry, sharp, quietly funny, unflappable.
Skin: deep brown (Monk skin tone 8).
Hair: short natural haircut, salt-and-pepper gray.
Must be clearly visible: bold square black eyeglass frames; she holds a tablet computer with a dark, blank screen.
Wardrobe, identical in all three views: a navy pantsuit with a crisp white shirt.
Expression: precise and poised, one eyebrow slightly raised.
```

- **Kết quả:** `09_media/ai-tao-ra/NV-NAD-01.png`
- **Soát trước khi chốt:** ☐ kính gọng vuông đen bản to · ☐ tóc ngắn muối tiêu · ☐ màn hình máy tính bảng tối, không chữ
- **Claude soát (gợi ý, tác giả quyết):** đạt đủ: tóc muối tiêu, kính vuông đen, máy tính bảng tối, vest navy.
- **Đánh giá & quyết định:**

### NV-TAM-01 · TAMIA, 26
- **Ngày:** 30/10/2026
- **Công cụ / model:** gpt-image-2.5, gửi qua Xưởng Phim Bigup 1.0.23 (`xuong.py tao-anh`) · **Gói:** trả phí qua cổng studio
- **Thiết lập:** 1536x1024 (ngang), 1 ảnh/lần, model mặc định của cổng
- **Tư liệu đầu vào:** không (lần tạo đầu)
- **Mô tả (VN):** cô 26 tuổi, da nâu sâu; tóc tự nhiên cắt sát (TWA) nhuộm đồng cam; kính gọng trong to tròn; cầm điện thoại gắn gimbal; mặc TA1 — hoodie xám quá khổ, quần đạp xe đen, giày thể thao hầm hố.
- **Prompt:**

```text
Photorealistic character reference sheet for a live-action drama. One landscape image showing the SAME person three times side by side, with a perfectly consistent face and identity: left - front-facing head-and-shoulders portrait; middle - three-quarter view head-and-shoulders portrait; right - full-body standing pose facing the camera. Plain light-gray seamless studio background, soft even studio lighting, natural skin texture, accurate skin tone, sharp focus, realistic proportions, dignified and natural look. No text, no letters, no numbers, no labels, no logos, no watermark anywhere in the image.

The person: a 26-year-old African American woman, an influencer's camera assistant who films everything on a phone gimbal; overlooked, watchful, underestimated.
Skin: deep brown (Monk skin tone 8).
Hair: a short natural teeny-weeny afro (TWA) dyed copper-orange.
Must be clearly visible: large round clear-frame eyeglasses; she holds a smartphone mounted on a handheld gimbal, screen dark.
Wardrobe, identical in all three views: an oversized gray hoodie, black biker shorts, chunky sneakers.
Expression: guarded, quietly observing.
```

- **Kết quả:** `09_media/ai-tao-ra/NV-TAM-01.png`
- **Soát trước khi chốt:** ☐ tóc TWA đồng cam · ☐ kính gọng trong, to tròn · ☐ điện thoại gắn gimbal
- **Claude soát (gợi ý, tác giả quyết):** LỖI: bàn tay ở ảnh toàn thân bị ám màu xanh lá, môi ở ảnh nghiêng xám bất thường — nên tạo lại (NV-TAM-02). Tóc, kính, gimbal đạt.
- **Đánh giá & quyết định:**

### NV-LAT-01 · LATASHA GREENE, 46
- **Ngày:** 30/10/2026
- **Công cụ / model:** gpt-image-2.5, gửi qua Xưởng Phim Bigup 1.0.23 (`xuong.py tao-anh`) · **Gói:** trả phí qua cổng studio
- **Thiết lập:** 1536x1024 (ngang), 1 ảnh/lần, model mặc định của cổng
- **Tư liệu đầu vào:** không (lần tạo đầu)
- **Mô tả (VN):** chị 46 tuổi, da nâu; tóc pixie nâu mật; bút chì cài tai; dây đeo thẻ + chùm chìa khoá; mặc LA1 — blazer đen ngoài áo thun đen, quần âu đen.
- **Prompt:**

```text
Photorealistic character reference sheet for a live-action drama. One landscape image showing the SAME person three times side by side, with a perfectly consistent face and identity: left - front-facing head-and-shoulders portrait; middle - three-quarter view head-and-shoulders portrait; right - full-body standing pose facing the camera. Plain light-gray seamless studio background, soft even studio lighting, natural skin texture, accurate skin tone, sharp focus, realistic proportions, dignified and natural look. No text, no letters, no numbers, no labels, no logos, no watermark anywhere in the image.

The person: a 46-year-old African American woman, the manager of an upscale hair salon; fast-talking, eager to please, easily flustered.
Skin: medium-deep brown (Monk skin tone 7).
Hair: honey-brown pixie cut.
Must be clearly visible: a pencil tucked behind her ear; a blank ID badge on a lanyard and a ring of keys.
Wardrobe, identical in all three views: a black blazer over a black T-shirt, black dress trousers.
Expression: a nervous, overly polite professional smile.
```

- **Kết quả:** `09_media/ai-tao-ra/NV-LAT-01.png`
- **Soát trước khi chốt:** ☐ pixie nâu mật · ☐ bút chì cài tai · ☐ thẻ trống, không chữ
- **Claude soát (gợi ý, tác giả quyết):** đạt tóc pixie nâu mật, bút chì cài tai, thẻ trống, chùm chìa khoá; ảnh ra cỡ 1376x768, nền hơi trắng hơn bộ còn lại.
- **Đánh giá & quyết định:**

### NV-IME-01 · THÁM TỬ LEON IMES, 48
- **Ngày:** 30/10/2026
- **Công cụ / model:** gpt-image-2.5, gửi qua Xưởng Phim Bigup 1.0.23 (`xuong.py tao-anh`) · **Gói:** trả phí qua cổng studio
- **Thiết lập:** 1536x1024 (ngang), 1 ảnh/lần, model mặc định của cổng
- **Tư liệu đầu vào:** không (lần tạo đầu)
- **Mô tả (VN):** ông 48 tuổi, da nâu; đầu cạo; ria mép tỉa gọn; phù hiệu vàng kẹp thắt lưng; sổ tay nhỏ; không thấy vũ khí; mặc IM1 — vest xám, sơ mi trắng.
- **Prompt:**

```text
Photorealistic character reference sheet for a live-action drama. One landscape image showing the SAME person three times side by side, with a perfectly consistent face and identity: left - front-facing head-and-shoulders portrait; middle - three-quarter view head-and-shoulders portrait; right - full-body standing pose facing the camera. Plain light-gray seamless studio background, soft even studio lighting, natural skin texture, accurate skin tone, sharp focus, realistic proportions, dignified and natural look. No text, no letters, no numbers, no labels, no logos, no watermark anywhere in the image.

The person: a 48-year-old African American man, a county police detective in financial crimes; fair, dry, unhurried.
Skin: medium-deep brown (Monk skin tone 7).
Hair: clean-shaven head; a neatly trimmed mustache.
Must be clearly visible: a gold detective badge clipped to his belt; a small notebook in his hand; no weapon visible.
Wardrobe, identical in all three views: a gray suit with a white shirt.
Expression: calm, attentive, non-judgmental.
```

- **Kết quả:** `09_media/ai-tao-ra/NV-IME-01.png`
- **Soát trước khi chốt:** ☐ đầu cạo, ria mép tỉa gọn · ☐ phù hiệu vàng ở thắt lưng · ☐ không thấy súng
- **Claude soát (gợi ý, tác giả quyết):** đạt đầu cạo, ria mép, phù hiệu vàng ở thắt lưng, sổ tay, không thấy súng.
- **Đánh giá & quyết định:**

## Tạo hình nhân vật — Vòng 2: chân dung mặt riêng (theo cách làm phim THE SHELTER)
> Lý do (30/10/2026): tác giả chưa ưng vòng 1. Claude đối chiếu hồ sơ THE SHELTER (`_ho-so-bang-chung/the-shelter`, mục B6 và khuôn ảnh của Xưởng Phim): tạo **chân dung mặt riêng, khổ dọc 1024x1536, một người** trước, trang phục toàn thân làm sau từ ảnh mặt; chất ảnh điện ảnh ARRI Alexa 35, hạt phim 35mm, da nâu giữ độ bóng, không xám. Nét mặt được tả kỹ hơn và vai chính được tả là ưa nhìn. Bianca, Charlene đổi sang cổ áo kín để tránh kiểm duyệt.

### NV-BEV-02 · BEVERLY THORNTON, 64 · chân dung mặt
- **Ngày:** 30/10/2026
- **Công cụ / model:** gpt-image-2.5, gửi qua Xưởng Phim Bigup 1.0.23 (`xuong.py tao-anh`) · **Gói:** trả phí qua cổng studio
- **Thiết lập:** 1024x1536 (dọc), 1 ảnh/lần
- **Tư liệu đầu vào:** không
- **Mô tả (VN):** bà 64, mặt trái xoan, gò má cao, mắt hạnh nhân, sang trọng; sisterlocks bạc rất mảnh; khe răng cửa; nốt ruồi gò má trái
- **Prompt:**

```text
Photoreal live-action film production reference photo, shot on ARRI Alexa 35 with an 85mm portrait lens, soft cinematic key light with gentle falloff and a subtle rim light, fine 35mm film grain, true-to-life skin texture with natural pores and a healthy sheen; brown skin keeps its warm glow, never gray or ashy. Head-and-shoulders frontal portrait of a 64-year-old African American woman, an elegant self-made beauty-industry billionaire: graceful oval face, high cheekbones, intelligent almond-shaped dark eyes, refined features, natural age lines that make her look distinguished; deep brown skin with a warm copper glow (Monk 8). Very fine silver-gray sisterlocks (tiny uniform micro-locs), shoulder length, softly framing her face. A small gap between her two upper front teeth shows in a gentle closed-to-parted smile. A small mole on her LEFT cheekbone (right side of the image). Small diamond studs, cream cashmere wrap cardigan over a plum silk blouse. Warm but watchful, the quiet authority of a matriarch. Eye level, looking into the lens. Plain warm-gray studio background, one subject only, sharp focus on the eyes. No text, no logo, no watermark, no collage.
```

- **Kết quả:** `09_media/ai-tao-ra/NV-BEV-02.png`
- **Claude soát (gợi ý, tác giả quyết):** đạt khe răng cửa, nốt ruồi đúng gò má trái, locs mảnh hơn vòng 1, sang và đúng tuổi.
- **Đánh giá & quyết định:**

### NV-AYA-02 · AYANNA ELLIS, 29 · chân dung mặt
- **Ngày:** 30/10/2026
- **Công cụ / model:** gpt-image-2.5, gửi qua Xưởng Phim Bigup 1.0.23 (`xuong.py tao-anh`) · **Gói:** trả phí qua cổng studio
- **Thiết lập:** 1024x1536 (dọc), 1 ảnh/lần
- **Tư liệu đầu vào:** không
- **Mô tả (VN):** cô 29, nữ chính xinh: mặt trái tim, mắt to ấm, môi đầy, da caramel ánh vàng; bím knotless đuôi mật ong; lúm đồng tiền má phải rõ; khuyên mũi phải
- **Prompt:**

```text
Photoreal live-action film production reference photo, shot on ARRI Alexa 35 with an 85mm portrait lens, soft cinematic key light with gentle falloff and a subtle rim light, fine 35mm film grain, true-to-life skin texture with natural pores and a healthy sheen; brown skin keeps its warm glow, never gray or ashy. Head-and-shoulders frontal portrait of a 29-year-old African American woman, the beautiful lead of a TV drama: soft heart-shaped face, full natural brows, large warm dark-brown eyes, full lips, natural glowing skin with minimal makeup; warm caramel-brown skin with golden undertones (Monk 7). Waist-length knotless box braids, dark brown fading to honey-blonde ends, worn down over one shoulder. A deep dimple in her RIGHT cheek clearly visible in a warm genuine smile; a small gold nose stud on her RIGHT nostril. Plain black T-shirt under the strap of a black stylist apron. Kind, steady, quietly strong. Eye level, looking into the lens. Plain warm-gray studio background, one subject only, sharp focus on the eyes. No text, no logo, no watermark, no collage.
```

- **Kết quả:** `09_media/ai-tao-ra/NV-AYA-02.png`
- **Claude soát (gợi ý, tác giả quyết):** mặt đẹp, bím đuôi mật ong đạt; LỖI: khuyên mũi nằm bên TRÁI (cần bên phải); lúm đồng tiền còn mờ.
- **Đánh giá & quyết định:**

### NV-DAR-02 · DARIUS THORNTON, 34 · chân dung mặt
- **Ngày:** 30/10/2026
- **Công cụ / model:** gpt-image-2.5, gửi qua Xưởng Phim Bigup 1.0.23 (`xuong.py tao-anh`) · **Gói:** trả phí qua cổng studio
- **Thiết lập:** 1024x1536 (dọc), 1 ảnh/lần
- **Tư liệu đầu vào:** không
- **Mô tả (VN):** anh 34, nam chính điển trai: hàm vuông, mắt sâu ấm; fade + twists; râu quai nón tỉa sắc; sẹo lông mày trái
- **Prompt:**

```text
Photoreal live-action film production reference photo, shot on ARRI Alexa 35 with an 85mm portrait lens, soft cinematic key light with gentle falloff and a subtle rim light, fine 35mm film grain, true-to-life skin texture with natural pores and a healthy sheen; brown skin keeps its warm glow, never gray or ashy. Head-and-shoulders frontal portrait of a 34-year-old African American man, the handsome romantic lead of a TV drama: strong square jaw, warm deep-set brown eyes, straight nose, broad shoulders of a former runner; deep brown skin (Monk 8). Low fade with short neat twists on top; full beard, neatly trimmed and sharply lined. A thin pale scar cutting vertically through his LEFT eyebrow (right side of the image). Navy quarter-zip sweater over a white T-shirt. Earnest, gentle, a man of few words. Eye level, looking into the lens. Plain warm-gray studio background, one subject only, sharp focus on the eyes. No text, no logo, no watermark, no collage.
```

- **Kết quả:** `09_media/ai-tao-ra/NV-DAR-02.png`
- **Claude soát (gợi ý, tác giả quyết):** đạt: sẹo ở lông mày trái, râu tỉa sắc, nam chính điển trai.
- **Đánh giá & quyết định:**

### NV-BIA-02 · BIANCA PIERCE, 30 · chân dung mặt
- **Ngày:** 30/10/2026
- **Công cụ / model:** gpt-image-2.5, gửi qua Xưởng Phim Bigup 1.0.23 (`xuong.py tao-anh`) · **Gói:** trả phí qua cổng studio
- **Thiết lập:** 1024x1536 (dọc), 1 ảnh/lần
- **Tư liệu đầu vào:** không
- **Mô tả (VN):** cô 30, phản diện đẹp sắc: gò má tạc, mắt mèo, trang điểm hoàn hảo, da mật ong sáng; tóc vàng mật rẽ giữa; móng bạc chrome; cổ áo kín
- **Prompt:**

```text
Photoreal live-action film production reference photo, shot on ARRI Alexa 35 with an 85mm portrait lens, soft cinematic key light with gentle falloff and a subtle rim light, fine 35mm film grain, true-to-life skin texture with natural pores and a healthy sheen; brown skin keeps its warm glow, never gray or ashy. Head-and-shoulders frontal portrait of a 30-year-old African American woman, a glamorous influencer and the beautiful villain of a TV drama: sculpted cheekbones, feline lifted eyes, defined brows, glossy nude lips, thick false lashes, flawless camera-ready makeup; light honey-brown skin (Monk 5). Sleek waist-length honey-blonde body-wave hair with a center part. One hand near her chin shows long almond-shaped silver chrome nails. Cream ribbed high-neck top with a chunky gold chain, oversized cream blazer draped on her shoulders. Poised, polished, a cool slightly arrogant look. Eye level, looking into the lens. Plain warm-gray studio background, one subject only, sharp focus on the eyes. No text, no logo, no watermark, no collage.
```

- **Kết quả:** `09_media/ai-tao-ra/NV-BIA-02.png`
- **Claude soát (gợi ý, tác giả quyết):** đạt: tóc, móng bạc chrome, cổ áo đã kín, đúng chất phản diện sang.
- **Đánh giá & quyết định:**

### NV-EAR-02 · EARNESTINE ELLIS, 77 · chân dung mặt
- **Ngày:** 30/10/2026
- **Công cụ / model:** gpt-image-2.5, gửi qua Xưởng Phim Bigup 1.0.23 (`xuong.py tao-anh`) · **Gói:** trả phí qua cổng studio
- **Thiết lập:** 1024x1536 (dọc), 1 ảnh/lần
- **Tư liệu đầu vào:** không
- **Mô tả (VN):** bà 77, mặt tròn hiền, nếp cười sâu, mắt tinh; da nâu rất sâu; tóc xoăn ngắn bạc trắng; kính mắt mèo vàng; thánh giá
- **Prompt:**

```text
Photoreal live-action film production reference photo, shot on ARRI Alexa 35 with an 85mm portrait lens, soft cinematic key light with gentle falloff and a subtle rim light, fine 35mm film grain, true-to-life skin texture with natural pores and a healthy sheen; brown skin keeps its warm glow, never gray or ashy. Head-and-shoulders frontal portrait of a 77-year-old African American grandmother and Baptist church mother: round kind face, deep laugh lines, twinkling knowing eyes, soft full cheeks; very deep brown skin with a warm sheen (Monk 9), natural age lines. Short, tightly curled snow-white natural hair. Gold cat-eye eyeglasses, a thin gold cross necklace. Royal-blue church suit jacket. A sly, warm half-smile, as if she already knows your secret. Eye level, looking into the lens. Plain warm-gray studio background, one subject only, sharp focus on the eyes. No text, no logo, no watermark, no collage.
```

- **Kết quả:** `09_media/ai-tao-ra/NV-EAR-02.png`
- **Claude soát (gợi ý, tác giả quyết):** đạt: kính mắt mèo vàng, thánh giá, tóc bạc, nụ cười tinh quái.
- **Đánh giá & quyết định:**

### NV-CHA-02 · CHARLENE PIERCE, 56 · chân dung mặt
- **Ngày:** 30/10/2026
- **Công cụ / model:** gpt-image-2.5, gửi qua Xưởng Phim Bigup 1.0.23 (`xuong.py tao-anh`) · **Gói:** trả phí qua cổng studio
- **Thiết lập:** 1024x1536 (dọc), 1 ảnh/lần
- **Tư liệu đầu vào:** không
- **Mô tả (VN):** bà 56: lông mày cong sắc, mắt tính toán, son đỏ; pixie đỏ đồng; kính râm trên đầu; hoa tai vòng to; cổ áo kín
- **Prompt:**

```text
Photoreal live-action film production reference photo, shot on ARRI Alexa 35 with an 85mm portrait lens, soft cinematic key light with gentle falloff and a subtle rim light, fine 35mm film grain, true-to-life skin texture with natural pores and a healthy sheen; brown skin keeps its warm glow, never gray or ashy. Head-and-shoulders frontal portrait of a 56-year-old African American woman, a flashy scheming mother: sharp arched brows, narrowed calculating eyes, bold red lipstick, full made-up face; medium brown skin (Monk 6). Short copper-red pixie cut with sunglasses pushed up on top of her head. Large gold hoop earrings. Leopard-print wrap top with a modest neckline. A smug smile. Eye level, looking into the lens. Plain warm-gray studio background, one subject only, sharp focus on the eyes. No text, no logo, no watermark, no collage.
```

- **Kết quả:** `09_media/ai-tao-ra/NV-CHA-02.png`
- **Claude soát (gợi ý, tác giả quyết):** đạt tóc đỏ đồng, kính râm, hoa tai, son đỏ; cổ áo vẫn còn khoét sâu.
- **Đánh giá & quyết định:**

### NV-NAD-02 · NADINE COLE, 51 · chân dung mặt
- **Ngày:** 30/10/2026
- **Công cụ / model:** gpt-image-2.5, gửi qua Xưởng Phim Bigup 1.0.23 (`xuong.py tao-anh`) · **Gói:** trả phí qua cổng studio
- **Thiết lập:** 1024x1536 (dọc), 1 ảnh/lần
- **Tư liệu đầu vào:** không
- **Mô tả (VN):** bà 51: mặt dài thanh, một bên mày nhướng; tóc ngắn muối tiêu; kính vuông đen bản to
- **Prompt:**

```text
Photoreal live-action film production reference photo, shot on ARRI Alexa 35 with an 85mm portrait lens, soft cinematic key light with gentle falloff and a subtle rim light, fine 35mm film grain, true-to-life skin texture with natural pores and a healthy sheen; brown skin keeps its warm glow, never gray or ashy. Head-and-shoulders frontal portrait of a 51-year-old African American woman, a razor-sharp chief of staff: long elegant face, high forehead, one eyebrow slightly raised; deep brown skin (Monk 8). Short natural salt-and-pepper hair. Bold square black eyeglass frames. Navy pantsuit jacket over a crisp white shirt. Dry, precise, unflappable. Eye level, looking into the lens. Plain warm-gray studio background, one subject only, sharp focus on the eyes. No text, no logo, no watermark, no collage.
```

- **Kết quả:** `09_media/ai-tao-ra/NV-NAD-02.png`
- **Claude soát (gợi ý, tác giả quyết):** đạt đủ.
- **Đánh giá & quyết định:**

### NV-TAM-02 · TAMIA, 26 · chân dung mặt
- **Ngày:** 30/10/2026
- **Công cụ / model:** gpt-image-2.5, gửi qua Xưởng Phim Bigup 1.0.23 (`xuong.py tao-anh`) · **Gói:** trả phí qua cổng studio
- **Thiết lập:** 1024x1536 (dọc), 1 ảnh/lần
- **Tư liệu đầu vào:** không
- **Mô tả (VN):** cô 26: mặt nhỏ, mắt to cảnh giác, kính gọng trong tròn; TWA đồng cam; hoodie xám
- **Prompt:**

```text
Photoreal live-action film production reference photo, shot on ARRI Alexa 35 with an 85mm portrait lens, soft cinematic key light with gentle falloff and a subtle rim light, fine 35mm film grain, true-to-life skin texture with natural pores and a healthy sheen; brown skin keeps its warm glow, never gray or ashy. Head-and-shoulders frontal portrait of a 26-year-old African American woman, an overlooked camera assistant: small oval face, big watchful eyes behind large round clear-frame glasses, natural lips, no makeup; deep brown skin (Monk 8). A short natural teeny-weeny afro dyed copper-orange. Oversized gray hoodie. Guarded, quietly observing everything. Eye level, looking into the lens. Plain warm-gray studio background, one subject only, sharp focus on the eyes. No text, no logo, no watermark, no collage.
```

- **Kết quả:** `09_media/ai-tao-ra/NV-TAM-02.png`
- **Claude soát (gợi ý, tác giả quyết):** đạt, đã hết lỗi tay xanh và môi xám của vòng 1.
- **Đánh giá & quyết định:**

### NV-LAT-02 · LATASHA GREENE, 46 · chân dung mặt
- **Ngày:** 30/10/2026
- **Công cụ / model:** gpt-image-2.5, gửi qua Xưởng Phim Bigup 1.0.23 (`xuong.py tao-anh`) · **Gói:** trả phí qua cổng studio
- **Thiết lập:** 1024x1536 (dọc), 1 ảnh/lần
- **Tư liệu đầu vào:** không
- **Mô tả (VN):** chị 46: mặt tròn, cười gượng lo âu; pixie nâu mật; bút chì cài tai; thẻ trống
- **Prompt:**

```text
Photoreal live-action film production reference photo, shot on ARRI Alexa 35 with an 85mm portrait lens, soft cinematic key light with gentle falloff and a subtle rim light, fine 35mm film grain, true-to-life skin texture with natural pores and a healthy sheen; brown skin keeps its warm glow, never gray or ashy. Head-and-shoulders frontal portrait of a 46-year-old African American woman, an anxious salon manager: round face, nervous polite smile, slightly worried eyes; medium-deep brown skin (Monk 7). Honey-brown pixie cut with a yellow pencil tucked behind her ear. Black blazer over a black T-shirt, a blank ID badge on a black lanyard. Eye level, looking into the lens. Plain warm-gray studio background, one subject only, sharp focus on the eyes. No text, no logo, no watermark, no collage.
```

- **Kết quả:** `09_media/ai-tao-ra/NV-LAT-02.png`
- **Claude soát (gợi ý, tác giả quyết):** đạt: vẻ lo âu đúng vai, bút chì cài tai (lộ ít), thẻ trống.
- **Đánh giá & quyết định:**

### NV-IME-02 · LEON IMES, 48 · chân dung mặt
- **Ngày:** 30/10/2026
- **Công cụ / model:** gpt-image-2.5, gửi qua Xưởng Phim Bigup 1.0.23 (`xuong.py tao-anh`) · **Gói:** trả phí qua cổng studio
- **Thiết lập:** 1024x1536 (dọc), 1 ảnh/lần
- **Tư liệu đầu vào:** không
- **Mô tả (VN):** ông 48: mặt điềm tĩnh, mắt chăm chú; đầu cạo; ria mép gọn; vest xám
- **Prompt:**

```text
Photoreal live-action film production reference photo, shot on ARRI Alexa 35 with an 85mm portrait lens, soft cinematic key light with gentle falloff and a subtle rim light, fine 35mm film grain, true-to-life skin texture with natural pores and a healthy sheen; brown skin keeps its warm glow, never gray or ashy. Head-and-shoulders frontal portrait of a 48-year-old African American man, a fair county police detective: strong calm face, steady attentive eyes; medium-deep brown skin (Monk 7). Clean-shaven head, neatly trimmed mustache. Gray suit, white shirt, no tie. Calm, non-judgmental. Eye level, looking into the lens. Plain warm-gray studio background, one subject only, sharp focus on the eyes. No text, no logo, no watermark, no collage.
```

- **Kết quả:** `09_media/ai-tao-ra/NV-IME-02.png`
- **Claude soát (gợi ý, tác giả quyết):** đạt đủ.
- **Đánh giá & quyết định:**

## Tạo hình nhân vật — Vòng 3: chất riêng, không giống số đông (5 vai chính)
> Lý do (30/10/2026): tác giả thấy vòng 2 đẹp nhưng giống tạo hình của nhiều kênh. Theo tinh thần THE SHELTER (mục B6: mỗi vai một chi tiết rất riêng như người thật — tàn nhang, răng bọc vàng, ria chữ bát; tránh mẫu đã lặp như móng đỏ dài), Claude đề xuất tạo hình mới: mặt người thật không kiểu người mẫu, mỗi vai một dấu hiệu khó nhầm. Giữ các dấu hiệu gắn cốt truyện (khe răng, nốt ruồi, sẹo, xăm nhịp tim, móng bạc). **Đây là đề xuất đổi thiết kế, chờ tác giả duyệt; THIET_KE.md chưa sửa.**

### NV-BEV-03 · BEVERLY THORNTON, 64 · chân dung chất riêng
- **Ngày:** 30/10/2026
- **Công cụ / model:** gpt-image-2.5, gửi qua Xưởng Phim Bigup 1.0.23 (`xuong.py tao-anh`) · **Gói:** trả phí qua cổng studio
- **Thiết lập:** 1024x1536 (dọc), 1 ảnh/lần
- **Tư liệu đầu vào:** không
- **Điểm riêng (VN):** mặt góc cạnh, cổ dài, trán cao, tàn nhang sẫm trên gò má; locs bạc vấn thành vương miện cao + MỘT khoen vàng trên một lọn; khuyên tai đồng điêu khắc; giữ khe răng + nốt ruồi
- **Prompt:**

```text
Photoreal still from a prestige independent film, shot on ARRI Alexa 35 with an 85mm lens, soft motivated window light, fine 35mm film grain, unretouched real skin with natural pores, sheen and tiny imperfections; brown skin keeps its warm glow, never gray or ashy. Cast like a character-driven drama, not a model or influencer: a specific, memorable real person with naturally asymmetric features. A 64-year-old African American woman, a self-made hair-care mogul. Long elegant neck, strong angular jaw, high regal forehead, hooded wise eyes with fine crow's feet, a scattering of dark freckles across her cheekbones; deep brown skin with a copper glow. Very fine silver sisterlocks swept up into a tall sculpted crown, with one thin hammered-gold cuff on a single loc by her temple. A small gap between her upper front teeth in a slight dry smile. A small mole on her LEFT cheekbone (right side of the image). One sculptural brass ear cuff, cream cashmere wrap with a plum silk collar. Head-and-shoulders portrait, eye level. Plain warm-gray backdrop, one subject only. No text, no logo, no watermark, no collage.
```

- **Kết quả:** `09_media/ai-tao-ra/NV-BEV-03.png`
- **Đánh giá & quyết định:**

### NV-AYA-03 · AYANNA ELLIS, 29 · chân dung chất riêng
- **Ngày:** 30/10/2026
- **Công cụ / model:** gpt-image-2.5, gửi qua Xưởng Phim Bigup 1.0.23 (`xuong.py tao-anh`) · **Gói:** trả phí qua cổng studio
- **Thiết lập:** 1024x1536 (dọc), 1 ảnh/lần
- **Tư liệu đầu vào:** không
- **Điểm riêng (VN):** da mật ong-caramel + tàn nhang, nụ cười hơi lệch, lúm má phải; tóc Fulani braids có khoen vàng + hạt gỗ (khoe tay nghề thợ tết); khuyên mũi phải
- **Prompt:**

```text
Photoreal still from a prestige independent film, shot on ARRI Alexa 35 with an 85mm lens, soft motivated window light, fine 35mm film grain, unretouched real skin with natural pores, sheen and tiny imperfections; brown skin keeps its warm glow, never gray or ashy. Cast like a character-driven drama, not a model or influencer: a specific, memorable real person with naturally asymmetric features. A 29-year-old African American woman, a hospital aide who braids hair at night. Warm honey-caramel skin with a soft dusting of freckles across her nose and cheeks, wide-set calm eyes, a slightly crooked natural smile, a deep dimple in her RIGHT cheek, full brows left natural. Her own masterpiece hairstyle: Fulani braids - a center cornrow running front to back, side cornrows curving around her ears, the rest falling in medium braids past her shoulders, accented with a few small gold cuffs and wooden beads. A tiny gold stud in her RIGHT nostril (left side of the image). Plain black T-shirt, a black apron strap on one shoulder. Grounded, kind, unbreakable. Head-and-shoulders portrait, eye level. Plain warm-gray backdrop, one subject only. No text, no logo, no watermark, no collage.
```

- **Kết quả:** `09_media/ai-tao-ra/NV-AYA-03.png`
- **Đánh giá & quyết định:**

### NV-DAR-03 · DARIUS THORNTON, 34 · chân dung chất riêng
- **Ngày:** 30/10/2026
- **Công cụ / model:** gpt-image-2.5, gửi qua Xưởng Phim Bigup 1.0.23 (`xuong.py tao-anh`) · **Gói:** trả phí qua cổng studio
- **Thiết lập:** 1024x1536 (dọc), 1 ảnh/lần
- **Tư liệu đầu vào:** không
- **Điểm riêng (VN):** mặt dài gầy, gò má cao, sống mũi hơi gồ; kính tròn gọng vàng mảnh; tóc 360 waves; râu ngắn lấm tấm bạc ở cằm; sẹo lông mày trái
- **Prompt:**

```text
Photoreal still from a prestige independent film, shot on ARRI Alexa 35 with an 85mm lens, soft motivated window light, fine 35mm film grain, unretouched real skin with natural pores, sheen and tiny imperfections; brown skin keeps its warm glow, never gray or ashy. Cast like a character-driven drama, not a model or influencer: a specific, memorable real person with naturally asymmetric features. A 34-year-old African American man, a gentle corporate heir and former runner. Lean long face, prominent cheekbones, a slightly bumped nose from an old fall, soft earnest eyes behind thin round gold wire-rim glasses; deep brown skin. Close-cropped hair brushed into neat 360 waves, a short tidy boxed beard with a hint of early gray at the chin. A thin pale scar cutting through his LEFT eyebrow (right side of the image). Navy quarter-zip over a white T-shirt. Shy, decent, a man of few words. Head-and-shoulders portrait, eye level. Plain warm-gray backdrop, one subject only. No text, no logo, no watermark, no collage.
```

- **Kết quả:** `09_media/ai-tao-ra/NV-DAR-03.png`
- **Đánh giá & quyết định:**

### NV-BIA-03 · BIANCA PIERCE, 30 · chân dung chất riêng
- **Ngày:** 30/10/2026
- **Công cụ / model:** gpt-image-2.5, gửi qua Xưởng Phim Bigup 1.0.23 (`xuong.py tao-anh`) · **Gói:** trả phí qua cổng studio
- **Thiết lập:** 1024x1536 (dọc), 1 ảnh/lần
- **Tư liệu đầu vào:** không
- **Điểm riêng (VN):** mặt nhỏ như búp bê, cằm nhọn, nốt ruồi duyên trên môi, son nâu anh đào; tóc vàng mật thẳng dài với MÁI BẰNG nặng (dáng nhận ra ngay); móng bạc chrome
- **Prompt:**

```text
Photoreal still from a prestige independent film, shot on ARRI Alexa 35 with an 85mm lens, soft motivated window light, fine 35mm film grain, unretouched real skin with natural pores, sheen and tiny imperfections; brown skin keeps its warm glow, never gray or ashy. Cast like a character-driven drama, not a model or influencer: a specific, memorable real person with naturally asymmetric features. A 30-year-old African American woman, a luxury hair influencer. Doll-like small face, sharp pointed chin, very arched thin brows, a beauty mark above the left corner of her lip, glossy cherry-brown lips, light honey-brown skin. Hair: a bone-straight glassy honey-blonde unit, waist length, with blunt heavy bangs cut straight at the brows - a severe, instantly recognizable silhouette. Long almond chrome-silver nails, one hand touching her collarbone. Cream high-neck knit, a thin gold chain. A pretty but cold, appraising stare. Head-and-shoulders portrait, eye level. Plain warm-gray backdrop, one subject only. No text, no logo, no watermark, no collage.
```

- **Kết quả:** `09_media/ai-tao-ra/NV-BIA-03.png`
- **Đánh giá & quyết định:**

### NV-EAR-03 · EARNESTINE ELLIS, 77 · chân dung chất riêng
- **Ngày:** 30/10/2026
- **Công cụ / model:** gpt-image-2.5, gửi qua Xưởng Phim Bigup 1.0.23 (`xuong.py tao-anh`) · **Gói:** trả phí qua cổng studio
- **Thiết lập:** 1024x1536 (dọc), 1 ảnh/lần
- **Tư liệu đầu vào:** không
- **Điểm riêng (VN):** nhỏ người, thẳng lưng, mặt dài, đồi mồi; MỘT răng bên bọc vàng khi cười; tóc bạc ép uốn sóng kiểu xưa (finger waves); kính mắt mèo vàng có dây; ghim cài áo cổ
- **Prompt:**

```text
Photoreal still from a prestige independent film, shot on ARRI Alexa 35 with an 85mm lens, soft motivated window light, fine 35mm film grain, unretouched real skin with natural pores, sheen and tiny imperfections; brown skin keeps its warm glow, never gray or ashy. Cast like a character-driven drama, not a model or influencer: a specific, memorable real person with naturally asymmetric features. A 77-year-old African American grandmother and church mother. Slim, small and upright, long face with deep laugh lines, a few age spots, very deep brown skin; one gold-capped side tooth that flashes when she grins. Silver hair pressed and set in neat old-fashioned finger waves close to her head. Gold cat-eye glasses on a beaded chain, a thin gold cross. Royal-blue church suit with a vintage brooch. A sly grin like she knows your secret. Head-and-shoulders portrait, eye level. Plain warm-gray backdrop, one subject only. No text, no logo, no watermark, no collage.
```

- **Kết quả:** `09_media/ai-tao-ra/NV-EAR-03.png`
- **Đánh giá & quyết định:**

## Tạo hình nhân vật — Vòng 4: chỉnh theo góp ý của tác giả
> Góp ý của tác giả (30/10/2026): Bianca cần thân hình gợi cảm hơn, vòng 1 và vòng 3 to hơn, đúng gu Mỹ gốc Phi; Darius trông hơi già. Bianca giữ mặt và tóc vòng 3 (ảnh gốc `NV-BIA-03.png`), làm ảnh ba phần tư người để thấy dáng; trang phục ôm nhưng kín (cổ cao, tay dài) để không bị kiểm duyệt khi gen video. Darius bỏ râu bạc và nếp nhăn, giữ kính, tóc waves, sẹo.

### NV-BIA-04 · BIANCA PIERCE, 30 · thân hình
- **Ngày:** 30/10/2026
- **Công cụ / model:** gpt-image-2.5, gửi qua Xưởng Phim Bigup 1.0.23 (`xuong.py tao-anh`) · **Gói:** trả phí qua cổng studio
- **Thiết lập:** 1024x1536 (dọc), 1 ảnh/lần
- **Tư liệu đầu vào:** `09_media/ai-tao-ra/NV-BIA-03.png`
- **Thay đổi (VN):** giữ mặt + tóc mái bằng của vòng 3; thân hình đồng hồ cát đầy đặn: ngực to, eo thon, hông và mông to, đùi đầy; váy bodycon kem cổ cao tay dài (kín, ôm sát) — gợi cảm nhưng an toàn kiểm duyệt
- **Prompt:**

```text
Photoreal still from a prestige independent film, shot on ARRI Alexa 35, soft motivated window light, fine 35mm film grain, unretouched real skin with natural pores and sheen; brown skin keeps its warm glow, never gray or ashy. Use the attached image as the exact face, skin tone, makeup and hair of this woman: same doll-like face, beauty mark above her lip, bone-straight waist-length honey-blonde hair with heavy blunt bangs. Three-quarter length shot from head to mid-thigh, standing in a confident angled pose, one hand on her hip showing long almond chrome-silver nails. She has a very curvy, voluptuous hourglass figure celebrated in Black American beauty culture: full large bust, tiny cinched waist, wide hips and a full round backside, thick thighs. She wears a fitted cream ribbed knit midi bodycon dress with a high neckline and long sleeves that hugs every curve, an oversized cream blazer draped on her shoulders, a thin gold chain. Tasteful and glamorous, fully covered, no cleavage. A cold, appraising stare. Plain warm-gray backdrop, one subject only. No text, no logo, no watermark, no collage.
```

- **Kết quả:** `09_media/ai-tao-ra/NV-BIA-04.png`
- **Claude soát (gợi ý, tác giả quyết):** đạt dáng đồng hồ cát đầy đặn, giữ đúng mặt + mái bằng + nốt ruồi + móng bạc, cổ cao tay dài; LỆCH: váy thành váy ngắn trên gối (thiết kế BI1 là dài qua gối).
- **Đánh giá & quyết định:**

### NV-DAR-04 · DARIUS THORNTON, 34 · trẻ lại
- **Ngày:** 30/10/2026
- **Công cụ / model:** gpt-image-2.5, gửi qua Xưởng Phim Bigup 1.0.23 (`xuong.py tao-anh`) · **Gói:** trả phí qua cổng studio
- **Thiết lập:** 1024x1536 (dọc), 1 ảnh/lần
- **Tư liệu đầu vào:** không
- **Thay đổi (VN):** giữ kính tròn gọng vàng, 360 waves, sống mũi gồ; trẻ lại: da căng, không nếp nhăn, râu đen tuyền không bạc, má đầy hơn, mắt sáng; sẹo lông mày trái rõ
- **Prompt:**

```text
Photoreal still from a prestige independent film, shot on ARRI Alexa 35, soft motivated window light, fine 35mm film grain, unretouched real skin with natural pores and sheen; brown skin keeps its warm glow, never gray or ashy. Head-and-shoulders portrait of a youthful, handsome African American man who looks 30 to 32, the romantic lead: smooth firm skin with no wrinkles and no gray hair, fuller youthful cheeks, a strong defined jaw, warm bright earnest eyes behind thin round gold wire-rim glasses, a slightly bumped nose from an old fall; deep brown skin with a healthy glow. Close-cropped black hair brushed into crisp 360 waves, a short neat jet-black boxed beard with sharp edges. A thin pale scar cutting vertically through his LEFT eyebrow, clearly visible (right side of the image). Athletic build of a runner, navy quarter-zip over a white T-shirt. A shy, warm half-smile. Eye level. Plain warm-gray backdrop, one subject only. No text, no logo, no watermark, no collage.
```

- **Kết quả:** `09_media/ai-tao-ra/NV-DAR-04.png`
- **Claude soát (gợi ý, tác giả quyết):** đạt trẻ lại (da căng, râu đen, không nếp nhăn), sẹo lông mày trái rõ, giữ kính + waves; mặt hơi đầy, nét ít 'dân chạy bộ' hơn vòng 3.
- **Đánh giá & quyết định:**

## Tạo hình nhân vật — Bước 2: trang phục (dùng ảnh chốt làm tham chiếu)

Sau khi chốt ảnh nhận diện, tạo từng mã trang phục trong `THIET_KE.md` mục 3.1: **đính kèm ảnh chốt** của nhân vật và dùng mẫu dưới. Mã lần thử: `TP-<mã trang phục>-01` (vd `TP-BV0-01`). Kiểu tóc theo mô tả của từng mã (vd BV1 búi thấp, BV3 vấn vương miện, AY1 búi cao, AY5 bím vấn vương miện, BI2 buộc rối).

Ưu tiên: **BV0** (cải trang, mở màn) → AY1/AY1M, BI1, DA1, EA2 → bộ dạ tiệc BV3, AY5, BI5, DA3, EA3, CH2 → các mã còn lại.

**Mẫu prompt đổi trang phục** — thay `[DẤU HIỆU]` bằng dòng "Must be clearly visible" của nhân vật, `[TRANG PHỤC]` bằng mô tả mã trang phục:

```text
Use the attached image as the identity reference. Keep exactly the same person: the same face, the same skin tone, the same distinctive marks ([DẤU HIỆU]). Change only the wardrobe and hairstyle to: [TRANG PHỤC]. Same layout: three views side by side (front head-and-shoulders, three-quarter head-and-shoulders, full-body standing), plain light-gray seamless studio background, soft even studio lighting, photorealistic. No text, no letters, no labels, no logos, no watermark.
```

### TP-BV0-01 · BEVERLY cải trang (cụm 1–12)
- **Ngày:**
- **Công cụ / model:** gpt-image-2.5, gửi qua Xưởng Phim Bigup 1.0.23 (`xuong.py tao-anh`) · **Gói:** trả phí qua cổng studio
- **Thiết lập:** 1536x1024 (ngang), 1 ảnh/lần, model mặc định của cổng
- **Tư liệu đầu vào:** ảnh chốt của Beverly (`09_media/ai-tao-ra/NV-BEV-xx.png`)
- **Mô tả (VN):** cùng khuôn mặt Beverly nhưng cải trang thành bà cụ nghèo: khăn trùm đầu ô liu bạc màu buộc dưới cằm giấu hết tóc, kính nhựa nâu dày trầy, cardigan nâu quá khổ xù lông ở khuỷu thiếu một khuy, váy hoa bạc màu dài qua bắp chân, tất dày màu be, giày chỉnh hình đen mòn mũi, túi nilon trắng nhàu, gậy gỗ quấn băng keo đen; không trang điểm, không trang sức. Vẫn phải thấy khe răng cửa và nốt ruồi.
- **Prompt:**

```text
Use the attached image as the identity reference. Keep exactly the same woman: the same face, the same deep brown skin tone, the same small gap between her upper front teeth, the same small mole on her LEFT cheekbone. Change only the wardrobe and styling: a faded olive headscarf tied under her chin that hides all of her hair; thick, scratched brown plastic eyeglasses; an oversized brown cardigan, pilled at the elbows, with one button missing; a faded floral house dress that falls below the calf; thick beige stockings; worn black orthopedic shoes; she holds a crumpled white plastic bag and a wooden cane with black electrical tape wrapped around the handle. No makeup, no jewelry, nothing looks new. She should read as a poor elderly woman who wandered into a luxury salon, while her face stays clearly recognizable; she smiles faintly in the front view so the gap in her teeth shows. Same layout: three views side by side (front head-and-shoulders, three-quarter head-and-shoulders, full-body standing), plain light-gray seamless studio background, soft even studio lighting, photorealistic. No text, no letters, no labels, no logos, no watermark.
```

- **Kết quả:** `09_media/ai-tao-ra/TP-BV0-01.png`
- **Soát trước khi chốt:** ☐ cùng khuôn mặt với ảnh chốt · ☐ khe răng cửa và nốt ruồi gò má TRÁI vẫn thấy · ☐ khăn giấu hết tóc · ☐ cardigan thiếu một khuy · ☐ gậy quấn băng keo đen ở tay cầm
- **Đánh giá & quyết định:**

## Bộ ảnh tham chiếu sản xuất (khuôn phim cũ — 30/10/2026)

> Tác giả chốt tạo hình: Beverly `NV-BEV-03`, Ayanna `NV-AYA-03` (giữ da mật ong-caramel), Darius `NV-DAR-04`, Bianca `NV-BIA-04` (giữ thân hình như tác giả yêu cầu), Earnestine `NV-EAR-03`; yêu cầu tạo toàn bộ nhân vật, bảng bối cảnh 4 góc và đạo cụ **theo khuôn các dự án trước** (BROKE ON PURPOSE, THE LOCKET, MOTHER OF THE GROOM).

- **Dự án ảnh:** `09_media/xuong/` — `du_an.json` (mô tả nhân vật theo cú pháp da của `06_tao_hinh_black_america.md`, 34 mã trang phục + 3 vai phụ nhỏ, 8 bảng 4 góc khai 4 tường, 21 đạo cụ). Ảnh ở `09_media/xuong/anh/`, bản gốc cổng trả ở `anh/_goc_ai/`.
- **Công cụ:** `scripts/tao_anh.py` của skill viết kịch bản (gói `xuong_anh`), gọi cổng Xưởng Phim Bigup 1.0.23, model mặc định gpt-image-2.5, 2 luồng, hậu kỳ `--bot-ai nhe`. Prompt từng ảnh do script dựng từ `du_an.json` theo khuôn cũ (mặt 1024x1536 → ảnh đồ → bảng nhân vật 2 ô 1920x1080 → bảng 4 góc 1920x1080 tự cắt 4 panel → đạo cụ); xem lại bằng `tao_anh.py --du-an 09_media/xuong anh --thu`.
- **Mã lần thử = tên file ảnh** (vd `OUTFIT_BV0`, `SHEET_AYANNA_AY1`, `VELOUR_BANG` → `VELOUR_DESK`, `PROP_WIG`). Ảnh mặt 5 vai chính chép từ ảnh đã chốt (`CHAR_BIANCA_FACE` cắt phần đầu-vai từ `NV-BIA-04`).
- **Đợt 1:** mặt 8 vai phụ + 34 ảnh đồ + 8 bảng 4 góc + 2 ngoại cảnh + 21 đạo cụ. **Đợt 2** (sau khi soát, lật ngang ảnh ngược bên): 36 bảng nhân vật 2 ô.
- **Kết quả (30/10/2026):** đợt 1 tạo 72/72 ảnh (8 mặt vai phụ, 34 ảnh đồ, 8 bảng 4 góc tự cắt 32 panel, 2 ngoại cảnh, 21 đạo cụ); đợt 2 tạo 36/36 bảng nhân vật 2 ô. `SHEET_CHARLENE_CH2C` (còng tay) bị chặn kiểm duyệt 2 lần, lần 3 qua.
- **Sửa lại:** `PROP_NOTICE` ra ảnh ghép nhiều cảnh, `LOC_VELOUR_BOARDWALK` ra biệt thự → viết prompt riêng ở `anh/_prompt_rieng.json`, tạo lại 1 lần, đạt.
- **Claude soát (gợi ý, tác giả quyết):** các bảng đều nằm ngang, mặt ô cận khớp ô toàn thân; Darius giữ kính + râu, Ayanna đúng Fulani braids cài hạt, Bianca giữ dáng đồng hồ cát. Cần tác giả xem kỹ: mặt Beverly ở ô cận hơi già và gầy hơn ảnh chốt `NV-BEV-03`; váy BI5 cúp ngực và BI1 váy ngắn có thể vướng kiểm duyệt khi gen video; ô cận mặt theo khuôn cũ để cổ trần (không áo).
- **Đánh giá & quyết định của tác giả:**

## Cảnh 1 — [tên cảnh]

### C01-01
- **Ngày:**
- **Công cụ / model:** [vd: Seedance 2.5] · **Gói:** [trả phí / miễn phí]
- **Thiết lập:** [tỷ lệ khung hình, thời lượng, seed, độ mạnh ảnh tham chiếu…]
- **Tư liệu đầu vào:** [file trong `09_media/tham-khao/`, do bạn tự làm hoặc có quyền dùng]
- **Prompt:**

```text

```

- **Kết quả:** `09_media/ai-tao-ra/C01-01.mp4`
- **Đánh giá & quyết định:** [Giữ / Bỏ / Sửa. Vì sao? Lần sau đổi gì?]

### C01-02
- **Ngày:**
- **Công cụ / model:** · **Gói:**
- **Thiết lập:**
- **Tư liệu đầu vào:**
- **Prompt:**

```text

```

- **Kết quả:** `09_media/ai-tao-ra/C01-02.mp4`
- **Đánh giá & quyết định:**
