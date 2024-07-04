# Kahve Satışlarını Artırmak İçin Derin Öğrenme ile Günlük Kar Tahmini ve Analizi
Bu proje, bir kahve dükkanında günlük kahve satışlarını analiz etmek ve gelecekteki karları tahmin etmek amacıyla derin öğrenme modelleri kullanmaktadır. Aşağıda, proje hakkında detaylı bilgi, veri seti açıklaması, kullanılan yöntemler, görselleştirmeler ve proje sonuçları yer almaktadır.

## İçindekiler
- Proje Hakkında
- Veri Seti
- Kullanılan Yöntemler
- Görselleştirmeler ve Analizler
- Sonuçlar ve Uygulama Alanları
- Gelecek Çalışmalar
- Yazarlar ve Teşekkür
- Proje Hakkında
## Bu projede 
bir kahve dükkanının günlük satış verileri kullanılarak satış trendlerini analiz etmek ve gelecekteki karları tahmin etmek amaçlanmıştır. Proje kapsamında, zaman serisi analizi ve derin öğrenme modelleri kullanılmıştır. Veriler, günlük toplam satış miktarları ve satılan kahve türlerini içermektedir.

## Veri Seti
Veri seti, kahve dükkanındaki satış verilerini içermektedir. Aşağıdaki sütunlar yer almaktadır:
link: https://www.kaggle.com/datasets/ihelon/coffee-sales

- date: Satışın gerçekleştiği tarih
- datetime: Satışın gerçekleştiği tam tarih ve saat
- cash_type: Ödeme yöntemi (nakit, kart)
- card: Anonim kart bilgisi
- money: Satış tutarı
- coffee_name: Satılan kahve türü
- Kullanılan Yöntemler
- Proje kapsamında aşağıdaki adımlar izlenmiştir:

- Veri Hazırlama: Veriler, uygun formatta yüklenmiş ve gerekli ön işlemler yapılmıştır.
- Zaman Serisi Analizi: Günlük toplam satış miktarları ve kahve türleri analiz edilmiştir.
- Derin Öğrenme Modeli: Gelecekteki karları tahmin etmek için bir LSTM (Long Short-Term Memory) modeli kullanılmıştır.
- Görselleştirme: Satış verileri çeşitli grafiklerle görselleştirilmiştir.
- Görselleştirmeler ve Analizler
## Projede kullanılan ve oluşturulan görselleştirmeler aşağıda detaylandırılmıştır:

## Günlük Toplam Satış Bar Grafiği:

- Günlük toplam satış miktarları bar grafiği ile görselleştirilmiştir. Bu grafik, belirli günlerdeki satış performansını analiz etmeye yardımcı olur.
Kahve Türlerinin Günlük Dağılımı Pasta Grafiği:

- Kahve türlerinin günlük satış dağılımı pasta grafiği ile gösterilmiştir. Bu grafik, hangi kahve türlerinin daha popüler olduğunu görselleştirir.
Kahve Türlerinin Günlük Satış Trendi Çizgi Grafiği:

- Kahve türlerinin günlük satış trendleri çizgi grafiği ile görselleştirilmiştir. Bu grafik, zaman içindeki satış eğilimlerini analiz eder.
Günlük Toplam Satış Kutu Grafiği:

- Günlük toplam satış miktarlarının aylık dağılımı kutu grafiği ile gösterilmiştir. Bu grafik, belirli ayların satış performansını karşılaştırmaya yardımcı olur.
## Sonuçlar ve Uygulama Alanları
Bu proje, kahve dükkanları için çeşitli faydalar sağlamaktadır:

Pazarlama ve Satış Stratejileri:

- Hedefli Kampanyalar: Belirli zaman dilimlerinde özel kampanyalar ve promosyonlar düzenlenebilir.
Müşteri Davranışları: Müşterilerin alışveriş alışkanlıkları analiz edilerek, yeni ürünler tanıtılabilir.
Stok Yönetimi:

- Talep Tahmini: Satış verileri analiz edilerek, belirli dönemlerde hangi kahve türlerinin daha fazla talep edildiği tahmin edilebilir.
Atık Azaltma: Stokların daha doğru yönetilmesi ile atık miktarı azaltılabilir.
Operasyonel Verimlilik:

- Çalışan Planlaması: Yoğun satış dönemleri belirlenerek, çalışan vardiya planlamaları daha verimli hale getirilebilir.
Maliyet Analizi: Satış ve kar analizleri yapılarak, operasyonel maliyetler düşürülebilir.
Müşteri Memnuniyeti:

- Kişiselleştirilmiş Hizmet: Müşterilerin en çok tercih ettiği kahve türleri belirlenerek, kişiselleştirilmiş hizmet sunulabilir.
Sadakat Programları: Müşteri sadakat programları geliştirilerek, tekrar eden müşterilere özel avantajlar sağlanabilir.
Kurulum ve Kullanım
Projeyi yerel ortamınızda çalıştırmak için aşağıdaki adımları izleyin:

## Gerekli Kütüphaneleri Yükleyin:

- bash
- Kodu kopyala
- pip install pandas numpy matplotlib seaborn tensorflow
## Gelecek Çalışmalar
- Sezonluk Analiz: Satışların mevsimsel etkinlikler
- Dönemdsel satış değişimleri takibi.
- Satış kar takibi.



