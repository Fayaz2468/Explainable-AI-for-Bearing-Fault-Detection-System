Link for published paper: https://ieeexplore.ieee.org/document/10183502

The Project "Explainable AI for Bearing Fault Detection System" focuses on the development and implementation of a machine learning-based system for detecting and diagnosing faults in rotating machinery bearings. Here is a short summary of the project:


1. **Introduction:**
   - The project emphasizes the importance of maintaining rotating machinery in industrial processes due to their critical role and frequent use.
   - Bearings, being crucial components, are prone to damage from fluctuating speeds, loads, and various fault severities, potentially leading to machine downtime and economic loss.
   - Fault detection techniques are necessary to identify and mitigate these issues before they cause major damage.

2. **Methodology:**
   - The proposed system uses vibration signal data from machinery, which is converted into statistical data for fault detection.
   - A machine learning classification model, CatGBoost, is used to detect and classify faults in the bearings.
   - Explainable AI, specifically SHapley Additive exPlanations (SHAP), is employed to understand the model's predictions and the impact of each feature on the fault classification.

3. **Case Study:**
   - The project utilizes the NASA dataset for bearing fault detection and classification, which includes vibration signals collected from bearings under controlled conditions.
   - Feature extraction and selection are performed on the collected data to create a dataset suitable for the machine learning model.
   - The system's architecture involves data collection, feature extraction, feature selection, fault detection, and model explanation using SHAP.

4. **Results and Discussion:**
   - The proposed system effectively detects and classifies bearing faults, providing explanations for the model's predictions through SHAP values.
   - The explainable AI approach enhances the transparency and reliability of the fault detection system, making it more understandable and acceptable for human experts.

5. **Conclusion and Future Work:**
   - The project concludes that the integration of machine learning and explainable AI provides a robust solution for bearing fault detection and diagnosis.
   - Future work includes improving the model's accuracy, testing with other datasets, and extending the approach to other types of machinery and fault detection scenarios.
