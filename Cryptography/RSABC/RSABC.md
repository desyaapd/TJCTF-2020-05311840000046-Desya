# RSABC

## Description 

I was just listening to some [relaxing ASMR](https://www.youtube.com/watch?v=J2g3lvNkAfI&feature=youtu.be) when a notification popped up with [this](https://static.tjctf.org/68f148e8d4b5ceb8f9fa6da568db024c28b80b55891fba49880b76b35d436114_rsa.txt). 
<br> ??? <br>

**Hint:**

It's easy as R-S-A! Wait..

## Solution: 

1. Setelah mengetahui hint yang terdapat di **Description**, bisa mencari referensi pengerjaan di [link ini](https://github.com/zst-ctf/tjctf-2019-writeups/tree/master/Writeups/Easy_as_RSA)

2. Melakukan faktorisasi (mendapatkan p dan q) pada alamat [factordb.com](http://factordb.com/)

```
p = 202049603951664548551555274464815496697
q =  285934543893985722871321330457714807993
```

3. Selanjutnya adalah menginputkan n, e, c serta p dan q kedalam Ruby Script:

```
$ruby main.rb
tjctf{BOLm1QMWi3c}
```

### Flag: 
```
tjctf{BOLm1QMWi3c}
```
