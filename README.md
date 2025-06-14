## 🌡️ **Plant Disease Detection - Deep Learning Project**
 
### **Project Objective**

This project focuses on solving the crop diseases reduce agricultural yields, threatening food security issues farmers as part of the capstone project for the Frontier ML Bootcamp program. This project aims to develop an AI system using image recognition to detect crop diseases early, enabling farmers and agricultural technicians to act swiftly and provide solutions. This project could be scaled to benefit diverse crops and regions, amplifying its impact on a country’s agriculture.

> **Relevance to Sustainable Development Goals (SDGs):**
  This project aligns with SDG 2: Zero Hunger by enhancing food security through sustainable agriculture and SDG 12: Responsible Consumption and Production by minimizing crop waste.

### 📂 **Project Structure**

```
plant-disease-detector/
  ├── app/
  │   ├── main.py                   
  │   └── requirements.txt            
  ├── model/
  │   └── disease_detector_v1.h5      
  ├── notebooks/
  │   └── plant-disease-prediction.ipynb 
  ├── demo/
  ├── images/                          
  ├── class_indices.json              
  ├── requirements.txt              
  ├── .gitignore                 
  └── README.md   
```

> Refer to the notebook [Here](https://github.com/edasaruhan/FTL_Ethiopia_ML2_Gr3/notebooks/plant-disease-prediction.ipynb) for more detail.

### 🔧 **Tools Used**

<p>
<img src="https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white">
<img src="https://img.shields.io/badge/-TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white">  
<img src="https://img.shields.io/badge/-Streamlit-FF4B4B?style=flat&logo=streamlit&logoColor=white">
<img src="https://img.shields.io/badge/-Keras-D00000?style=flat&logo=keras&logoColor=white"> 
<img src="https://img.shields.io/badge/-scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white">
<img src="https://img.shields.io/badge/-NumPy-013243?style=flat&logo=numpy&logoColor=white">
<img src="https://img.shields.io/badge/-Pandas-150458?style=flat&logo=pandas&logoColor=white">
<img src="https://img.shields.io/badge/-Matplotlib-11557C?style=flat&logo=matplotlib&logoColor=white">
<img src="https://img.shields.io/badge/-Seaborn-3888E3?style=flat&logo=seaborn&logoColor=white">
</p>



### 📦 **Setup and Installation**

Follow these steps to set up and run the project:

1. Clone the repository:
    ```bash
    git clone https://github.com/edasaruhan/FTL_Ethiopia_ML2_Gr3.git
    cd FTL_Ethiopia_ML2_Gr3
    ```

2. Install dependencies:
   ```bash
    pip install -r requirements.txt
   ```
3. Run the script:
   ```bash
    streamlit run app/main.py
   ```
4. Provide inputs when prompted:

   - Place your pre-trained model disease_detector_v1.h5 inside a model/ directory in the project root.
   - Place your class_indices.json file in the project root.
  
5. Results:

   - The app will display the prediction of the leaf as unhealthy or healthy ***eg. test_blueberry_healthy***.



### ✨ **Demo**
![Disease Prediction Demo](https://raw.githubusercontent.com/edasaruhan/FTL_Ethiopia_ML2_Gr3/main/demo/disease_prediction%202.PNG)


### 🚀 **How It Works**

1. Upload Image 🖼️: Just drop your image into the app.
2. Magic Prep ✨: Clean it up—resize, reshape, and get it ready for the model.
3. Predict! 🤔: The model takes a look and guesses what it is.
4. See Results! ✅: App Shows you the answer!


### 📝 **License**

This project is licensed under the MIT License. See [LICENSE](./LICENSE) file for more details.


### 🧑‍🤝‍🧑 **Project Constributors**
```python
- Abenezer Tesfaye
- Shewanek Zewdu
- Emran Kamil 
- Hewan
- Biniyam Berga 
```
