# 1. Soru
[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.
Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

# 2.Soru
[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.


# Cevaplar
* [22,27,16,2,18,6]
* [22,16,27,2,18,6]
* [16,22,27,2,18,6]
* [16,22,2,27,18,6]
* [16,2,22,27,18,6]
* [2,16,22,27,18,6]
* [2,16,22,18,27,6]
* [2,16,18,22,27,6]
* [2,16,18,22,6,27]
* [2,16,18,6,22,27]
* [2,16,6,18,22,27]
* [2,6,16,18,22,27]

# Big-O Gösterimi ve Time Complexity
Her diziyi n defa kontrol ettiğimiz için Big-0 Gösterimi
* O(n^2) dir
* Best Case: Dizi sıralı halde gelse bile bütün elemanlar kontrol edilmelidir. Bundan dolayı O(n^2) dir
* Average Case: Aynı şekilde her eleman kontrol edileceğidinden O(n^2) dir.
* Worst Case: Her eleman tek tek kontrol edilmesi gerektiği için yine O(n^2) dir.

# Cevap 2
* İLK 4 ADIM
* [3,7,5,8,2,9,4,15,6]
* [3,5,7,8,2,9,4,15,6]
* [3,5,7,8,2,9,4,15,6]
* [3,7,5,2,8,9,4,15,6]


