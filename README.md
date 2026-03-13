​--Diyabet Tahmin ve Klinik Veri Analizi Projesi
​Bu proje, veri bilimi ve Python yolculuğumdaki ilk büyük ve en anlamlı adımdır. 
Bir tıp öğrencisi olarak, klinik verilerin yapay zeka ile nasıl yorumlanabileceğini keşfettiğim bu çalışma; sadece kod yazmayı değil, verinin içindeki tıbbi hikayeyi okumayı öğrenme sürecimi temsil etmektedir.
​
--Kişisel Not
​Bu script, benim "merhaba dünya" aşamasından "veri odaklı tıp" aşamasına geçişimin bir belgesidir. 
Öğrenme serüvenimde ilk kez; gerçek bir veri setini temizledim, aykırı değerleri bilimsel yöntemlerle ayıkladım ve bir yapay zekayı "eğiterek" klinik sonuçlar almasını sağladım. 
Yardım aldığım noktalar olsa da, her satırı anlayarak ve üzerine koyarak ilerlediğim bu yolculuk, gelecekteki "Dijital Sağlık" vizyonumun temel taşını oluşturmaktadır.

​--Projenin Kapsamı ve Yapılan İşlemler
​Proje boyunca bir veri bilimcinin izlediği "Pipeline" (iş akışı) adımlarını takip ettim:
​Veri Sterilizasyonu (Cleaning): Klinik olarak imkansız olan 0 değerlerini (Glikoz, BMI, İnsülin vb.) tespit edip, bu boşlukları istatistiksel Medyan değerleri ile doldurdum.
​Anomali Tespiti (IQR): Interquartile Range (IQR) yöntemini kullanarak, İnsülin değerlerindeki aykırı (outlier) hastaları belirledim ve veriyi daha sağlıklı bir hale getirdim.
​Korelasyon Analizi (EDA): Isı haritaları (Heatmaps) ve yoğunluk grafikleri (KDE Plots) aracılığıyla Glikoz, BMI ve Yaş faktörlerinin diyabet üzerindeki etkisini görselleştirdim.
​Yapay Zeka Modelleme: * Logistic Regression: Doğrusal bir model ile %74.12 başarı skoru elde ettim.
​Random Forest: Daha karmaşık bir "Karar Ormanı" yapısı kurdum ve sonuçları kıyasladım.
​Teknik Çıkarım (Complexity Paradox): Veri setinin boyutu nedeniyle basit modellerin, çok daha karmaşık modellere göre daha stabil sonuçlar verdiğini ("Overfitting" riski) gözlemledim.
​
--Kullanılan Teknolojiler
​Python 3
​Pandas & Numpy: Veri manipülasyonu ve matematiksel işlemler.
​Seaborn & Matplotlib: Klinik veri görselleştirme.
​Scikit-Learn: Makine öğrenmesi modelleri (Logistic Regression, Random Forest, StandardScaler).
​
--Bulgular
​Glikoz, diyabet teşhisinde en yüksek "Önem Skoru"na (Feature Importance) sahip olan değişken olarak belirlendi.
​Yaşın ilerlemesiyle birlikte diyabet yoğunluğunun (Density) arttığı görsel olarak kankanıtlandı

-Nasıl Kullanılır?
​Repoyu bilgisayarınıza klonlayın.
​Gerekli kütüphaneleri kurun: pip install pandas numpy seaborn matplotlib scikit-learn
​Scripti çalıştırın ve klinik sonuçları inceleyin!
​-İletişim
​Öğrenme sürecime dair geri bildirimleriniz benim için çok kıymetlidir. 
Bir tıp öğrencisinin veri bilimi yolculuğuna dair önerileriniz varsa lütfen iletişime geçin!
**[emre195yunus@hotmail.com](mailto:emre195yunus@hotmail.com)**
