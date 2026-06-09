# otobusbiletkuyrugusimulasyonu
# 🎟️ SimPy ile Kapı Geçiş Simülasyonu

 📌 Proje Bilgileri

 Ad Soyad: Dorukhan Perdeci
 Öğrenci Numarası: 21430070029

# 📖 Proje Hakkında

Bu proje, Python programlama dili kullanılarak geliştirilmiş bir Ayrık Olay Simülasyonu (Discrete Event Simulation) uygulamasıdır. Projede, etkinlik girişlerinde kullanılan bilet kontrol ve kapı geçiş sistemi modellenmiştir.

# Simülasyon içerisinde:

Otobüslerle gelen ziyaretçiler,
Bilet satış noktaları,
Kuyruk sistemleri,
Turnike ve tarayıcı noktaları

gerçek hayattaki akış mantığına uygun şekilde simüle edilmektedir.

Proje, özellikle yoğun insan trafiğinin bulunduğu alanlarda oluşabilecek kuyrukları ve kaynak kullanımını analiz etmeyi amaçlamaktadır.

# 🎯 Projenin Amacı

# Bu projenin temel amacı:

Kuyruk sürelerini analiz etmek
Kaynak kullanım verimliliğini ölçmek
Gişe ve tarayıcı performansını incelemek
Müşteri akışını modellemek
Sistem darboğazlarını tespit etmek

ve farklı senaryolar altında sistem davranışını gözlemlemektir.

# 🛠 Kullanılan Teknolojiler
Python
SimPy
Tkinter
Matplotlib
JSON
HTML5 Canvas

# 📚 SimPy Nedir?

SimPy, Python dili için geliştirilmiş süreç tabanlı bir ayrık olay simülasyonu kütüphanesidir. Gerçek dünyadaki birçok sistemin modellenmesini sağlar.

Örneğin:

Hastane sistemleri
Trafik simülasyonları
Üretim hatları
Banka kuyrukları
Bilet kontrol sistemleri

gibi birçok yapı SimPy ile modellenebilir.

Bu projede SimPy, ziyaretçilerin sisteme giriş süreçlerini ve kuyruk davranışlarını simüle etmek için kullanılmıştır.

# ⚙️ Simülasyonun Çalışma Mantığı

# Simülasyon aşağıdaki adımlarla çalışmaktadır:

Belirli aralıklarla otobüsler gelir.
Yolcular otobüslerden grup halinde iner.
Bazı ziyaretçiler doğrudan tarayıcıya yönelir.
Bazıları önce bilet satın alma işlemi gerçekleştirir.
Kaynak yoğunluğuna göre kuyruk oluşur.
Bilet tarama işlemi yapılır.
Ziyaretçiler giriş alanına geçiş yapar.
Sistem istatistikleri sürekli olarak hesaplanır.

# 🔍 Proje Özellikleri

✅ Gerçek zamanlı ayrık olay simülasyonu
✅ Kuyruk yönetim sistemi
✅ Çoklu gişe ve tarayıcı desteği
✅ Dinamik müşteri üretimi
✅ İstatistiksel analiz sistemi
✅ Bekleme süresi hesaplama
✅ Görselleştirme desteği
✅ Olay kayıt sistemi
✅ HTML5 animasyon desteği

# 📊 Ölçülen Performans Değerleri

Simülasyon sırasında aşağıdaki değerler analiz edilmektedir:

Ortalama gişe bekleme süresi
Ortalama tarayıcı bekleme süresi
Kuyruk uzunlukları
Kaynak kullanım oranları
Sistemdeki toplam müşteri sayısı
Yoğunluk zamanları

Bu veriler sayesinde hangi sistem yapılandırmasının daha verimli olduğu gözlemlenebilir.

# 🧠 Ayarlanabilir Parametreler

# Projede aşağıdaki parametreler değiştirilebilir:

Gişe sayısı
Tarayıcı sayısı
Kuyruk sayısı
Otobüs geliş sıklığı
Müşteri grup büyüklüğü
Hizmet süreleri

Bu sayede farklı senaryolar test edilebilir.

# ▶️ Projeyi Çalıştırma
Gerekli Kütüphaneleri Kurma
pip install simpy matplotlib
Simülasyonu Başlatma
python "simpy example.py"

# 📈 Görselleştirme

Projede farklı görselleştirme yöntemleri kullanılmaktadır:

Tkinter ile canlı simülasyon ekranı
Matplotlib ile grafiksel analizler
HTML5 Canvas animasyonu
JSON tabanlı olay kayıt sistemi

Bu yapılar sayesinde sistem davranışı daha kolay analiz edilebilmektedir.

# 📂 Proje Dosya Yapısı
gate-simulation/
│
├── simpy example.py
├── output/
├── visualize.html
├── visualize.ts
└── README.md

# 💡 Proje Kazanımları

Bu proje sayesinde aşağıdaki konularda deneyim kazanılmıştır:

Ayrık olay simülasyonu
Kuyruk teorisi
Süreç tabanlı modelleme
Python programlama
Veri görselleştirme
Gerçek zamanlı sistem analizi


Bu proje, SimPy kütüphanesi kullanılarak gerçek hayattaki kuyruk ve geçiş sistemlerinin nasıl modellenebileceğini göstermektedir. Farklı parametreler ile sistem performansı analiz edilerek kaynak kullanım verimliliği üzerine önemli çıkarımlar yapılabilmektedir.
