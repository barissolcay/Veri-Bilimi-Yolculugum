# 📘 Detaylı Yol Haritası: Veri Profesyonelliği (2025-2026)

Merhaba! Bu doküman, son sınıf bilgisayar mühendisliği öğrencisi olarak 1 yıllık veri mühendisliği ve analistliği yolculuğumun takip listesidir. Her görevi tamamladığımda ✔️ ile işaretleyeceğim.

---

## 🗓️ Genel Strateji
- **Toplam Süre:** 40-45 hafta
- **Haftalık Rutin:** 10-15 saat (Aktif Üretim ≥ %70, Pasif Öğrenme ≤ %30)
- **GitHub Stratejisi:** Tüm çalışmalar tek bir Capstone Proje repo'sunda toplanacak, her hafta düzenli `commit` yapılacak ve `README` güncellenecek.

---

## 🎯 Stratejik Çerçeve ve Capstone Proje
- **Tek Capstone Proje:** Tüm aşamalar, **"E-ticaret Kullanıcı Davranış Analizi ve Churn Tahmini"** adlı tek bir proje etrafında birleşecek. Projenin ana hedefi, teknik metriklerin ötesinde, **iş değerini (örn: kurtarılan müşteri geliri)** ortaya koymaktır.
- **Odaklanmış Teknoloji Yığını:** **GCP (BigQuery, Cloud Composer) + dbt + Power BI + MLflow + FastAPI**.
- **Ölçülebilir Hedefler:** Her aşamanın çıktısı somut teknik (ROC-AUC, PR-AUC) ve iş (KPI) metrikleriyle ölçülecek.
- **Uygulama Disiplini:** Sürekli kurs izlemek yerine, zamanın çoğu kod yazarak ve proje geliştirerek geçirilecek.

---

## ✅ Aşama 0: Atölyenin Kurulumu (Matematik & Mühendislik Temelleri)
**Süre:** 2-4 Hafta (Eylül 2025)
**Hedef:** Capstone projenin temelini atacak matematiksel ve mühendislik altyapısını kurmak.

### Görevler
- [ ] Lineer Cebir, Calculus, Olasılık ve İstatistik konularını Python (NumPy/SciPy) ile uygulamak.
- ✅ Git/GitHub ile versiyon kontrolü mantığını oturtmak.
- ✅ Linux komut satırı (CLI) temellerini öğrenmek.
- [ ] Docker ile container mantığını anlamak ve basit bir imaj oluşturmak.
- ✅ Conda/Mamba ile proje ortamını oluşturmak ve `requirements.txt` dosyasını hazırlamak.
### Capstone Proje Çıktısı
- [ ] Projede kullanılacak sentetik kullanıcı verisini (yaş, harcama vb.) üreten bir Python script'i yazmak ve temel istatistiksel testleri uygulamak.

---

## 📊 Aşama 1: Veri Okuryazarlığı & Hikayeleştirme
**Süre:** 4-6 Hafta (Ekim-Kasım 2025)
**Hedef:** Capstone projenin verisini anlama, temizleme, analiz etme ve görsel bir hikayeye dönüştürme.

### Görevler
- [ ] NumPy ve Pandas ile veri manipülasyonu ve temizliği.
- [ ] İleri SQL (Window Functions, CTEs).
- [ ] Matplotlib/Seaborn ile görselleştirme ve **Storytelling**.
- [ ] Power BI ile interaktif dashboard oluşturma.
### Capstone Proje Çıktısı
- [ ] Kaggle'dan indirilen e-ticaret veri setine kapsamlı bir Keşifsel Veri Analizi (EDA) yapmak.
- [ ] **Ölçülebilir Hedef:** Analiz sonuçlarını içeren ve **en az 5 anlamlı iş KPI'ı (örn: Churn Rate, Müşteri Yaşam Boyu Değeri)** barındıran interaktif bir Power BI dashboard'u oluşturmak.

---

## 🏗️ Aşama 2: Modern Veri Mühendisliği & Altyapı
**Süre:** 6-8 Hafta (Kasım-Ocak 2026)
**Hedef:** Capstone projenin verisini bulut ortamında, otomatik ve güvenilir bir boru hattı ile işlemek.

### Görevler
- [ ] Bulut Bilişim (GCP) temel servislerini öğrenmek (Cloud Storage, Cloud Functions).
- [ ] **Google BigQuery** üzerinde veri depolama ve sorgulama.
- [ ] Veri Modelleme (Star Schema) ve **dbt ile transformasyon**.
- [ ] **Cloud Composer (Managed Airflow)** ile ETL/ELT pipeline'ları oluşturmak.
- [ ] Veri Kalitesi (dbt tests, Great Expectations) kavramlarını öğrenmek.
### Capstone Proje Çıktısı
- [ ] Veriyi Cloud Storage'dan alıp dbt ile BigQuery'de dönüştüren bir Cloud Composer DAG'ı kurmak.
- [ ] **Ölçülebilir Hedef:** Pipeline'ın **en az 10 farklı veri kalite testinden** (örn: null kontrolü, benzersizlik) başarıyla geçmesini sağlamak.

---

## 🤖 Aşama 3: Üretim Odaklı Makine Öğrenmesi (MLOps)
**Süre:** 4-6 Hafta (Ocak-Mart 2026)
**Hedef:** Capstone proje için bir ML modeli geliştirip bunu test edilebilir, versiyonlanabilir ve bir ürün olarak sunulabilir hâle getirmek.

### Görevler
- [ ] Scikit-learn pipelines ve ileri feature engineering.
- [ ] **Açıklanabilir YZ (XAI)**: SHAP/LIME ile model yorumlama.
- [ ] MLflow ile deney takibi ve model versiyonlama.
- [ ] FastAPI ile model API'si oluşturma ve servis etme.
- [ ] GitHub Actions ile temel bir CI (Sürekli Entegrasyon) pipeline'ı kurmak (dbt test, python test).
### Capstone Proje Çıktısı
- [ ] BigQuery'deki temiz veriyle bir kullanıcı churn tahmin modeli eğitmek (dengesiz veri setleri için uygun metotlarla).
- [ ] **Ölçülebilir Hedef:** Modeli **ROC-AUC (≥ 0.80) ve PR-AUC** metrikleri ile değerlendirmek. **Karar eşiğini (threshold) ayarlayarak** modelin iş etkisini (kurtarılan gelir simülasyonu) analiz etmek ve modeli bir FastAPI endpoint'i olarak deploy etmek.


---

## 🧠 Aşama 4: İleri Seviye Uzmanlık Modülü (Opsiyonel)
**Süre:** 4-6 Hafta (Mart-Nisan 2026)
**Hedef:** Capstone projeyi NLP teknikleri ile zenginleştirmek.

### Görevler
- [ ] PyTorch temelleri ve Transformers mimarisi.
- [ ] Hugging Face kütüphanesi ile NLP uygulamaları yapmak.
- [ ] RAG mimarisini konsept olarak anlamak.
### Capstone Proje Çıktısı
- [ ] Projedeki kullanıcı yorumu verileriyle bir duygu analizi modeli uygulamak.
- [ ] **Ölçülebilir Hedef:** Modelin test verisindeki **F1-Skorunu ≥ 0.80** yapmak.

---

## ⚖️ Aşama 5: Profesyonel Olgunluk & Etik
**Süre:** 2-4 Hafta (Mayıs-Haziran 2026)
**Hedef:** Capstone projeyi etik ve iş değeriyle birleştirerek profesyonel bir sunuma dönüştürmek.

### Görevler
- [ ] İleri MLOps: Kubernetes ile model deployment kavramını anlamak.
- [ ] Yapay Zeka etiği, yanlılık (bias) tespiti ve veri gizliliği (GDPR).
- [ ] Proje için `privacy.md` dosyası oluşturmak (veri gizliliği adımlarını açıklayan).
### Capstone Proje Çıktısı
- [ ] Capstone projenin tüm aşamalarını (veri mühendisliği, BI, ML) ve **iş değerini** anlatan detaylı bir blog yazısı (Medium vb.) yayınlamak.
- [ ] Modeldeki potansiyel etik riskleri ve alınan önlemleri açıklamak.
