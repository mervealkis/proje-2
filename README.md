# proje-2
merge sort projesi

[16,21,11,8,12,22] -> Merge Sort

1.Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.




|                                                 |  |  |  |  |  |  |  |  |  |  |  |  |
|-----------------------------------------------  |- |- |- |- |- |- |- |- |- |- |- |- |
|Diziyi ikiye bölerek yeniden yazıyoruz           |  |  |  |16|21|11|8 |12|22|  |  |  |
|                                                 |  |  |  |  |  |  |  |  |  |  |  |  |
|Sol ve sağdaki dizileri tekrar ikiye böluyoruz.  |  |  |16|21|11|  |  |8 |12|22|  |  |
|                                                 |  |  |  |  |  |  |  |  |  |  |  |  |
|Tek eleman kalana kadar bir kez daha bölüyoruz.  |  |16|  |21|11|  |  |8 |12|  |22|  |
|                                                 |  |  |  |  |  |  |  |  |  |  |  |  |
|                                                 |16|  |21|  |11|  |  |8 |  |12|  |22|                
|                                                 |11|16|21|  |  |  |  |8 |12|22|  |  |
|Sıralı yeni dizi                                 |  |  |8 |11|12|16|21|22|  |  |  |  |


2.Big-O gösterimini yazınız.

Big-o(nlogn) yani big-O(6log6)
