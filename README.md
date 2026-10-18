# Nextion HMI - Resource-Optimized Smart Monitoring UI

🌍 *[🇹🇷 Türkçe versiyon için aşağıya kaydırın (Click here for Turkish)](#türkçe-versiyon)*

This project is a highly memory-optimized smart environment and sensor monitoring interface developed for Nextion HMI (Human-Machine Interface) displays with a 400x240 resolution. Designed to operate under strict hardware constraints (maximum 3584 bytes of RAM), it centers on UI/UX design and memory management principles for embedded systems.

## 🚀 Key Highlights

- **Ultra-Low Memory Footprint (RAM Optimization):** The 3.5 KB RAM limit was successfully overcome through precise scope management of variables (`vscope` - global/local isolation) and rigorous configuration of maximum character limits (`txt_maxl`). Memory-intensive operations, such as dynamic QR code generation, were successfully integrated into the system by meticulously resolving memory bottlenecks.
- **Modular and Symmetrical UI Design:** Built on a fixed top status bar and bottom navigation menu, the interface features flexible home page variations utilizing 2x2, 3x2, and 1+4 symmetrical card grids to adapt to varying sensor densities.
- **Dynamic Bilingual Support (EN/TR):** Instant and seamless language switching across all screens was achieved using custom scripts executed during the page loading phase (`Preinitialize Event`).
- **Comprehensive System Management:** Dedicated control pages were coded for temperature, humidity, power, and flood sensors, as well as network settings and threshold (limit) configurations.

## 🛠️ Technologies & Concepts

- **Environment:** Nextion Editor
- **Concepts:** HMI Design, Embedded UI/UX, Memory Management, Resource-Constrained Environments

---

## 🇹🇷 Türkçe Versiyon

Bu proje, 400x240 çözünürlüğe sahip Nextion HMI (Human-Machine Interface) ekranlar için geliştirilmiş, yüksek bellek optimizasyonuna sahip bir akıllı ortam ve sensör izleme arayüzüdür. Kısıtlı donanım kaynaklarında (maksimum 3584 bayt RAM) çalışacak şekilde tasarlanmış olup, gömülü sistemlerde UI/UX tasarımı ve bellek yönetimi prensiplerini merkeze almaktadır.

## 🚀 Öne Çıkan Özellikler (Key Highlights)

- **Ultra-Düşük Bellek Kullanımı (RAM Optimization):** 3.5 KB RAM sınırı, değişkenlerin kapsam yönetimi (`vscope` - global/local izolasyonu) ve maksimum karakter sınırlarının (`txt_maxl`) hassas konfigürasyonu ile aşılmıştır. Dinamik QR kod üretimi gibi yüksek RAM gerektiren işlemler, bellek darboğazları optimize edilerek sisteme başarıyla entegre edilmiştir.
- **Modüler ve Simetrik UI Tasarımı:** Sabit üst durum çubuğu ve alt navigasyon menüsü üzerine inşa edilmiş; 2x2, 3x2 ve 1+4'lük simetrik kart ızgaraları (grid) ile farklı sensör yoğunluklarına adapte olabilen esnek ana sayfa varyasyonları tasarlanmıştır.
- **Dinamik Çoklu Dil Desteği (TR/EN):** Sayfa yüklenme aşamasında (`Preinitialize Event`) çalışan özel scriptler sayesinde, ekranlar arası geçişte anlık ve pürüzsüz dil değişimi sağlanmıştır.
- **Kapsamlı Sistem Yönetimi:** Sıcaklık, nem, güç, sel (flood) sensörleri, ağ ayarları ve eşik (limit) konfigürasyonları için özel kontrol sayfaları kodlanmıştır.

## 🛠️ Kullanılan Teknolojiler

- **Ortam:** Nextion Editor
- **Kavramlar:** HMI Design, Embedded UI/UX, Memory Management, Resource-Constrained Environments