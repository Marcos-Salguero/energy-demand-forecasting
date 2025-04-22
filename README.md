# ⚡ Electric Energy Demand Forecasting with Neural Networks  

Hello everyone! My name is Marcos Salguero Carrero, and here is my Bachelor's Thesis on forecasting electricity demand using Neural Networks. Throughout this project, we will go through all the necessary steps from data collection, processing, model development, and final prediction evaluation. For this project, I used TensorFlow's Keras library to develop both recurrent (RNN) and convolutional (CNN) neural network models.  

## 📌 Description  

This project uses neural networks to predict electricity demand based on historical data. Deep learning techniques are employed to improve accuracy and detect patterns in energy consumption.  

## 🚀 Features  

✅ Processing and cleaning of historical electricity consumption data.  
✅ Implementation of neural networks with **TensorFlow/Keras**.  
✅ Model evaluation using error metrics (MAE, RMSE, etc.).  
✅ Visualization of results and future predictions.  

## 📂 Project Structure  

📁 energy-demand-forecasting  
│── 📂 data/                 # Electricity consumption datasets  
│── 📂 models/               # Trained models  
│── 📂 src/                  # Project source code  
│── ── requirements.txt      # Project dependencies  
│── ── README.md             # Project documentation  

## 🛠️ Installation and Setup  

### 1️⃣ Clone the Repository  

```bash  
git clone https://github.com/Marcos-Salguero/energy-demand-forecasting.git  
cd energy-demand-forecasting
```

2️⃣ Create and Activate a Virtual Environment
```bash
python -m venv venv  
source venv/bin/activate  # On macOS/Linux  
venv\Scripts\activate     # On Windows
```

3️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

📊 Usage    

🔹 Load the Model

In the models folder, you will find models in .pkl format, which you can use to generate predictions and later compute a weighted average of all of them to obtain the final forecast. Remember that the input data must be in the same format as the one the model was trained on (21,289).

📈 Results and Evaluation   
The results can be visualized in plots generated with matplotlib and seaborn, showing the model’s accuracy compared to real data.

📄 License  
This project is licensed under the MIT License.

📞 Contact  
📧 Email: msalgueroc@gmail.com

🌍 GitHub: github.com/Marcos-Salguero