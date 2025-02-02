# insertion-
Kodluyoruz Eğitimi kapsamında açtığım  repo
[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

Big-O gösterimini yazınız.

Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

Average case: Aradığımız sayının ortada olması
Worst case: Aradığımız sayının sonda olması
Best case: Aradığımız sayının dizinin en başında olması.
.



[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.



Merge Sort Aşamaları
Verilen dizi: [16, 21, 11, 8, 12, 22]

Merge Sort, "böl ve fethet" yöntemini kullanarak diziyi ikiye böler ve ardından sıralı şekilde birleştirir.

1) Diziyi İkiye Bölme Aşamaları:
[16, 21, 11] - [8, 12, 22]
[16, 21] - [11] ve [8, 12] - [22]
[16] - [21] - [11] ve [8] - [12] - [22] (Artık tüm alt diziler tek elemanlıdır.)
2) Birleştirme Aşamaları:
[16] ve [21] birleşir → [16, 21]
[16, 21] ile [11] birleşir → [11, 16, 21]
[8] ve [12] birleşir → [8, 12]
[8, 12] ile [22] birleşir → [8, 12, 22]
[11, 16, 21] ile [8, 12, 22] birleşir → [8, 11, 12, 16, 21, 22] ✅
Son sıralı dizi: [8, 11, 12, 16, 21, 22]

Big-O Gösterimi:
Merge Sort’un zaman karmaşıklığı her zaman O(n log n)’dir.

✅ Big-O: O(n log n)
