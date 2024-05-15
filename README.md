- 👋 Hi, I’m @mirzatumay
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
mirzatumay/mirzatumay is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
---># Üretim Süreci Akış Diyagramı

```mermaid
graph TD
    subgraph Üretim Süreci
        A[Kanal Açma Operasyonu] --> B[Diş Açma Kısmı]
        B --> C[Diş Açma Sonrası Süreçler]
        C --> D[Nihai Kontrol ve Ambalajlama]
    end
    subgraph Kalite Kontrol
        A --> AA[Kanal Açma Ölçümleri]
        B --> BA[Diş Açma Ölçümleri]
        BA --> BB[Yıkama ve Kumlama Ölçümleri]
        D --> DA[Nihai Kontrol]
    end
    subgraph Bakım ve Eğitim
        DA --> E[Eğitim ve Sürekli İyileştirme]
        E --> F[Ölçüm Cihazlarının Bakımı ve Temizliği]
    end


