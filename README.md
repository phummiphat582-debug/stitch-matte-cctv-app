# Stitch Matte CCTV Field Survey UI

เว็บแอพ static SPA สำหรับจำลองหน้าจอจาก `stitch_matte_monochrome_ui_design.zip`

## เปิดใช้งาน

เปิด `index.html` ด้วยเบราว์เซอร์ได้โดยตรง หรือรัน static server เช่น:

```powershell
python -m http.server 4173 --directory .
```

จากนั้นเปิด `http://localhost:4173/`

## หน้าจอที่รวมไว้

- แปลนสำรวจ: floor plan canvas, marker, FOV, zoom และรายละเอียด CAM-01
- อุปกรณ์: search, status/type filters, BOM summary, photo log และ export actions
- รายละเอียดอุปกรณ์: state matrix, network specs, DORI range, field photos และ offline save
- สรุป/ส่งออก: blueprint preview, export packages, layer switches และ PDF/Excel actions

ไฟล์รูปตัวอย่างใช้ URL เดียวกับ reference ที่แนบมา และมี fallback ซ่อนรูปอัตโนมัติเมื่อไม่สามารถโหลดภายนอกได้
