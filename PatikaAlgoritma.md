# PatikaAlgoritma
Proje 1 <br>
[22,27,16,2,18,6] -> Insertion Sort <br>
1-)Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız. <br>
2-)Big-O gösterimini yazınız.<br>
3-)Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız<br>
Average case: Aradığımız sayının ortada olması<br>
Worst case: Aradığımız sayının sonda olması<br>
Best case: Aradığımız sayının dizinin en başında olması.<br>
4-)[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.<br><br>

1)Baştan başlayarak sürekli en küçük eleman bulunup bir sonraki elemana geçilir dizi küçükten büyüğe sıralama oluncaya kadar devam edilir.<br>
*[2,27,16,22,18,6]<br>
*[2,6,16,22,18,27]<br>
*[2,6,16,18,22,27]<br><br>

2)Big-o gösterimi için sıralama Worst Case göre düşünülür buna göre;<br>
*n<br>
*n-1<br>
  .<br>
  .<br>
  .<br>
*1<br>
---->n*(n+1)/2<br>
---->Baskın ifade n² buna göre O(n²)<br><br>

3)Dizi sıralandıktan sonra ([2,6,16,18,22,27]) 18 ortada olduğuna göre Average Case kapsamına girer.<br><br>

4)<br>
*[2,3,5,8,7,9,4,15,6]<br>
*[2,3,5,8,7,9,4,15,6]<br>
*[2,3,4,8,7,9,5,15,6]<br>
*[2,3,4,5,7,9,8,15,6]<br>




