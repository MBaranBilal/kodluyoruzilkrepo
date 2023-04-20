## Proje 3
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

* Başlangıçta root'u 7 olarak alalım.
* Sonrasında "5", "7"den küçük olduğu için 7'nin sol tarafına konumlanır.
```
         7
      ___|
      |      
      5
```
* "1" elamanı 7den küçük olduğundan sol tarafta yer alacaktır. 1 aynı zamanda 5'ten de küçük olduğundan yine 5'in solunda konumlanır.
```       
         7
      ___|
      |      
      5
   ___|
   |
   1
```
* 8, 7'den büyük olduğundan 7'nin sağında konumlanır.
  
 ```       
         7
      ___|___
      |     |
      5     8
   ___|
   |
   1
```

* Aynı mantıkla listenin kalanını da yerlerine koyduğumuzda:
  
```       
           7
        ___|___
        |     |
        5     8
     ___|___  |___
     |     |     |
     1     6     9
  ___|___
  |     |
  0     3
     ___|___
     |     |        
     2     4
```