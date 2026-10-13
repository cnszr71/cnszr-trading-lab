# CNSZR Trading Lab

TradingView için Pine Script v6 ile geliştirilen teknik analiz indikatörü.

## v1.0 özellikleri

- **SuperTrend:** Trend yönünü ve olası dönüşleri gösterir.
- **ADX / +DI / -DI:** Trend gücünü izler; minimum ADX eşiği sinyalleri filtrelemeye yardımcı olur.
- **Bollinger Bands:** Üst, alt ve orta bantları grafikte gösterir.
- **AL / SAT etiketleri:** SuperTrend dönüşü ve ADX filtresi birlikte koşulları sağladığında oluşur.
- **Alarm koşulları:** TradingView'de AL ve SAT alarmı kurulabilir.
- **Kapanış onayı:** Varsayılan olarak sinyalin mum kapanışında doğrulanmasını bekler.

## TradingView'e ekleme

1. [CNSZR_Trading_Lab.pine](./CNSZR_Trading_Lab.pine) dosyasını aç.
2. Kodu kopyala.
3. TradingView'de bir grafik aç ve **Pine Editor** bölümüne gir.
4. Kodu editöre yapıştırıp **Save** ve **Add to chart** seçeneklerini kullan.
5. İndikatör ayarlarından ADX eşiğini ve Bollinger seçeneklerini ihtiyacına göre değiştir.

## İlk test için öneri

- Piyasa: BIST hisseleri
- Zaman dilimi: Günlük
- SuperTrend ATR Length: 10
- SuperTrend Factor: 3.0
- ADX Minimum: 20
- Bollinger Length: 20
- Bollinger Deviation: 2.0

Bunlar başlangıç ayarlarıdır; kârlılık garantisi değildir. Farklı hisselerde ve dönemlerde test etmeden gerçek işlemlerde kullanma.

## Önemli notlar

- Bu sürüm bir **indikatördür**; otomatik emir vermez ve strateji performansı raporlamaz.
- ADX, trendin yönünü değil gücünü ölçer.
- Parametreler her hisse ve zaman diliminde aynı sonucu vermeyebilir. Geçmiş performans gelecekteki sonuçları garanti etmez.
- Bu proje eğitim ve araştırma amaçlıdır; yatırım tavsiyesi değildir.

## Sonraki geliştirme

Bir sonraki aşamada ayrı bir Pine Script **strategy** dosyası hazırlayıp komisyon, kayma ve pozisyon kurallarıyla geçmiş test yapacağız.
