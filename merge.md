# merge sort ödevi #

[16,21,11,8,12,22] -> merge sort

her adımda 2 ye bölerek 1 değer kalana kadar bölünür. 1 kaldıktan sonra küçük büyük sıralamasına uygun olarak tekrar bir araya getirilir.


1. adım [16,21,11,8,12,22]

2. adım [16,21,11]-[8,12,22]

3. adım [16,21]--[11]----[8,12]--[22]

4. adım [16]-[21]--[11]----[8]-[12]--[22]

5. adım [16,21]--[11]----[8,12]--[22]

6. adım [11,16,21]----[8,12,22]

7. adım [8,11,12,16,21,22]

big O her seferinde 2 ye böldüğümüz için 2^x=n olacaktır. Bu yüzden O(logn) dir.