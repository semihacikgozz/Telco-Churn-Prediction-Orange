# Telco-Churn-Prediction-Orange

Bu proje bir telekomünikasyon şirketindeki müşterilerin hizmeti terk etme (churn) eğilimlerini analiz etmek ve makine öğrenmesi modelleri ile tahminlemek amacıyla hazırlanmıştır.

## Kullanılan Teknolojiler ve Araçlar
* **Orange Data Mining:** Veri madenciliği süreçleri.
* **Veri Seti:** Kaggle Telco Customer Churn.
* **Algoritmalar:** Logistic Regression, Random Forest, Decision Tree.

## Proje Adımları
1. **Veri Hazırlama:** Eksik veriler ortalama ile dolduruldu, `TotalCharges` sayısal tipe çevrildi ve gereksiz sütunlar (`customerID`) çıkarıldı.
2. **Görsel Analiz (EDA):** Sözleşme tiplerinin ve aylık ödemelerin terk etme oranına etkisi incelendi.
3. **Modelleme:** Veri %80 eğitim, %20 test olarak ayrıldı.
4. **Performans Ölçümü:** Modeller AUC ve CA değerlerine göre kıyaslandı.

## 📈 Sonuçlar
* **En İyi Model:** Logistic Regression (%81 Doğruluk oranı).
* **Kritik Bulgular:** En yüksek risk grubunun "Month-to-month" sözleşmeli müşteriler olduğu tespit edildi.
