# Smart_Irrigation_AICTE_Shell

This project demonstrates the development of an AI-powered Smart Irrigation System designed to optimize water usage in agriculture. The system uses real-time data from soil sensors (e.g., moisture, temperature, humidity) to make intelligent decisions about when and where to irrigate.

By employing a machine learning model trained on historical irrigation data, the system predicts whether each sprinkler (across 20 parcels) should be turned ON or OFF. The model is integrated into a Streamlit web application, where users can simulate sensor input using sliders (scaled between 0 and 1) and view instant predictions for each sprinkler zone.

### Key Features:
- **Automated irrigation control** based on real-time soil data.
- **ML model (.pkl)** predicts sprinkler status for each crop area.
- **User-friendly Streamlit app** for simulation and visualization.
- **20 sensor input support**, providing parcel-wise control.
- **Efficient water management** and reduced manual intervention.

###  Technologies Used:
- **Python** – Core programming language.
- **scikit-learn** – Machine learning model training and evaluation.
- **joblib** – For model serialization (`.pkl` file).
- **NumPy, Pandas** – Data manipulation and preprocessing.
- **Streamlit** – Web-based UI for user interaction.
- **Jupyter Notebook** – Model development and experimentation.

### Impact & Applications:
- **Conserves water** by eliminating over-irrigation.
- **Promotes crop health** through precise watering.
- **Scalable and modular** for larger farms with IoT integration.
- Useful in **remote or water-scarce regions** to automate irrigation.
- Encourages **eco-friendly, sustainable farming practices**.

###  Future Enhancements:
- Integration with **real-time IoT sensors** and edge devices (e.g., Raspberry Pi).
- Use of **weather APIs** for smarter, context-aware irrigation planning.
- **Cloud deployment** for mobile access and farm-wide analytics.
- Support for **crop-type specific irrigation patterns** using advanced ML.

### Repository Contents:
- `Smart_irrigation.ipynb` – Data analysis, model training, evaluation.
- `Farm_Irrigation_System.pkl` – Trained ML model.
- `app.py` – Streamlit application code.
- `irrigation_machine.csv` – Dataset used for training and testing.
- `README.md` – Project overview and documentation.

---

This project was developed as part of the **AICTE Internship Program in collaboration with Edunet Foundation**, focusing on the application of AI for real-world societal problems in agriculture.
