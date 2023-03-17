# Merge-Sort-Projesii
Merge Sort aşamaları:

[16,21,11,8,12,22]
[16,21,11] ve [8,12,22] olmak üzere iki parçaya bölünür.
[16,21,11] -> [16], [21,11] -> [21], [11] olacak şekilde parçalara ayrılır.
[16] ve [11] iki parçanın birleştirilmesiyle [11,16] oluşur. [21] parçası zaten tek başına doğru konumdadır.
[11,16] ve [21] parçaları birleştirilerek [11,16,21] oluşur.
[8,12,22] -> [8,12], [22] olacak şekilde parçalara ayrılır.
[8,12] -> [8], [12] olacak şekilde parçalara ayrılır.
[8] ve [12] iki parçanın birleştirilmesiyle [8,12] oluşur. [22] parçası zaten tek başına doğru konumdadır.
[8,12] ve [22] parçaları birleştirilerek [8,12,22] oluşur.
Son olarak, [11,16,21] ve [8,12,22] iki sıralanmış parça birleştirilir ve [8, 11, 12, 16, 21, 22] sıralanmış dizi elde edilir.
Big-O gösterimi: Merge Sort'un time complexity'si O(nlogn)'dir.
