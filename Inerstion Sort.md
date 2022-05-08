# Insertion Sort
# [22,27,16,2,18,6] -> n 

Sıralama aşalamaları şu şekikde olur, tek tek en küçükten büyüğe doğru "Yer değiştirerek" sıralarız. Random en büyük olanı başa yazmayız.
1) [2,27,16,22,18,6] -> n -1
2) [2,6,16,22,18,27] -> n-2
3) [2,6,16,18,22,27] -> n-3     (16 elemanı doğru konumda olduğu için onu atlıyor yanındaki elemana bakıyorum)

# Big-O = O(n)

Array sıralandıktan sonra 18 sayısını arıyorsak, bu Avarage Case olacaktır.


# [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

1) [2,3,5,8,7,9,4,15,6] -> n-1
2) [2,3,4,8,7,9,5,15,6] -> n-2
4) [2,3,4,5,7,9,8,15,6] -> n-3
5) [2,3,4,5,6,9,8,15,7] -> n-4
