# Merge-Sort-Dersi

Merge Sort algoritması aşağıdaki adımları içerir:

Veri setini ortadan ikiye ayır.
1- İki parçayı da Merge Sort algoritması ile sırala.
2- Sıralanmış iki parçayı birleştir.
3- Yukarıdaki dizinin Merge Sort'a göre aşamaları aşağıdaki gibidir:

[16, 21, 11, 8, 12, 22]
[16, 21, 11] [8, 12, 22] # Veri setini ikiye ayır
[16] [21, 11] [8] [12, 22] # Veri setlerini tekrar ikiye ayır
[16] [11, 21] [8] [12, 22] # Parçaları sırala
[11, 16, 21] [8, 12, 22] # İki parçayı birleştir

Bu şekilde devam ederek sıralama işlemi tamamlanır.

Merge Sort'un Big-O gösterimi O(n log n) dir.

Bu dizi için 18 sayısı Merge Sort'ta arama işlemi için ayrı bir adım bulunmamaktadır.
