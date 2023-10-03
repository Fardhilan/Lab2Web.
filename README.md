# Lab2Web.
# 1
![image](https://github.com/Fardhilan/Lab2Web./assets/93815689/05f1e81c-8d62-4e3d-9470-21569f4187b7)
Pada contoh ini, terdapat elemen ```<h1>``` dengan class "title dan elemen ```<p>``` dengan class "text". Class tersebut akan digunakan sebagai selector dalam CSS untuk mengubah properti dan nilai.
Dalam file CSS (style.css), terdapat aturan CSS yang dideklarasikan untuk class "title" dan "text". Aturan tersebut mengubah properti "color" pada elemen dengan class tersebut. Anda dapat mengubah nilai properti "color" pada file CSS sesuai keinginan Anda untuk melihat perubahan yang terjadi pada judul ```(h1)``` dan paragraf ```(p)``` dalam hal warna teks.
### OUTPUT YANG DI HASILKAN
![image](https://github.com/Fardhilan/Lab2Web./assets/93815689/aadc20af-d6f8-4082-a99d-8ca8e33e312c)
# 2
![image](https://github.com/Fardhilan/Lab2Web./assets/93815689/7d12b7a8-db76-4a45-af71-709f771f8465)
Pada contoh ini, terdapat elemen ```<h1>``` yang berada di dalam elemen ```<div>``` dengan ID "intro" dan juga elemen ```<h1>``` yang berdiri sendiri tanpa ada elemen lain di dalamnya.
![image](https://github.com/Fardhilan/Lab2Web./assets/93815689/6182d486-3b59-4147-9a09-830e1a4a8cf1)
Dalam file CSS (styles.css), terdapat aturan CSS yang dideklarasikan untuk selector ```"h1"``` dan "#intro h1". Aturan CSS h1 {...} akan berlaku untuk semua elemen ```<h1>``` dalam dokumen. Sementara itu, aturan CSS #intro h1 {...} hanya akan berlaku untuk elemen ```<h1>``` yang berada di dalam elemen dengan ID "intro". Perbedaan ini menyebabkan warna teks pada judul (h1) yang berada di dalam elemen dengan ID "intro" menjadi merah, sedangkan warna teks pada judul (h1) yang berdiri sendiri tetap biru.
# 3
![image](https://github.com/Fardhilan/Lab2Web./assets/93815689/95eb45b8-0a74-484a-badf-7740ea66f76e)
Pada contoh ini, terdapat elemen <p> dengan deklarasi CSS internal di dalam tag ```<style>```, deklarasi CSS eksternal dalam file styles.css, dan deklarasi inline CSS menggunakan atribut "style" di dalam elemen tersebut.
![image](https://github.com/Fardhilan/Lab2Web./assets/93815689/c9e72cde-5845-487e-b839-728927f85cc4)
Deklarasi CSS internal di dalam tag ```<style>``` akan berlaku untuk elemen ```<p>```, tetapi warna teks yang dideklarasikan menjadi biru tidak akan terlihat karena deklarasi inline CSS menggunakan atribut "style" memiliki prioritas tertinggi. Oleh karena itu, warna teks pada paragraf akan menjadi merah sesuai dengan deklarasi inline CSS. Deklarasi CSS eksternal dalam file styles.css tidak akan berlaku dalam contoh ini karena deklarasi inline CSS memiliki prioritas yang lebih tinggi.
# 4
![image](https://github.com/Fardhilan/Lab2Web./assets/93815689/5bdc7847-f4fa-45c3-988a-5b36ca793f8d)
Pada contoh ini, terdapat elemen ```<p>``` dengan ID "paragraf-1" dan class "text-paragraf".
![image](https://github.com/Fardhilan/Lab2Web./assets/93815689/b6778dc6-47c8-4cc1-be81-6ad3f72676d2)
Dalam file CSS (styles.css), terdapat aturan CSS yang dideklarasikan untuk ID selector "#paragraf-1" dan class selector ".text-paragraf". Aturan CSS #paragraf-1 {...} akan berlaku untuk elemen dengan ID "paragraf-1" dan mengubah properti "color" menjadi biru. Sementara itu, aturan CSS .text-paragraf {...} akan berlaku untuk elemen dengan class "text-paragraf" dan mengubah properti "font-size" menjadi 16px. Dalam contoh ini, warna teks pada paragraf akan menjadi biru sesuai dengan deklarasi CSS menggunakan ID selector karena spesifisitasnya lebih tinggi daripada class selector.

