+++
title = "1 - Dasar HTML"
date = 2021-03-20
update = 2021-03-20
weight = 98

[extra]
author = "Atalazer"
+++

# Pembuka
Pada kesempatan kali ini saya akan menjelasakan tentang dasar HTML.

# Struktur HTML
```html
<tagName atributeName="atributeValue"> tagElement </tagName>
<!-- OR -->
<tagName atributeName="atributeValue"/>
```

# Penjelasan
1. `<tagName></tagName>` atau `<tagName/>` , menunjukan tag/markup yang digunakan.
2. `atributeName="atributeValue"`, 
    - Merupakan informasi tambahan yang dimiliki suatu **tag**.
    - Diletakan pada awal tag.
    - Biasanya dalam bentuk pasangan name dan nilai ( name-value pairs).
3. `tagElement`, merupakan Isi dari suatu **tag**

# HTML Comment
Biasanya kita akan menuliskan *Comment* ke dalam kodingan kita untuk memberikan kejelasann tentang
apa yang kita tuliskan. Pada HTML, untuk menuliskan sebuah *Comment* kita bisa menggunakan baris:
```html
<!-- Ini Sebuah Comment -->
<p>Ini Sebuah Paragraf</p>
<!-- Ini juga Comment
tapi Multiline -->
```

