TWGM (Term Weighting based on Graph Model)

Deskripsi

Proyek ini mengimplementasikan model pembobotan kata berbasis graf untuk meningkatkan representasi fitur pada tugas klasifikasi teks. Pendekatan ini membangun graf kata dari dokumen, di mana setiap kata direpresentasikan sebagai node dan hubungan antarkata direpresentasikan sebagai edge berdasarkan kemunculan bersama (co-occurrence).

Model memanfaatkan informasi struktural graf melalui berbagai ukuran centrality dan pembobotan, seperti Degree, Strength, PageRank, RB-node, RB-strength, serta variasi model lainnya untuk menghasilkan bobot kata yang lebih informatif.

Alur Proses
1. Memuat dataset teks.
2. Melakukan preprocessing teks.
3. Membangun graf kata berdasarkan hubungan co-occurrence.
4. Menghitung bobot node dan edge.
5. Menghitung nilai centrality:
    * Degree
    * Strength
    * PageRank
6. Menghasilkan bobot kata berbasis graf.
7. Melakukan ekstraksi fitur teks.
8. Menerapkan model klasifikasi.
9. Mengevaluasi hasil menggunakan metrik performa.

Catatan: Untuk dataset Twitter dapat diperoleh dari penelitian sebelumnya (B. Zhou, et al.)

Referensi Dataset:

[1] H. Abdelmotaleb, C. Mcneile, and M. Wojtyś, “A comparative study of word embedding techniques for classification of star ratings,” Expert Systems with Applications, vol. 297, p. 129037, Feb. 2026, doi: 10.1016/j.eswa.2025.129037.

[2] T. Sabri, S. Bahassine, O. E. Beggar, and M. Kissi, “Improving the Efficiency of Arabic Text Classification with New Term Weighting Scheme.” Elsevier BV, 2025. doi: 10.2139/ssrn.5135639.

[3] B. Zhou et al., “VictimFinder: Harvesting rescue requests in disaster response from social media with BERT,” Computers, Environment and Urban Systems, vol. 95, p. 101824, Jul. 2022, doi: 10.1016/j.compenvurbsys.2022.101824.

