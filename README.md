#  Video Game Sales Analysis Dashboard

โปรเจกต์นี้วิเคราะห์ข้อมูลยอดขายวิดีโอเกมจาก Kaggle โดยใช้ **Tableau** เพื่อแสดงภาพรวมแนวโน้มยอดขายตามปี แยกตามแพลตฟอร์ม ประเภทเกม และภูมิภาคต่างๆ (NA, EU, JP)

---

##  Tableau Dashboard Overview

![Tableau Dashboard](Dashboad1.jpg)

---

##  รายละเอียดใน Dashboard

### 1.  แนวโน้มยอดขายตามเวลา (Global Sales by Year)
- **ประเภทกราฟ**: Line Chart
- **Insight**: ยอดขายพุ่งสูงสุดช่วงปี 2006–2010 และลดลงหลังจากนั้น

---

### 2.  ยอดขายตามแพลตฟอร์ม (Platform over Time)
- **ประเภทกราฟ**: Multi-line Chart
- **Insight**: PS2, Wii, และ DS มียอดขายสูงในยุค 2000s, Xbox 360 และ PS3 ตามมา

---

### 3.  ยอดขายตามภูมิภาค
- **ประเภทกราฟ**: Treemap (แยกตาม NA, EU, JP)
- **Insight**:
  - NA ชอบเกมแนว Action และ Shooter
  - JP นิยม RPG
  - EU มียอดขายใกล้เคียง NA แต่หลากหลายกว่า

---

### 4.  ยอดขายตามประเภทเกมและ Platform
- **ประเภทกราฟ**: Horizontal Bar Chart
- **Field ที่ใช้**: `Genre + Platform` (Combined Field)
- **Insight**: Action-PS2 และ Sports-Wii ทำยอดขายสูงสุด

---

### 5.  Top 10 เกมยอดขายสูงสุด (แยกตามภูมิภาค)
- **ประเภทกราฟ**: Bar Chart
- **Insight**: 
  - NA: Need for Speed, LEGO, FIFA ขายดี
  - JP: ซีรีส์ Final Fantasy และ Pokémon ครองอันดับต้นๆ
  - EU: FIFA ครองอันดับท็อปต่อเนื่องหลายเวอร์ชัน

---

##  Dataset
-  [Kaggle: Video Game Sales Dataset](https://www.kaggle.com/datasets/gregorut/videogamesales)

##  Tools Used
- Tableau (Data Visualization)
- Python (Data Cleaning)
- GitHub (Project Hosting)


