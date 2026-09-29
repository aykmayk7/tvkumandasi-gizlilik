# Gizlilik politikası sayfası

`index.html` tek dosyadır: betik yok, dış yazı tipi yok, izleyici yok.
Mobilde ve masaüstünde, açık ve koyu temada sınandı.

Google Play ve App Store gizlilik politikası için **halka açık bir URL**
istiyor — dosya değil. Bu klasör GitHub Pages'e olduğu gibi konabilir.

## Yayınlama

Bu klasörün içeriğiyle yeni ve **herkese açık** bir depo oluştur (örn.
`tvkumandasi-gizlilik`), sonra:

```bash
cd docs/magaza/site
git init && git add . && git commit -m "Gizlilik politikası"
git branch -M main
git remote add origin https://github.com/<kullanıcı>/tvkumandasi-gizlilik.git
git push -u origin main
```

GitHub'da: **Settings → Pages → Source: Deploy from a branch → main / (root)**.

Adres birkaç dakika içinde açılır:
`https://<kullanıcı>.github.io/tvkumandasi-gizlilik/`

Bu adres Play Console'da **Uygulama içeriği → Gizlilik politikası** alanına,
App Store Connect'te de aynı ada karşılık gelen alana yazılır.

## Güncellerken

Kaynak metin `docs/magaza/gizlilik.md` dosyasıdır; `index.html` onun
yayınlanabilir hâlidir. **İkisi birlikte güncellenir** — uygulamanın davranışı
değişip politika değişmezse mağazaya yanlış beyanla gidilmiş olur.
