# kuaforeray.com

Tekirdağ Süleymanpaşa'daki bir erkek kuaförü için yaptığım tek sayfalık web sitesi.

Canlı site: https://kuaforeray.com

## Ne yapıyor

- **WhatsApp randevu formu:** Ziyaretçi hizmeti, önümüzdeki 14 günden birini ve yarım saatlik bir saati seçer. Site bu seçimleri hazır bir WhatsApp mesajına çevirir. Pazar günleri ve geçmiş saatler seçilemez.
- **Açık/kapalı göstergesi:** İstanbul saatine göre dükkânın şu an açık olup olmadığını ve ne zaman açılacağını gösterir.
- **Arama motoru verisi:** schema.org işletme verisi, sosyal medya paylaşım etiketleri, sitemap ve robots dosyaları.
- **Mobil uyum:** Telefonda ekranın altında sabit "Randevu al" ve "Ara" düğmeleri.
- **Erişilebilirlik:** Görünür klavye odağı, ekran okuyucu etiketleri ve hareketi azaltma tercihine uyan animasyon.

## Teknik kararlar

- Sunucu ve kütüphane yok. Site tek bir `index.html` dosyasında düz HTML, CSS ve JavaScript ile yazıldı.
- GitHub Pages üzerinde ücretsiz barındırılıyor ve `kuaforeray.com` alan adına bağlı.
- Randevular veritabanına kaydedilmiyor. İstek WhatsApp mesajı olarak gidiyor ve işletme onaylayınca kesinleşiyor.
- Harita, işletme Google Haritalar'da kayıtlı olmadığı için doğrudan adrese sabitlendi.

## Çalıştırma

Derleme adımı yok. `index.html` dosyasını tarayıcıda açmak yeterli.

## Geliştiren

Mert Yüksek: tasarım ve geliştirme.

Site, yapay zeka asistanı Claude ile birlikte çalışılarak geliştirildi. Gereksinimleri belirleme, tasarım kararları, gerçek işletme bilgileriyle test etme ve yayına alma süreci bana aittir.
