# Selection-Sort-Projesi
## [22,27,16,2,18,6] -> Insertion Sort
Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

    1. aşama; en baştaki ilk iki sayı kıyaslanır. 22 27'den küçük olduğu için sıralama değişmez. 
    [22,27,16,2,18,6]

    2. aşama; 2. ve 3. sıradaki iki sayı olan 27 ile 16 kıyaslanır. 16 hem 27 hem 22'den küçük olduğu için en başa alınır. 
    [16,22,27,2,18,6]

    3. aşama; 27 ile 2 kıyaslanır. 2 baştaki bütün sayılardan küçük olduğu için birinci sıraya alınır. 
    [2,16,22,27,18,6]

    4. aşama; 27 ve 18 kıyaslanır. 18 3. sıraya alınır. 
    [2,16,18,22,27,6]

    5. aşama; 27 ve 6 kıyaslanır. 6 ikinci sıraya alınır. 
    [2,6,16,18,22,27]

## Big-O gösterimini yazınız.
O(n^2)

## Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

Average case: Aradığımız sayının ortada olması
Worst case: Aradığımız sayının sonda olması
Best case: Aradığımız sayının dizinin en başında olması.

Cevap: 18 ortada olduğu için average case kapsamına girer.

## [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.
    1. aşama; dizideki en küçük sayı bulunup en başa yazılır. Böylece 7 ve 2 yer değiştirmiş olur. 
    [2,3,5,8,7,9,4,15,6]

    2. aşama; 3 doğru sırada olduğu için sabit kalır. 4 ve 5 yer değiştirir. 
    [2,3,4,8,7,9,5,15,6]

    3. aşama; 5 ve 8 yer değiştirir. 
    [2,3,4,5,7,9,8,15,6]

    4. aşama; 6 ve 7 yer değiştirir. 
    [2,3,4,5,6,9,8,15,7]