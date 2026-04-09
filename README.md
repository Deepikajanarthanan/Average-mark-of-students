📊 Student Best-of-Two Average Calculator

📌 Project Description

This project calculates the average of the best two marks for each student using Python and a CSV dataset.
The implementation is done in a Jupyter Notebook (.ipynb) and includes a pie chart visualization.

---

🚀 Features

- 📥 Read student data from a CSV file
- 🧮 Select best two marks for each student
- 📊 Calculate average based on best two marks
- 🥧 Generate a pie chart for visualization
- 📒 Implemented using Jupyter Notebook

---

🛠️ Technologies Used

- Python
- Pandas
- Matplotlib
- Jupyter Notebook

---

📂 Project Structure

student-best-two-average/
│── data.csv
│── best_two_average.ipynb
│── pie_chart.png
│── README.md

---

📊 Dataset (CSV File)

The dataset contains marks of students in multiple subjects.

Example:

Name,Maths,Science,English
Alice,80,75,90
Bob,60,70,65
Charlie,85,95,80
David,50,55,60

---

▶️ How to Run the Project

1. Install required libraries:

pip install pandas matplotlib notebook

2. Open Jupyter Notebook:

jupyter notebook

3. Open the file:

best_two_average.ipynb

4. Run all cells to see results and pie chart

---

🧠 Logic Used

- Read CSV file using pandas
- For each student:

best_two = sorted(marks, reverse=True)[:2]
average = sum(best_two) / 2

- Store and display results
- Visualize using pie chart

---

🥧 Pie Chart

The pie chart shows the distribution of average marks (best two subjects) among students.

---

📌 Future Improvements

- Support more subjects dynamically
- Add ranking system
- Export results to Excel

---

🙌 Conclusion

This project helps understand:

- Data processing using pandas
- Logic building (best-of-two selection)
- Data visualization using pie charts
- Working with Jupyter Notebook

---

⭐ Author

Deepika




