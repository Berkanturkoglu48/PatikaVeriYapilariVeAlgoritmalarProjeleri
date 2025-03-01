# PatikaVeriYapilariVeAlgoritmalarProjeleri

INSERTION SORT PROJESİ (PROJE 1)

Soru 1 : Dizinin insertion sorta göre aşamaları nedir ?

[22,27,16,2,18,6]
[16,22,27,2,18,6]
[2,16,22,27,18,6]
[2,16,18,22,27,6]
[2,6,16,18,22,27]

Soru 2: Big-O gösterimini yazınız .

En iyi durum (Best Case - O(n)): Eğer dizi zaten sıralıysa, her eleman sadece bir kez kontrol edilir ve hiçbir kaydırma işlemi yapılmaz. Bu durumda O(n) karmaşıklığı oluşur.
En kötü durum (Worst Case - O(n²)): Eğer dizi tamamen ters sıralıysa (örneğin [27, 22, 18, 16, 6, 2]), her eleman kendisinden önceki tüm elemanlarla karşılaştırılır ve kaydırmalar yapılır. Bu durumda O(n²) olur.
Ortalama durum (Average Case - O(n²)): Rastgele bir dizinin sıralanması sırasında genellikle her eleman için yaklaşık n/2 karşılaştırma ve kaydırma işlemi yapılır. Bu da O(n²) olur.

Soru3 : Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

Cevap: 18 sayısı dizi sıralandıktan sonra orta sıralarda bulunduğu için Average Case - O(n²) kapsamına girer.

Soru4: [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

[7,3,5,8,2,9,4,15,6]
[2,3,5,8,7,9,4,15,6]  1
[2,3,5,8,7,9,4,15,6]  2
[2,3,4,8,7,9,5,15,6]  3
[2,3,4,5,7,9,8,15,6] 4

MERGE SORT (PROJE2)

[16,21,11,8,12,22] -> Merge Sort

Soru 1: Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

[16,21,11,8,12,22] 
[16,21,11] ---- [8,12,22]
[16] , [21,11] ----- [8] , [12,22]
[16] , [21] , [11] ------ [8] , [12] , [22]   İlk olarak diziyi parçalara ayırdık.
[11] , [16,21]  ------ [8] , [12,22]
[11,16,21] ------ [8,12,22]
[8,11,12,16,21,22]  Sonrasında adım adım sıralayarak birleştirdik.

Soru 2 : Big-O gösterimini yazınız.

Merge Sort algoritmasının Big-O gösterimi O(n log n)'dir.

BINARY SEARCH TREE PROJESİ (PROJE3)

Soru : [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.
                                                                        7
                                                                  /         \
                                                             5                 8
                                                        /         \               \
                                                    1               6                9
                                                 /    \           /
                                               0         3      4 
                                                    /
                                                 2









