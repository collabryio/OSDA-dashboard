# OSDA-dashboard

- src :: Referans Dokümantasyonu: Tüm Scriptlerimiz || ((20735eb6-a49e-4e3d-9e13-8c27d19830ea))

## Niçin?

- Takım üyeleri birden fazla sistemde çalışıyor: issue'lar, push'lar, bbl'ler.
	- Bunları tek bir arayüzden takip etmek istiyoruz.

## Ne yapıyor?

Üç sistemi tek dashboard'da gösterir:

- **Issues** — kim hangi görevleri tamamladı, yarattı, açık bıraktı
- **Push Raporu** — kim hangi dosyaları pushladı
- **BBL'ler** — `#g/nxt`, `#g/ltr` gibi etiketlere göre filtrelenebilir görev listesi

## Kullanım

[https://osda-dashboard.collabry.io](https://osda-dashboard.collabry.io) adresinden erişilir.

Açılışta api-key girilir, `localStorage`'a kaydedilir.

## Dosyalar

| Dosya | Açıklama |
|---|---|
| `index.html` | Tek sayfalık dashboard uygulaması |

## Çözdüğü OSDA Problemleri

| OSDA Dokümanı | Repo | ID |
|---|---|---|
| Geçtiğimiz hafta kim hangi dosyaları pushladı? | [OSDA-who-pushed-which-files](https://github.com/collabryio/OSDA-who-pushed-which-files) | `((9fe09103-90a7-4438-b6b6-df16b6417d45))` |
| Geçtiğimiz hafta kim hangi görevleri tamamladı? | [OSDA-Who-Completed-Which-Issues-Last-Week](https://github.com/collabryio/OSDA-Who-Completed-Which-Issues-Last-Week) | `((ba5646dc-3962-45b0-83b6-549a1473b117))` |
| Redis'e yeni kayıt eklenince Teams bildirimi | [OSDA-bbl-to-redis-teams-notification](https://github.com/collabryio/OSDA-bbl-to-redis-teams-notification) | `((17ae52af-c6cd-49e2-8a79-5adf48353a9c))` |
| Referans Dokümantasyonu: Tüm Scriptlerimiz | [OSDA-api](https://github.com/collabryio/OSDA-api) | `((20735eb6-a49e-4e3d-9e13-8c27d19830ea))` |

## API

Tüm veriler `https://osda-api.collabry.io` üzerinden çekilir. Detaylar için bkz. [OSDA-api](https://github.com/collabryio/OSDA-api).
