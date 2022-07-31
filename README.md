# Insertion-Sort-Projesi
[22,27,16,2,18,6] -> Insertion Sort
1.Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız.

[22,27,16,2,18,6] -- (n)
açıklama:
Yukarıdaki sayı dizisi, bize verilen dizidir.Verilen bu dizinin en küçük elemanı en başa konularak başlanmalıdır.
2 dizideki en küçük elemandır bu nedenle baştaki 22 ile yer değiştirilir.


1.ADIM:
[2,27,16,22,18,6] -- (n-1)

açıklama:
Daha sonra ise,ikinci en küçük eleman aranır.6 ikinci en küçük elemandır.6 ile 27 yerdeğiştirilir.

2.ADIM:
[2,6,16,22,18,27] -- (n-2)

açıklama:
Aynı yol ile,üçüncü en küçük eleman aranır.16 üçüncü en küçük elemandır.

3.ADIM:
[2,6,16,18,22,27] -- (n-3)

İşleme devam edersek 18 ile 22 yer değiştirilir.

Üçüncü adımdan sonra dizi sıralanmış olur;yeni bir işleme ihtiyaç duyulmaz ve sorting tamamlanmış olur.

dizinin son durumu: [2,6,16,18,22,27]

2.Big-O gösterimini yazınız.

O(n^2)'dir.
açıklama:
n + (n-1) + (n-2) + (n-3) + ... + 1= (n.(n+1))/2 dir.
Big-O'da domine eden fonksiyon alınır,burada n^2 domine eden fonksiyon olduğu için,cevap O(n^2)'dir.


3.Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.

Worst Case:
[27,22,18,16,6,2] - O(n^2)

Best Case:
[2,6,16,18,22,27] - O(n)

Average Case:
[2,6,16,18,22,27] - O(n^2) (Dizimizin son durumu zaten avarage case'e örnektir.)

4.Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

18 sayısı dizinin ortanca değeri olduğu için,avarage case kapsamına girmektedir.
[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

1.adım :
[2,3,5,8,7,9,4,15,6]

2.adım :
[2,3,4,8,7,9,5,15,6]

3.adım :
[2,3,4,5,7,9,8,15,6]

4.adım :
[2,3,4,5,6,9,8,15,7]

www.patika.dev
