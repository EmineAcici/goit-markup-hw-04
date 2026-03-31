# GoIT Markup Homework 04 - WebStudio (Advanced CSS & SVG)

Bu proje, GoIT Full Stack Developer eğitimi kapsamında hazırlanan **WebStudio** projesinin dördüncü aşamasıdır. Bu bölümde, web sitesine gelişmiş interaktivite, vektörel grafik yönetimi (SVG Sprites) ve modern animasyon teknikleri entegre edilmiştir.

## 🚀 Proje Gereksinimleri ve Teknik Standartlar

Bu çalışma, belirtilen tüm teknik kriterlere (A1-C11) tam uyumlu olarak geliştirilmiştir:

### 🏗️ Varlık Yönetimi ve Yapı (A Serisi)
- **SVG Sprites:** Tüm vektörel ikonlar, `images/` klasöründeki tek bir `icons.svg` (sprite) dosyasında toplanmıştır.
- **Optimizasyon:** Tüm görseller ve vektörler web performansı için optimize edilmiştir.
- **Normalizasyon:** `modern-normalize` kullanımı sürdürülerek tarayıcı uyumluluğu korunmuştur.
- **Kod Standartları:** Stil kuralları `css/styles.css` dosyasında toplanmış ve **Prettier** ile biçimlendirilmiştir.

### 📝 Gelişmiş İşaretleme (B Serisi)
- **Vektör Kullanımı:** İkonlar HTML içerisinde `<svg>` ve `<use>` etiketleri kullanılarak sprite üzerinden çağrılmıştır.
- **İkon Entegrasyonu:** - "Advantages" (Avantajlar) bölümüne temsilî ikonlar eklenmiştir.
  - "Our Team" kartlarına ve "Footer" alanına sosyal medya ikonları yerleştirilmiştir.
- **Semantik Yapı:** Tüm öğeler anlamsal (semantic) HTML5 etiketleri ile işaretlenmiştir.

### 🎨 İleri Seviye Tasarım ve Animasyon (C Serisi)
- **Hero Arka Planı:** Hero bölümünde 1440px genişliği aşmayan, degrade (gradient) ve solma efekti içeren çok katmanlı bir arka plan kullanılmıştır.
- **Efektler ve Gölgeler:** - "Our Team" kartlarına kalıcı gölge, "Our Portfolio" kartlarına ise `:hover` durumunda gölge efekti eklenmiştir.
  - Portföy kartlarında, üzerine gelindiğinde aşağıdan yukarı doğru açılan mavi metin kaplaması (Overlay) uygulanmıştır.
- **Geçişler (Transitions):** - Tüm etkileşimli öğeler (renk, arka plan, gölge) için **250ms** süre ve **cubic-bezier(0.4, 0, 0.2, 1)** zaman fonksiyonu tanımlanmıştır.
  - `transition: all` kullanımından kaçınılmış, değişen özellikler (örn: `color`, `background-color`) açıkça belirtilmiştir.
- **Navigasyon Alt Çizgisi:** Mevcut sayfayı belirtmek için ana navigasyon linklerine `::after` sözde öğesi (pseudo-element) ile dekoratif alt çizgi eklenmiştir.

## 🛠️ Kullanılan Teknolojiler
* **HTML5 & CSS3**
* **SVG Sprites** (İkon Yönetimi)
* **CSS Transitions & Pseudo-elements**
* **BEM Methodology** (Sınıf Adlandırma)
* **Prettier**

## 🔗 Canlı Önizleme
Projenin interaktif versiyonuna aşağıdaki bağlantıdan ulaşabilirsiniz:
[GitHub Pages Üzerinden Görüntüle](https://emineacici.github.io/goit-markup-hw-04/)

---
*Hazırlayan: [Emine Acıcı](https://github.com/EmineAcici)*
