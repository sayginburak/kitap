# Büyük Kitap Değişimi

"Büyük Kitap Değişimi" zincir oyunu için oluşturulmuş basit, statik bir web uygulaması. GitHub Pages üzerinde çalışır.

## Nasıl Çalışır?

1. Hikâyenizde kitap değişimi metnini paylaşın
2. "Varım!" diyen kişilere kişisel linkinizi gönderin
3. Onlar linki açar, kitap göndereceği adresi görür ve kendi adresini girer
4. Kendi linklerini oluşturup zinciri devam ettirirler

Adresler URL-safe Base64 ile kodlanır, backend gerekmez. Her şey tarayıcıda çalışır, hiçbir veri sunucuya gönderilmez.

## Kurulum

GitHub'a push edin ve Settings → Pages → Deploy from branch (main) üzerinden GitHub Pages'i aktif edin.

Uygulama tek bir `index.html` dosyasından oluşur, bağımlılığı yoktur.

## Teknoloji

- Saf HTML, CSS, JavaScript
- Framework yok, build adımı yok
- Mobil öncelikli responsive tasarım
- Türkçe karakter desteği için URL-safe Base64 kodlama
