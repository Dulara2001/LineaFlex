# Integrated Human Motion Monitoring System for Enhanced Productivity and Well-being in the Apparel Industry

## Background
The apparel industry relies on precision and efficiency, yet workers often face challenges such as incorrect hand movements and poor posture, which can hinder productivity and negatively impact their well-being. Traditional manual monitoring approaches are inconsistent and inefficient. To address these issues, our research introduces an advanced motion monitoring system that utilizes machine learning, camera systems, and sensors to revolutionize the industry by enhancing productivity and fostering a safer working environment.

---

## Research Objectives
The primary aim of this research is to design and implement a cutting-edge system that integrates real-time motion detection, posture recognition, and skill monitoring to optimize sewing operations. This system supports employee well-being, encourages better posture, and enhances operational efficiency by:

- Detecting target employees for optimized motion monitoring.
- Identifying and correcting incorrect hand movements in real time (**my contribution**).
- Monitoring sitting postures using sensors and machine learning.
- Providing personalized skill insights through a predictive dashboard.

---

## Main Problem
Imprecise hand movements during sewing processes often lead to lower efficiency, compromised product quality, and increased strain on workers. Conventional methods of monitoring these movements lack consistency, scalability, and real-time feedback mechanisms, necessitating an automated solution.

---

## My Contribution (Solution)
I focused on automating the detection and correction of incorrect hand movements, a critical component of the sewing process. By leveraging machine learning algorithms and real-time monitoring, my solution:

- Captures imprecise hand movements against General Sewing Data (GSD) standards.
- Provides real-time feedback to workers for immediate correction.
- Enhances sewing accuracy and product quality while reducing manual intervention.
- Collects actionable data for performance analysis and skill development.

---

## System Diagram
<img src="https://github.com/user-attachments/assets/6e3e923e-8fd3-4d9d-8249-eef3d430bfed" alt="System Diagram" width="700">



## Methodology
To achieve our objectives, we adopted the following structured approach:

1. **Data Collection**: Precise recordings of skilled operators’ sewing techniques were captured to create a comprehensive dataset meeting GSD standards. These recordings detailed the correct hand movements for each sewing stage.
2. **Data Preprocessing**: Collected data underwent noise removal and formatting to ensure suitability for analysis, forming the foundation for model training.
3. **Model Training**: Two machine learning classifiers, Random Forest and Support Vector Machine (SVM), were trained using labeled datasets. The dataset was split into 80% for training and 20% for testing. Random Forest was selected as the preferred model for its ability to handle high-dimensional data, deliver high accuracy, and provide interpretable results.
4. **Real-Time Validation**: The trained model was deployed in a manufacturing setting, enabling non-disruptive, real-time monitoring of sewing operations.
5. **Continuous Improvement**: Feedback from real-world deployment was used to refine and enhance the system, ensuring adaptability and long-term effectiveness.

---

## Result
<img src="https://github.com/user-attachments/assets/f1b41305-4b49-4eff-89a6-28c7d1ebdfb5" alt="Screenshot 2" width="200"/>
<img src="https://github.com/user-attachments/assets/1df4fa43-f65a-4ec1-8ad1-34c5a512de36" alt="Screenshot 3" width="200"/>





## Impact
This system represents a transformative step forward in the apparel industry, automating the detection and correction of incorrect hand movements, optimizing productivity, and supporting worker well-being. By leveraging machine learning, it provides a scalable and reliable solution that aligns with modern manufacturing demands, setting a benchmark for innovation in the sector.
