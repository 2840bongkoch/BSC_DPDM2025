# 📘 SC663403 — การเตรียมข้อมูลและการทำเหมืองข้อมูล  

---

## 📌 รายวิชา (Course Info)

### **รหัสวิชา:** `SC663403`  
### **ชื่อวิชา:** การเตรียมข้อมูลและการทำเหมืองข้อมูล  
### **ชื่อภาษาอังกฤษ:** Data Pre-processing and Data Mining

---

## 📝 คำอธิบายรายวิชา (TH)

แนวคิดของการเตรียมข้อมูล ชนิดและประเภทของข้อมูล เครื่องมือที่ใช้ในการเตรียมข้อมูล  
การจัดการข้อมูลในรูปแบบต่าง ๆ พื้นฐานของการทำเหมืองข้อมูลและแนวคิดเชิงพรรณนา  
การสกัดความรู้จากข้อมูล อัลกอริทึมการสร้างตัวแบบเพื่อการทำนาย  
การค้นพบความสัมพันธ์ในการทำเหมืองข้อมูล การจัดกลุ่มข้อมูล  
เทคนิคการประเมินตัวแบบ การเรียนรู้จากตัวแบบที่หลากหลาย  
และกรณีศึกษาที่เกี่ยวข้อง

---

## 📝 Course Description (EN)

Concept of data pre-processing, data and variable types, data pre-processing tools,  
manipulating various types of data, data mining primitives and concept description,  
knowledge elicitation, predictive modeling algorithms, mining association discovery,  
clustering, model evaluation techniques, multiple model learning,  
and current data mining topics with case studies.

---

## ✨ หัวข้อที่ครอบคลุม (Topics Covered)

- Data Pre-processing  
- Data Types & Variable Types  
- Data Cleaning / Integration / Transformation  
- Data Mining Concepts  
- Classification, Clustering, Association Analysis  
- Model Evaluation  
- Trend & Pattern Discovery  
- Case Studies in Data Mining 

---

## 📊 สัดส่วนคะแนนรายวิชา

| รายการประเมินผล | รายละเอียด | สัดส่วน (%) |
|------------------|-------------|--------------|
| **Midterm** | Data preprocessing (เดี่ยว) | **25%** |
| **Final** | ทฤษฎี Data Mining (เดี่ยว) | **25%** |
| **Project** | Data preprocessing + Data mining (ทำกลุ่ม 5–6 คน) | **20%** |
| **Homework** | แบ่งกลุ่มใหม่ทุกครั้ง | **15%** |
| **Quiz** | ทำเดี่ยว ตอบในห้อง | **10%** |
| **GitHub** | งานบน GitHub | **5%** |

### สูตรคำนวณคะแนนรวม  
**Final Score = Score × %Attendance**

---

# 📑 เนื้อหา (Contents)


# บทที่ 1: บทนำสู่การทำเหมืองข้อมูล (Introduction)
เนื้อหา:
- ความสำคัญของ Data Mining  
- Data Mining คืออะไร  
- กระบวนการ KDD  
- มุมมองแบบหลายมิติของ Data Mining  
- ประวัติการพัฒนา

📄 **สไลด์ประกอบ:**  
[Chapter 1 Intro](Slides/01IntroBongkoch.pdf)

# บทที่ 2: การทำความรู้จักข้อมูล  (Getting to Know Your Data)

เนื้อหา:
- ประเภทของชุดข้อมูล (Types of Data Sets)
- ลักษณะสำคัญของข้อมูล (Characteristics of Structured Data)
- วัตถุข้อมูลและชนิดแอตทริบิวต์ (Data Objects & Attribute Types)
- คำอธิบายเชิงสถิติพื้นฐาน (Basic Statistical Descriptions)
- การแสดงผลข้อมูล (Data Visualization)
- การวัดความคล้ายและความแตกต่างของข้อมูล  
  (Measuring Similarity & Dissimilarity)
  
📄 **สไลด์ประกอบ:**  
[Chapter 2 Data](Slides/02DataBongkoch.pdf)

# บทที่ 3: การเตรียมข้อมูล (Data Pre-processing)

เนื้อหา:
- การทำความสะอาดข้อมูล (Data Cleaning): จัดการข้อมูลที่สูญหาย (Missing values) และข้อมูลรบกวน (Noise)
- การรวมข้อมูล (Data Integration): การรวมข้อมูลจากหลายแหล่งและการจัดการข้อมูลที่ซ้ำซ้อน
- การลดรูปข้อมูล (Data Reduction): การลดจำนวนมิติ (Dimensionality Reduction) เช่น PCA
- การแปลงรูปข้อมูล (Data Transformation): การทำ Normalization และ Discretization

📄 **สไลด์ประกอบ:**
[Chapter 3 Pre-processing](Slides/03Preprocessingbongkoch.pdf)


# บทที่ 6: การวิเคราะห์รูปแบบที่พบบ่อย (Mining Frequent Patterns & Association Rules)

เนื้อหา:
- แนวคิดพื้นฐานของการหา Frequent Itemsets
- อัลกอริทึม Apriori
- การสร้างกฎความสัมพันธ์ (Association Rules)
- การวัดประสิทธิภาพ: Support, Confidence และ Lift

📄 **สไลด์ประกอบ:** 
[Chapter 6 Association Rules](Slides/06FPBasicBk.pdf)

# บทที่ 8: การจำแนกประเภทข้อมูล (Classification)

เนื้อหา:
- แนวคิดพื้นฐานของการจำแนกประเภท (Classification Concepts)
- การสร้างตัวแบบตัดสินใจ (Decision Tree Induction)
- อัลกอริทึมอื่นๆ เช่น Naïve Bayes, Support Vector Machines (SVM)
- การวัดประสิทธิภาพของตัวแบบ (Model Evaluation): Accuracy, Precision, Recall, F1-score

📄 **สไลด์ประกอบ:** 
[Chapter 8 Classification](Slides/08ClassBasic.pdf)

# บทที่ 9: การจำแนกประเภทข้อมูลระดับสูง (Advanced Classification)

เนื้อหา:
- การจำแนกประเภทเชิงสถิติ (Bayesian Classification)
- ตัวแบบการทำนายเชิงความน่าจะเป็น (Naive Bayes)
- การวัดประสิทธิภาพตัวแบบขั้นสูง (Advanced Evaluation Metrics)
- การปรับจูนพารามิเตอร์และการเลือกโมเดล

📄 **สไลด์ประกอบ:** 
[09 Class Advanced](Slides/09ClassAdvanced.pdf)

# บทที่ 10: การวิเคราะห์การจัดกลุ่มข้อมูล (Cluster Analysis)

เนื้อหา:
- แนวคิดพื้นฐานและประเภทของการจัดกลุ่ม (Cluster Analysis: Basic Concepts)
- อัลกอริทึมการแบ่งกลุ่ม (Partitioning Methods): K-Means
- อัลกอริทึมการจัดกลุ่มตามลำดับชั้น (Hierarchical Methods)
- การจัดกลุ่มตามความหนาแน่น (Density-Based Methods): DBSCAN
- การประเมินผลการจัดกลุ่ม (Clustering Evaluation)

📄 **สไลด์ประกอบ:** 
[10 Cluster Basic](Slides/10ClusBasic.pdf)

## 🛠️ เครื่องมือและภาษาที่ใช้ (Tools)
- **Language:** Python 🐍
- **Library:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
- **Platform:** Google Colab / Jupyter Notebook
- **Version Control:** GitHub
