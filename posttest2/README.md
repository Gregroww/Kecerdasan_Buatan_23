<h1>Kesimpulan dari hasil analisis dan visualisasi data </h1>
1. Dataset books ini memiliki Total Buku sebanyak 11125 ,Total Publisher 2291 ,dan Total Author 6642.<br />

2. Hasil perhitungan deskriptif menunjukkan bahwa distribusi average_rating cenderung tinggi dengan rata-rata berada di kisaran 3–4, yang berarti mayoritas buku memperoleh penilaian baik. Atribut ratings_count dan text_reviews_count memiliki standar deviasi besar dengan nilai maksimum jauh di atas median.<br />
<img width="726" height="248" alt="Screenshot 2025-09-27 105622" src="https://github.com/user-attachments/assets/98fe91db-3949-40d4-bda6-c10d1d690c65" /> <br />

3. Atribut object dalam dataset seperti title, authors, publisher, language_code, isbn, dan publication_date memiliki variasi label yang berbeda-beda. title hampir selalu unik, authors dan publisher mencatat ribuan variasi, sementara language_code hanya puluhan label dengan dominasi bahasa Inggris. ISBN juga unik per buku, sedangkan publication_date memiliki keragaman tahun terbit yang luas.<br />
<img width="387" height="346" alt="image" src="https://github.com/user-attachments/assets/4cfad45b-c98d-4efa-aad6-597c9781e968" /> <br />

4. Visualisasi histrogram dari average rating buku menunjukan banyak buku dengan rating 4 ,dan terlihat perbandingan buku dengan rating dibawah 4 lebih banyak ketimbang buku diatas rating 4.> <br />
<img width="698" height="467" alt="Screenshot 2025-09-27 111659" src="https://github.com/user-attachments/assets/173e4e9f-544b-49b9-abcd-a53df12789df" />> <br />

5. Visualisasi line plot dari publication_date menunjukkan tren jumlah buku yang diterbitkan per tahun semakin meningkat pada era modern, menandakan perkembangan signifikan dalam industri penerbitan.<br />
<img width="905" height="488" alt="image" src="https://github.com/user-attachments/assets/2468b0c1-3b38-4787-9b76-7b8a4e1e0bcb" /> <br />

6. Histogram dari num_pages menegaskan bahwa mayoritas buku memiliki jumlah halaman di bawah 500, dengan sedikit outlier berupa buku sangat tebal.<br />
<img width="699" height="467" alt="image" src="https://github.com/user-attachments/assets/ed42e131-2d8d-49b5-b9f7-a3ce3fdc8a6f" /><br />

7. Pie Chart dari language_code menunjukkan dominasi besar bahasa Inggris dibanding bahasa lain, mencerminkan bias dataset terhadap literatur berbahasa Inggris.<br />
<img width="556" height="562" alt="image" src="https://github.com/user-attachments/assets/2439260b-3ac2-433a-9bd5-ba82fd360891" /><br />

8. Heatmap korelasi memperlihatkan hubungan yang sangat kuat antara ratings_count dan text_reviews_count, yang logis karena semakin banyak orang memberi rating, semakin banyak pula yang menulis review. Sementara itu, average_rating memiliki korelasi lemah dengan jumlah halaman maupun popularitas, sehingga kualitas buku berdasarkan rating tidak dipengaruhi oleh panjang buku atau banyaknya ulasan. Secara keseluruhan, heatmap membantu mengonfirmasi relasi antar variabel penting dalam dataset. <br />
<img width="872" height="641" alt="image" src="https://github.com/user-attachments/assets/7f25793a-cb58-48db-9cb7-09e0ef5da6c7" /> <br />
