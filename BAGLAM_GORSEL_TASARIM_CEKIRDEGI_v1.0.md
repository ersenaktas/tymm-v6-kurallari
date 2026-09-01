# TYMM Bağlam ve İşlevsel Görsel Tasarım Çekirdeği — v1.0

Bu belge, eski birleşik kılavuzdaki güçlü bağlam, bilişsel görev ve görsel tasarım ilkelerini
revize v2.2 kılavuzunun tek ortak bağlam/testlet ve kalite güvence sistemiyle birlikte kullanmak
için hazırlanmış operasyonel ektir. Ana kılavuzla çelişirse müfredat kapsamı, ölçme geçerliği,
bilimsel doğruluk ve tek ortak bağlam kuralları önceliklidir.

## 1. Öncelik sırası

1. Öğrenme çıktısı ve süreç bileşenleri
2. Her süreç bileşeni için gerekli gözlenebilir kanıt
3. Kanıtları doğal biçimde taşıyan tek ortak durum
4. Bağlamın işlevselliği ve kaynak doğruluğu
5. Uygun sunum biçimi, etki alanı ve kurgu stratejisi
6. Yakın geçmişten farklılaşma

Çeşitlilik uygunluğun önüne geçemez. Yakın geçmişte kullanılan bir yapı hedefe en uygun yapıysa
yeniden kullanılabilir; tekrar gerekçesi teknik kayıtta belirtilir. Yalnız rotasyonu tamamlamak için
yapay bir bağlam kurulamaz.

## 2. Kanıt öncelikli ortak bağlam tasarımı

Bağlamı yazmadan önce içsel olarak şu plan yapılır:

- Her SB hangi bilişsel işlemi gerektiriyor?
- Öğrenci bu işlemi yaparken ortak bağlamdaki hangi somut kanıtı kullanacak?
- Kanıt alan bilgisiyle nasıl birleştirilecek?
- Doğru cevaba götüren yol nedir?
- Hangi gerçekçi hata yolları çeldiricilere dönüşebilir?
- Aynı ortak bağlam bütün SB'lere yeterli kanıt sağlıyor mu?

Önce olayın veya problemin doğal mantığı kurulur. Diyalog, tablo, belge paketi, simülasyon izi gibi
sunum biçimleri olayın üzerine sonradan ve yalnız uygunsa uygulanır. Bir etiket, olayın içeriğini
belirleyen ana neden olamaz.

Her soru için beklenen zihinsel yanıt yolu:

1. Bağlamdan gerekli veri veya kanıtı seçme
2. Bu kanıtı hedef alan bilgisiyle ilişkilendirme
3. SB'nin gerektirdiği gözlenebilir sonuca ulaşma

Bağlam çıkarıldığında soru aynı biçimde çözülebiliyorsa bağlam dekoratiftir. Bağlamdaki kritik kanıt
değiştirildiğinde en az bir doğru cevabın değişmesi beklenir.

## 3. Bilişsel görev havuzu

Görev havuzundan rastgele seçim yapılmaz. SB'nin eylemine uygun olan görev seçilir:

- ilişkisel çıkarım ve neden-sonuç zinciri
- kanıt değerlendirme ve iddia test etme
- güvenilir kaynak seçme ve bilgi doğrulama
- karşılaştırmalı değerlendirme
- örüntü bulma ve genelleme
- varsayım analizi
- hata veya kavram yanılgısı tespiti
- süreç sıralama ve değişim analizi
- sınıflandırma ve hiyerarşik ilişki kurma
- modelleme veya model karşılaştırma
- ölçütlere dayalı karar verme
- risk ve sınırlama analizi
- yeni duruma transfer

Aynı testlette soru kökleri yüzeysel olarak çeşitlenirken her soru kendi birincil SB'sini ölçer.
Farklılık uğruna SB'nin gerektirmediği bir bilişsel işlem eklenmez. Sorular ortak bağlamı kullanır
fakat birbirlerinin doğru cevabını açıklamaz.

## 4. Doğal bağlam kontrolü

Bağlam:

- yaş ve sınıf düzeyine uygun olmalı,
- gerçek veya açıkça kurgusal olduğu belirtilmiş makul bir duruma dayanmalı,
- öğrenciyi yapay biçimde yetişkin bir meslek rolüne sokmamalı,
- ölçülmeyen uzmanlık, tüketim deneyimi veya sağlık kararı gerektirmemeli,
- aynı tema içindeki komşu öğrenme çıktılarının içeriğini taşımamalı,
- gereksiz karakter, kurum adı, teknik jargon ve dekoratif ayrıntı içermemelidir.

Kişisel sağlık, tedavi veya etik kararlar yalnız hedef çıktı bunu gerektiriyorsa kullanılır. Bir bilimsel
dönüm noktasını ölçmek için öğrenci veya aile bireyini gerçek bir tedavi kararı vermeye zorlamak
zorunlu değildir; tarihsel belge, kanıt paketi, zaman akışı veya araştırma dosyası daha doğal olabilir.

## 5. Kaynak ve sayısal veri kilidi

- Gerçek dünyaya ilişkin kesin tarih, yüzde, oran, maliyet, klinik sonuç, risk veya başarı değeri
  yalnız yüklenen kaynakta açıkça bulunuyorsa kullanılabilir.
- Her kesin olgu için kaynak dosyası ve bölüm/başlık belirtilir.
- Kaynakta bulunmayan kesin sayı gerçek veri gibi sunulamaz.
- Öğretim amaçlı sentetik veri kullanılacaksa açıkça "Bu veriler soru amacıyla kurgulanmıştır."
  denir; veri bilinen bilimsel ilişkiyle çelişemez.
- "Sıfır risk", "tamamen ortadan kalkar", "her zaman" gibi mutlak bilimsel iddialar kaynakta açık
  kanıt yoksa kullanılmaz.
- Kontrol modeli, bağlamın kendi içinde yazılan raporu o rapordaki iddianın bağımsız kaynağı sayamaz.

## 6. İşlevsel görsel karar kapısı

Görsel otomatik olarak eklenmez. Önce şu soru sorulur:

> Görsel, metinde bulunmayan ve sorunun çözümü için gerekli yeni bir veri, ilişki veya mekânsal yapı
> sunacak mı?

Yanıt hayırsa `visual_spec.required=false` yazılır ve dekoratif görsel üretilmez.

Yanıt evetse uygun tür seçilir:

- grafik
- harita veya kroki
- kavram/ilişki şeması
- süreç diyagramı veya zaman çizelgesi
- deney düzeneği
- model veya kesit
- bilgi görseli
- belge/fotoğraf benzeri kanıt görseli

Tablo, salt görsel çeşitlilik amacıyla resme dönüştürülmez. Kesin sayısal grafikler ve şemalar için
kritik veri kilidi, serbest üretim promptundan daha üst önceliklidir.

## 7. Görsel tasarım paketi

Görsel gerekliyse `visual_spec` içinde şunlar doldurulur:

- `type`: görsel türü
- `rationale`: neden gerekli olduğu ve hangi sorulara kanıt sağladığı
- `student_caption`: öğrenciye gösterilecek kısa başlık
- `designer_prompt_tr`: Türkçe tasarımcı yönergesi
- `image_prompt_en`: görsel üretim aracı için İngilizce prompt
- `critical_visual_data`: aynen korunacak eksen, sayı, etiket, yön, renk anlamı ve ilişkiler
- `alt_text`: görselin erişilebilir metinsel karşılığı

Prompt şu özellikleri taşımalıdır:

- sade, iki boyutlu ve yaş düzeyine uygun tasarım
- okunaklı Türkçe etiketler
- gereksiz dekor, logo, filigran veya fotogerçekçi ayrıntı olmaması
- sorunun çözümünde kullanılan kritik verilerin açık görünmesi
- metni yalnızca resmetmek yerine yeni kanıt sunması

Mevcut Word/PDF üretiminde gerçek görsel dosyası oluşturulmadığı için `material_markdown`, görseldeki
bütün kritik verilerin erişilebilir metinsel eşdeğerini de taşımalıdır. Böylece tasarım yapılmadan önce
de soru denetlenebilir. Görsel sonradan eklendiğinde bu eşdeğer veriyle birebir karşılaştırılır.

## 8. Son kontrol

- Bağlam SB'lerden mi türedi, yoksa seçilen etiketlere uyduruldu mu?
- Her soru ortak bağlamdaki farklı ve gerekli bir kanıtı mı kullanıyor?
- Kaynaksız kesin sayı veya bilimsel iddia var mı?
- Bağlam doğal mı, yoksa çeşitlilik göstermek için mi karmaşıklaştırılmış?
- Görsel gerçekten gerekli mi?
- Görsel promptu kritik verileri kilitliyor mu?
- Görsel olmadan sunulan metinsel eşdeğer aynı kanıtı eksiksiz taşıyor mu?
- Sorular birbirlerinin doğru cevaplarını ele veriyor mu?

Bu kontrollerden biri başarısızsa set kullanıcıya sunulmadan önce hedefli olarak revize edilir.
