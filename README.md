
## Moonlay Academy - Backend Test (GOLANG)

Anda akan membuat backend handler untuk aplikasi **Todo List**.
>**Todo List App**
Aplikasi yang umumnya digunakan untuk memelihara tugas sehari-hari atau membuat daftar semua yang harus dilakukan, dengan urutan prioritas tugas tertinggi hingga terendah. Sangat membantu dalam merencanakan jadwal harian.

### Spesifikasi Bisnis:
```
- Menampilkan, menambahkan, mengubah dan menghapus data.
- Dapat menambahkan sub list untuk setiap list yang terdaftar. Sub list bisa ditambah, diubah dan dihapus. ( hanya 2 level )

Data Input untuk masing-masing list/sub list :
- Title [required | maximum 100 karakter | alphanumeric]
- Deskripsi [required | maximum 1000 karakter]
- File Upload [optional | hanya menerima file dengan extension .txt dan .pdf]
```
Buat API Todo List dengan kriteria sebagai berikut :
1. Menampilkan data list tanpa sub list ( dengan dan tanpa pagination ).
2. Menampilkan data list beserta dengan sub list nya jika ada.
3. Menampilkan data sub list by list id.
4. Menambahkan data list.
5. Menambahkan data sub list untuk spesifik list.
6. Mengubah data list/sub list dengan kritera input diatas.
7. Menghapus data list/sub list.

>Jumlah API yang dibutuhkan untuk mengakomodir fitur ini tidak dibatasi, silahkan buat se-efisien mungkin.

### Teknologi dan library yang wajib digunakan:
| Teknologi   | Version | Link |
| ----------- | ---------------- | ------------------- |
| Golang      | v1.18 or later   | [Go Download](https://go.dev/dl)  |
| Go Echo Framework     | v4     | [Echo Installation](https://echo.labstack.com/guide/#installation) | 
| GORM | v2 | [GORM Installation](https://gorm.io/docs/#Install) |
| PostgreSQL | v13 or later | [PostgreSQL Download](https://www.postgresql.org/download/) |
<br>
```
Catatan :
Gunakan `SOLID` Principle
Reference :
- https://dave.cheney.net/2016/08/20/solid-go-design
- https://s8sg.medium.com/solid-principle-in-go-e1a624290346
```
Aplikasi ini adalah aplikasi berskala besar yang memiliki potensi perubahan atau penambahan fitur secara berkala sehingga membuat aplikasi ini akan menjadi lebih kompleks dan memerlukan lebih dari 1 developer dalam pengerjaannya (kolaborasi team).

**Code quality di aplikasi ini harus reusable, readable dan easy to upgrade.**

Sangat baik jika ada :
1. Migration Database ( database version control )
2. Design file handler dan database handler agar saat nantinya ingin mengganti db ke MongoDB misalnya, cukup menambahkan atau mengubah env config dan menambahkan file untuk handling mongodb connection and queries tanpa harus mengubah code di controller/business layer.
Hal yang serupa untuk file handler, asumsikan file yg diupload sekarang disimpan di local system dan nantinya akan di upgrade untuk disimpan di cloud storage.
*Good luck and Have Fun.* :rocket: