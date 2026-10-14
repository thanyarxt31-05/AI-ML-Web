# Visualize Machine Learning Algorithm

เว็บจำลองการทำงานของอัลกอริทึม Machine Learning แบบโต้ตอบได้ 14 หน้า แต่ละหน้าเป็นไฟล์ HTML เดียวจบ (CSS และ JavaScript อยู่ในไฟล์) ไม่ต้องติดตั้งไลบรารีใด ๆ

| # | ไฟล์ | อัลกอริทึม |
|---|------|-----------|
| 1 | `01-linear-regression.html` | Linear Regression |
| 2 | `02-logistic-regression.html` | Logistic Regression |
| 3 | `03-knn.html` | k-Nearest Neighbors |
| 4 | `04-decision-tree.html` | Decision Tree |
| 5 | `05-random-forest.html` | Random Forest |
| 6 | `06-svm.html` | Support Vector Machine |
| 7 | `07-kmeans.html` | K-Means |
| 8 | `08-mlp.html` | MLP Neural Network |
| 9 | `09-cnn.html` | CNN |
| 10 | `10-lstm.html` | LSTM |
| 11 | `11-transformer.html` | Transformer |
| 12 | `12-reinforcement-learning.html` | Reinforcement Learning |
| 13 | `13-xgboost.html` | XGBoost |
| 14 | `14-stacking.html` | Stacking |

## ดูหน้าเว็บ
**https://thanyarxt31-05.github.io/AI-ML-Web/**

ที่อยู่ของ repository (เก็บโค้ด): https://github.com/thanyarxt31-05/AI-ML-Web

## วิธีเปิดดูในเครื่อง
ดับเบิลคลิกไฟล์ `index.html` หรือไฟล์ของแต่ละอัลกอริทึม

## วิธีขึ้น GitHub Pages
1. สร้าง repository แบบ Public (ที่นี่ใช้ชื่อ `AI-ML-Web`)
2. กด **Add file > Upload files** แล้วลากไฟล์ทั้งหมดในโฟลเดอร์นี้ขึ้นไป แล้วกด **Commit changes**
3. ไปที่ **Settings > Pages** เลือก Source เป็น **Deploy from a branch**, Branch เป็น `main` และโฟลเดอร์ `/ (root)` แล้วกด **Save**
4. รอประมาณ 1 นาที หน้าเว็บจะอยู่ที่ `https://<ชื่อผู้ใช้>.github.io/<ชื่อ repo>/`
   ชื่อ repo ต้องสะกดตัวพิมพ์ใหญ่-เล็กให้ตรงกับที่ตั้งไว้

> ลิงก์ที่ลงท้ายด้วย `.git` (เช่น `https://github.com/<ชื่อผู้ใช้>/<ชื่อ repo>.git`) เป็นที่อยู่ของ repository สำหรับคำสั่ง git เท่านั้น ไม่ใช่ลิงก์หน้าเว็บ

หรืออัปโหลดด้วยคำสั่ง git:
```bash
git init
git add .
git commit -m "Visualize Machine Learning Algorithm"
git branch -M main
git remote add origin https://github.com/thanyarxt31-05/AI-ML-Web.git
git push -u origin main
```
