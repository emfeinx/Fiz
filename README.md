##SpoMini: Güçlü Mini YouTube Oynatıcısı

##🌟 Proje Hakkında
SpoMini, saf HTML, CSS ve Vanilla JavaScript kullanılarak geliştirilmiş, minimalist ve özellik dolu bir mini müzik oynatıcısıdır. Proje, herhangi bir harici kütüphaneye (YouTube IFrame API hariç) bağımlı kalmadan, modern ve karanlık bir arayüz ile YouTube videolarını oynatmanıza, kendi çalma sıranızı (Queue) yönetmenize ve playlistlerinizi yerel olarak kaydetmenize olanak tanır.

Son versiyon, YouTube'un API kısıtlamalarını aşmak ve performansı artırmak amacıyla video bilgilerini (başlık, sanatçı) yerel placeholder verileriyle değiştirmeyi ve yalnızca video kapağını (thumbnail) göstermeyi hedefleyen kararlı bir yapıya sahiptir.

---

##✨ Temel Özellikler
YouTube Entegrasyonu: YouTube IFrame API'si aracılığıyla URL veya Video ID ile kolayca şarkı ekleme.

Gelişmiş Kuyruk Yönetimi: Çalma sırasındaki şarkıları ekleme, kaldırma ve sürükle-bırak (Drag & Drop) ile yeniden düzenleme.

Playlist Sistemi: Oluşturduğunuz çalma sıralarını tarayıcınızın Yerel Depolamasına (LocalStorage) kaydedin, yükleyin ve yönetin.

Minimalist Tasarım: Modern, karanlık tema ve tercihe bağlı olarak kapatılabilen akıcı arka plan animasyonları.

Disk Animasyonu: Çalan parçanın kapağını dönen bir disk (vinil) olarak görselleştirir.

Oynatma Kontrolleri: Duraklat/Oynat, İleri/Geri Sarma (10 saniye), Önceki/Sonraki Parça, Ses Kontrolleri ve İlerleme Çubuğu ile hızlı atlama.

Oynatma Modları: Tek şarkı döngüsü (Loop One), tüm sıra döngüsü (Loop All) ve rastgele çalma (Shuffle) modları.

Kişiselleştirme: Kullanıcı adı, avatar (resim yükleme ve gösterme) ve dil (Türkçe/İngilizce) gibi gelişmiş ayarlar.

---

##🚀 Nasıl Başlatılır
SpoMini, sadece tek bir HTML dosyası (index.html) olduğu için kurulumu son derece basittir.

Yöntem 1: Yerel Olarak Çalıştırma
Bu depoyu klonlayın veya son index.html dosyasını indirin.

Dosyayı herhangi bir modern web tarayıcısı (Chrome, Firefox, Edge vb.) ile açın.

Yöntem 2: GitHub Pages Kullanımı
index.html dosyasını doğrudan GitHub Pages'da yayınlayarak anında çalışan bir mini oynatıcıya sahip olabilirsiniz.

---

##💡 Kullanım Adımları
Şarkı Ekleme: Sol taraftaki Sıra panelini açın. YouTube URL'sini veya video ID'sini giriş alanına yapıştırın ve "Sıraya Ekle" butonuna tıklayın.

Playlist Oluşturma: Şarkılarınızı sıraya ekledikten sonra, Playlistler sekmesine geçin ve sırayı kalıcı olarak kaydetmek için bir isim verin.

Ayarlar: Sağ taraftaki ⚙️ ikonuna tıklayarak profil bilgilerinizi ve uygulamanın görünüm/davranış ayarlarını değiştirebilirsiniz.

---

##🛠️ Teknolojiler
HTML5 & CSS3 (Vanilla)

Vanilla JavaScript (ES6+)

YouTube IFrame Player API

LocalStorage (Kalıcı veri saklama için)
