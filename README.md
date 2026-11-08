# StudTrack

**LEGO koleksiyonunu, parçalarını ve projelerini tek bir yerde yönet.**

StudTrack, kişisel LEGO koleksiyonu için geliştirilen, Windows üzerinde çalışan bir masaüstü koleksiyon yönetimi uygulamasıdır. Koleksiyon kayıtları yerel SQLite veritabanında tutulur; uygulamanın temel koleksiyon yönetimi için bulut hesabı gerekmez.

> **Bu depo**, StudTrack'in **Windows sürümlerini ve imzalı uygulama içi güncelleme dosyalarını** yayımlamak içindir. Kullanıcı koleksiyonu, satın alma belgeleri, kişisel yedekler veya özel imzalama anahtarları bu depoya yüklenmez.

## Özellikler

- **Koleksiyonum:** LEGO setlerini, aynı modelin farklı fiziksel kopyalarını, durumlarını ve görsellerini yönet.
- **Parça envanteri:** Serbest stoktaki parçaları numara, renk ve adet bazında takip et; stok hareketlerini kaydet.
- **MOC projeleri:** Parça kullanımını projelerle ilişkilendir.
- **Siparişler ve satın almalar:** Satıcı, tarih, para birimi ve gerçekleşmiş alış maliyeti kayıtlarını takip et.
- **Fiyat takibi:** Kaynağı doğrulanmış fiyat gözlemlerini veya manuel değerleri ayrı tut; geçmiş alış maliyeti ile güncel piyasa değerini karıştırma.
- **Analiz ve raporlar:** Koleksiyon ve stok verilerini incele.
- **Görünüm:** StudTrack renklerine sahip koyu, açık ve Windows sistemini takip eden tema seçenekleri.

**Fiyat verileri hakkında:** Türkiye'deki mağazalardan otomatik canlı fiyat toplama entegrasyonu henüz tamamlanmadı. Kaynağı olmayan modellerde fiyat tahmini uydurulmaz; eksik değerler açıkça belirtilir. Bazı katalog/parça ve minifigür bilgileri de ek veri kaynağı gerektirebilir.

## Windows için indirme ve güncelleme

Güncel yayımlanmış sürüm dosyalarına **[GitHub Releases](https://github.com/canak13/studtrack-updates/releases)** sayfasından ulaşabilirsin.

Kurulu StudTrack'te yeni sürümleri kontrol etmek için **Ayarlar → Güncellemeleri Kontrol Et** bölümünü kullan. Uygulama içi güncellemeler imzalı Windows kurulum dosyalarıyla yapılır.

Bir sürüm yayımlanırken aşağıdaki dosyalar birlikte bulunur:

| Dosya | İşlev |
| --- | --- |
| `StudTrack_<sürüm>_x64-setup.exe` | Windows kurulum paketi (yeni marka sürümlerinde) |
| `.exe.sig` | Kurulum paketinin dijital güncelleme imzası |
| `latest.json` | Uygulama içi güncelleme bildirimi ve indirme bilgileri |

İmza dosyası, ilgili EXE ile **aynı derlemeden** üretilmelidir. Önceki sürümlere ait tarihsel paket adları, güncelleme uyumluluğunu korumak için değiştirilmez.

## Sürüm notları

Her sürümün değişiklikleri, ilgili **[Release](https://github.com/canak13/studtrack-updates/releases)** sayfasında açıklanır.

> **v0.2.7 geçiş notu:** Tam Windows marka/kurulum kimliği değişikliği ayrı bir yükseltme işlemi gerektirebilir. Eski kurulumu veya yerel verileri yeni sürümde koleksiyonun doğrulanmadan kaldırmayın. v0.2.7 yayımlanmadan önce Windows kurulum, veri taşıma, yedekleme ve güncelleme geçişi doğrulanmalıdır.

## Verilerin korunması

- Koleksiyon verileri kullanıcı bilgisayarında yerel olarak saklanır.
- Uygulama sürümü yükseltilmeden önce yedek alınması önerilir.
- Yedekler ve özel kişisel dosyalar **GitHub Releases'e yüklenmemelidir**.
- Kurulum kimliği değişen sürümlerde iki ayrı uygulama geçici olarak görünebilir; bu durum veri geçişi doğrulanmadan eski uygulamanın kaldırılmasını gerektirmez.

## Marka renkleri

- **Yeşil:** `#5D9253`
- **Sarı:** `#FFCB3D`

**StudTrack — kişisel LEGO koleksiyon yönetimi.**
