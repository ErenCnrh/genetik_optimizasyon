# genetik_optimizasyon
Yapay Zeka Sistemleri Dersi 1. Proje - Senaryo 5: Genetik Algoritma ile Optimizasyon Çözümü

# Genetik Algoritma ile Reaksiyon Verimi Optimizasyonu (Senaryo 5)

Bu proje, Yapay Zeka Sistemleri dersi kapsamında, Genetik Algoritma kullanılarak bir kimya tesisindeki reaksiyon parametrelerinin optimize edilmesi amacıyla geliştirilmiştir.

## Proje Hakkında
Ders: BLG 307 - Yapay Zeka Sistemleri
Ödev Konusu: Genetik Algoritma ile bir amaç fonksiyonunun verilen kısıtlara göre optimizasyonu.
Senaryo: Senaryo 5 - Kimya Tesisinde Reaksiyon Süresi (x1) ve Sıcaklık (x2) Ayarı.
Amaç: Belirlenen kısıtlar altında reaksiyon verimini maksimize eden en uygun süre ve sıcaklık değerlerini bulmaktır.

### Matematiksel Model
Amaç Fonksiyonu (Verim Puanı y):
y = 8*x1 + 3*x2 - x1*x2 + x1^2  (reaksiyon verimi)

Değişken Aralıkları:
Süre (x1): 10 ile 60 dakika arası
Sıcaklık (x2): 40 ile 120 Santigrat Derece arası

Kısıtlar (Ceza Fonksiyonu ile Yönetilen):
1. Toplam Sınır: x1 + x2 küçük eşit 140
2. Minimum Sıcaklık: x2 büyük eşit 60

## Kurulum ve Gereksinimler

Projeyi kendi bilgisayarınızda çalıştırmak için aşağıdaki adımları izleyin:

1. Bu GitHub deposunu klonlayın:
   git clone [](https://github.com/ErenCnrh/genetik_optimizasyon)

2. Gerekli Python kütüphanelerini yükleyin:
   pip install numpy matplotlib

## Kullanım Talimatı

Proje, genetik_optimizasyon.ipynb adlı Jupyter Notebook dosyasında bulunmaktadır. Notebook içinde her adımda açıklamalar (Markdown) yer almalıdır.

1. Jupyter Notebook/Lab ortamını başlatın.
2. Proje dosyasını açın.
3. Notebook içindeki tüm hücreleri sırasıyla çalıştırın.

Çalışma sonucunda, çıktı olarak aşağıdaki bilgiler sunulacaktır:
1. Her jenerasyonda elde edilen en iyi uygunluk (fitness) skorları.
2. Optimizasyon sonucunda elde edilen en iyi x1 ve x2 değerleri.
3. Yakınsama Grafiği: En iyi çözümün jenerasyonlara göre değişimini gösteren grafiksel çıktı.

## Geliştirici Bilgileri:

Adınız: Eren
Soyadınız: Canruh
Okul Numarası: 2312721045
GitHub Repo Bağlantısı: https://github.com/ErenCnrh/genetik_optimizasyon.git)
