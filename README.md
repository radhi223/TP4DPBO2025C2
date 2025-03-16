# LP5DPBO2025C2

# Design Program
![image](https://github.com/user-attachments/assets/b1e1a7a0-f807-4e7d-8999-28be0e9fc510)
Penjelasan Design : Menu menjadi inti dari program ini, dan segala proses dijalankan disini. Menu merupakan turunan dari JFrame, dan Menu memiliki banyak hubungan composite dengan Kelas komponen UI lainnya untuk dapat membentuk UI yang dapat ditunjukkan kepada User.
Hubungan composite tunggal dengan Menu : JPanel dan JTable;
Hubungan composite multiple dengan Menu : Mahasiswa, JTextField, JButton, JComboBox, dan JLabel.

# Penjelasan Alur
Pada program ini, user dapat melihat tabel daftar mahasiswa dan dapat menambahkan, mengubah, dan menghapus data mahasiswa pada tabel. Jika ada mahasiswa yang dipilih, maka kolom-kolom diatas akan terisi oleh data mahasiswa yang dipilih dan tombol add akan menjadi update. Kolom kolom nya berupa NIM, Nama, Jenis Kelamin, dan Status Mahasiswa(Aktif/Dropout/Alumni menggunakan comboBox). 
User dapat mengganti data dan menekan update button untuk mengubah data mahasiswa, user juga dapat menekan cancel untuk unselect mahasiswa dan menekan delete button serta konfirmasi untuk menghapus data mahasiswa. Setelah proses apapun dilaksanakan, kolom-kolom akan kembali kosong dan tabel akan berubah untuk aksi selain cancel. Konfirmasi pada delete button berupa pop up window dengan kalimat ("Hapus Data?") dan pilihan antara yes or no. Jika yes, maka data mahasiswa yang terpilih akan terhapus, sedangkan jika no maka tidak ada perubahan.

# Dokumentasi
https://github.com/user-attachments/assets/c6af8ef9-244f-4967-872e-70df08147c61

