# Portfolio — Vũ Duy Thông (Mason) · Performance Marketing Specialist

Portfolio cá nhân 1 file (`index.html`), CSS/JS + icon SVG nhúng sẵn, không cần build / không cần internet.
Định vị: **"Tôi xây hệ thống để hiểu VÌ SAO ads thắng hay thua"**.

## Cấu trúc
1. **Hero / About** — giới thiệu: lĩnh vực (khách sạn 2–4★ · nội thất · dinh dưỡng), kỹ năng
   (Meta Ads · Google Ads · Landing Page · Marketing Automation), LinkedIn + email + SĐT. *(Đã bỏ khối 4 chỉ số.)*
2. **Case Study — MEANDER** *(Dự án mới nhất)*: bối cảnh (6 chi nhánh, 2–4★, vào lúc chưa có gì) →
   **chart tăng trưởng ROAS theo tháng** (0 → ổn định 3–4x) → kết quả → 7 thị trường + insight → creative.
3. **Systems & Process** — Testing System (6 biến test + "vì sao quan trọng") + Funnel diagnostic.
4. **Dự án khác** — **slider** (Orgalife · dinh dưỡng + slide CTA "dự án kế tiếp").
5. **Certifications** — 4 chứng chỉ logo + link xác minh.
6. **Contact.**

> Toàn bộ icon là **SVG vẽ tay** (không emoji). Cờ quốc gia cũng là SVG. Đã bỏ mọi nhắc tới quy đổi VND.

## ⚠️ Cần biết / điền
- **Chart ROAS**: đường ROAS theo tháng là **đường tăng trưởng đại diện** (idealized) cho hành trình
  0 → 3–4x, không phải số ROAS thô từng tháng (số tháng thô bị trộn tiền tệ nên nhiễu & thấp hơn thực tế).
  Mốc tổng: blended ROAS ~3.3x. Nếu cần đường ROAS chính xác từng tháng quy đổi VND → báo mình kéo thêm data.
- **Ngày tham gia MEANDER** đang để **06/2025** (bạn từng ghi 2/6/2026 = tương lai). Sửa trong `#case` nếu khác.
- **2 tên chứng chỉ** "Google Ads Certification" (Skillshop) + "Digital Marketing — Professional Certificate"
  (Coursera) là tên gần đúng — sửa đúng tên thật trong `#certs`.

## Ảnh cần bỏ vào (chưa có thì tự hiện placeholder)
- `assets/meta/` — ảnh static (tất cả tỉ lệ **4:5** dạng IG feed):
  - A/B test (4 ảnh):
    - `osaka-namba.jpg` — Osaka Variant A: Couple Base · 2-min walk Namba
    - `osaka-july.jpg` — Osaka Variant B: "Osaka in July smarter, quieter, better value"
    - `1948-gift-flat.jpg` — 1948 Variant A: travel gift flat lay
    - `1948-gift-bedroom.jpg` — 1948 Variant B: stay 2+ nights bedroom lifestyle
  - "Creative khác" mini-slide (4 ảnh đa ngôn ngữ):
    - `taipei-solo-zh.jpg` — Taipei Solo · 中文
    - `taipei-heart.jpg` — Taipei "Heart of Taipei" · EN
    - `saigon-family.jpg` — Saigon "Family base" · EN
    - `taipei-solo-de.jpg` — Taipei Solo · DE (German)
- `assets/meta/oani-logo.png` — **logo vuông xanh Oani** (Meander Collection) cho LP thumbnail. Background card đã set sẵn màu sage green #4D6C46 để khớp logo.
- `assets/other/` — slider: `orgalife.jpg` (tỉ lệ **16:9**). Slide 2 là CTA "dự án kế tiếp" — không cần ảnh.
- 3 thumbnail KOL Reel (tỉ lệ **4:5**) cũng đặt trong `assets/meta/`:
  - `greanleila.jpg` → card @greenleila (Meander 1948) — *lưu ý tên file có typo nhưng đã match*
  - `venice.jpg` → card @venice_mendoza (Osaka, Top Performer)
  - `dnvrchoi.jpg` → card @dnvrchoi (Oani Taipei)
- `assets/meta/mason-hero.jpg` — **ảnh chân dung** làm nền hero (phía phải, fade sang trái). Tự hide trên mobile.

> **Landing page card** (Oani Taipei) — thumb dùng logo vuông xanh `assets/meta/oani-logo.png`
> trên nền sage green. Link card → `https://oani-taipei.staymeander.com/`.

## Thông tin cá nhân (đã điền)
Email `vvuduythong@gmail.com` · ĐT `0362 167 934` · LinkedIn `linkedin.com/in/vuduythong`.

## Mở / host
```powershell
cd C:\Users\mason\port
python -m http.server 8080   # http://localhost:8080
```
Host nhanh: kéo thư mục `port` vào **Netlify Drop** (app.netlify.com/drop).
