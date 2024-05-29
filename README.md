# Spotify ve YouTube Veri Analizi

Bu depo, Spotify ve YouTube verilerinin kapsamlı bir keşifsel veri analizi (EDA) çalışmasını içerir. Proje, Python kullanarak veri analizi ve görselleştirme yaparak bu iki platformdaki şarkıların ve videoların çeşitli özellikleri hakkında içgörüler sağlar.

Bu projede, Spotify ve YouTube'dan alınan veri setlerini analiz ederek bu platformlardaki müzik parçalarının özelliklerini ve trendlerini anlamaya çalışıyoruz. Python kullanarak keşifsel veri analizi (EDA) yapıyor ve bulgularımızı görselleştirerek kalıpları ve içgörüleri ortaya çıkarıyoruz. 


Veri seti aşağıdaki kolonları içermektedir:

### Spotify Verileri
- `track`: Şarkının Spotify'da görünen adı.
- `artist`: Sanatçının adı.
- `spotify_url`: Sanatçının Spotify'daki URL'si.
- `album`: Şarkının dahil olduğu albüm.
- `album_type`: Şarkının tekil mi yoksa bir albümün parçası olarak mı yayınlandığını gösterir.
- `danceability`: Şarkının dans etmek için uygunluğunu tanımlar.
- `energy`: Şarkının algılanan yoğunluğunu ve aktivitesini temsil eder.
- `key`: Şarkının tonunu temsil eder.
- `loudness`: Şarkının genel ses seviyesi (desibel - dB) ölçüsüdür.
- `acousticness`: Şarkının ne kadar akustik olduğunu belirtir.
- `instrumentalness`: Şarkının vokal içerip içermediğini tahmin eder.
- `liveness`: Kayıtta bir izleyici varlığını tespit eder. Daha yüksek liveness değerleri şarkının canlı olarak çalındığı olasılığını gösterir.
- `valence`: Şarkının müzikal pozitifliği ile ilgili bir ölçüdür.
- `tempo`: Şarkının tahmini tempo değeridir.
- `duration_ms`: Şarkının süresi milisaniye cinsinden ölçülmüştür.
- `stream`: Şarkının Spotify'daki akış sayısı.

### YouTube Verileri
- `url_youtube`: Şarkıya bağlı olan YouTube video URL'si, eğer varsa.
- `title`: YouTube videoklip başlığı.
- `channel`: Videoyu yayınlayan kanalın adı.
- `views`: YouTube'daki video görüntüleme sayısı.
- `likes`: YouTube'daki video beğeni sayısı.
- `comments`: YouTube'daki video yorum sayısı.
- `description`: YouTube'daki video açıklaması.
- `licensed`: Videonun lisanslı içeriği temsil edip etmediğini belirtir.
- `official_video`: Şarkının resmi video olup olmadığını gösteren boolean değeri.

EDA, şarkıların dans edilebilirliği, enerjisi ve hem Spotify hem de YouTube'daki popülerlikleri gibi çeşitli özellikler hakkında içgörüler sağlar. Görselleştirmeler, farklı özellikler arasındaki trendleri ve korelasyonları anlamamıza yardımcı olur.
