# Proje 1
[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

Big-O gösterimini yazınız.

Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

1.Average case: Aradığımız sayının ortada olması

2.Worst case: Aradığımız sayının sonda olması

3.Best case: Aradığımız sayının dizinin en başında olması.

.

[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

---

# Cevaplar

## 1.Soru :
### Aşamalar :
1.Aşama: Dizinin en küçük elemanı bulunur (2) ve dizinin başındaki elemanla yer değiştirir.Bu işlem sonucunda 2 ve 22 sayıları yer değiştirmiş olur. [2,27,16,22,18,6].

2.Aşama: 1.sıradaki 2 sayısı sabit yerini korur. Kalan elemanlar arasındaki en küçük sayı bulunur (6) ve 2. sıradaki sayı ile yer değiştirir.[2,6,16,22,18,27].

3.Aşama: 1. ve 2. sıradaki sayılar yerini korur. Kalan elemanlar arasındaki en küçük sayı bulunur (16) ve 3. sıradaki sayı ile yer değiştirir. 16 zaten olması gerektiği yerde olduğundan sırada bir değişiklik olmaz.[2,6,16,22,18,27].

4.Aşama: 1,2 ve 3. sıradaki sayılar yerlerini korur.Kalan elemanlar arasındaki en küçük sayı bulunur (18) ve 4. sıradaki sayı ile yer değiştirir.[2,6,16,18,22,27].

5.Aşama:Dizinin 5. ve 6. sırasındaki sayılar olması gerektikleri yerlerde olduklarından sıralarında değişiklik yapılmaz.

### Big-O Gösterimi :
1. aşamada-> n elemana bakılır.
2. aşamada-> n-1 elemana bakılır.
3. aşamada-> n-2 elemana bakılır.
4. aşamada-> n-3 elemana bakılır.

Sonuç olarak n+(n-1)+(n-2)+(n-3)...+1= [n*(n+1)]/2 --> (n^2+n)/2 elde edilir. Dominant kısım n^2 olduğundan O(n^2) olarak ifade edilir.

### 18 sayısının Time Complexity değeri :
Dizi sıralandığında ortada yer aldığından Average Case olarak değerlendirilir.

## 2.Soru :

1. [7,3,5,8,2,9,4,15,6] n
2. [2,3,5,8,7,9,4,15,6] n-1
3. [2,3,4,8,7,9,5,15,6] n-2
4. [2,3,4,5,7,9,8,15,6] n-3


