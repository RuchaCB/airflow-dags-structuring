# 🧩 Airflow DAG Structuring – From SubDAGs to Task Groups

This project demonstrates how to **refactor Apache Airflow DAGs** using modern structuring techniques. 
It begins with a classic **SubDAG-based implementation**, then upgrades to a cleaner, Airflow 2+ preferred design using **Task Groups**.

🔁 **Journey: SubDAGs → Task Groups**

---

## 🚀 What’s Inside

| Pattern             | DAG ID          | Description                                                                 |
|---------------------|-----------------|-----------------------------------------------------------------------------|
| 🛠️ SubDAGs         | `group_dag`     | Legacy pattern using `SubDagOperator` to encapsulate reusable logic        |
| ✅ Task Groups     | `group_tasks`   | Modern, lightweight task grouping using `TaskGroup` (Airflow 2+)          |

---

##📸 Output

Here are some screenshots showcasing the key outputs and results from running the pipeline.
##Step 1
![image](https://github.com/user-attachments/assets/4212aefe-e1fb-4eda-8d8f-ac71ecd25cd8)
##Step 2
![image](https://github.com/user-attachments/assets/b116fcfc-4a0d-4d12-98dd-322b79797dc9)
##Step 3
![image](https://github.com/user-attachments/assets/0cce3e6d-750a-42ba-8db7-5a9db7b1ef29)
##Step 3 Adios SubDAGs, Welcome TaskGRoups
![group_tasks gif](https://github.com/user-attachments/assets/eaf003d0-8c0c-46cd-a21a-018f972e01e6)



## 📚 Acknowledgment

This project is based on a learning exercise from the Udemy course:  
**[The Complete Hands-On Course to Master Apache Airflow](https://www.udemy.com/course/the-complete-hands-on-course-to-master-apache-airflow/)** by *Marc Lamberti*.


I recreated and extended the project for practice and personal learning. All credits for the original project structure and logic go to the course instructor.
