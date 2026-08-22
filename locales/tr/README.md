# ARAS'ın Çevrilmesine Yardım Edin

[🇦🇪 العربية](../ar/README.md) • [🇩🇪 Deutsch](../de/README.md) • [🇺🇸 English](../../README.md) • [🇪🇸 Español](../es/README.md) • [🇵🇭 Filipino](../fil/README.md) • [🇫🇷 Français](../fr/README.md)  
[🇮🇳 हिन्दी](../hi/README.md) • [🇮🇩 Bahasa Indonesia](../id/README.md) • [🇮🇹 Italiano](../it/README.md) • [🇰🇭 ខ្មែរ](../km/README.md) • [🇰🇷 한국어](../ko/README.md) • [🇲🇾 Bahasa Melayu](../ms/README.md)  
[🇳🇱 Nederlands](../nl/README.md) • [🇵🇱 Polski](../pl/README.md) • [🇧🇷 Português (Brasil)](../pt-BR/README.md) • [🇷🇴 Română](../ro/README.md) • [🇷🇺 Русский](../ru/README.md) • [🇱🇰 සිංහල](../si/README.md)  
**[🇹🇷 Türkçe](../tr/README.md)** • [🇺🇦 Українська](../uk/README.md) • [🇵🇰 اردو](../ur/README.md) • [🇻🇳 Tiếng Việt](../vi/README.md) • [🇨🇳 简体中文](../zh-Hans/README.md)  

---

ARAS, topluluğumuzdaki gönüllüler tarafından çevrilmektedir. Başka bir dil biliyorsanız, menülerin, düğmelerin ve iletilerin daha fazla kişi için doğal ve anlaşılır olmasına yardımcı olabilirsiniz.

Programlama deneyimine, özel bir yazılıma veya kaynak koduna erişime ihtiyacınız yoktur. Her şey doğrudan GitHub üzerinde web tarayıcınızdan yapılabilir.

## Nasıl Yardım Edebilirsiniz

- Henüz listede olmayan bir dili eklemek
- Hâlâ İngilizce kalan metinleri tamamlamak
- Yazım veya dilbilgisi hatalarını düzeltmek
- İfadeleri Türkçede daha akıcı ve doğal hale getirmek
- Menüler ve iletiler arasındaki tutarlılığı artırmak
- Başka bir katılımcının sunduğu çeviriyi gözden geçirmek

Küçük iyileştirmeler her zaman memnuniyetle karşılanır. Tüm dili tek seferde çevirmek zorunda değilsiniz.

## Mevcut bir dili düzenleme

1. `.json` dosyaları listesinde dilinizi bulun. Örneğin Türkçe `tr.json` ve Almanca `de.json` dosyasıdır.
2. Dosyayı açın ve kalem simgeli **Edit this file** düğmesine tıklayın.
3. Yalnızca her satırın sağ tarafındaki çevrilmiş metni değiştirin.
4. **Preview changes** sekmesine tıklayarak değişikliklerinizi kontrol edin.
5. **Propose changes** düğmesine tıklayın ve bir pull request açın.

```json
"Cancel": "İptal"
```

Soldaki `Cancel` orijinal İngilizce metindir. Sağdaki `İptal` Türkçe çevirisidir. Yalnızca sağ tarafı değiştirin.

## Yeni bir dil talep etme

Bir issue açarak dili, bölgeyi ve çeviri/inceleme durumunuzu bize bildirin.

## Önemli çeviri ipuçları

- `ARAS` adını değiştirmeden bırakın. Bu ürünün adıdır.
- Android, macOS, Mac, ProMotion ve Adreno gibi isimleri genellikle değiştirmeyin.
- ADB, QEMU, QCOW2, DPI, FPS ve GiB gibi teknik kısaltmaları değiştirmeyin.
- Türkçe konuşanlar için doğal bir dille yazın; birebir kelime çevirisinden kaçının.
- Menü ve düğme metinlerini kısa tutun.
- «Aygıt», «ayarlar», «saklama alanı» ve «güncelleme» gibi terimlerde tutarlılık sağlayın.
- Veri silme ve sıfırlama uyarıları net ve ciddi olmalıdır.
- `%@`, `%ld`, `%s`, `%.1f` veya `\n` gibi özel belirteçleri aynen koruyun.
- Makine çevirisi taslak içindir, mutlaka akıcı konuşan biri tarafından kontrol edilmelidir.
- Asla reklam, bağlantı veya kişisel bilgi eklemeyin.

`%@`, `%ld`, `%s`, `%.1f` ve `\n` belirteçleri çalışma sırasında otomatik olarak doldurulur.

Daha fazla bilgi için [çeviri stil kılavuzuna](STYLE_GUIDE.md) bakın.

## Dil dosya adları

Dosya adındaki harfler dili belirtir (ör. `tr.json` — Türkçe).

## İnceleme süreci

Pull request'ler proje yöneticileri tarafından incelenir. [Davranış Kuralları](CODE_OF_CONDUCT.md) geçerlidir.

## [CONTRIBUTING.md](CONTRIBUTING.md)

## Topluluk dosyaları

- `README.md` — Başlangıç ve genel bakış
- `CONTRIBUTING.md` — Katkıda bulunma kuralları
- `CODE_OF_CONDUCT.md` — Topluluk davranış kuralları
- `STYLE_GUIDE.md` — Çeviri ve stil kılavuzu
- `REVIEW_CHECKLIST.md` — İnceleme kontrol listesi
- `../../tr.json` — ARAS Türkçe çeviri kataloğu

## Lisans

Çeviri dosyaları ve belgeler [MIT Lisansı](../../LICENSE) kapsamındadır.
