# Gym Equipment Sales Data Analysis

Bu proje, **Gym Malzemeleri Satış Verisi Analizi** üzerine odaklanmaktadır. Bir gym ekipmanı satan firmanın satış verilerini içeren Excel dosyasını kullanarak, ürünlerin yıllık satış performanslarını analiz ettim. Proje kapsamında satışların yıllara göre kıyaslaması yapılmış, kar hesaplamaları gerçekleştirilmiş ve grafiksel olarak firmaların satış performansları görselleştirilmiştir. Ayrıca, her bir ürünün bir önceki yıla göre satış yüzdesi tablo halinde listelenmiştir.

## Proje Özeti

Bu veri analizi projesi, gym ekipmanlarının satış verilerini incelemekte ve aşağıdaki analizleri yapmaktadır:

- **Yıllık Satış Performans Analizi**: Firmaların yıllık satışları, fiyatları ve karları kıyaslanarak analiz edilmiştir.
- **Satış Yüzde Değişimi**: Her ürün için, bir önceki yıl ile karşılaştırmalı olarak satışlardaki yüzdelik değişim hesaplanmıştır.
- **Grafiksel Görselleştirme**: Firmaların satışları ve karları yıllık bazda grafiklerle görselleştirilmiştir.
- **Kar Hesaplamaları**: Her ürün ve firma için satıştan elde edilen kar hesaplanarak analiz edilmiştir.

## Kullanılan Araçlar ve Teknolojiler

- **Microsoft Excel**: Verilerin saklanması, analiz edilmesi ve görselleştirilmesi için kullanılmıştır.
- **Excel Formülleri ve Fonksiyonları**: Kar hesaplamaları, yüzdelik değişim hesaplamaları ve veri filtreleme işlemleri için kullanılmıştır.
- **Excel Grafik Araçları**: Yıllık satış ve kar performanslarını görselleştirmek için grafikler kullanılmıştır.

## Veritabanı / Veri Seti

Bu proje, gym ekipmanları satan bir firmanın ürün ve satış verilerini içeren **Excel tablosu** üzerine yapılmıştır. Aşağıdaki veriler yer almaktadır:

- **Ürün Adı**: Gym ekipmanlarının isimleri.
- **Firma Adı**: Satış yapan firmaların isimleri.
- **Satış Miktarı**: Yıl bazında satılan ürün sayısı.
- **Fiyat**: Ürünlerin satış fiyatları.
- **Satış Tutarı**: Ürünlerin satışı ile elde edilen toplam gelir.
- **Maliyet**: Ürünlerin üretim ya da temin maliyetleri.
- **Kar**: Satıştan elde edilen kar (Satış Tutarı - Maliyet).

## Veriyi Analiz Etme

1. **Yıllık Satış Karşılaştırması**:
   - Her firma ve ürün için yıllık bazda satışlar karşılaştırıldı.
   - Firmaların yıllık satış büyüme oranları grafiklerle görselleştirildi.

2. **Satış Yüzde Değişimi**:
   - Ürünlerin yıllık bazda satışlarındaki yüzdelik değişim hesaplanarak bir tablo halinde sunuldu.
   - **Yüzde değişim formülü**:  
     ``` 
     Yüzde Değişim = ((Bu Yıl Satışı - Geçen Yıl Satışı) / Geçen Yıl Satışı) * 100 
     ```

3. **Kar Hesaplamaları**:
   - Ürünler için satış fiyatı ve maliyet arasındaki fark hesaplanarak yıllık bazda kar hesaplandı.
   - **Kar Formülü**:  
     ``` 
     Kar = Satış Tutarı - Maliyet
     ```

## Grafiksel Görselleştirme

Verilerin görselleştirilmesi için Excel'deki grafik araçları kullanıldı. Aşağıdaki grafikler oluşturuldu:

- **Yıllık Satış Performansı Grafiği**: Her yıl için firma bazında satış miktarlarını gösteren grafikler.
- **Yıllık Kar Grafiği**: Firma ve ürünler için yıllık karları karşılaştıran grafikler.
- **Firma Bazında Yüzdelik Değişim Grafiği**: Yıllık satış değişimlerini yüzdelik dilimde gösteren grafikler.

## Excel Dosyasında Yer Alan Ana Sayfalar

1. **Veri Seti**: Ürün ve satış verilerinin bulunduğu ana sayfa.
2. **Satış Analizi**: Yıllık satışlar ve kar hesaplamalarının yer aldığı sayfa.
3. **Yüzde Değişim**: Ürünlerin yıllık satışlarındaki yüzdelik değişimlerin yer aldığı tablo.
4. **Grafikler**: Satış ve kar verilerinin görselleştirildiği grafik sayfası.

## Kurulum ve Kullanım

### 1. Excel Dosyasını İndirme

Projeyi kullanmaya başlamak için **Excel dosyasını** indirmeniz gerekmektedir. Dosyayı indirip açarak projeyi inceleyebilir ve kendi verilerinizi de ekleyebilirsiniz.

### 2. Veri Setini Düzenleme

Eğer verinizi güncellemek veya değiştirmek isterseniz, **"Veri Seti"** sayfasında gerekli düzenlemeleri yapabilirsiniz. Ürün adı, firma adı, fiyat, satış miktarı gibi bilgileri güncelledikten sonra analizlerinizi otomatik olarak görmek mümkün olacaktır.

### 3. Yıllık Satışları ve Karları Görselleştirme

Grafik sayfasında yer alan **"Yıllık Satış Performansı Grafiği"** ve **"Yıllık Kar Grafiği"** gibi görselleri inceleyebilirsiniz. Grafikler, verileri analiz etmek ve karşılaştırmak için oldukça faydalıdır.

### 4. Yüzde Değişim Hesaplama

Bir önceki yıla göre ürünlerin satışındaki yüzdelik değişimi görmek için **"Yüzde Değişim"** sayfasını kullanabilirsiniz. Veritabanındaki satış miktarlarını ve yıllık değişimleri analiz edebilirsiniz.

## Katkı Sağlama

Bu projeye katkı sağlamak isterseniz, aşağıdaki adımları takip edebilirsiniz:

1. Projeyi fork'layın.
2. Değişikliklerinizi yapın ve kendi dalınızı oluşturun.
3. Pull request oluşturun.

## Lisans

Bu proje [MIT Lisansı](LICENSE) altında lisanslanmıştır.
