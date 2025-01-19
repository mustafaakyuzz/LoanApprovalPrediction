# Loan Approval Prediction Project

## Project Overview
This project involves predicting loan approval statuses using machine learning models. The dataset contains information about applicants and their loan details. The final model achieves an accuracy score of **0.94**.

---

## Dataset
The dataset used for this project is **loan_approval_dataset.csv** and contains information about loan applicants, such as their education level, self-employment status, and financial details. Key columns include:
- **loan_id**: Unique identifier for each loan.
- **education**: Whether the applicant is a graduate (1) or not (0).
- **self_employed**: Whether the applicant is self-employed (1) or not (0).
- **loan_status**: Target column indicating loan approval (1) or rejection (0).

---

## Models Trained
Four models were trained and evaluated using `GridSearchCV` to find the best hyperparameters:
- **Decision Tree Classifier**
- **Random Forest Classifier**
- **K-Nearest Neighbors (KNN)**
- **Support Vector Machine (SVM)**

### Results:
- **Best Model**: Random Forest Classifier with an accuracy score of **0.94**.
- **Optimal Parameters**:
  - `max_depth`: None
  - `min_samples_split`: 5
  - `n_estimators`: 200

---

## Predicting Loan Status
The model can predict whether a loan request will be approved or rejected based on input applicant data.

---

## Conclusion
The Random Forest Classifier effectively predicts loan approval statuses with high accuracy. This tool can assist financial institutions in automating loan approval processes while ensuring consistent and reliable predictions.

---

# Kredi Onayı Tahmin Projesi

## Proje Genel Bakış
Bu proje, makine öğrenmesi modellerini kullanarak kredi onayı durumlarını tahmin etmeyi amaçlar. Veri seti, başvuru sahipleri ve kredi detayları hakkında bilgiler içermektedir. En son karar verilen modelde, **0.94 doğruluk skoru**na ulaşmıştır.

---

## Veri Kümesi
Bu proje için kullanılan veri kümesinde başvuru sahiplerinin eğitim durumu, serbest meslek sahibi olup olmadığı ve finansal detayları gibi bilgileri içermektedir. Önemli sütunlar:
- **loan_id**: Her kredi için benzersiz bir kimlik.
- **education**: Başvuru sahibinin mezun (1) veya değil (0) olduğunu belirtir.
- **self_employed**: Başvuru sahibinin serbest meslek sahibi (1) veya değil (0) olduğunu belirtir.
- **loan_status**: Kredinin onaylandığını (1) veya reddedildiğini (0) gösterir.

---


## Eğitilen Modeller
**GridSearchCV** kullanılarak en iyi hiperparametreleri bulmak için dört model eğitildi ve değerlendirildi:
- **Decision Tree Classifier**
- **Random Forest Classifier**
- **K-Nearest Neighbors (KNN)**
- **Support Vector Machines (SVM)**

### Sonuçlar:
- **En İyi Model**: Random Forest Classifier, **0.94 doğruluk skoru** ile.
- **En İyi Parametreler**:
  - `max_depth`: None
  - `min_samples_split`: 5
  - `n_estimators`: 200

---

## Kredi Durumunu Tahmin Etme
Model, başvuru sahibi verilerine dayanarak bir kredi talebinin onaylanıp onaylanmayacağını tahmin eder.

---

## Sonuç
**Random Forest Classifier**, kredi onayı durumlarını yüksek doğrulukla tahmin etmektedir. Bu araç, finans kuruluşlarının kredi onay süreçlerini otomatikleştirmelerine yardımcı olurken tutarlı ve güvenilir tahminler sağlar.
