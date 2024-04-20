# -text-based-emotion-prediction
Duygu Tanıma Modeli README Dosyası
Bu proje, duygu tanıma üzerine bir modelin geliştirilmesi ve eğitilmesi için bir Python kodunu içermektedir. Bu README dosyası, projenin amacını, kullanımını ve kodun çalıştırılmasını açıklar.

Proje Amacı
Bu proje, duygusal metinleri analiz etmek ve bu metinlerdeki duyguları sınıflandırmak için bir makine öğrenimi modeli oluşturmayı amaçlamaktadır. Model, duygusal metinlerin altında yatan duyguları tespit etmek için derin öğrenme tekniklerini kullanır.

Gereksinimler
Bu kodun çalıştırılması için aşağıdaki Python kütüphanelerine ihtiyaç vardır:

pandas
numpy
matplotlib
seaborn
re
nltk
BeautifulSoup
scikit-learn
TensorFlow
Keras
Gerekli kütüphaneleri yüklemek için aşağıdaki komutu kullanabilirsiniz:

Copy code
pip install pandas numpy matplotlib seaborn nltk beautifulsoup4 scikit-learn tensorflow keras
Veri Seti
Bu projede kullanılan veri seti, Kaggle'dan alınmıştır. Veri seti, duygusal metinleri içeren bir CSV dosyasından oluşur. Her metnin yanında, metnin hangi duygu kategorisine ait olduğunu belirten bir etiket bulunur.

Veri setine şu bağlantıdan erişebilirsiniz. https://www.kaggle.com/datasets/nelgiriyewithana/emotions

Kullanım
Kodun çalıştırılması için:

Python ortamınızda gerekli kütüphaneleri yükleyin.
Veri setini indirin ve belirtilen dosya yoluna yerleştirin.
Kodu çalıştırın.
Kod, veri setini yükleyecek, metin işleme adımlarını gerçekleştirecek, modeli oluşturacak, eğitecek ve son olarak duygu tahminleri yapacaktır.
