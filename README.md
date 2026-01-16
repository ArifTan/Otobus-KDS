Pamukkale Seyahat - Karar Destek Sistemi (KDS) 

Bu proje, Pamukkale Seyahat firmasının geçmiş yıl verilerini analiz ederek gelecekteki sefer planlamalarını optimize etmek, talep dalgalanmalarını öngörmek ve ekonomik kayıpları minimize etmek amacıyla geliştirilmiş bir Karar Destek Sistemi'dir. Sistem, yöneticilere stratejik ve taktiksel düzeyde karar alma süreçlerinde rehberlik eder.


📊 Proje Özellikleri

Talep Öngörüsü: Geçmiş verileri analiz ederek gelecekteki yoğunlukları tahmin eder.


Doluluk Analizi: Güzergahların günlük ve aylık doluluk oranlarını grafiklerle sunar.


Kıyaslama Modülü: Farklı güzergahların doluluk oranlarını ve performanslarını karşılaştırmalı tablolarla analiz eder.


Gecikme Analizi: Seferlerdeki gecikme nedenlerini (trafik, hava şartları, arıza vb.) görselleştirir ve analiz sunar.


Envanter ve Personel Takibi: Otobüs detayları ve şoför performanslarının (sefer sayısı, gecikme durumu) takibi.


🛠 Kullanılan Teknolojiler
Proje, çevik yazılım geliştirme metodolojisi (Agile) kullanılarak modern web teknolojileri ile inşa edilmiştir:



Backend: Node.js, Express 



Frontend: HTML5, CSS3, JavaScript 



Veritabanı: MySQL (XAMPP) 




Veri Görselleştirme: Chart.js 

🗄 Veritabanı Yapısı
Sistem, birbiriyle ilişkili 5 temel tablo üzerine kurulmuştur:

seferler: Sefer detayları, doluluk oranları ve gecikme nedenleri.

guzergahlar: Hat isimleri ve tanımları.

otobusler: Plaka, marka, model ve kapasite bilgileri.

soforler: Sürücü iletişim ve performans verileri.

login: Sisteme yetkili giriş bilgileri.
