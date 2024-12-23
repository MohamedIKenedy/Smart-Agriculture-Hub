# Smart Agriculture Hub 🌾

A comprehensive machine learning platform for smart agriculture, combining crop recommendation and milk quality prediction systems.

![Agriculture Banner](https://www.synox.io/wp-content/uploads/2022/04/smart-farming-smart-agriculture-iot.jpg)

## 🚀 Features

- **Crop Recommendation System**: Intelligent crop suggestions based on soil and environmental parameters
- **Milk Quality Prediction**: Advanced ML model for predicting milk quality metrics
- **Label Encoding**: Automated data preprocessing for categorical variables

## 📋 Project Structure

```
Smart-Agriculture-Hub/
├── Crop_Recommend_model.pkl    # Trained crop recommendation model
├── Crop_recommendation.csv     # Dataset for crop recommendations
├── crop_recommendation.ipynb   # Jupyter notebook for crop analysis
├── label_encoder.pkl          # Label encoder for categorical data
└── milk-quality-prediction.ipynb  # Milk quality analysis notebook
```

## 💻 Technologies Used

- Python 3.x
- Scikit-learn
- Pandas
- NumPy
- Jupyter Notebook

## 🛠️ Installation & Setup

1. Clone the repository:
```bash
git clone https://github.com/MohamedIKenedy/Smart-Agriculture-Hub.git
cd Smart-Agriculture-Hub
```

2. Install required dependencies:
```bash
pip install -r requirements.txt
```

## 📊 Models

### Crop Recommendation System
- Uses machine learning to suggest optimal crops based on:
  - Soil parameters
  - Climate conditions
  - Regional factors

### Milk Quality Prediction
- Predicts milk quality using parameters such as:
  - pH levels
  - Temperature
  - Taste
  - Odor
  - Fat content
  - Turbidity

## 🎯 Usage

### For Crop Recommendations:
```python
import pickle

# Load the model
with open('Crop_Recommend_model.pkl', 'rb') as file:
    model = pickle.load(file)

# Make predictions
prediction = model.predict([[N, P, K, temperature, humidity, ph, rainfall]])
```

### For Milk Quality Prediction:
```python
# Load and run the Jupyter notebook
jupyter notebook milk-quality-prediction.ipynb
```

## 📈 Results

![Sample Results]([https://via.placeholder.com/600x300.png?text=Sample+Results+Visualization](https://freeeway.com/wp-content/uploads/2023/04/IoT-in-agriculture-%E2%80%93-6-smart-farming-examples-1.png))

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## 👥 Authors

- Mohamed IFQIR - *Initial work*

## 🙏 Acknowledgments

- Thanks to all contributors who helped in building this project
- Special thanks to the agricultural research community for domain expertise
- Appreciation to the open-source ML community

---
⭐ Star this repository if you find it helpful!
