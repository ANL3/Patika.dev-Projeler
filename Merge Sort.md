# Patika.dev-Projeler
 Veri Yapıları ve Algoritmalar - Proje 2

## Merge Sort

### Aşamalar (16 21 11 8 12 22)

|||
|-|-|
|16 21 11|8 12 22|

|||||
|-|-|-|-|
|16 21|11|8 12| 22|

|||||||
|-|-|-|-|-|-|
|16| 21|11|8 |12| 22|

|||||
|-|-|-|-|
|16 21|11|8 12| 22|

|||
|-|-|
|11 16 21|8 12 22|

||
|-|
|8  11 12 16 21 22|



### Big O Gösterimi (Worst Case)
 
Öncelikle algoritmanın ayrılma aşamasında verilen sayıların uzunluğunu yani adetini n kabul ettğimizde, n değerini sürekli ikiye bölerek elemanların tek tek ayrılmasını istiyoruz. Burada ikiye bölme amacımız algortimanın yapısından kaynaklanmaktadır. Yani matematiksel olarak

n/(2^x)=1

eşitliğinin sağlanmasını bekliyoruz. Buradan

2^x=n 

elde edilmektedir.
 
x = logn (2 tabanında)

bulunmaktadır. Bu sonuç birleştirme aşaması için de geçerlidir. Aslında burada yapılan toplam işlem 2logn olsa da katsayıların davranışa etkisi olmadığından ihmal edilmektedir.

Birleştirme aşamasında son satırda n eleman için n-1 işlem yapılmaktadır. En büyük eleman kıyaslanmayacaktır. Son satırın Big O değeri n olarak hesaplanır. 

Diğer satırlarda da her yarı kendi için bir eksiği kadar işlem yapacaktır. Son satırdan bir önceki satır içim (n-1)/2 veya (n+1)/2 veya n/2 hesaplamalarda karşımıza gelebilir. Katsayıların davranışa etkisi olmadığından sonuçları aynı çıkmaktadır. Örnek olarak n/2 olarak düşündüğümüzde iki parça için n/2-1 işlem yapılacaktır. Yine Big O değeri n olarak hesaplanır. Tüm satılarda yapılan sıralama işlemlerinin Big O karakteri n olarak hesaplanır. 

Birleştirme aşaması için inceleme yaptığımızda logn satır ve her satırda n işlem olarak düşündüğümüzde sonuç aşağıdaki gibi hesaplanacaktır.

O (n.logn) 

www.patika.dev
