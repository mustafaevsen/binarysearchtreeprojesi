Proje 3
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

root'u 7 alalım.
root'un soluna root'dan küçük sayılar, root'un sağına root'dan büyük sayılar gelmelidir.

Dizinin elemanlarını sırası ile ekleyelim.

[5]
```
  7
 /
5
```
[1]
```
    7
   /
  5
 /
1
```
[8]
```
    7
   / \
  5   8
 /
1
```
[3]
```
    7
   / \
  5   8
 /
1
 \
  3 
```
[6]
```
    7
   / \
  5   8
 / \
1   6
 \
  3
```
[0]
```
      7
     / \
    5   8
   / \
  1   6
 / \
0   3
```
[9]
```
      7
     / \
    5   8
   / \   \
  1   6   9
 / \
0   3
```
[4]
```
      7
     / \
    5   8
   / \   \
  1   6   9
 / \
0   3
     \
      4
```
[2]
```
      7
     / \
    5   8
   / \   \
  1   6   9
 / \
0   3
   / \
  2   4
```


www.patika.dev

[zloine](https://app.patika.dev/zloine)


