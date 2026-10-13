# CNSZR Trading Lab

TradingView için Pine Script v6 tabanlı indikatör geliştirme alanı.

## İlk sürüm: Trend Signals

Dosya: `CNSZR_Trading_Lab_Trend_Signals.pine`

Özellikler:
- SuperTrend yön değişimlerinde AL/SAT sinyalleri
- İsteğe bağlı ADX trend gücü filtresi
- İsteğe bağlı Bollinger orta çizgisi filtresi
- SuperTrend ve Bollinger çizimleri
- TradingView alarm koşulları

## TradingView'e ekleme

1. Pine dosyasını açıp tüm kodu kopyala.
2. TradingView'de bir grafik aç.
3. Alt bölümden **Pine Editor**'ü aç.
4. Kodu yapıştır ve **Save** ardından **Add to chart** seç.
5. Alarm kurmak için alarm penceresinde **CNSZR AL** veya **CNSZR SAT** koşulunu seç.

## İlk test için öneri

- Piyasa: BIST hisseleri
- Zaman dilimi: Günlük
- SuperTrend ATR Length: 10
- SuperTrend Factor: 3.0
- ADX Minimum: 20
- Bollinger Length: 20
- Bollinger Deviation: 2.0

Bunlar başlangıç ayarlarıdır; kârlılık garantisi değildir. Sinyalleri farklı hisselerde ve dönemlerde test etmeden gerçek işlemlerde kullanma. Bu sürüm bir **indikatördür**, otomatik alım-satım stratejisi veya yatırım tavsiyesi değildir.
