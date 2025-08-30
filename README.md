**Sentiment Analysis of Amazon Product Reviews**

**🔎 Overview:**
Proyek ini menganalisis sentimen pelanggan dari review produk Amazon menggunakan IBM Granite AI.

**📊 Dataset:** 
Amazon Customer Reviews with Sentiment
Link : https://www.kaggle.com/datasets/thedevastator/amazon-customer-reviews-with-2013-2019-sentiment

**👉 Insight & Findings:** 
1. **Distribusi Sentimen (50 Sampel)**
   Dari 50 review yang dianalisis dan diklasifikasikan menggunakan IBM Granitte AI, didapatkan:
   29 review positif
   19 review negatif
   2 review netral
   → Artinya mayoritas review condong ke sentimen positif, menunjukkan produk cukup diterima baik.
2. **Distribusi Sentimen per Kategori Produk**
   Semua kategori produk (books, mobile, mobile accessories, refrigerator, smartTV) memiliki dominasi review positif.
   Kategori mobile dan mobile accessories memiliki jumlah review terbanyak, memperlihatkan tingginya perhatian konsumen di kategori ini.
3. **Word Cloud Review**
   Review Positif: kata dominan seperti good, nice, great, excellent, awesome, superb, best. Hal ini menunjukkan konsumen cenderung menekankan kualitas positif, khususnya
   pada camera, battery, dan performance.
   Review Negatif: kata dominan seperti issues, battery, noise, problem, video, failed. Mayoritas keluhan berkaitan dengan daya tahan baterai, performa video, serta masalah
   teknis lain.
4. **Panjang Review**
   Review negatif cenderung lebih panjang dibandingkan positif maupun netral. Ini menunjukkan konsumen yang tidak puas lebih detail dalam menjelaskan masalah.
   Korelasi Rating dengan Sentimen
   Review dengan sentimen positif umumnya memiliki rating bintang 3–5.
   Review negatif cenderung berada pada rating bintang 1–2.
   Review netral sering muncul di rating 3–5.
   → Hal ini menunjukkan konsistensi antara hasil klasifikasi AI dengan penilaian rating bintang asli.
Dengan insight ini, dapat ditarik kesimpulan bahwa:
- Produk mobile dan aksesoris adalah fokus utama konsumen.
- Battery & video performance adalah masalah utama yang sering dikeluhkan.
- Rating konsumen selaras dengan sentimen AI, sehingga klasifikasi cukup akurat untuk analisis perilaku pelanggan.

**🤖 AI Support Explanation**
Dalam project ini, digunakan IBM Granite AI sebagai model NLP untuk melakukan klasifikasi otomatis review konsumen. Model Granite membaca teks review dan mengelompokkannya ke dalam tiga kategori: Positif, Netral, dan Negatif. Penggunaan AI Granite memberikan keunggulan:
- Otomatisasi → ribuan review dapat dianalisis tanpa harus dibaca manual.
- Konsistensi → klasifikasi dilakukan dengan standar yang sama pada semua data.
- Efisiensi Waktu → mempercepat proses analisis sentimen dalam jumlah data besar.
- Integrasi Mudah → Granite diakses melalui API Replicate, sehingga dapat dijalankan langsung di Google Colab bersama data CSV.
Hasil klasifikasi AI kemudian digabung dengan analisis statistik sederhana (visualisasi distribusi, word cloud, perbandingan rating) untuk menghasilkan insight yang lebih komprehensif.
