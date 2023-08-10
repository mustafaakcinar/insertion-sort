# insertion sort projesi#
[22,27,16,2,18,6] -> insertion sort

en küçük bulunup en başa yazılır.

[2,27,16,22,18,6]

ilk sıraya yazılan en küçükle işlem biter. ikinci sıradan devam edilerek işlemler tekrarlanır..

[2,6,16,22,18,27] burada 16 sayısı 3. sıradan sonra yapılan işlem için en küçük olduğundan dokunmadan 4. sıradan devam ediyoruz.

[2,6,16,18,22,27] işlem burada tamamlanıyor. geriye kalan sayılar zaten sıralı şekilde olduklarından işlem tamamlandı.

big O notation için ilk işlemimiz n=6 olacak şekildedir.
daha sonrasında n+(n-1)+(n-2) şeklinde 1 e kadar iner formüle dökersek  (n.(n+1))/2 olur big O notationumuz dominant değerden dolayı O(n^2) olur.

-------------------------------------------------------

dizi sıralandıktan sonra 18 sayısı [2,6,16,18,22,27] indeks 3 olacağından average case olacaktır.

-------------------------------------------------------------------------

[7,3,5,8,2,9,4,15,6]

ilk adım        :   [2,3,5,8,7,9,4,15,6]


ikinci adım     :   [2,3,4,8,7,9,5,15,6]


üçüncü adım     :   [2,3,4,5,7,9,8,15,6]


dördüncü adım   :   [2,3,4,5,6,9,8,15,7]


