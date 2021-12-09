# Insertion Sort

## Dizi = [22,27,16,2,18,6] 

+ Insertion Sort'a Göre Yapılışı


```
    // 1. Adım
        [22,27,16,2,18,6]  
    // 2. Adım
        [2,27,16,22,18,6]

    // 3. Adım
        [2,6,16,22,18,27]
    // 3. Adım
        [2,6,16,18,22,27] 
````
+ Big O Gösterimi

``` 
   n*(n+1)/2=(n²+n)/2
    O(n²) -> Big O sadece n² alınır. Diğerleri O için önemli değildir.
```

+ Time Completixy

```
 Average Case, aranılan sayının '18' olması
 Best Case , aranılan sayının  '2' olması
 Worst Case, aranılan sayının '27' olması
```

```
  Dizi sıralandıktan sonra aranılan 18 average case olur.
```


## Dizi = [7,3,5,8,2,9,4,15,6] 

```
    // 1. Adım
        [7,3,5,8,2,9,4,15,6]
    // 2. Adım
        [2,3,5,8,7,9,4,15,6]
    // 3. Adım
        [2,3,4,8,7,9,5,15,6]
    //4. Adım
        [2,3,4,5,7,9,8,15,6]
    // 5. Adım
        [2,3,4,5,6,9,8,15,7]
    //6. Adım
        [2,3,4,5,6,7,8,15,9]
    // 7. Adım
        [2,3,4,5,6,7,8,9,15]
```
# Merge Sort

## Dizi= [16,21,11,8,12,22]

``` 
    // 1. Adım
        [16,21,11,8,12,22]
    // 2. Adım
        [16,21,11] ,[8,12,22]
    //3.Adım
        [16,21] [11],[8,12] [22]
    //4.Adım
        [16] [21] 11], [8] [12] [22]
    //5.Adım
        [11,16,21], [8,12,22]
    //6. Adım
        [8,11,12,16,21,22]
```
## Big O Gösterimi= O(n*log(n))


# Binary Search Tree

## Dizi= [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] 

```
    root 3 kabul edilmiştir. 3'ten küçük sayılar sola,büyük sayılar sağa yazılır.
                    3 ->root
          2                      6
        1                    5       8
    0                     4    7        9
                                  
                                     
    -2 < 3 ->3'ün sağına , 6 > 3 ->3'ün soluna
    -1 <2 ->2'nin sağına 
    -5<6 ->6'in sağına && 8 > 6 ->6'nin soluna
    -0 < 1 -> 1'in sağına
    -4<5 -> 5'in sağına && 7>5 -> 5'in soluna
    -9>8 -> 8'in soluna 
```
