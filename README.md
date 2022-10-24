# BinarySearch
https://www.patika.dev/tr

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

diziyi sıralayalım_[0,1,2,3,4,5,6,7,8,9]


Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

  root=6 dır
  
  root'un solunda [0,1,2,3,4,5] bulunur 
  sağında ise [7,8,9] bulunur
  
  root'un sol kısmına bakalım şimdi de
  [0,1,2,3,4,5]
  burda 3 ü baz alalım
  sol tarafında :
  [0,1,2] 
  sağ tarafında :
  [4,5]
  
  3 ün sol tarafına bakalım şimdi de:
  1 i baz alırsak:
  sol taraf:
  [0]
  sağ taraf:
  [2]
  
  şimdi 3 ün sağ tarafına bakalım:
  [4,5]
  4 ü baz alırsak 
  sol tarafta bir şey kalmıyor
  sağ taraf: [5] oluyor 
  
  
  
  rootun sağ tarafına geçecek olursak:
  [7,8,9]
  8 i baz alırsak: 
  sol taraf:
  [7]
  sağ taraf :
  [9] şeklinde 
  Binary Search Tree projesi oluyor
  
  
  
  
  
  
  
