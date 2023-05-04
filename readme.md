{
  "name": "John Doe",
  "email": "johndoe@example.com",
  "password": "password123"
}

Book Endpoints
GET /books: Menampilkan seluruh buku.
GET /books/:id: Menampilkan detail buku dengan ID tertentu.
POST /books: Menambahkan buku baru.
PUT /books/:id: Mengubah data buku dengan ID tertentu.
DELETE /books/:id: Menghapus buku dengan ID tertentu.

User Endpoints
POST /register: Mendaftarkan akun baru.
POST /login: Melakukan proses login dan menghasilkan token JWT.

Yang belum. 
GET /users: Menampilkan seluruh data user.
GET /users/:id: Menampilkan data user dengan ID tertentu.
PUT /users/:id: Mengubah data user dengan ID tertentu.
DELETE /users/:id: Menghapus user dengan ID tertentu.

Untuk mengakses semua endpoint API pada tabel Book, kecuali endpoint GET /books, harus menggunakan token JWT pada header request. Sedangkan untuk mengakses endpoint pada tabel Users, harus menggunakan token JWT pada header request dengan role superadmin.

Pastikan Anda telah melakukan registrasi atau login terlebih dahulu untuk mendapatkan token JWT yang akan digunakan pada request.