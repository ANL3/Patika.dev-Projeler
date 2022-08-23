# Patika.dev-Projeler
 Python Temel - Proje

## Proje 1

### Problem

Bir listeyi düzleştiren (flatten) fonksiyon yazın. Elemanları birden çok katmanlı listelerden ([[3],2] gibi) oluşabileceği gibi, non-scalar verilerden de oluşabilir.

Örnek olarak:

input: [[1,'a',['cat'],2],[[[3]],'dog'],4,5]

output: [1,'a','cat',2,3,'dog',4,5]

"""Python

    def Flatten_Everything(line):
    
        l="0123456789"                              #ileride sayısal verileri int şeklinde döndürmek için tanımladım
    
        liner="[]''"                                #verilen yapıdaki parantezleri ve kesme işaretlerini silmek için tanımladım
    
        for e in liner:                             #burada input ile verilen listede liner içinde de bulunan stringleri sildim 
            line=line.replace(e,"")
        line=line.split(",")
    
        line_1=line.copy()                          #iterasyon yapacağım için kopya oluşturdum
    
        for i in range(len(line_1)):                #integar olması gerekenleri dönüştürdüm
            if line_1[i] in l:
                line.pop(i)
                line.insert(i,int(line_1[i]))
            else:
                continue
        return line

    print(Flatten_Everything(input()))

"""

## Proje 1

### Problem

Verilen listenin içindeki elemanları tersine döndüren bir fonksiyon yazın. Eğer listenin içindeki elemanlar da liste içeriyorsa onların elemanlarını da tersine döndürün.

Örnek olarak:

input: [[1, 2], [3, 4], [5, 6, 7]]

output: [[[7, 6, 5], [4, 3], [2, 1]]

"""Python



"""

www.patika.dev
