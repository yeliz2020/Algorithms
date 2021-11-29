# Insertion Sort

Insertion sort algoritması temel sıralama algoritmalarından bir tanesidir. Algoritmanın mantığına göre elimizdeki A dizisinin elemanları arasında sıralama yapılmak istenildiğinde A[1] indisinden başlanarak önceki elemanlar ile karşılaştırma yapılır. Eğer A[1] indisli eleman kendinden önceki elemanlardan küçük ise yer değiştirme işlemi gerçekleşir ve dizinin başına A[1] elemanı geçer, aksi takdirde yer değiştirme işlemi gerçekleşmez ve bir sonraki elemana bakılır.

Araya sokma algoritması, sıralı bir diziye eleman ekleme işlemi için uygun bir algoritmadır. Bunun için daha çok bağlı liste (linked list) kullanılır. Eleman eklemek için karmaşıklık O(n) iken, sıralama yapmak için karmaşıklığımız O(n^2) olur.

<img src="https://upload.wikimedia.org/wikipedia/commons/0/0f/Insertion-sort-example-300px.gif" srcset="https://upload.wikimedia.org/wikipedia/commons/0/0f/Insertion-sort-example-300px.gif 1x" alt="">

<img width="911" alt="Ekran Resmi 2021-11-28 22 31 02" src="https://user-images.githubusercontent.com/69525712/143783085-a14e27b3-0848-4492-b455-3d6e388ff8e1.png">

##### Big O ve Time Complexity

|              |                   |
| ------------ | ----------------- |
| Worst Case   | O (n<sup>2</sup>) |
| Best Case    | O (n)             |
| Average Case | O (n<sup>2</sup>) |

Dizi sıralandıktan sonra 18 sayısı Average Case kapsamına girer.

---

[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımı

<img width="438" alt="Ekran Resmi 2021-11-28 23 11 03" src="https://user-images.githubusercontent.com/69525712/143785195-05559f98-deec-4d4e-89a7-4c327c6506c5.png">
