## Recursion
Bir problemin alt problemlere bölünüp hesaplanmasına, nerde son bulacağımı belirttiğimiz ifadelere recursion (Özyineleme) diyoruz. Hadi gelin fibonacci serisi ile konumuzu pekiştirelim.

![](https://raw.githubusercontent.com/Kodluyoruz/taskforce/main/veri-yapilari-algoritmalar/recursion/figures/fibonacci.png)

Fibonacci serisi 0,1 den başlayarak her önceki 2 sayının toplamı şeklinde bir kurala sahiptir. 0+1 = 1, 1+1=2, 2+1=3, 3+2=5 gibi. Kendinden bir önceki eleman ile iki önceki elemanın toplamı serinin devam sayısını verir. Recursion kullanımı : Fonksiyonumuz fib(x). 3. elemana n diyelim, fib(n-1) + fib(n-2) bize 3.elemanı yani 1 sonucunu verir. fib(n-1) + fib(n-2) => Recursion

Aşağıdaki örnek Python dilinde yazılmış bir faktoriyel işlemidir. Bir fonksiyon kendi içerisinde kendisini problemin daha küçüğünde çağırıyorsa ona ***recursive fonksiyon*** denir.
```python
def factorial(x):
    if x ==1:
        return 1

    return x * factorial(x-1)

```

