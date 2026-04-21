```
Nama    : Nisrina Alya Nabilah
Kelas   : Advanced Programming B
NPM     : 2406425924
```

# Tutorial Module 6 - Concurrency


## Commit 1 Reflection Notes

Pada milestone ini, saya mempelajari cara kerja `handle_connection`.
Method ini menerima `TcpStream` yang merupakan koneksi dari browser.
`BufReader` digunakan untuk membaca stream secara efisien baris per baris.
HTTP request diakhiri dengan baris kosong, sehingga `.take_while(|line| !line.is_empty())`
digunakan untuk mengumpulkan semua header. Hasilnya adalah Vec<String> berisi
semua header HTTP yang dikirim browser seperti method (GET), path, dan metadata lainnya.

## Commit 2 Screen Capture

![Commit 2 screen capture](assets\images\commit2.png)