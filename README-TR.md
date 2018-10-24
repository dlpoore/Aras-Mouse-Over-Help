Aras Fare Aşırı Yardımı
Bu proje, fare imlecini bir form alanı üzerinde gezdirirken araç ipuçlarını görüntülemek için bir yöntem sağlar.

Tarihçe
Sürüm notları
v1 İlk sürüm
Desteklenen Aras Sürümleri
Proje Aras
v1 11.0 SP9
Kurulum
Önemli!
Bir içe aktarma paketi veya kod ağacı eki uygulamadan önce her zaman kod ağacınızı ve veritabanınızı yedekleyin!

Ön koşul
Aras Innovator yüklü
Aras Paket İthalat Aracı
ArasMouseOverHelp ithalat paketi
Adımları Yükle
Veritabanınızı yedekleyin ve BAK dosyasını güvenli bir yerde saklayın.
Aras Paketi Alma aracını açın.
Giriş bilgilerinizi girin ve Giriş'i tıklayın.
Not: Başarılı olmak için paket içe aktarma için root olarak giriş yapmalısınız!
Paket adını TargetRelease alanına girin.
İsteğe bağlı: Açıklama alanına bir açıklama girin.
Manifest Dosyası alanına yerel imports.mf dosyanızın yolunu girin.
İçe Aktarılabilir alanında tümünü seçin.
Type = Birleştirme ve Mod = Kapsamlı Mod'u seçin.
Sol üst köşedeki İçe Aktar'ı tıklayın.
Aras Paket Alma aracını kapatın.
kullanım
Fare metnini yapılandır
Öğe Türü Yapılandırma Not: 'Yardım Metni' sütunu yeniden konumlandırılmıştır. Varsayılan olarak, kılavuzun sağ tarafında bulunur.

Aras'a admin olarak giriş yap.
TOC'deki Administration> ItemTypes öğesine gidin ve mouseover ipuçlarını eklemek istediğiniz ItemType öğesini arayın.
Düzenlemek için ItemType'ı açın.
Bir fareyle ilgili ipucu almak istediğiniz her özellik için ipucu metnini "Yardım Metni" alanına girin.
ItemType'ı kaydedin.
Form etkinliğini ekle
Görünümler sekmesini seçin ve görüntülemek için ItemType'ın formunu açın.
Formu kilitle.
Form Etkinlikleri sekmesini seçin.
FRM_SetHelpText yöntemiyle yeni bir OnFormPopulated form olayı ekleyin.
Formu kaydedin, kilidini açın ve kapatın.
Bir Öğede mouseover ipuçlarını görüntüle
Öğe Türü Yapılandırması Fare önleme ipuçları yapılandırılmış bir öğeyi açın ve imleci bir alanın üzerine getirin. Bir açılır pencere görünmezse, tarayıcı önbelleğini çıkın ve temizleyin.
View the ItemType Glossary report
ItemType Yapılandırması ItemType Sözlük Raporu, ItemType'ın özelliklerini ve yapılandırılmış mouseover yardım metnini görüntüler.

Eylem> Öğe Türü Sözlük Raporu'nu seçin.
Contributing
Çatalla!
Özellik dalınızı oluşturun: git checkout -b my-new-feature
Değişikliklerinizi yapın: git commit -am 'Add some feature'
Şubeye itin: git push origin my-new-feature
Çekme isteği gönderin
Kredi
Darryl Poore tarafından düzenlendi.
