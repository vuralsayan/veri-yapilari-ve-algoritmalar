## Qucik Sort

Quick Sort günümüzde çok yaygın olarak kullanılan bir sıralama algoritmasıdır. N tane sayısı average case e göre big-o nlogn, word case e göre big-o n^2 karmaşıklığı ile sıralanır.

<img src="https://raw.githubusercontent.com/Kodluyoruz/taskforce/main/veri-yapilari-algoritmalar/quick-sort/figures/Quicksort.png" alt="quick sort" width="500" height="320">

- ilk olarak bir pivot belirlenir bu pivota göre pivottan küçük ve eşitler sol kısmına, pivottan büyük ve eşitler sağ kısmına yazılır. Parçalanmış kısımlar yeni bir pivot belirlenip parçalanmaya devam edilir.

Worst case: O(n^2) <br>
Average case: O(nlogn)