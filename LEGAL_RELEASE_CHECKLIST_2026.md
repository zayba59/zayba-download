# ZAYBA hukuki yayımlama kontrolü (4 Kasım 2026)

Bu dosya **hukuki uygunluk onayı değil**, canlıya geçmeden tamamlanması gereken kontrol listesidir.

- [ ] Gerçek kişi veri sorumlusunun ad-soyadını ve uygun yazışma kanalını doğrula; KVKK aydınlatma metnini gerçek bilgilerle tamamla.
- [ ] Supabase veri işleme amaçları, KVKK m.5 hukuki sebepleri, saklama süreleri, alt işleyenler, barındırma bölgesi ve varsa yurt dışı aktarım güvencelerini doğrula.
- [ ] Kişisel veri başvuru, hesap kapatma ve silme/düzeltme taleplerinin uygulama ve veritabanında gerçekten işlendiğini test et.
- [ ] Ayrı iç veri ihlali müdahale planı, sorumlular, kayıtlar ve bildirim akışını hazırla.
- [ ] Ücretsiz kullanım vaatlerini uygulama arayüzü, lisans ekranı ve dağıtılan kurulum dosyasında karşılaştır.
- [ ] Ticari ileti gönderiliyorsa ayrı onay ve geri alma sürecini kur; sadece zorunlu hesap iletileri gönderiliyorsa pazarlama izni toplama.
- [ ] Fontların yerel yüklenişini ve üçüncü taraf ağ isteklerini tarayıcıda denetle.
- [ ] Gerçek yayımlama altyapısını doğrula: Vercel, GitHub entegrasyonu, alan adı ve hangi dalın üretime dağıtıldığı.
- [ ] İndirme dosyası, sürüm, SHA-256 ve SmartScreen uyarılarını gerçek dağıtımla doğrula.
- [ ] İlgili finansal hizmet mevzuatı ve yazılımın gerçek işlevleri için uzman hukuk değerlendirmesi yap.

Yasal kimlik, saklama süresi veya uluslararası veri aktarımı hakkında **doğrulanmamış beyanları yayımlama**. Bu dalın amacı görünür çelişkileri gidermek ve kalan belirsizlikleri belgelemektir; üretim dağıtımı için onay yerine geçmez.
