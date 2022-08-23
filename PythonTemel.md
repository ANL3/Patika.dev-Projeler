# Patika.dev-Projeler
 Python Temel - Proje

## Proje 1

### Aşamalar

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



www.patika.dev
