## Daftar Fitur Dataset `mental_health.csv`

Dataset ini berisi **10.000 baris** dan **51 kolom** yang mencakup berbagai faktor terkait demografi, pekerjaan, gaya hidup, hingga riwayat kesehatan. Dataset ini sepenuhnya sintetis, tanpa adanya nilai yang hilang (*missing values*).

---

## 1. Demographics (Faktor Demografis)

| No | Nama Kolom | Terjemahan | Tipe | Keterangan |
|----|-----------|------------|------|------------|
| 1 | `Age` | Usia | Numerik | Usia responden |
| 2 | `Gender` | Jenis Kelamin | Kategorikal | Jenis kelamin responden (Male, Female, Non-binary, dll) |
| 3 | `Country` | Negara | Kategorikal | Negara asal responden |
| 4 | `Education` | Tingkat Pendidikan | Kategorikal | Tingkat pendidikan terakhir (High School, Bachelor, dll) |
| 5 | `Marital_Status` | Status Pernikahan | Kategorikal | Status pernikahan responden |
| 6 | `Income_Level` | Tingkat Pendapatan | Kategorikal | Kategori tingkat pendapatan (Low, Middle, High) |

---

## 2. Work / Academic Factors (Faktor Pekerjaan / Akademik)

| No | Nama Kolom | Terjemahan | Tipe | Keterangan |
|----|-----------|------------|------|------------|
| 7 | `Employment_Status` | Status Pekerjaan | Kategorikal | Status pekerjaan (Full-time, Part-time, Student, dll) |
| 8 | `Work_Hours_Per_Week` | Jam Kerja per Minggu | Numerik | Jumlah jam kerja dalam satu minggu |
| 9 | `Remote_Work` | Status Kerja Jarak Jauh | Kategorikal | Apakah responden bekerja jarak jauh (Yes, No, Hybrid) |
| 10 | `Job_Satisfaction` | Kepuasan Kerja | Numerik | Skala tingkat kepuasan kerja |
| 11 | `Work_Stress_Level` | Tingkat Stres Kerja | Numerik | Skala tingkat stres dari pekerjaan |
| 12 | `Work_Life_Balance` | Keseimbangan Kerja & Hidup | Numerik | Skala tingkat keseimbangan kehidupan kerja |
| 13 | `Ever_Bullied_At_Work` | Pernah Dirundung di Kerja | Kategorikal | Apakah pernah mengalami perundungan di tempat kerja (0=Tidak, 1=Ya) |
| 14 | `Company_Mental_Health_Support` | Dukungan Mental Perusahaan | Kategorikal | Apakah perusahaan memberikan dukungan kesehatan mental |

---

## 3. Lifestyle & Habits (Gaya Hidup & Kebiasaan)

| No | Nama Kolom | Terjemahan | Tipe | Keterangan |
|----|-----------|------------|------|------------|
| 15 | `Exercise_Per_Week` | Frekuensi Olahraga | Kategorikal | Frekuensi olahraga per minggu (Never, 1-2 times, dll) |
| 16 | `Sleep_Hours_Night` | Durasi Tidur per Malam | Numerik | Jumlah jam tidur di malam hari |
| 17 | `Caffeine_Drinks_Day` | Konsumsi Kafein per Hari | Numerik | Jumlah minuman berkafein per hari |
| 18 | `Alcohol_Frequency` | Konsumsi Alkohol | Kategorikal | Frekuensi minum alkohol (Never, Rarely, Weekly, dll) |
| 19 | `Smoking` | Kebiasaan Merokok | Kategorikal | Status merokok (Never, Former, Current) |
| 20 | `Screen_Time_Hours_Day` | Waktu Layar per Hari | Numerik | Jumlah jam menatap layar di luar jam kerja |
| 21 | `Social_Media_Hours_Day` | Waktu Medsos per Hari | Numerik | Jumlah jam menggunakan media sosial per hari |
| 22 | `Hobby_Time_Hours_Week` | Waktu Hobi per Minggu | Numerik | Jam yang dihabiskan untuk hobi per minggu |
| 23 | `Diet_Quality` | Kualitas Diet | Kategorikal | Kualitas pola makan (Poor, Average, Good, Excellent) |
| 24 | `Financial_Stress` | Stres Finansial | Numerik | Skala tingkat stres terkait masalah keuangan |

---

## 4. Symptoms & Emotional State (Gejala & Emosi - 30 Hari Terakhir)

| No | Nama Kolom | Terjemahan | Tipe | Keterangan |
|----|-----------|------------|------|------------|
| 25 | `Feeling_Sad_Down` | Merasa Sedih / Murung | Numerik | Skala intensitas perasaan sedih atau murung |
| 26 | `Loss_Of_Interest` | Kehilangan Minat | Numerik | Skala tingkat kehilangan minat pada berbagai hal |
| 27 | `Sleep_Trouble` | Masalah Tidur | Numerik | Skala kesulitan tidur |
| 28 | `Fatigue` | Kelelahan | Numerik | Skala rasa lelah fisik atau mental |
| 29 | `Poor_Appetite_Or_Overeating`| Perubahan Nafsu Makan | Numerik | Skala perubahan nafsu makan (menurun/makan berlebih) |
| 30 | `Feeling_Worthless` | Merasa Tidak Berharga | Numerik | Skala intensitas perasaan merasa tidak berguna |
| 31 | `Concentration_Difficulty` | Kesulitan Berkonsentrasi | Numerik | Skala tingkat kesulitan fokus |
| 32 | `Anxious_Nervous` | Cemas / Gugup | Numerik | Skala perasaan cemas atau gugup |
| 33 | `Panic_Attacks` | Serangan Panik | Numerik | Intensitas frekuensi serangan panik |
| 34 | `Mood_Swings` | Perubahan Suasana Hati | Numerik | Skala perubahan emosi yang tidak menentu (mood swings) |
| 35 | `Irritability` | Iritabilitas | Numerik | Skala tingkat mudah marah atau kesal |
| 36 | `Obsessive_Thoughts` | Pikiran Obsesif | Numerik | Skala frekuensi pemikiran obsesif |
| 37 | `Compulsive_Behavior` | Perilaku Kompulsif | Numerik | Skala dorongan perilaku kompulsif |
| 38 | `Self_Harm_Thoughts` | Pemikiran Menyakiti Diri | Kategorikal | Indikasi adanya pemikiran menyakiti diri sendiri (0=Tidak, 1=Ya) |
| 39 | `Suicidal_Thoughts` | Pemikiran Bunuh Diri | Kategorikal | Indikasi adanya pemikiran bunuh diri (0=Tidak, 1=Ya) |

---

## 5. History & Background (Riwayat & Latar Belakang)

| No | Nama Kolom | Terjemahan | Tipe | Keterangan |
|----|-----------|------------|------|------------|
| 40 | `Family_History_Mental_Illness` | Riwayat Penyakit Keluarga | Kategorikal | Adanya riwayat penyakit mental dalam keluarga (0=Tidak, 1=Ya) |
| 41 | `Previously_Diagnosed` | Diagnosis Sebelumnya | Kategorikal | Apakah pernah didiagnosis penyakit mental (0=Tidak, 1=Ya) |
| 42 | `Ever_Sought_Treatment` | Mencari Perawatan | Kategorikal | Pernah mencari perawatan untuk kesehatan mental (0=Tidak, 1=Ya) |
| 43 | `On_Therapy_Now` | Sedang Terapi | Kategorikal | Sedang menjalani terapi saat ini (0=Tidak, 1=Ya) |
| 44 | `On_Medication` | Dalam Pengobatan | Kategorikal | Sedang mengonsumsi obat psikiatri (0=Tidak, 1=Ya) |
| 45 | `Trauma_History` | Riwayat Trauma | Kategorikal | Adanya kejadian traumatis di masa lalu (0=Tidak, 1=Ya) |

---

## 6. Social Support (Dukungan Sosial)

| No | Nama Kolom | Terjemahan | Tipe | Keterangan |
|----|-----------|------------|------|------------|
| 46 | `Social_Support` | Tingkat Dukungan Sosial | Numerik | Skala persepsi atas dukungan sosial yang diterima |
| 47 | `Close_Friends_Count` | Jumlah Teman Dekat | Numerik | Banyaknya teman dekat yang dimiliki |
| 48 | `Feel_Understood` | Merasa Dipahami | Numerik | Skala perasaan dimengerti oleh orang lain |
| 49 | `Loneliness` | Kesepian | Numerik | Skala tingkat rasa kesepian |
| 50 | `Discuss_Mental_Health` | Diskusi Kesehatan Mental | Kategorikal | Tingkat kenyamanan mendiskusikan kesehatan mental |

---

## LABEL / TARGET KLASIFIKASI

| No | Nama Kolom | Terjemahan | Tipe | Nilai |
|----|-----------|------------|------|-------|
| **51** | **`Has_Mental_Health_Issue`** | **Indikasi Masalah Kesehatan Mental** | **Kategorikal** | **`1`** = Kemungkinan besar ada masalah kesehatan mental, **`0`** = Tidak ada masalah signifikan |

> [!IMPORTANT]
> **`Has_Mental_Health_Issue` adalah LABEL (target) untuk klasifikasi.** > Target ini dihasilkan menggunakan model risiko probabilistik (*probabilistic risk model*) yang menggabungkan:
> 1. Tingkat keparahan gejala (*Symptom severity*)
> 2. Indikator risiko psikologis (*Psychological risk indicators*)
> 3. Stresor gaya hidup dan sosial (*Lifestyle and social stressors*)

---

## 📈 Use Cases (Kasus Penggunaan)

Dataset ini dapat digunakan untuk berbagai keperluan analitik dan akademis, antara lain:
- **Supervised ML:** Klasifikasi masalah kesehatan mental dan penanganan ketidakseimbangan data (*imbalance handling*).
- **Feature Importance & Explainability:** Memahami fitur mana yang paling memengaruhi klasifikasi.
- **Mental Health Risk Modeling:** Membangun pemodelan risiko untuk deteksi dini.
- **Synthetic Data Experimentation:** Melakukan pengujian eksperimental pada data sintetis.
- **Educational and Academic Projects:** Sempurna untuk bahan ajar, tugas kuliah, dan proyek akhir mahasiswa.

---

## ⚠️ Ethical Disclaimer (Peringatan Etika)

> [!WARNING]
> - Dataset ini **sepenuhnya sintetis** (*fully synthetic*).
> - **Tidak ada individu nyata** yang direpresentasikan dalam dataset ini.
> - **Dilarang keras** menggunakan dataset ini untuk evaluasi klinis yang sesungguhnya atau tujuan diagnostik nyata. Dataset ini hanya bertujuan untuk eksperimen edukasi dan pemodelan ML semata.

---

## 📁 File Information (Informasi File)

- **Rows (Jumlah Baris):** 10.000
- **Features (Jumlah Kolom):** 51
- **Format:** CSV
- **Missing values:** None (Tidak ada data kosong)
