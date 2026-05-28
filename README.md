# 📊 Exploratory Data Analysis (EDA) – Student Performance

> Exploratory Data Analysis project using Python, Pandas, Matplotlib, and Seaborn

---

## 📌 Project Overview

This project performs a complete **Exploratory Data Analysis (EDA)** on a student performance dataset. It explores patterns in scores across subjects (Maths, Science, English) and investigates how **attendance impacts academic performance**.

---

## 📁 Project Structure

```
Exploratory-Data-Analysis-EDA-Project/
│
├── Student_EDA.ipynb        # Main Jupyter Notebook
├── eda_students.csv         # Dataset
├── images/                  # Output screenshots & charts
│   ├── dataset_info.png
│   ├── statistical_summary.png
│   ├── avg_marks_bar.png
│   ├── attendance_histogram.png
│   ├── attendance_vs_marks.png
│   └── correlation_heatmap.png
├── requirements.txt
├── .gitignore
└── README.md
```

---

## 📋 Dataset

| Column | Type | Description |
|--------|------|-------------|
| Name | object | Student's name |
| Gender | object | Male / Female |
| Maths | int64 | Marks in Maths (out of 100) |
| Science | int64 | Marks in Science (out of 100) |
| English | int64 | Marks in English (out of 100) |
| Attendance | int64 | Attendance percentage |

- **Total Records:** 10 students
- **No missing values** across all 6 columns

### Dataset Preview
![Dataset Info](images/dataset_info.png)

---

## 📈 Statistical Summary

![Statistical Summary](images/statistical_summary.png)

| Metric | Maths | Science | English | Attendance |
|--------|-------|---------|---------|------------|
| Mean | 78.2 | 81.9 | 80.7 | 89.8 |
| Std | 11.33 | 11.45 | 12.99 | 7.57 |
| Min | 55 | 60 | 58 | 75 |
| Max | 91 | 95 | 96 | 99 |

🏆 **Top Performing Student: Anjali** (Average: 93.67, Attendance: 99%)

---

## 📊 Visualizations

### 1. Average Marks of Students (Bar Chart)
![Average Marks Bar Chart](images/avg_marks_bar.png)

### 2. Attendance Distribution (Histogram)
![Attendance Histogram](images/attendance_histogram.png)

### 3. Attendance vs Average Marks (Scatter Plot)
![Scatter Plot](images/attendance_vs_marks.png)

### 4. Correlation Heatmap
![Correlation Heatmap](images/correlation_heatmap.png)

---

## 💡 Key Insights

- 📌 **Attendance strongly correlates with performance** — students with higher attendance consistently score higher
- 📌 **All subjects are highly correlated** (0.96–0.98), indicating consistent performers across subjects
- 📌 **Top student: Anjali** with an average of 93.67 marks and 99% attendance
- 📌 **Lowest performer: Rohan** with 58 average marks and only 75% attendance
- 📌 The scatter plot shows a **clear upward trend** between attendance and average marks

---

## 🛠️ Tools & Libraries

| Tool | Purpose |
|------|---------|
| Python 3 | Programming language |
| Pandas | Data manipulation & analysis |
| Matplotlib | Data visualization |
| Seaborn | Statistical data visualization |
| Jupyter Notebook | Interactive coding environment |

---

## 🚀 How to Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/Exploratory-Data-Analysis-EDA-Project.git
   cd Exploratory-Data-Analysis-EDA-Project
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Launch Jupyter Notebook**
   ```bash
   jupyter notebook Student_EDA.ipynb
   ```

   > Or open directly in [Google Colab](https://colab.research.google.com/) by uploading the `.ipynb` file.

---

## 👤 Author

**Your Name**  
[GitHub](https://github.com/your-username) • [LinkedIn](https://linkedin.com/in/your-profile)
