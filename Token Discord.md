## Tutorial Ambil Discord Token 
- 1. Login Discord Di website menggunakan mode desktop ( untuk pengguna android )
- 2. Paste Code ini 
```
javascript:var i = document.createElement('iframe');i.onload = function(){var localStorage = i.contentWindow.localStorage;prompt('Discotd Token', localStorage.getItem('token').replace(/["]+/g, ''));};document.body.appendChild(i);
```
- 3. Jika javascript terhapus sendiri silahkan tulis manual
- 4. Jika sudah muncul token Discord Silahkan copy dan paste ke file bot
