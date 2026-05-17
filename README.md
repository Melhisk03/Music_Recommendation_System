# Music_Recommendation_System

Bu proje, makine öğrenmesi ve müzik özellikleri kapsamında çalışan bir içerik tabanlı (content-based)
müzik öneri sistemidir.

Sistemin amacı, kullanıcının girdiği şarkıların ses özelliklerini, tür bilgilerini ve benzerlik oranlarını analiz ederek kullanıcıya benzer müzik önerileri sunar.

Veri seti (Genel_veriseti) Kaggle'dan alınan 3 adet veri setinin birleştirilmesiyle oluşturulmuştur.

VerisetKod-Analiz dosyasında elde edilen Genel_veriseti kullanılarak, modeller eğitilmiştir.
Veri seti Drive'a yüklenerek Colab'a import edilmiştir. Dosyalar Colab'da açıldığında çıktılar görülebilmektedir.

Proje bir ekip çalışması olarak gerçekleştirilmiştir.

Rol aldığım bölümler:
- Müzik öneri sistemi (Recommendation Engine)
- Cosine Similarity tabanlı benzerlik hesaplama
- TF-IDF ile genre vektörleştirme
- Öneri fonksiyonunun geliştirilmesi, parametrelerin seçimi.
- PCA ile cosine similarity uygulanması
- Model performans optimizasyonu

Kullanılan Teknolojiler
- Python
- Pandas
- NumPy
- Scikit-learn
- SciPy
- Matplotlib
- Seaborn
- Google Colab

Modelde kullanılan temel audio özellikler:
- danceability
- energy
- valence
- acousticness
- instrumentalness
- tempo
- loudness
- speechiness
- liveness
- popularity
- release_year




