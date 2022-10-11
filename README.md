# MERGE SORT PROJECT [Patika.dev](https://www.patika.dev/tr)

## Merge Sort : verilen dizinin sort türüne göre aşamalarını yazınız.

|Dizi|16|21|11|8|12|22|     
|------|- |- |- |-|- |-|

                      [16,21,11,8,12,22]
                      /                \
                  [16,21,11]         [8,12,22]
                   /    \             /     \ 
               [16,21]   [11]      [8,12]    [22]
               /    \      \       /    \      \
             [16]   [21]   [11]  [8]    [12]   [22]
               \     /      /     \      /      /
               [16,21]    [11]     [8,12]     [22]
                  \        /          \       /  
                  [11,16,21]          [8,12,22]
                       \                 /
                       [8,11,12,16,21,22]                  
## Big-O Notation
| Big-O   |
|:------:|
| O(nlog(n))  |                       
                       
