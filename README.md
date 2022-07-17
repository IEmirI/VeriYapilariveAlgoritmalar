# VeriYapilariveAlgoritmalar

## Insertion Sort Projesi

[22,27,16,2,18,6] -> Insertion Sort

1-) Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

2-) Big-O gösterimini yazınız.

3-) Time Complexity:

Average case: Aradığımız sayının ortada olması,

Worst case: Aradığımız sayının sonda olması,
 
Best case: Aradığımız sayının dizinin en başında olması.

4-) Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

5-) [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

### 1-) Insertion Sort Aşamaları

```
[22,27,16,2,18,6],
[2,27,16,22,18,6],
[2,6,16,22,18,27],
[2,6,16,18,22,27].
```

### 2-) Big O Notation Gösterimi

```
Best Case : O(n),
Worst Case : O(n^2),
Avarage Case : O(n^2).
```

### 3-) Time Complexity

```
Best Case : [2,6,16,18,22,27],
Worst Case : [27,22,18,16,6,2],
Average case:[2,6,16,18,22,27].
```

### 4-) 18 Sayısının Case Durumu

```
Dizimiz sıralandıktan sonra 18 sayısı tam ortada yer almaktadır. Bu sebeple avarage case sayılabilir.
Dizimizin son durumu [2,6,16,18,22,27] olmaktadır.
```

### 5-) [7,3,5,8,2,9,4,15,6] Dizisinin İlk 4 Adımı

```
[7,3,5,8,2,9,4,15,6]
[3,7,5,8,2,9,4,15,6]
[3,5,7,8,2,9,4,15,6]
[3,5,7,8,2,9,4,15,6]
```

# [Patika.dev](https://app.patika.dev/courses/veri-yapilari-ve-algoritmalar/insertion-sort-proje)
