# Aygaz_veribilimi 

Bu proje, elektrikli araç verisi üzerinde yapılan analizleri ve veri ön işleme işlemlerini içermektedir. Proje, Kaggle'dan alınan **Electric Vehicle Population Data** veri seti ile çalışmaktadır.

## Proje İçeriği

1. **Veri Yükleme ve İnceleme:**
   - Kaggle'dan alınan veri seti, pandas kullanılarak yüklenmiş ve veri setinin ilk 5 satırı görüntülenmiştir.
   - Veri seti hakkında temel bilgiler elde edilmiş, sayısal değişkenlerin istatistiksel özetleri incelenmiştir.

2. **Eksik Veriler:**
   - Veri setine rastgele eksik veriler eklenmiştir (%5).
   - Eksik veriler, sayısal ve kategorik sütunlar için uygun stratejilerle (ortalama ve mod ile) doldurulmuştur.

3. **Veri Görselleştirme:**
   - Elektrikli araçların menzil ve fiyat dağılımları histogramlarla görselleştirilmiştir.
   - Korelasyon matrisi ve heatmap kullanılarak sayısal değişkenler arasındaki ilişkiler analiz edilmiştir.
   - Kutu grafik ve scatter plot ile uç değerler ve değişkenler arasındaki ilişkiler görselleştirilmiştir.

4. **İstatistiksel Analizler:**
   - Sayısal sütunlar için standart sapma, medyan ve mod hesaplanmıştır.
   - En popüler marka ve model kombinasyonu bulunmuş ve elektrikli araçların menzil ve fiyat istatistikleri çıkarılmıştır.

5. **Yeni Özellikler:**
   - Fiyat ve elektrik menzili oranı gibi yeni özellikler eklenmiş ve bu özellikler ile ilgili analizler yapılmıştır.

## Kullanılan Teknolojiler

- **Python**: Veri analizi ve görselleştirme için Python dilini kullanarak gerekli analizler yapılmıştır.
- **Pandas**: Veri manipülasyonu ve analizi için pandas kütüphanesi kullanılmıştır.
- **Matplotlib & Seaborn**: Verilerin görselleştirilmesi için bu kütüphaneler kullanılmıştır.

## Projeyi Çalıştırmak İçin

1. Bu projeyi yerel ortamınızda çalıştırmak için önce gerekli kütüphaneleri yüklemeniz gerekmektedir:
    ```bash
    pip install pandas matplotlib seaborn
    ```

2. Ardından, projeyi çalıştırmak için aşağıdaki komutu kullanabilirsiniz:
    ```bash
    python analysis_script.py
    ```

## Katkıda Bulunma

Bu projeye katkıda bulunmak isterseniz, lütfen aşağıdaki adımları izleyerek pull request (PR) oluşturun:
1. Depoyu fork edin.
2. Yeni bir branch oluşturun (`git checkout -b yeni-ozellik`).
3. Değişikliklerinizi yapın ve commit edin (`git commit -am 'Yeni özellik ekle'`).
4. Branch'ınızı GitHub'a push edin (`git push origin yeni-ozellik`).
5. Pull request oluşturun.

## kaggle Linki

https://www.kaggle.com/code/zeyyser/notebook50b6084fcf 
