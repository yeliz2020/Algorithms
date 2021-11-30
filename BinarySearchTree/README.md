# Binary Search Tree

İkili arama ağacı, verileri organize etmek için kullanılan bir çeşit ikili ağaçtır.
İkili ağaçtan temel farkı, verilerin sıralanmış bir şekilde tutulmasıdır, bu sayede ikili arama algoritmasının kullanılmasına imkân verir.

### İkili arama ağaç sistemi oluşturma kuralları

1. Kural:
En başdaki eleman “root” dur yani kökümüz dür. O her zaman en başa yazılır.
2. Kural:
En başa yazılan elemana göre konumlandırmalar başlar. Bu konumlandırmalar en baştaki eleman sağına veya soluna konumlandırılır. Kökden sonraki eleman küçük ise sola, büyük ise sağa konumlandırılır.
3. Kural:
Kökün altında en fazla 2 ağaç olabilir. Sonrakiler o diğer 2 ağaçtan birine konulabilir.
4. Kural:
Eşit elemanlardan biri üst üstte gelir ise her zaman sağa konumlandırılır.
5. Kural:
Dizme işlemi her zaman en baştaki elemandan başlar.

#### [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamaları
Root (dizinin ilk elemanı) 7'dir.

<img width="377" alt="BinarySearchTree" src="https://user-images.githubusercontent.com/69525712/144008310-73904252-88f5-4fc5-8699-748eee9d8eee.png">
