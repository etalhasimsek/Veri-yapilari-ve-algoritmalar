# Veri-yapilari-ve-algoritmalar
Insertion Sort
Soru 1:
[22,27,16,2,18,6] -> Insertion Sort
Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
Çözüm:
Big-O gösterimini yazınız.
[22,27,16,2,18,6] == n
[2,27,16,22,18,6]== n-1
[2,6,16,22,18,27] == n-2
[2,6,16,18,22,27] == 1

Big O Notation = n*(n+1)/2 =(n^2+n) / 2 = n^2
Big O Notation = O(n^2)

Soru 2:
Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

Average case: Aradığımız sayının ortada olması
Worst case: Aradığımız sayının sonda olması
Best case: Aradığımız sayının dizinin en başında olması.

Cevap: Sıralı dizi: [2,6,16,18,22,27]
Aradığımız sayı olan 18 sayısı dizinin ortasında bulunduğundan; uygun kapsam "Average Case"dir

Soru 3:
[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.
[7,3,5,8,2,9,4,15,6] n
[2,3,5,8,7,9,4,15,6] n-1
[2,3,4,8,7,9,5,15,6] n-2
[2,3,4,5,7,9,8,15,6] n-3
[2,3,4,5,6,9,8,15,7] n-4
