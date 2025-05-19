# 🚗 Parking Availability Prediction using Random Forest Regressor and LightGBM

This project uses machine learning models—**Random Forest Regressor** and **LightGBM**—to predict parking spot availability in Singapore. The dataset is sourced from [yoshall's GitHub repository](https://github.com/yoshall).

---

## 🎯 Project Goals

1. Predict the number of available parking spots in real time  
2. Simulate a data science role at JustPark  
3. Explore and improve model performance using different algorithms and data volumes

---

## 📊 Model Comparison

| Metric   | Random Forest (10% Data) | LightGBM (100% Data) |
|----------|--------------------------|-----------------------|
| MAE      | 52.83                    | **21.47**             |
| RMSE     | 77.24                    | **41.41**             |
| R² Score | 0.89                     | **0.97**              |
| Accuracy | 70.97%                   | **88.34%**            |

✅ **LightGBM significantly outperformed Random Forest**, benefiting from access to the full dataset and efficient training on large volumes of structured data.

---

## 🧰 Technologies Used

- Python  
- LightGBM  
- Random Forest (from Scikit-learn)  
- Pandas, NumPy  
- Scikit-learn (metrics, train-test split)  
- Matplotlib (for visualization)

---

## 📁 Project Structure

├── parking_availability/
│ ├── raw/ # Raw .npz and .csv files
│ ├── notebooks/ # Jupyter Notebooks
│ ├── exported/ # Exported HTML reports
├── README.md
