# toko
JOIN dalam SQL digunakan untuk menggabungkan data dari dua tabel yang memiliki hubungan, seperti tabel pelanggan dan pesanan yang terhubung melalui kolom id_pelanggan. INNER JOIN digunakan untuk menampilkan hanya data yang memiliki kecocokan di kedua tabel. Artinya, hanya pelanggan yang memiliki pesanan produk seperti Laptop, Smartphone, atau Headset yang akan ditampilkan dalam hasil query.

LEFT JOIN digunakan untuk menampilkan seluruh data dari tabel pelanggan, meskipun pelanggan tersebut belum melakukan pesanan. Jika pelanggan tidak memiliki pesanan, maka kolom produk akan bernilai NULL. Sedangkan RIGHT JOIN menampilkan seluruh data dari tabel pesanan, meskipun data pelanggan tidak ditemukan. Jika tidak ada data pelanggan yang sesuai, maka kolom nama pelanggan akan bernilai NULL. Dengan demikian, pemilihan jenis JOIN bergantung pada kebutuhan data yang ingin ditampilkan dalam sistem.
berikut code code dari berbagai join tersebut:
