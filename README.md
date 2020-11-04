# Exploratory Data Analysis of Bank
Berikut ini merupakan hasil Exploratory Data Analysis oleh Brian Ivan Cusuanto mengenai data nasabah yang pindah dan tidak.
## Problems:
  1. Apa alasan nasabah ingin berhenti menabung di bank yang bersangkutan?
  2. Apakah **kepemilikan CC** mempengaruhi pemberhentian rekening?
  3. Apa pengaruh **CreditScore** terhadap pemberhentian rekening?
  3. Apakah **Tenure** mempengaruhi terhadap pemberhentian rekening?
  5. Apakah **NumOfProducts** mempengaruhi terhadap pemberhentian rekening?

## Goals:
  1. Menilai pelayanan bank dari loyalitas nasabah.
  2. Menemukan alasan nasabah yang keluar ke bank lain.
  
## Kesimpulan
1. Kepemilikan kartu kredit tidak mempengaruhi nasabah berpindah dari bank.
    - Sebanyak 80% nasabah yang memiliki kartu kredit adalah nasabah yang tidak pindah
    - 79% nasabah yang memiliki kartu kredit, tidak meninggalkan bank
2. Durasi tenor pinjaman dari bank ke nasabah tidak mempengaruhi nasabah untuk pindah ke bank lain. Baik durasinya dalam bulanan maupun 10 tahun, persentase nasabah yang tidak pindah tetap jauh lebih besar daripada nasabah yang pindah.
3. Usia nasabah sangat tidak mempengaruhi nasabah berpindah dari bank.
4. Aktif atau tidaknya seorang nasabah tidak mempengaruhi pindahnya nasabah.
    - Sebanyak 73% nasabah yang tidak aktif terbukti tidak pindah
    - Sebanyak 85% nasabah yang aktif pun terbukti tidak pindah
4. Credit Score mempengaruhi nasabah untuk berpindah ke bank lain
    - credit score mulai dengan 475 ke bawah (nilai 300an) cenderung berhenti dan pindah dari bank ini
    - nasabah dengan credit score tinggi (di atas 470) cenderung tidak meninggalkan dan pindah dari bank ini.
    - hanya nasabah dengan credit score 475 dan 839
    - nasabah dengan credit score rendah (di bawah 470) memiliki kecenderungan untuk berpindah dari bank ini
    - Dilansir dari [The Balance](https://www.thebalance.com/side-effects-of-bad-credit-960383) bahwa credit score yang rendah membuat orang tidak memiliki kesempatan untuk mendapatkan fasilitas publik lainnya seperti pinjaman dalam jumlah besar.
5. Jumlah Produk yang dimiliki oleh nasabah mempengaruhi nasabah untuk pindah.
    - Nasabah yang hanya memiliki paling banyak 2 produk bank, cenderung tinggal tetap
    - Malahan nasabah yang memiliki banyak produk cenderung pindah bank
    - sebanyak 83% nasabah yang memiliki 3 produk bank malah pindah
    - dan seluruh nasabah yang memiliki 4 produk bank sudah pasti pindah
  
## Saran dan Rekomendasi
1. Pelayanan bank ini sudah baik. Terbukti dari kepemilikan kartu kredit, pinjaman yang diberikan nasabah, usia, dan aktif atau tidaknya nasabah; tidak mempengaruhi nasabah untuk berpindah dari bank ini.
2. Nasabah yang pindah ke bank lain merupakan nasabah yang memiliki nasabah yang memang credit score-nya rendah, yang berarti memang belum layak diberikan layanan atau fasilitas lebih untuk nasabah. Bagaimana nasabah bisa diberikan layanan yang lebih jika tanggung jawab pinjaman saja masih rendah. Jadi, itu hal yang normal jika nasabah berpindah.
3. Nasabah yang pindah ke bank lain merupakan nasabah yang memiliki banyak jumlah produk yang ditawari pihak bank. Bisa dikatakan bahwa nasabah tersebut hanya ingin sekedar tahu layanan dan fasilitas yang bank punya, dan kemudian nasabah cenderung meninjau ulang dan membandingkan dengan bank lain, produk bank manakah yang tepat untuknya. Ibarat zaman sekarang, nasabah tersebut hanya sekedar *reviewer* yang tidak serius untuk loyal namun hanya serius untuk mencari tahu keunggulan dan kekurangn dari masing-masing bank.
4. Pihak Bank sudah baik, karena dari keseluruhan faktor nasabah yang pindah ke bank lain tidaklah signifikan dan tidak prinsip seperti tanggung jawab credit yang rendah atau sekedar memiliki produk bank yang banyak variasinya.
