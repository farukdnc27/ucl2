# 🦁 Galatasaray UCL Squad

Galatasaray'ın UEFA Şampiyonlar Ligi kadrosunu ve saha dizilişini görüntülemek için geliştirilmiş, modern ve etkileşimli bir web uygulaması.

🌐 **Canlı Demo:** [https://galatasarayuclsquad.netlify.app/](https://galatasarayuclsquad.netlify.app/)

![Project Preview](https://galatasarayuclsquad.netlify.app/assets/screenshot-or-logo.png) <!-- Buraya projenizden bir ekran görüntüsü ekleyebilirsiniz -->

## 📋 Proje Hakkında

Bu proje, Galatasaray taraftarları ve futbol severler için takımın Şampiyonlar Ligi kadrosunu görsel bir arayüzde sunar. Oyuncu verilerini dinamik olarak çeker ve futbol sahası üzerinde veya liste halinde kullanıcıya gösterir.

### ✨ Özellikler

*   **Güncel Kadro:** JSON tabanlı veri yapısı sayesinde oyuncu bilgileri.
*   **Saha Görünümü:** Futbol sahası (`pitch-lines.svg`) üzerinde görsel yerleşim.
*   **Modern Arayüz:** Kullanıcı dostu ve responsive (mobil uyumlu) tasarım.
*   **Hızlı Performans:** Vite ve React altyapısı (build edilmiş statik yapı) sayesinde hızlı yükleme süreleri.

## 🛠 Teknolojiler

Bu proje aşağıdaki teknolojiler kullanılarak oluşturulmuştur:

*   **Frontend:** React, TypeScript, Vite
*   **Veri:** JSON (`players.json`)
*   **Assets:** SVG Grafikler

## 🚀 Kurulum ve Çalıştırma

Bu repo, projenin derlenmiş (build alınmış) statik dosyalarını veya saf HTML/JS yapısını içermektedir. Bilgisayarınızda çalıştırmak için şu adımları izleyebilirsiniz:

1.  **Projeyi Klonlayın:**
    ```bash
    git clone https://github.com/farukdnc27/ucl2.git
    ```

2.  **Dizine Gidin:**
    ```bash
    cd ucl2
    ```

3.  **Çalıştırın:**
    *   Bu aşamada herhangi bir `npm install` komutuna ihtiyacınız yoktur (repo statik dosyaları içerdiği için).
    *   Dosyaları görüntülemek için **VS Code Live Server** eklentisini kullanabilir veya `index.html` dosyasını tarayıcınızda açabilirsiniz.

## 📂 Dosya Yapısı

*   `index.html`: Uygulamanın giriş noktası.
*   `players.json`: Oyuncu verilerinin (isim, numara, pozisyon vb.) tutulduğu dosya.
*   `assets/`: CSS, JavaScript ve görsel dosyaların bulunduğu klasör.
*   `pitch-lines.svg`: Saha zemin görseli.

## 🤝 Katkıda Bulunma

Katkıda bulunmak isterseniz:
1.  Bu projeyi forklayın.
2.  Yeni bir özellik dalı (branch) oluşturun (`git checkout -b yeni-ozellik`).
3.  Değişikliklerinizi commit yapın (`git commit -m 'Yeni özellik eklendi'`).
4.  Branch'inizi pushlayın (`git push origin yeni-ozellik`).
5.  Bir Pull Request oluşturun.

## 👤 Yazar

**Faruk DNC**
*   GitHub: [@farukdnc27](https://github.com/farukdnc27)

---
*Bu proje Galatasaray SK'nın resmi uygulaması değildir, taraftar yapımı bir çalışmadır.*
