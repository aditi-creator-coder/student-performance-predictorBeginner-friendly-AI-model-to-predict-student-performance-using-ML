 📊 Student Performance Predictor

## 📖 Overview  
This is a beginner-friendly AI project that predicts student academic performance based on various inputs such as study time, attendance, and past scores. It uses machine learning techniques to help understand patterns and support academic decisions.

## 🚀 How It Works
1. **Load Dataset** – The dataset contains student features like study hours, attendance, and marks.  
2. **Data Preprocessing** – Cleans and prepares the data for training.  
3. **Train Model** – Uses ML algorithms like Linear Regression or Random Forest to train the prediction model.  
4. **Make Predictions** – Predicts final scores or grade category based on input features.  
5. **Visualize Results** – Displays charts to help understand student trends and performance factors.

### 🔍 Example  
If a student has:
- Study Hours: 3 hours/day  
- Attendance: 92%  
- Previous Score: 78  

The model might predict a performance score around **80-85** depending on the training data.

## 📂 Files Included

| File Name                        | Description                                  |
|----------------------------------|----------------------------------------------|
| `student_performance_predictor.py` | Main ML script for training and predicting   |
| `student_data.csv`               | Sample dataset with student information      |
| `README.md`                      | Project explanation and usage instructions   |

## 💻 How to Run the Project

1. **Install Dependencies**  
   ```bash
   pip install pandas scikit-learn matplotlib seaborn
   ```

2. **Run the Project**  
   ```bash
   python student_performance_predictor.py
   ```

## ✅ Dataset Sample

```
StudyHours,Attendance,PreviousScore,FinalScore
2,85,70,72
4,90,80,84
3,75,65,68
5,95,85,89
1,60,50,52
```

## 📌 Requirements
- Python 3.x  
- pandas  
- scikit-learn  
- matplotlib  
- seaborn  

## 📈 Future Improvements
- Add more features like sleep schedule, participation, etc.  
- Include deep learning methods (like neural networks)  
- Build a simple web app using Streamlit  

## 👩‍💻 Author
**Aditi Saha**  
Made with ❤️ for academic learning and showcasing beginner-level ML skills.
