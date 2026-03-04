# toko
JOIN dalam SQL digunakan untuk menggabungkan data dari dua tabel yang memiliki hubungan, seperti tabel pelanggan dan pesanan yang terhubung melalui kolom id_pelanggan. INNER JOIN digunakan untuk menampilkan hanya data yang memiliki kecocokan di kedua tabel. Artinya, hanya pelanggan yang memiliki pesanan produk seperti Laptop, Smartphone, atau Headset yang akan ditampilkan dalam hasil query.

LEFT JOIN digunakan untuk menampilkan seluruh data dari tabel pelanggan, meskipun pelanggan tersebut belum melakukan pesanan. Jika pelanggan tidak memiliki pesanan, maka kolom produk akan bernilai NULL. Sedangkan RIGHT JOIN menampilkan seluruh data dari tabel pesanan, meskipun data pelanggan tidak ditemukan. Jika tidak ada data pelanggan yang sesuai, maka kolom nama pelanggan akan bernilai NULL. Dengan demikian, pemilihan jenis JOIN bergantung pada kebutuhan data yang ingin ditampilkan dalam sistem.
berikut code code dari berbagai join tersebut:

<img width="1276" height="472" alt="image" src="https://github.com/user-attachments/assets/e0ee74e5-3da0-40f9-89bf-279df27804c1" />

<img width="1272" height="512" alt="image" src="https://github.com/user-attachments/assets/3b84095b-e4c4-481b-9558-929e981edb4f" />

<img width="1312" height="468" alt="image" src="https://github.com/user-attachments/assets/e0f61280-712f-4a68-8938-3033db19714b" />

Berdasarkan penjelasan di atas, dapat disimpulkan bahwa JOIN dalam SQL sangat penting untuk menghubungkan data antar tabel yang memiliki relasi, seperti tabel pelanggan dan pesanan. INNER JOIN digunakan ketika hanya ingin menampilkan data yang saling berhubungan di kedua tabel, LEFT JOIN digunakan untuk menampilkan seluruh data pelanggan meskipun belum memiliki pesanan, sedangkan RIGHT JOIN digunakan untuk menampilkan seluruh data pesanan meskipun data pelanggan tidak tersedia. Pemilihan jenis JOIN harus disesuaikan dengan kebutuhan laporan atau sistem yang sedang dikembangkan.
