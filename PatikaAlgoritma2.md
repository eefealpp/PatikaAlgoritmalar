# PatikaAlgoritma2
Proje2<br>
[16,21,11,8,12,22] -> Merge Sort<br>
1-)Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.<br>
2-)Big-O gösterimini yazınız.<br><br>

1)<br>
[16,21,11,8,12,22] /Tek kalana kadar yarıya bölünür.<br>
*[16,21,11][8,12,22]<br>
*[16,21][11][8,12][22]/Tek kalan elemanlardan sonra sıralanıp birleştirilir.<br>
*[11,16,21][8,12,22]<br>
*[8,11,12,16,21,22]<br><br>

2)Big-o gösterimi Worst Case göre yapılır buna göre;<br>
*Sürekli yarıya ayırdığımız için log2 tabanında n * eleman sayısı yani n<br> 
*O(log2n**n)

