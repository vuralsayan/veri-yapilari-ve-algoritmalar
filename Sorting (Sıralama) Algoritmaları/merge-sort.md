 ## Merge Sort

 Insertion Sort'da, Big-O gösteriminden dolayı input'um arttığında n2 olduğunda dolayı çalışma zamanı artıyor.

 - Peki daha hızlı bir şekilde sıralama yapılabilir mi? Evet, ***Merge Sort*** burada yardımımıza koşuyor. Bir listeyi her adımda parçaya ayırıp tek eleman kalıncaya kadar bölüyor. Böldükten sonra sıralı bir şekilde bize sunuyor (Performans).

 <img src="https://raw.githubusercontent.com/Kodluyoruz/taskforce/main/veri-yapilari-algoritmalar/merge-sort/figures/merge-sort.png" alt="merge sort" width="500" height="380"> <br>

 Insertion sort'da, time complexity **n2** olduğundan ötürü çalışma zamanımız artıyordu. Merge sort'da ise **nlogn** olduğu için açık ara performans olarak daha iyi diyebiliriz.