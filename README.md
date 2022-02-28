# Tugas Kecil 2 IF2211 Strategi Algoritma
Merupakan sebuah program yang dapat mengembalikan convex hull dari kumpulan data 2 dimensi (dapat dianggap kumpulan titik 2 dimensi). Himpunan titik pada bidang planar disebut convex jika untuk sembarang dua titik pada bidang tersebut (misal p dan q), seluruh segmen garis yang berakhir di p dan q berada pada himpunan tersebut. Titik convex hull yang dihasilkan akan divisualisasikan. Program ini menggunakan bahasa Python.

## Requirement Program
* Python
* Package 
  * matplotlib
  * pandas
  * scipy
<br> Dapat diinstall dengan menjalankan ``` pip install --user numpy scipy matplotlib ipython jupyter pandas ``` di terminal

## Cara menggunakan Program
1. Jalankan semua cells pada file `myConvexHull.ipynb`
2. Ubah dataset yang ingin digunakan pada bagian
   ``` data = datasets.load_iris() ``` di cell kedua
   <br>
   Dataset yang dapat digunakan yaitu :
   * load_iris
   * load_wine
   * load_breast_cancer
 3. Nomor kolom yang ingin digunakan dapat diubah pada cell ketiga bagian
    ```
    #kolom yang ingin digunakan
    a = 0
    b = 1
    ```

## Author
> Lyora Felicya - 13520073
