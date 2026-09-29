# 911: Idle Dispatch yönlendirme sayfası

`index.html` tek başına GitHub Pages üzerinde çalışır. iOS ve Android mağaza bağlantıları ile GA4 ölçüm kimliği dosyada hazırdır.

## Yayınlama

Depo: [hanxgames/911-idle-dispatch-download](https://github.com/hanxgames/911-idle-dispatch-download)

Adres: [911: Idle Dispatch indirme sayfası](https://hanxgames.github.io/911-idle-dispatch-download/)

GA4 Web akışı ölçüm kimliği: `G-W6SN1JY1H2`

[Bu oyunun GA4 raporlarını aç](https://analytics.google.com/analytics/web/?authuser=4#/a381400007p556548084/reports/intelligenthome)

## Sayıları görme

GA4'te **Raporlar → Gerçek zamanlı genel bakış** ekranı son 30 dakikayı gösterir. Geçmiş veriler için **Raporlar → Oyun raporları → Etkileşim → Etkinlikler** yolunu izle ve tarih aralığını seç. Yeni olayların geçmiş raporlarda görünmesi zaman alabilir.

| Olay | Anlamı |
| --- | --- |
| `page_view` | Yönlendirme sayfasının açılma sayısı |
| `app_store_redirect` | App Store'a yönlendirme veya düğme tıklaması |
| `google_play_redirect` | Google Play'e yönlendirme veya düğme tıklaması |

**Event count** tekrarları içerir. **Total users** aynı dönemde olayı gerçekleştiren yaklaşık tekil kullanıcı sayısıdır. Bunlar mağazada gerçekleşen indirmeleri göstermez. Reklam engelleyiciler ve bağlantı açıldıktan hemen sonra kapanan sayfalar nedeniyle sayımlar eksik olabilir.
