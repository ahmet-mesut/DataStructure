 # Veri Yapıları ve Algoritmalar Proje 1

 1 [22,27,16,2,18,6] -> Insertion Sort

 - En küçük sayı için sort edilir daha sonra 1.ile yerdeğiştirilir.Bu işlem liste tamamlanana kadar tekrarlanır.

 * [2,27,16,22,18,6] 
 * [2,6,16,22,18,27] 
 * [2,6,16,22,18,27]  
 * [2,6,16,18,22,27] 
 * [2,6,16,18,22,27]  
 * [2,6,16,18,22,27] 

 2 Big-O gösterimini yazınız.

 * O(n^2)

 3 Time Complexity: 
 Average case: Aradığımız sayının ortada olması,
 Worst case: Aradığımız sayının sonda olması, 
 Best case: Aradığımız sayının dizinin en başında olması.

 4 Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
 * Aradığımız sayı ortada olduğu için **AverageCase** kapsamına girer.
 
 5 [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

 * [2,3,5,8,7,9,4,15,6] 
 * [2,3,5,8,7,9,4,15,6] 
 * [2,3,4,8,7,9,5,15,6] 
 * [2,3,4,5,7,9,8,15,6] 