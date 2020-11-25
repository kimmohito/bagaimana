Repo ini ditujukan khas bagi mereka yang mempunyai minat dalam bidang pengaturcaraan dalam bahasa melayu.

## Asas Laman Web
*Website* atau lebih dikenali sebagai laman sesawang. Merupakan *landing page* yang mempunyai *domain name server* ([*DNS*](#domain)) dan diterbitkan di sekurang-kurangnya satu [*web server*](#web-server). Contoh yang terkenal adalah seperti: `google.com`, `twitter.com`, `github.com`.

Semua laman web yang boleh diakses secara terbuka merupakan *Word Wide Web* (*www*). Terdapat juga laman web peribadi yang hanya dapat diakses di rangkaian peribadi seperti laman web dalaman syarikat, ataupun laman web yang menggunakan servis [Apache](xampp#apache) melalui pemasangan [XAMPP](xampp) dalam komputer atau laptop anda.

Laman web biasanya dikhaskan untuk topik atau tujuan tertentu, seperti berita, pendidikan, perdagangan, hiburan atau jaringan sosial. Pautan antara laman web yang digunakan sering dimulakan dengan halaman utama.

Pengguna dapat mengakses laman web menggunakan pelbagai peranti termasuk komputer, laptop, tablet dan telefon pintar. Aplikasi perisian yang digunakan dipanggil penyemak-imbas web ([*web browser*](#web-browser)).

Untuk pengaturcaraan laman web, anda boleh menggunakan [*text-editor*](#text-editor) seperti Notepad yang sedia ada dalam *OS Windows*, ataupun aplikasi lain seperti Notepad++, Visual Studio Code, Atom, Sublime, Vim, Nano, Bracket, dan sebagainya. Kenapa tidak menggunakan WordPress ataupun Wix? WordPress bukanlah *text-editor*, ia adalah laman web yang memberikan kemudahan kepada pengguna untuk proses pembanggunan laman web secara *Graphical User Interface* ([GUI](gui)) tanpa perlu mengetahui ilmu pengaturcaraan. Pengguna hanya perlu *drag & drop* untuk menyiapkan sebuah laman web.

## Domain
Seperti yang sedia maklmum, *domain* adalah nama laman web yang ditulis pada *address bar*, anda juga boleh menulis ip-address laman web tersebut. Fungsi DNS adalah sama seperti ip-address. Cuma, untuk manusia. Perkataan seperti `google.com` lebih mudah dihafal berbanding `172.217.174.174`.

```
https://www.example.com.my/user/index.html?id=123&name=kim
```
| Bahagian | Nama | Penjelasan |
| - | - | - |
| https:// | Protocol | Protokol komunikasi adalah sistem peraturan yang membolehkan dua atau lebih entiti sistem komunikasi menghantar maklumat melalui jenis variasi kuantiti fizikal. Untuk penjelasan lanjut mengenai HTTP, boleh baca di bahagian [HTTP vs HTTPS](##http-vs-https) |
| www. | Sub Domain | Dalam hierarki Sistem Nama Domain, subdomain merupakan pecahan domain dibawah domain utama. |
| example | Domain Name Server (DNS) | Nama domain digunakan dalam pelbagai konteks rangkaian dan untuk tujuan penamaan dan alamat khusus aplikasi. |
| .com | Top-level Domain (TLD) | Sesiapa sahaja boleh daftar untuk TLD `.com-commercial` ini. Manakala TLD yang terkawal seperti `.org-organization`, `.edu-education`, `.gov-goverment` hanya boleh didaftarkan oleh pertubuhan rasmi sahaja. |
| .my | Country Code Top-level Domain (ccTLD) |ccTLD dikhususkan untuk negara, semua ccTLD terdiri daripada 2 huruf sahaja. Berikut merupakan senarai ringkas:<br> `.my` - malaysia<br>`.id` - indonesia <br>`.jp` - jepun<br>`.ru` - rusia<br> *Untuk mempunyai TLD `.my`, pemilik domain perlu mempunyai SSM terlebih dahulu. |
| /user/ | path folder | Sekiranya folder tidak wujud, laman web akan menunjukkan laman `error 404 not found` menandakan path atau file tidak wujud. |
| index.html | file | Semua laman web menggunakan `index` sebagai halaman utama mereka. boleh jadi:<br>`.html`<br>`.php`<br>`.js`<br>`.aspx`  |
| ?id=123&name=kim | query parameter | Dimulakan dengan simbol `?` dan dipisahkan dengan simbol `&`, disini kita dapat lihat terdapat dua query yang telah ditulis iaitu:<br>`id=47`<br>`name=kim` |


## HTTP vs HTTPS
Hypertext Transfer Protocol (HTTP) adalah protokol lapisan aplikasi untuk menghantar dokumen hipermedia, seperti HTML. Ia dirancang untuk komunikasi antara pelayar web dan pelayan web, tetapi juga dapat digunakan untuk tujuan lain.
Manakala HTTPS pula adalah Hypertext Transfer Protocol Secure, fungsinya sama seperti HTTP cuma ditambahkan *ecnryption*. Supaya penggodam tidak dapat memahami komunikasi antara client dan server.
<img src="hacker.jpg">






## Web Server




## Web Browser



## Text Editor