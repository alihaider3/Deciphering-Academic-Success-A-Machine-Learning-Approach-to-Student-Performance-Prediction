# Deciphering-Academic-Success-A-Machine-Learning-Approach-to-Student-Performance-Prediction

This project explores the factors influencing student academic performance using machine learning techniques. We analyze a dataset containing student demographics, academic behaviors, and grades to identify key predictors of success.

Dataset:

The analysis utilizes a CSV dataset comprising information on students from diverse nationalities and grade levels. The dataset includes a range of features such as:

Nationality

Grade level

Class participation (e.g., number of hands raised)

Attendance

Study habits (e.g., number of hours studied)

Other relevant academic factors

Methodology:

We employ various classification algorithms to build predictive models that determine the relationship between these features and student performance, as represented by their grades. The project evaluates the performance of several machine learning models to ascertain the most effective approach for this prediction task.

Results and Visualization:

The effectiveness of each model is evaluated, and the results are presented using clear visualizations, including:

Performance metrics: Accuracy, precision, recall, and F1-score are used to assess the predictive power of each model.

Visual aids: Graphs and confusion matrices provide an intuitive understanding of model performance and the impact of different features on student grades.

Goal:

The ultimate goal of this project is to accurately identify the factors that significantly influence student grades. This knowledge can be leveraged to develop targeted interventions and support strategies to enhance student learning and academic achievement.

***

Example:

1. Gender: "M" or "F"
   Example: `M`

2. Nationality: (any nationality)
   Example: `Kuwait`

3. Place of Birth: (any place)
   Example: `Kuwait`

4. Grade ID: Format should be "G-<number>" (G-02, G-04 through G-12)
   Example: `G-07`

5. Section: (any section)
   Example: `A`

6. Topic: (subject topic)
   Example: `Math`

7. Semester: "F" (Fall) or "S" (Spring)
   Example: `F`

8. Relation: "Father" or "Mum"
   Example: `Father`

9. Raised hands: (number)
   Example: `75`

10. Visited Resources: (number)
    Example: `40`

11. Announcements viewed: (number)
    Example: `30`

12. Number of Discussions: (number)
    Example: `50`

13. Parent Answered Survey: "Y" or "N"
    Example: `Y`

14. Parent School Satisfaction: "Good" or "Bad"
    Example: `Good`

15. Number of Absences: "Under-7" or "Above-7"
    Example: `Under-7`

After providing these inputs, the system will use five different machine learning models (Decision Tree, Random Forest, Perceptron, Logistic Regression, and Neural Network) to predict the student's class level (H-High, M-Medium, or L-Low).
