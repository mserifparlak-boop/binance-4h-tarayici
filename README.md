# Binance 4H Tarayıcı

Mobil uyumlu, tarayıcıda çalışan Binance USDT-M perpetual tarayıcısı.

## Filtreler
- Son tamamlanmış 4 saatlik mum kapanışı EMA(50) üzerinde.
- Stoch RSI K (14,14,3,3) değeri 40 veya altında.
- Yalnızca TRADING durumundaki USDT kotasyonlu perpetual sözleşmeler.

## GitHub Pages ile yayınlama
1. Depoda **Settings → Pages** bölümünü açın.
2. **Build and deployment** altında **Deploy from a branch** seçin.
3. Branch olarak **main**, klasör olarak **/(root)** seçip **Save** deyin.
4. Birkaç dakika sonra site şu adreste açılır: https://mserifparlak-boop.github.io/binance-4h-tarayici/

## Kullanım
Siteyi telefonda açın ve **Taramayı başlat** düğmesine dokunun. Tarama tamamlanınca eşleşen pariteler Stoch RSI K değerine göre küçükten büyüğe sıralanır. Arama kutusuyla coin filtreleyebilirsiniz.

## Hesaplama notu
EMA, son tamamlanmış 4 saatlik mumların kapanışlarından hesaplanır. Stoch RSI, RSI(14), son 14 RSI değeri üzerindeki stochastic aralığı ve 3 mumluk K ortalaması kullanılarak hesaplanır. Açık olan 4 saatlik mum bilerek dışarıda bırakılır.

Bu araç bilgilendirme ve teknik tarama içindir; yatırım tavsiyesi değildir. Binance herkese açık API'sine erişim, ağ ve API kullanılabilirliğine bağlıdır.
