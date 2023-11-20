#Pythonda String Tanımlama

# Pythonda Karakter Dizileri yani string veri tipleri tek tırnak (' ') ya da çift tırnak (" ") ile oluşturulur.

# 'Hello World' ile "Hello World" tanımlaması aynıdır. Ancak bazen karakter dizileri içerisinde tek tırnak karakterini karakter dizisinin bir elemanı gibi göstermek isteriz.

#Örnek

# "I'm from Turkey" şeklinde tek tırnak karakterini tanımlayabilmek için mecburen çift tırnak kullanmamız gerekir çünkü 'I'm from Turkey' bu şekilde bir kullanım hata verecektir.

#Birden Fazla Satırda String Tanımlama

#3 tırnak ile birden fazla satırda string tanımlaması yapabilirsiniz. 3 tane tek tırnak ya da 3 tane çift tırnak kullanabilirsiniz.

#Örnek

text = """Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.""" 
print(text)

#String Birleştirme (String Concatenation)

#Tanımladığımız string ifadeleri '+' operatörü ile birleştirebiliriz. Ancak string birleştirmede number değişkenleri str() ile string'e çevirmemiz gerekiyor

# Örnek

name="Turan"
surname="Dursun"
age=100

birlestirme=("Adım :"+'  '+ name+ "\n Soyadım :"+surname+'  '+"ve ben"+' '+str(age)+' '+ "yaşındayım")
print(birlestirme)

#Bu şekilde değişken içeriklerine göre bir string ifadeyi + operatörü ile oluşturmuş olduk ve age değişkeni number türünde olduğundan dolayı str(age) şeklinde string' e çevirdik.

#String Formatlama

#'+' operatörünü kullanarak string birleştirme işlemi bazen zor olabiliyor. Dolayısıyla kullanabileceğimiz format() metodu ile f-string isminde iki farklı alternatifimiz mevcut.

#String format() Metodu

#.format() metoduna vereceğimiz her parametre sırasıyla { }' lerin yerine kopyalanır. 
ad="Özdemir"
soyad="Asaf"
print("Benim Adım {} {}".format(ad,soyad))

#.format() metoduna vereceğimiz her parametre sırasıyla { }' lerin yerine kopyalanır. 

print("Benim Adım {1} {0}".format(ad,soyad))

#{ }' ler için indeks numarası da verebiliriz. Yani format metodu içindeki name 0,ve surname 1 değerlerini alır. 

print("Benim Adım {s} {n}".format(s=surname,n=name))

# format() metodu içindeki değişkenlere takma isim de verebiliriz.

print("Benim Adım {0} {0} ve ben {0} yaşındayım".format(soyad))
#forma içine eklediğimiz 3 tane name değişkeni sırasıya süslü parantezler yerine gelir. Eğer ki tek name değerini 3 kere yazdırmak istersek, {0} şeklinde kullanabiliriz.

#f-String ile String Formatlama

#f-string ile kolaylıkla string birleştirme işlemi yapabiliriz. Çünkü string ifadenin içinde süslü parantezler içinde değişkenleri yazabiliriz.
print(f"Benim Adım {ad} {soyad} ve ben {age} yaşındayım")


#String Parçalama (String Slicing)

#String veri tipleri bir karakter dizisi olarak anılır yani bir karakter listesi olarak tanımlanırlar. Dizilerin her bir karakterine soldan 0' dan başlayarak bir indeks numarası atanır. Atanan indeks numaraları dizi içerisindeki her bir elemana ulaşırken kullanılır.
                                                                                                                                                                                                                                                                                    
#Örnek
ornek ="Yunus"
print(ornek[3])
#gördüğünüz gibi greeting karakter dizisinin ilk elemanı soldan sağa doğru 0 indeks numarası ile başlar ve greeting[0] dediğimizde bize 0.indeksteki M karakteri gelir.

print(ornek[-5])
#Pozitif indeks numarası soldan sağa 0'dan başlar negatif indeks numarası ise -1 ile sağdan başlar.

#Karakter dizilerinin daha doğrusu dizilerin eleman sayısını len() metodu ile bulabiliriz.
ornek=len("Emree")
print(ornek)

#Bir karakter dizisini başlangıç ve bitiş aralığında istediğimiz şekilde bölebiliriz.
surnamee = "dayanikli" 
print(surnamee[3:7])

#Burada ise başlangıç indeksini belirtmediğimizden dolayı en başta başlar ve 7. indekse kadar gider.
print(surnamee[:6])

#Burada ise başlangıç indeksi 3 ve bitiş indeksi belirtilmediğinden dolayı en sona kadar alınır.
print(surnamee[2:])

#Burada ise 0. indeksten 7. indekse kadar alınır ancak adım sayısı 2 olarak belirtildiğinden dolayı bir karakter alınır bir diğeri alınmaz.
print(surnamee[0:9:2])

#Adım sayısı 1 olduğundan dolayı [0:10] ile gene aynı sonucu verir. Ancak adım sayısına pozitif değer yerine negatif değer verirsek bu durumda sağdan sola doğru ilerleriz.
print(surnamee[0:9:1])

#Dolayısıyla karakterleri tersten yazdırmak istediğimizde aşağıdaki gibi sonuç alırız. [::] ile tüm karakter dizisini al ancak adım sayısı negatif olduğundan sağdan sola doğru birer birer ilerle. Dolayısıyla yazı tersten yazdırılmış olur.
print(surnamee[::-1])

#Python String Uygulamaları

website = "http://www.fikiristbiri.blogspot.com" 
course = "Python Kursu: Baştan Sona Python Programlama Rehberiniz (40 saat)"

#1- 'course' karakter dizisinde kaç karakter bulunmaktadır ?
#C1-
print(len(course))

#2- 'website' içinden www karakterlerini alın.
#C2-
print(website[7:10])

#3- 'website' içinden com karakterlerini alın.
#C3-
print(website[33:36])

#4- 'course' içinden ilk 15 ve son 15 karakterlerini alın.
#C4-
print(course[:15])
print(course[15:])

#5- 'course' ifadesindeki karakterleri tersten yazdırın.
#C5-
print(course[::-1])

name, surname, age, job = 'Bora','Yılmaz', 32, 'mühendis'

#6- Yukarıda verilen değişkenler ile ekrana aşağıdaki ifadeyi yazdırın.

#'Benim adım Bora Yılmaz, Yaşım 32 ve mesleğim mühendis.'
#C6-
print("Benim adım "+name+" "+surname+" Yaşım "+str(age)+" ve mesleğim "+job)
print("Benim adım {} {} , Yaşım {} ve mesleğim {}".format(name,surname,age,job))
print(f"Benim adım {name} {surname}, Yaşım {age} ve mesleğim {job}")

#7- 'Hello world' ifadesindeki w harfini 'W' ile değiştirin.
#C7
s="Hello world"
print('W'+ s[-4:])

#8- 'abc' ifadesini yan yana 3 defa yazdırın.
#C8
print('abc'*3)
