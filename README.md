🌟 CoinPazarı 🌟


CoinPazarı 💰, kullanıcıların kripto para birimleri hakkında en güncel verilere erişmesini sağlayan dinamik bir web uygulamasıdır. CoinGecko API'si üzerinden veri çekerek, global piyasa verilerinden popüler coin'lere kadar çeşitli bilgileri sunar. Ayrıca, kullanıcılar uygulamanın temasını (açık veya koyu) değiştirebilir ve piyasa trendlerini takip edebilirler.

🚀 Özellikler
Global Piyasa Verisi 🌍: Toplam kripto para sayısı, borsaların sayısı, piyasa değeri, işlem hacmi ve daha fazlası.

Tema Değiştirme 🎨: Kullanıcılar, uygulamanın temasını rahatlıkla değiştirebilir (açık/dark).

Kripto Para Trendleri 📈: En popüler coin'ler, NFT'ler ve piyasa trendleri.

Kripto Para Borsaları 🏦: En yüksek güven puanına sahip borsalar.

Kripto Para Kategorileri 🗂️: Coin'ler farklı kategorilere ayrılır.

Gerçek Zamanlı Veri ⏱️: Tüm veriler CoinGecko API'sinden anlık olarak çekilir.

🛠️ Kullanılan Teknolojiler
HTML5 📄: Uygulamanın temel yapısının oluşturulmasında kullanıldı.

CSS3 🎨: Sayfa stilini belirlemek ve responsive tasarım sağlamak için kullanıldı.

JavaScript ⚡: Dinamik veri çekme ve kullanıcı etkileşimlerini işlemek için kullanıldı.

Bootstrap 🧰: Sayfanın duyarlı tasarımını kolaylaştırmak için kullanıldı.

Chart.js 📊: Kripto para birimlerinin 7 günlük grafiklerini göstermek için kullanıldı.

CoinGecko API 🔌: Kripto para verilerini çekmek için açık kaynaklı API.

LocalStorage 💾: API verilerinin cache edilmesi ve sayfa yenilendiğinde hız sağlanması için kullanıldı.


🔍 Kod Yapısı
JavaScript İşlevleri
Tema Yönetimi 🎨: Kullanıcı tema değiştirdiğinde, tercih localStorage'a kaydedilir ve sayfa yüklendiğinde otomatik olarak uygulanır.

Veri Çekme ve Görüntüleme 📊: API'den veri çekme işlemi fetchGlobal() fonksiyonu ile yapılır ve veriler dinamik olarak sayfada görüntülenir.

Grafikler 📈: Chart.js ile her coin'in 7 günlük fiyat değişimi görsel olarak sunulur.

📑 Fonksiyonlar
getLocalStorageData(): localStorage'tan veri okuma.

setLocalStorageData(): localStorage'a veri kaydetme.

toggleSpinner(): Veriler yüklenirken spinner (yükleniyor) simgesi gösterme.

createTable(): Veri için dinamik tablo oluşturma.

createWidget(): TradingView gibi widget'ları sayfaya ekleme.


Ekran görüntüaü:

![Image](https://github.com/user-attachments/assets/0432fb4e-8dff-4983-8c94-8a065f0dea37)



