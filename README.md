# Otizm Spektrum Bozukluğu Veri Analizi

Bu proje, Otizm Spektrum Bozukluğu (OSB) ile ilgili veri setini kullanarak çeşitli makine öğrenimi yöntemleri ile analiz yapmak amacıyla geliştirilmiştir. Proje, verilerin ön işlenmesi, model eğitimi ve modelin performansının değerlendirilmesi adımlarını içermektedir.

## İçindekiler
- [Veri Seti](#veri-seti)
- [Kullanılan Kütüphaneler](#kullanılan-kütüphaneler)
- [Veri Ön İşleme](#veri-ön-i̇şleme)
- [Model Eğitimi](#model-eğitimi)
- [Model Performansı](#model-performansı)
- [Sonuçlar](#sonuçlar)

## Veri Seti
Veri seti, `OSB.csv` dosyasından yüklenmektedir. Bu dosya, bireylerin otizm spektrum bozukluğu ile ilgili özelliklerini içeren verileri barındırmaktadır. Hedef değişken, bireylerin OSB durumu olup, diğer sütunlar çeşitli demografik ve klinik bilgileri temsil etmektedir.

## Kullanılan Kütüphaneler
- `pandas`: Veri işleme ve analizi için.
- `numpy`: Nümerik hesaplamalar için.
- `matplotlib`: Verilerin görselleştirilmesi için.
- `seaborn`: İleri düzey veri görselleştirmeleri için.
- `scikit-learn`: Makine öğrenmesi ve modelleme için.

## Veri Ön İşleme
1. **Veri Yükleme**: Veri seti yüklendikten sonra, veriler üzerinde genel bir inceleme yapılmaktadır.
2. **Eksik Değer Analizi**: Veri setindeki eksik değerler kontrol edilmekte ve gerekli işlemler yapılmaktadır.
3. **Kategorik Verilerin Kodlanması**: Kategorik veriler, modelin anlayabileceği biçimde sayısal verilere dönüştürülmektedir.
4. **Veri Normalizasyonu**: Özelliklerin ölçeklendirilmesi, modelin performansını artırmak için yapılmaktadır.

## Model Eğitimi
1. **Model Seçimi**: OSB durumunu tahmin etmek için `DecisionTreeClassifier` veya başka makine öğrenimi algoritmaları kullanılmaktadır.
2. **Eğitim ve Test Kümeleri**: Veri seti, eğitim ve test kümeleri olarak ayrılmakta ve model eğitilmektedir.

## Model Performansı
Modelin performansı, doğruluk, kesinlik, duyarlılık ve F1 skoru gibi metriklerle değerlendirilmektedir. Bu metrikler, modelin genel başarısını ve güvenilirliğini analiz etmekte yardımcı olmaktadır.

## Sonuçlar
Analiz sonuçları, OSB ile ilgili bulguları ve modelin başarısını içermekte olup, hangi özelliklerin OSB durumu ile daha güçlü bir ilişkiye sahip olduğu belirlenmektedir. 

## Kullanım
Proje dosyalarını indirip çalıştırarak, Otizm Spektrum Bozukluğu verisi ile makine öğrenimi modelini kendiniz de deneyebilirsiniz. Kodun çalışabilmesi için gerekli kütüphanelerin yüklü olması gerekmektedir.
