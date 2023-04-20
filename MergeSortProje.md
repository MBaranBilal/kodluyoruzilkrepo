## Proje 2
[16,21,11,8,12,22] -> Merge Sort

* Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
* Big-O gösterimini yazınız.
---

1. Adım: Listedeki elemanları iki ayrı gruba ayırırız.[16,21,11]  -  [8,12,22].
   
2. Gruplardaki elemanları tek başlarına kalıncaya dek ayırmaya devam ederiz. 
[16,21,11]-->[16,21]-[11]-->[16]-[21]/[11]
[8,12,22]-->[8,12]-[22]-->[8]-[12]/[22]

3. Bu adımda ayrılmış elemanlar sıralandıktan sonra birleştirilir.
[11,16,21]-[8,12,22]-->[8,11,12,16,21,22]
---
Big-O:O(nlogn) --> Her adımda toplam eleman sayısını ikiye bölerek ilerledik ve bölünmüş gruplar içerisindeki eleman sayısı kadar sorgu yaptık.
  
  * 2^x=n --> x=logn
  * Big-O:logn.n olmuş olur.

