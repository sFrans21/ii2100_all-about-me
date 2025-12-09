# UAS-3 My Innovations

**HarmonAI-Architect: Arsitektur Sistem Deteksi Multimodal dan Detoksifikasi Generatif**

![HarmonAI System Architecture](../images/harmonai_architecture.png)

Inovasi utama saya adalah **HarmonAI-Architect**, sebuah platform _hybrid-intelligence_ yang mengubah paradigma penanganan konflik dari "reaktif-biner" (hapus/biarkan) menjadi "proaktif-restoratif" (deteksi, ukur, sembuhkan). Sistem ini mengintegrasikan kecerdasan buatan dalam kerangka strategi _Ends-Ways-Means_ untuk mencapai perdamaian berkelanjutan.

Sistem ini beroperasi melalui empat modul terintegrasi yang membentuk siklus resolusi konflik:

### 1. Sentinel-X: Modul Deteksi Multimodal (The Sensing Layer)

Inovasi pertama adalah kemampuan sistem untuk "melihat" dan "membaca" secara bersamaan, mengatasi keterbatasan moderasi konvensional yang buta terhadap konteks budaya visual.

- **Mekanisme:** Menggunakan pendekatan **Multimodal Deep Learning** yang menggabungkan fitur teks dan visual.
- **Teknologi:** Menggunakan _Optical Character Recognition_ (Tesseract) untuk mengekstrak teks dari meme, kemudian memadukan fitur visual (menggunakan ResNet/VGG16) dengan fitur tekstual (menggunakan _transformer models_ seperti Afro-XLMR).
- **Keunggulan:** Mampu mendeteksi kebencian yang tersirat dalam _meme_ (kombinasi gambar + teks) yang seringkali lolos dari deteksi teks biasa, serta mendukung bahasa _low-resource_ yang sering terabaikan.

### 2. Spectrum Analyzer: Mesin Analisis Intensitas (The Cognitive Layer)

Berbeda dengan sistem lama yang hanya melabeli "Benci" atau "Tidak", modul ini menganalisis **spektrum intensitas** konflik.

- **Inovasi Skala Kontinuum:** Mengadopsi skala Likert (1-5 atau 1-10) untuk mengukur tingkat toksisitas, mulai dari "Peringatan Dini" (Mild) hingga "Hasutan Kekerasan" (Severe).
- **Identifikasi Target:** Sistem secara spesifik memetakan target kebencian, apakah serangan tersebut ditujukan pada etnis, politik, atau agama, yang merupakan pemicu utama konflik di wilayah rentan. Hal ini memungkinkan pemetaan risiko yang lebih akurat untuk intervensi kebijakan.

### 3. Detox-Gen: Mesin Detoksifikasi Generatif (The Action Layer)

Ini adalah inti dari inovasi restoratif HarmonAI. Sistem tidak menghapus konten, tetapi menawarkan **penulisan ulang (rewriting)**.

- **Mekanisme:** Menggunakan _Large Language Models_ (LLMs) yang telah di-_fine-tune_ dengan korpus paralel (_Parallel Detoxification Corpus_) untuk melakukan _style transfer_.
- **Fungsi:** Mengubah kalimat toksik menjadi kalimat netral atau non-toksik tanpa menghilangkan makna aslinya. Ini memberikan opsi bagi moderator atau pengguna untuk "mendinginkan" suasana tanpa memberangus kebebasan berpendapat.

### 4. Agora-Link: Antarmuka Mediasi Digital (The Human Layer)

Sistem ini tidak berjalan otonom penuh, tetapi menempatkan manusia sebagai pemegang kendali (_Human-in-the-Loop_) untuk menjamin akuntabilitas.

- **Transparansi & Kontrol:** Sesuai prinsip kebijakan publik, setiap keputusan AI (misalnya rekomendasi detoksifikasi) harus dapat diaudit dan diverifikasi oleh manusia.
- **Digital Storytelling:** Jika eskalasi terdeteksi tinggi, sistem memfasilitasi ruang mediasi digital di mana pihak yang bertikai dapat berbagi narasi (_storytelling_) untuk membangun empati, menggunakan teknologi sebagai jembatan interaksi sosial.

---

**Ringkasan Arsitektur Teknis:**

| Komponen              | Input                | Teknologi Inti                   | Output                           |
| :-------------------- | :------------------- | :------------------------------- | :------------------------------- |
| **Sentinel-X**        | Teks + Meme (Gambar) | VGG16/ResNet + Afro-XLMR         | Label Multimodal (Hate/Non-Hate) |
| **Spectrum Analyzer** | Label Awal           | Regression Models (Likert Scale) | Skor Intensitas (1-10) & Target  |
| **Detox-Gen**         | Teks Toksik          | Generative LLMs (mBART/GPT-4)    | Teks Terdetoksifikasi (Netral)   |
| **Agora-Link**        | Konflik Eskalatif    | Platform ODR & Dashboard Manusia | Resolusi Konflik & Mediasi       |

Dengan arsitektur ini, HarmonAI-Architect menjawab tantangan "kebutaan" teknologi terhadap bahasa lokal dan konteks visual, sekaligus menawarkan solusi damai melalui teknologi generatif.
