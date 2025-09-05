# 🛢️ Well Log Data ML Research — KNUST, with Dr. Caspar Daniel Adenutsi (2022)

## 🎯 Objective: Predict RHOB (bulk density) and NPOR (neutron porosity) from well log data

- 🔄 Workflow mirrored bioturbation ML research but with cross-well validation:

- 🏗️ Trained/validated on one well, tested on a completely separate well (Saltpond & Conger fields)

- 📊 Generated depth vs. RHOB/NPOR plots comparing predictions vs. actual logs

## ⚙️ Models & Methods:

- 🤖 TensorFlow with batch training, callbacks, and early stopping

- 🌲 XGBoost, 📉 Linear Regression, 📐 SVR, ✒️ Lasso/Ridge

- 🧹 Applied standard preprocessing and regularization techniques

- 🧠 Integrated domain knowledge for feature engineering

## 📂 Data Handling:

- 🛠️ Learned the LASIO framework to convert .las well log files to .csv

- 📉 Results:

- Saltpond dataset proved insufficient for robust conclusions

- Conger dataset required further preprocessing; models showed overfitting/overperformance artifacts

- ⏳ Project terminated due to TA tenure completion and data limitations
