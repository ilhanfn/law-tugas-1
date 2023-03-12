# Expense Tracker Web Services
Web services ini memberikan layanan berupa pencatatan pengeluaran keuangan sehingga pengguna tidak perlu khawatir akan adanya pengeluaran yang tidak diketahui.

Berikut list parameter API dengan membuat request HTTP ke endpoints berikut:

- GET /expenses/ - me-list semua pengeluaran
- POST /expenses/ - membuat pengeluaran baru
- GET /expenses/{id}/ - mengambil pengeluaran dengan id tertentu
- PUT /expenses/{id}/ - perbarui pengeluaran dentan id tertentu
- DELETE /expenses/{id}/ - hapus pengeluaran dengan id tertentu

Untuk tingkat kesulitan dari membuat web services dari expense tracker kali ini sepertinya berada pada kategori menengah keatas.

Keunikan dari service yang dibuat ini adalah dengan melakukan tracking pengeluaran yang dimana hal ini tentu memiliki tingkat urgensi sesuai dengan kemampuan finansial setiap masing-masing pengguna. Ada yang memang membuatuhkan tracker ini dan ada pula yang hanya sekadar memastikan pengeluaran keuangannya tidak berlebihan tanpa adanya dokumentasi atau bukti pencatatan historis secara jelas.
