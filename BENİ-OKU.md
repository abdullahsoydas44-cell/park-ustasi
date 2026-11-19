# Park Ustası — Android uygulaması

Bu depo, Park Ustası oyununu her güncellemede otomatik olarak Android uygulamasına (APK) dönüştürür.
Oyun internetsiz çalışır: 3D motoru, yazı tipleri ve bütün araç modelleri uygulamanın içindedir.

## APK nasıl indirilir

1. Bu sayfanın sağ tarafındaki **Releases** bölümüne girin.
2. En üstteki sürümde **Park-Ustasi.apk** dosyasına dokunup indirin.
3. Telefonda dosyayı açın. İlk seferde "bilinmeyen kaynaklardan yükleme" izni istenir: izin verip **Yükle**'ye basın.

## Dosyalar

| Dosya / klasör | Ne işe yarar |
|---|---|
| `src/game.html` | Oyunun kendisi. Güncellemede yalnızca bu dosya (ve gerekirse `src/data`) değişir. |
| `src/data/` | Araç, bina ve doku dosyaları. |
| `scripts/prepare-web.js` | Oyunu internetsiz çalışacak hale getirir. |
| `.github/workflows/apk.yml` | APK'yı GitHub'da otomatik üreten adımlar. |
| `assets/icon-only.png` | Uygulama simgesi. |
| `android-imza/debug.keystore` | Uygulamanın imzası. Silmeyin: yeni sürümler eskisinin üstüne bu sayede kurulur. |

Not: "Arkadaşla yarış" modu yalnızca claude.ai'de çalıştığı için uygulamada gizlidir.
