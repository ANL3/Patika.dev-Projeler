# Patika.dev-Projeler
 Veri Yapıları ve Algoritmalar - Proje 3

## Binary Search Tree

### Aşamalar (7 5 1 8 3 6 0 9 4 2 ) 

7 rakamını root olarak belirleyelim.

|||||||||||||Seviye|
|-|-|-|-|-|-|-|-|-|-|-|-|-|
|||||||7||||||0|
||||||||||||||
||||||||||||||
||||||||||||||
||||||||||||||
||||||||||||||
||||||||||||||
||||||||||||||
||||||||||||||

5 rakamı root değerinden küçük olduğu için sol tarafa bağlıyoruz.

|||||||||||||Seviye|
|-|-|-|-|-|-|-|-|-|-|-|-|-|
|||||||7||||||0|
||||||x|||||||-|
|||||5||||||||1|
||||||||||||||
||||||||||||||
||||||||||||||
||||||||||||||
||||||||||||||
||||||||||||||

1 rakamı root değerinden küçük olduğu için sol tarafta yer almalıdır. 1 rakamı 5 değerinden de küçük olduğu için 5'in soluna bağlıyoruz.

|||||||||||||Seviye|
|-|-|-|-|-|-|-|-|-|-|-|-|-|
|||||||7||||||0|
||||||x|||||||-|
|||||5||||||||1|
||||x|||||||||-|
|||1||||||||||2|
||||||||||||||
||||||||||||||
||||||||||||||
||||||||||||||

8 rakamı root değerinden büyük olduğu için sağ tarafa bağlıyoruz.

|||||||||||||Seviye|
|-|-|-|-|-|-|-|-|-|-|-|-|-|
|||||||7||||||0|
||||||x||x|||||-|
|||||5||||8||||1|
||||x|||||||||-|
|||1||||||||||2|
||||||||||||||
||||||||||||||
||||||||||||||
||||||||||||||

3 rakamı root değerinden küçük olduğu için sol tarafta yer almalıdır. 3 rakamı 5 değerinden de küçük olduğu için sol tarafta yer almalıdır. 
3 rakamı 1 değerinden büyük olduğu için 1'in sağına bağlanmalıdır.

|||||||||||||Seviye|
|-|-|-|-|-|-|-|-|-|-|-|-|-|
|||||||7||||||0|
||||||x||x|||||-|
|||||5||||8||||1|
||||x|||||||||-|
|||1||||||||||2|
||||x|||||||||-|
|||||3||||||||3|
||||||||||||||
||||||||||||||

6 rakamı root değerinden küçük olduğu için sol tarafta yer almalıdır. 6 rakamı 5 değerinden büyük olduğu için 5'in sağ tarafına bağlanmalıdır.

|||||||||||||Seviye|
|-|-|-|-|-|-|-|-|-|-|-|-|-|
|||||||7||||||0|
||||||x||x|||||-|
|||||5||||8||||1|
||||x||x|||||||-|
|||1||||6||||||2|
||||x|||||||||-|
|||||3||||||||3|
||||||||||||||
||||||||||||||

0 rakamı root değerinden küçük olduğu için sol tarafta yer almalıdır. 0 rakamı 5 ve sonrasında 1 değerinden de küçük olduğu için 1'in sol tarafına bağlanmalıdır.

|||||||||||||Seviye|
|-|-|-|-|-|-|-|-|-|-|-|-|-|
|||||||7||||||0|
||||||x||x|||||-|
|||||5||||8||||1|
||||x||x|||||||-|
|||1||||6||||||2|
||x||x|||||||||-|
|0||||3||||||||3|
||||||||||||||
||||||||||||||

9 rakamı root değerinden büyük olduğu için sağ tarafta yer almalıdır. 9 rakamı 8 değerinden de büyük olduğu için 8'in sağ tarafına bağlanmalıdır.

|||||||||||||Seviye|
|-|-|-|-|-|-|-|-|-|-|-|-|-|
|||||||7||||||0|
||||||x||x|||||-|
|||||5||||8||||1|
||||x||x||||x|||-|
|||1||||6||||9||2|
||x||x|||||||||-|
|0||||3||||||||3|
||||||||||||||
||||||||||||||

4 rakamı root değerinden küçük olduğu için sol tarafta yer almalıdır. Sıralama aynı şekilde devam etiğinde 3'ün sağına bağlanmalıdır.

|||||||||||||Seviye|
|-|-|-|-|-|-|-|-|-|-|-|-|-|
|||||||7||||||0|
||||||x||x|||||-|
|||||5||||8||||1|
||||x||x||||x|||-|
|||1||||6||||9||2|
||x||x|||||||||-|
|0||||3||||||||3|
||||||x||||||||
|||||||4|||||||

2 rakamı root değerinden küçük olduğu için sol tarafta yer almalıdır. Sıralama aynı şekilde devam etiğinde 3'ün soluna bağlanmalıdır.

|||||||||||||Seviye|
|-|-|-|-|-|-|-|-|-|-|-|-|-|
|||||||7||||||0|
||||||x||x|||||-|
|||||5||||8||||1|
||||x||x||||x|||-|
|||1||||6||||9||2|
||x||x|||||||||-|
|0||||3||||||||3|
||||x||x||||||||
|||2||||4|||||||

www.patika.dev
