# Merge-Sort-Projesi-www.patika.dev-

**Patika - Veri Yapıları ve Algoritmalar Derslerinin Alıştırma Projeleri Kapsamında Yapılmıştır. Merge Sort Projesi'dir. [www.patika.dev]**

## Merge Sort Projesi

 [16,21,11,8,12,22] -> Merge Sort

----------------------------
### 1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

    1. aşama = [16,21,11] [8,12,22]
    2. aşama = [16] [21,11] | [8,12] [22]
    3. aşama = [16] [21] [11] | [8] [12] [22]
    4. aşama = [16] [11,21] | [8,12] [22]
    5. aşama = [11,16,21] | [8,12,22]
    5. aşama = [8,11,12,16,21,22]

----------------------------
### 2. Big-O gösterimini yazınız.
    
    - Big-O göstermine bakacak olursak, her aşamada n-1 kere işlem yapmış oluruz. 
    - Bu sebepten dolayı n-1 olsada -1 değeri Big-O da ele alınmaz ve her aşama için Big-O => O(n) olmuş olur.
    - Merge Sortta aşama aşama parçalama işlemi olur.
    - Parçalama işleminden dolayı her seferinde yarıya ineceğinden dolayı  2^x = n eşit olur. Çünkü her seferinde ikiye parçalar.
    - Buradanda x'i yalnız bırakırsak x = logn olur. 
    - Böylece Merge Sort'un Big-O gösterimi O(n*logn) olur.

    - Big-O => O(n*logn)

    
    

