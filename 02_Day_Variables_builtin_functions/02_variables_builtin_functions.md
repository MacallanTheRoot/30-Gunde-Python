<div align="center">
  <h1> 30 Günde Python: Gün 2 - Değişkenler, Built in Functions (Builtin İşlevleri)</h1>
  <a class="header-badge" target="_blank" href="https://www.linkedin.com/in/asabeneh/">
  <img src="https://img.shields.io/badge/style--5eba00.svg?label=LinkedIn&logo=linkedin&style=social">
  </a>
  <a class="header-badge" target="_blank" href="https://twitter.com/Asabeneh">
  <img alt="Twitter Follow" src="https://img.shields.io/twitter/follow/asabeneh?style=social">
  </a>


</div>

[<< Gün 1](../readme.md) | [Gün 3 >>](../03_Day_Operators/03_operators.md)

![30DaysOfPython](../images/30DaysOfPython_banner3@2x.png)

- [📘 Gün 2](#-day-2)
  - [Built in functions](#built-in-functions)
  - [Değiişkenler](#variables)
    - [Declaring Multiple Variable in a Line](#declaring-multiple-variable-in-a-line)
  - [Data Türleri](#data-types)
  - [Veri türlerini ve Dökümantasyonu Kontrol Etme](#checking-data-types-and-casting)
  - [Sayılar](#numbers)
  - [💻 Egzersiz - Gün 2](#-exercises---day-2)
    - [Egzersiz: Level 1](#exercises-level-1)
    - [Egzersiz: Level 2](#exercises-level-2)

# 📘 Gün 2

## Built in functions

Python çok fazla built-in functions'a sahibiz. Built-in functions are globally available for your use that mean you can make use of the built-in functions without importing or configuring. Some of the most commonly used Python built-in functions are the following: _print()_, _len()_, _type()_, _int()_, _float()_, _str()_, _input()_, _list()_, _dict()_, _min()_, _max()_, _sum()_, _sorted()_, _open()_, _file()_, _help()_, and _dir()_. In the following table you will see an exhaustive list of Python built-in functions taken from [python documentation](https://docs.python.org/3.9/library/functions.html).

![Built-in Functions](../images/builtin-functions.png)

Python kabuğunu açıp en yaygın built-in function'larını kullanmaya başlayalım

![Built-in functions](../images/builtin-functions_practice.png)

Farklı built-in function'larını kullanarak daha fazla pratik yapalım

![Help and Dir Built in Functions](../images/help_and_dir_builtin.png)

Üst taraftaki terminalden görüldüğü üzere, Python'un ayrılmış kelimeleri var. Değişkenleri veya işlevleri bildirmek için ayrılmış sözcükler kullanmayız. Bir sonraki bölümde değişkenleri ele alacağız.

İnanıyorum ki built-in function'lara artık alışmışşınızdır. built-in functions'larla biraz daha alıştırma yapalım ve sonra sonraki bölüme geçelim.

![Min Max Sum](../images/builtin-functional-final.png)

## Variables (Değişkenler)

Değişkenler verileri bilgisayar belleğinde saklar. Mnemonic variables (Anımsatıcı Değişkenler) çoğu yazılım dilinde kullanılması önerilir.A mnemonic variables kolayca hatırlanabilen ve ilişkendirilebilen bir değişken adıdır.Variable verilerin saklandığı bir hafıza adresini ifade eder. baştakı sayı, özel karakter, tire bir değişkeni adlandırırken izin vermez. Değişkenlerin kısa adları olabilir (Örneğin x, y, z), fakat daha çok açıklayıcı bir isim tercih edilir (firstname, lastname, age, country).

Python (Değişken) Variable isim kuralları

- Değişken ismi bir harf veya alt çizği ile başlamalıdır
- Değişken ismi bir sayıyla başlayamaz
- Değişken ismi sadece alpa_numeric karakterler ve alt treler alabilir (A-z, 0-9, ve \_ )
- Değişken ismi büyük-küçük duyarlıdır (firstname, Firstname, FirstName ve FIRSTNAME) bunlar farklı değişkenlerdir)

Geçerli Variable (Değişken) adlarını görelim

```shell
ilkisim
soyisim
yas
ulke
sehir
ilk_isim
soy_isim
_if # bir reserved (ayrılmış) kelimeyi değişken olarak kullanmak istiyorsak
sene_2022
sene2022
su_anki_sene_2022
dogum_tarihi
num1
num2
```

Yanlış (Değişken) variables isimleri

```shell
first-name
first@name
first$name
num-1
1num
```

Birçok Python geliştiricisi tarafından benimsenen standart Python değişken adlandırma stilini kullanacağız. Python geliştiricileri, snake case(snake_case) diye adlandırılan adlandırma kuralını kullanır. Birden fazla kelime içeren bir değişken için her kelimeden sonra alt çizgi karakteri kullanırız (örn. ad_adı, soyadı, motor_dönüşü_hızı). Aşağıdaki örnek, değişkenlerin standart adlandırılmasına bir örnektir, değişken adı birden fazla kelime olduğunda alt çizgi gereklidir.



Bir değişkene belirli bir veri tipi atadığımızda buna değişken bildirimi (variable declaration) denir. Örneğin aşağıdaki örnekte benim adım bir first_name değişkenine atanmıştır. Eşittir işareti bir atama operatörüdür. Atama, değişkende veri depolamak anlamına gelir. Python'daki eşittir işareti, Matematikteki gibi eşitlik değildir. 


Ornekler:_

```py
# Python'da değişkenler
first_name = 'Efe'
last_name = 'Sahinbas'
country = 'Turkey'
city = 'Van'
age = 250
is_married = False
skills = ['HTML', 'CSS', 'JS', 'Python']
person_info = {
   'firstname':'Efe',
   'lastname':'Sahinbas',
   'country':'Turkey',
   'city':'Van'
   }
```

Hadi _print()_ ve _len()_ built-in functionlarını kullanalım.  Print fonksiyonu sınırsız sayıda argüman alır. Argüman, iletebileceğimiz veya fonksiyon parantezinin içine koyabileceğimiz bir değerdir, aşağıdaki örneğe bakın.

**Örnek:**

```py
print('Merhaba, Dunya!') # Merhaba, dünya! bir argümandır
print('Merhaba',',', 'Dunya','!') #print birden fazla argüman alabilir, dört argüman iletildi
print(len('Merhaba, Dunya!')) # sadece bir argüman alır
```

En üstte belirtilen değişkenlerin uzunluğunu yazdıralım ve bulalım:


**Örnek:**

```py
# Değişkenlerde saklanan değerleri yazdırma

print('First name:', first_name)
print('First name length:', len(first_name))
print('Last name: ', last_name)
print('Last name length: ', len(last_name))
print('Country: ', country)
print('City: ', city)
print('Age: ', age)
print('Married: ', not_married)
print('Skills: ', skills)
print('Person information: ', person_info)
```

### Bir satırda birden çok değişken bildirmek

bir satırda birden çok değişken bildirilebilir:

**Örnek:**

```py
first_name, last_name, country, age, is_married = 'Efe', 'Sahinbas', 'Van', 250, False

print(first_name, last_name, country, age, is_married)
print('First name:', first_name)
print('Last name: ', last_name)
print('Country: ', country)
print('Age: ', age)
```

_input()_ yerleşik işlevini kullanarak kullanıcı girdisi alma. Bir kullanıcıdan aldığımız verileri first_name ve age değişkenlerine atayalım.
**Örnek:**

```py
first_name = input('İsmin ne?: ')
age = input('Kaç yaşındasın? ')

print(first_name)
print(age)
```

## Data Türleri

Python'da birkaç veri türü vardır. Veri türünü belirlemek için yerleşik _type_ işlevini kullanırız. Farklı veri tiplerini çok iyi anlamaya odaklanmanızı rica ediyorum. Programlama söz konusu olduğunda, her şey veri türleri ile ilgilidir. En başta veri türlerini tanıttım ve tekrar geliyor çünkü her konu veri türleri ile ilgili. Veri türlerini ilgili bölümlerinde daha ayrıntılı olarak ele alacağız.


##Veri türlerini ve dökümanları kontrol etmek

- Veri türlerini kontrol edin: Belirli verilerin/değişkenlerin veri türünü kontrol etmek için _type_ kullanırız. 
- **Örnek:**

```py
# Farklı python veri türleri
# Değişkenleri çeşitli veri türleriyle tanımlayalım

first_name = 'Efe'     # str
last_name = 'Sahinbas'       # str
country = 'Turkey'        # str
city= 'Van'            # str
age = 250                   # int

# Diğer Türleri yazdırma
print(type('Efe'))     # str
print(type(first_name))     # str
print(type(10))             # int
print(type(3.14))           # float
print(type(1 + 1j))         # complex
print(type(True))           # bool
print(type([1, 2, 3, 4]))     # list
print(type({'name':'Efe','age':250, 'is_married':250}))    # dict
print(type((1,2)))                                              # tuple
print(type(zip([1,2],[3,4])))                                   # set
```

- Döküman: Bir veri tipini başka bir veri tipine dönüştürme. _int()_, _float()_, _str()_, _list_, _set_ kullanıyoruz. Aritmetik işlemler yaptığımızda string numaraları önce int veya float'a dönüştürülmelidir, aksi takdirde hata verir. Bir sayıyı bir dizge ile birleştirirsek, sayı önce bir dizgeye dönüştürülmelidir. String bölümünde birleştirme hakkında konuşacağız.
  **Example:**

```py
# int to float (sayıyı, ondalığa çevirmek)
num_int = 10
print('num_int',num_int)         # 10
num_float = float(num_int)
print('num_float:', num_float)   # 10.0

# float to int (ondalığı, sayıya çevirmek)
gravity = 9.81
print(int(gravity))             # 9

# int to str  (sayıyı yazıya çevirmek)
num_int = 10
print(num_int)                  # 10
num_str = str(num_int)
print(num_str)                  # '10'

# str to int or float
num_str = '10.6'
print('num_int', int(num_str))      # 10
print('num_float', float(num_str))  # 10.6

# str to list
first_name = 'Asabeneh'
print(first_name)               # 'Asabeneh'
first_name_to_list = list(first_name)
print(first_name_to_list)            # ['A', 's', 'a', 'b', 'e', 'n', 'e', 'h']
```

## Sayılar

Python'da sayı veri türleri:

1. Integers (Sayılar) : Integer(negative, sıfır ve pozitif) sayılar
   Örnek:
   ... -3, -2, -1, 0, 1, 2, 3 ...

2. Floating Point Numbers(Decimal numbers) (kayan ondalıklı sayılar)
   Örnek:
   ... -3.5, -2.25, -1.0, 0.0, 1.1, 2.2, 3.5 ...

3. Complex Numbers (karmaşık sayılar)
   Örnek:
   1 + j, 2 + 4j, 1 - 1j

🌕 Way Efsanesin. 2. gün zorluklarını tamamladınız ve mükemmelliğe giden yolda iki adım öndesiniz. Şimdi beynin kaslarınız için bazı egzersizler yapın.

## 💻 Egzersizler - Gün 2

### Egzersizler: Level 1

1. 30GundePython içinde day_2 adlı bir klasör oluşturun. Bu klasörün içinde variables.py adlı bir dosya oluşturun.
2. 2. 'Gün 2: 30 Günlük python programlama' diyen bir python yorumu yazın
3. Bir ad değişkeni bildirin ve ona bir değer atayın
4. Bir soyadı değişkeni bildirin ve ona bir değer atayın
5. Bir tam ad değişkeni bildirin ve ona bir değer atayın
6. Bir ülke değişkeni bildirin ve ona bir değer atayın
7. Bir şehir değişkeni bildirin ve ona bir değer atayın
8. Bir yaş değişkeni bildirin ve ona bir değer atayın
9. Bir yıl değişkeni bildirin ve ona bir değer atayın
10. Bir değişken evli_mi bildirin ve ona bir değer atayın
11. Bir değişken is_true bildirin ve ona bir değer atayın
12. Bir değişken is_light_on bildirin ve ona bir değer atayın
13. Bir satırda birden çok değişken bildir

### Egzersizler: Level 2

1. type() yerleşik işlevini kullanarak tüm değişkenlerinizin veri türünü kontrol edin
1. _len()_ yerleşik işlevini kullanarak adınızın uzunluğunu bulun
1. Adınızın ve soyadınızın uzunluğunu karşılaştırın
1. 5'i num_one ve 4'ü num_two olarak bildirin
   1. num_one ve num_two ekleyin ve değeri bir toplam değişkene atayın
    2. num_one'dan num_two'yu çıkarın ve değeri diff değişkenine atayın
    3. Sayı_iki ve Sayı_Bir'i çarpın ve değeri değişken bir çarpıma atayın
    4. num_one'u num_two'ya bölün ve değeri değişken bir bölüme atayın
    5. Sayı_iki'nin sayı_bir'e bölünmesini bulmak için modül bölmeyi kullanın ve değeri bir değişken kalanına atayın
    6. num_one'un num_two üssünü hesaplayın ve değeri bir exp değişkenine atayın
    7. num_one'un num_two'ya göre kat bölümünü bulun ve değeri bir Floor_division değişkenine atayın
1. Bir dairenin yarıçapı 30 metredir.
    1. Bir dairenin alanını hesaplayın ve değeri _area_of_circle_ değişken adına atayın
    2. Bir dairenin çevresini hesaplayın ve değeri _circum_of_circle_ değişken adına atayın
    3. Kullanıcı girişi olarak yarıçapı alın ve alanı hesaplayın.
1. Kullanıcının adını, soyadını, ülkesini ve yaşını almak ve değeri karşılık gelen değişken adlarına kaydetmek için yerleşik giriş işlevini kullanın.
1. Python'a ayrılmış kelimeleri veya anahtar kelimeleri kontrol etmek için Python kabuğunda veya dosyanızda help('keywords') komutunu çalıştırın
🎉 BAŞARILAR ! 🎉

[<< Gün 1](../readme.md) | [Gün 3 >>](../03_Day_Operators/03_operators.md)
