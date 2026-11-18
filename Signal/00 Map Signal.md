# 🗺️ Map — Signal Chapter 1

> ศูนย์กลางโยงทุกเรื่องใน `Signal/` — เปิด `Graph view` แล้วจะเห็นเส้นโยงออกไป

```mermaid
flowchart TD
  MAP["00 Map Signal"] --> PDF1["[[PDF 1]]"]
  PDF1 --> EVO["[[Even-Odd]]"]
  PDF1 --> PER["[[Periodic]]"]
  PDF1 --> EP["[[Energy-Power]]"]
  PDF1 --> BASIC["[[Basic Signals]]"]
  PDF1 --> OPS["[[Operations]]"]
  PDF1 --> SYS["[[System Types]]"]
  PDF1 --> C2["[[คาบที่ 2]]"]
  EVO <--> PER
  PER <--> EP
  BASIC <--> OPS
  OPS <--> SYS
```

## เส้นหลัก
- [[PDF 1]] — สรุปใหญ่ Chapter 1
- [[คาบที่ 2]] — โน้ตในห้องเรียน

## เส้นย่อย (แตกหัวข้อให้กราฟแน่น)
- [[Even-Odd]] — คู่/คี่ + แยกส่วน
- [[Periodic]] — คาบ CT/DT + ตัวอย่าง 1.4/1.8-1.13
- [[Energy-Power]] — E/P + ตัวอย่าง 1.5-1.7
- [[Basic Signals]] — u/δ/r/sin/exp + sifting
- [[Operations]] — shift/scale/x(at+b)/ประตู u-r
- [[System Types]] — Memory/Causal/BIBO/T-Invariant/Linear

---
*วิธีดูเส้น: `Ctrl+G` (Graph) / โน้ตนี้ `...` → Open local graph*
