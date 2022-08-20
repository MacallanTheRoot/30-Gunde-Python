# 🐍 30 Günde Python 

|# Günler | Konular                                                    |
|------|:---------------------------------------------------------:|
| 01  |  [Giriş](./readme.md)|
| 02  |  [Değişkenler, Yerleşik İşlevler](./02_Day_Variables_builtin_functions/02_variables_builtin_functions.md)|
| 03  |  [Operatörler](./03_Day_Operators/03_operators.md)|
| 04  |  [String'ler](./04_Day_Strings/04_strings.md)|
| 05  |  [Listeler](./05_Day_Lists/05_lists.md)|
| 06  |  [Demetler](./06_Day_Tuples/06_tuples.md)|
| 07  |  [Sets](./07_Day_Sets/07_sets.md)|
| 08  |  [Sözlükler](./08_Day_Dictionaries/08_dictionaries.md)|
| 09  |  [Şartlar](./09_Day_Conditionals/09_conditionals.md)|
| 10  |  [Döngüler](./10_Day_Loops/10_loops.md)|
| 11  |  [Fonksiyonlar](./11_Day_Functions/11_functions.md)|
| 12  |  [Modüller](./12_Day_Modules/12_modules.md)|
| 13  |  [Comprehension Listesi](./13_Day_List_comprehension/13_list_comprehension.md)|
| 14  |  [Daha Yüksek Dereceli Fonksiyonlar](./14_Day_Higher_order_functions/14_higher_order_functions.md)|     
| 15  |  [Python Type Hataları](./15_Day_Python_type_errors/15_python_type_errors.md)| 
| 16 |  [Python Tarih ve Saat](./16_Day_Python_date_time/16_python_datetime.md) |     
| 17 |  [İstisna İşleme](./17_Day_Exception_handling/17_exception_handling.md)|    
| 18 |  [Düzenli İfadeler](./18_Day_Regular_expressions/18_regular_expressions.md)|    
| 19 |  [Dosya Yönetimi](./19_Day_File_handling/19_file_handling.md)|
| 20 |  [Python Paket Yöneticisi](./20_Day_Python_package_manager/20_python_package_manager.md)|
| 21 |  [Sınıflar and Objeler](./21_Day_Classes_and_objects/21_classes_and_objects.md)|
| 22 |  [Web Scraping](./22_Day_Web_scraping/22_web_scraping.md)|
| 23 |  [Sanal Çevre](./23_Day_Virtual_environment/23_virtual_environment.md)|
| 24 |  [İstatistikler](./24_Day_Statistics/24_statistics.md)|
| 25 |  [Pandas](./25_Day_Pandas/25_pandas.md)|
| 26 |  [Python web](./26_Day_Python_web/26_python_web.md)|
| 27 |  [MongoDB ile Python](./27_Day_Python_with_mongodb/27_python_with_mongodb.md)|
| 28 |  [API](./28_Day_API/28_API.md)|
| 29 |  [API Yaratma](./29_Day_Building_API/29_building_API.md)|
| 30 |  [Sonuçlar](./30_Day_Conclusions/30_conclusions.md)|

🧡🧡🧡 Mutlu Kodlamalar 🧡🧡🧡


<div align="center">
  <h1> 30 Günde Python: Gün 1 - Giriş</h1>
  <a class="header-badge" target="_blank" href="https://www.linkedin.com/in/asabeneh/">
  <img src="https://img.shields.io/badge/style--5eba00.svg?label=LinkedIn&logo=linkedin&style=social">
  </a>
  <a class="header-badge" target="_blank" href="https://twitter.com/Asabeneh">
  <img alt="Twitter Follow" src="https://img.shields.io/twitter/follow/asabeneh?style=social">
  </a>

  <sub>Yazar:
  <a href="https://www.linkedin.com/in/asabeneh/" target="_blank">Asabeneh Yetayeh</a>
  <sub>Çeviren:
  <a href="https://www.linkedin.com/in/hamza-efe-%C5%9F-018178213/" target="_blank">Hamza Efe Şahinbaş</a><br>
  <small> Son Düzenleme: Temmuz, 2021</small>
  </sub>
</div>


[Gün 2 >>](./02_Day_Variables_builtin_functions/02_variables_builtin_functions.md)

![30DaysOfPython](./images/30DaysOfPython_banner3@2x.png)

- [🐍 30 Günde Python](#-30-days-of-python)
- [📘 Gün 1](#-day-1)
  - [Hoş Geldiniz](#welcome)
  - [Giriş](#introduction)
  - [Neden Python ?](#why-python-)
  - [Ortam Kurulumu](#environment-setup)
    - [Python Kurulumu](#installing-python)
    - [Python Shell](#python-shell)
    - [Visual Studio Code Kurulumu](#installing-visual-studio-code)
      - [Visual Studio Code Nasıl Kullanılır?](#how-to-use-visual-studio-code)
  - [Temel Python](#basic-python)
    - [Python Syntax](#python-syntax)
    - [Python Girintisi](#python-indentation)
    - [Yorumlar](#comments)
    - [Data Türleri](#data-types)
      - [Numaralar](#number)
      - [String'ler](#string)
      - [Boolean'ler](#booleans)
      - [List](#list)
      - [Dictionary](#dictionary)
      - [Tuple](#tuple)
      - [Set](#set)
    - [Data Türlerini Kontrol Etme](#checking-data-types)
    - [Python Dosyaları](#python-file)
  - [💻 Egzersiz - Gün 1](#-exercises---day-1)
    - [Egzersiz: Level 1](#exercise-level-1)
    - [Egzersiz: Level 2](#exercise-level-2)
    - [Egzersiz: Level 3](#exercise-level-3)

# 📘 Gün 1

## Hoş Geldiniz

30 Günde python kodlama meydan okumasına başlamaya karar verdiğiniz için **başarılar**. Bu meydan okumada programlamanın tüm konseptini ve python kodlama için gereken her şeyi öğreneceksin . Bu meydan okumanın sonunda "_30DaysOfPython_ programming challenge" sertifikasını alacaksın.

Meydan okumaya aktif olarak katılmak istiyorsanız,[30DaysOfPython challenge](https://t.me/ThirtyDaysOfPython) telegram grubumuza katılabilirsiniz.  

## Giriş

Python Genel amaçlı kodlama için üst düzey bir programlama dilidir. Açık kaynak kodlu, yorumlanmış, nesne yönelimli bir programlama dilidir.  Python Holalndalı yazılımcılar tarafından oluşturulmultur, Guido van Rossum. Python programlama dilinin adı, bir İngiliz eskiz komedi dizisinden türetilmiştir, *Month Python's Flying Circus*. İlk versiyonu 20 Şubat 1991'de yayınlandı.Bu "30 Günde Python" meydan okuması Pytho'nun son sürümünü öğrenmeniz için yardımcı olacaktır, adım adım Python 3. Konular 30 güne bölünmüştür. Her gün, anlaşılması kolay açıklamalar, gerçek dünyadan örnekler, birçok uygulamalı alıştırmalar ve projeler içeren birkaç konu içerir.

Bu meydan okuma python kodlama öğrenmek istiyen, yeni başlayanlar ve profesyoneller için tasarlandı . Bu meydan okumayı bitirmek 30 ila 100 gün sürebilir. Telgram grubuna aktif olarak katılan kişilerin görevi tamamlama olasılığı yüksektir.
Sanal bir öğrenciyseniz ve ya videolarla öğrenen biri iseniz, bununla başlaya bilirsiniz [Yeni başlayanlar için Python](https://www.youtube.com/watch?v=11OYpBrhdyM).

## Neden Python ?

İnsan diline yakın olan programlama dili ve öğrenmesi ve kullanması kolay bir dil.
Python çeşitli indüstiriler ve şirketler tarafınca kullanılıyor (Google'da dahil olmak üzere). Web uygulamarı, masaüstü uygulamalar, sistem yönetimi ve makine öğrenimi kütüphanelerini geliştirmek için kullanılmıştır. Python, veri bilimi ve makine öğrenimi topluluğunda oldukça benimsenen bir dildir. Umarım bu sizi python öğrenmek için teşvik edebilmiştir. Python Dünyayı yiyor ve seni yemeden önce onu öldürüyosun.

## Ortam kurulumları

### Python Kurma

Python script'ini çalıştırmak için pythonu kurman gerekir. Hadi  python'u [indirelim](https://www.python.org/).
Eğer windows kullanıcısı iseniz, kırmızı daire ile işaretli butona tıklayın.

[![Windows'da Kurulum](./images/installing_on_windows.png)](https://www.python.org/)

Eğer macOS kullanıcısı iseniz, kırmızı daire ile işaretli butona tıklayın.
 

[![Macos'da Kurulum](./images/installing_on_macOS.png)](https://www.python.org/)

Python'un kurulu olup olmadığını kontrol etmek için cihazınızın terminaline aşağıdaki komutu yazın. 
  
```shell
python --version
```

![Python Version](./images/python_versio.png)

Terminalde görebildiğin üzere, şu anda _Python 3.7.5_ kullanıyorum. Python sürümünüz benimkinden farklı olabilir ancak 3.6 veya üstü olmalıdır.Eğer python sürümünü görmeyi başardıysanız tebrikler python bilgisayarınızda kurulu. Diğer bölüme ilerleyin.

### Python Shell

Python yorumlanmış bir betik dilidir, yani derlenmesine gerek yok. Bu kodu satır satır yürüttüğü anlamına gelir. Python _Python Shell (Python Etkğleşimli Kabuk)_ ile beraber geliyor. Tek bir python komutunu çalıştırmak ve sonucu almak için kullanılır.

Python Shell kullanıcıdan python kodunu bekler. kodu girdiğiniz zaman, kodu yorumlar ve sonucu bir sonraki satırda gösterir.
Terminalinizi veya Komut İstemcisini(cmd) açın ve yazın :

```shell
python
```

![Python Scripting Shell](./images/opening_python_shell.png)

Python Etkileşimli Kabuğu açıldı ve sizin python kodu yazmanızı bekliyor (Python script).Bu >>> Sembolden sonra kodu yazmanızı ve sonra Enter'a basmanızı bekliyor.Hadi ilk kodumuzu Python Script Kabuğunda yazalım.

![Python script on Python shell](./images/adding_on_python_shell.png)

Tebrikler! Python Etkileşimli Kabuğundaki ilk kodunu yazdın. Peki python etkileşimli kabuğu nasıl kapatırız?
Kabuğu kapatmak için bu >> sembolden sonra **exit()** komudunu yazıp Enter'a basın.

![Exit from python shell](./images/exit_from_shell.png)

Şimdi Python Etkileşimli Kabuğu nasıl açıp kapatacağını öğrendin.
  
Eğer pythonun anlayacağı kodlar yazarsanız size sonuçlarını vericektir.Aksi takdirde size hata olarak geri dönecektri. Kasıtlı bir hata yapıp pythonun nasıl cevap verdiğini görelim

![Invalid Syntax Error](./images/invalid_syntax_error.png)

Gördüğünüz gibi bir hata olarak cevap verdi. Python o kadar zeki ki, yaptığımız hatayı ve hangisinin yanlış olduğunu biliyor _Syntax Error: invalid syntax_. Pythonda çarpma işleminde x'i kullanmak sözdizimi(syntax) hatası verir çünkü (x) pythonda geçerli bir syntax değildir. (**x**) in yerine biz çarpma işlemlerinde asterix kullanırız (*). Döndürülen hata, neyin düzeltileceğini açıkça gösterir.

Hataları tanımlayan ve kaldıran programa *debugging* denir.  **x** yerine * Koyarak hata ayıklayalım.

![Fixing Syntax Error](./images/fixing_syntax_error.png)

Hatamız düzeltildi. Kod çalıştı ve beklediğimiz sonucu aldık. Bir programcı olarak bu tür hataları günlük olarak göreceksiniz. Nasıl debug (hata ayıklama) yapıcağınızı bilmek iyidir. Debuging'de iyi olmak için ne tür hatalarla karşılaşacağınızı anlamak gekerikir. Karşılacağınız hatalardan bazıları *SyntaxError*, *IndexError*, *NameError*, *ModuleNotFoundError*, *KeyError*, *ImportError*, *AttributeError*, *TypeError*, *ValueError*, *ZeroDivisionError* vb. Sonra daha fazla **_error types_ (hata türleri)** göreceğin.

Python Etkileşimli Kabukda biraz pratik yapalım. Terminalinize veya Komut istemcisine gidip şunu yazın: **python**.

![Python Scripting Shell](./images/opening_python_shell.png)

Python Etkileşimli Kabuk açıldı. Bazı matematiksel işlemler yapalım (topama, çıkarma, çarpma, bölme, modüller,  üstlü).

Herhangi bir python kodu yazmadan önce biraz matematik işlemi yapalım:

- 2 + 3 = 5
- 3 - 2 = 1
- 3 \* 2 = 6
- 3 / 2 = 1.5
- 3 ^ 2 = 3 x 3 = 9

Pythonda aşşağıdaki ek işlemlere sahibiz:

- 3 % 2 = 1 => Kalanı bulmak anlamına gelir
- 3 // 2 = 1 => Kalanın kaldırılması anlamına gelir

Yukardaki matematiksel ifadeleri python koduna çevirelim.Python kabuğu açdık şimdi kabuğun başına açıklama yazalım.

Bir _yorum_ python tarafından yürütülmeyen bir kodun parçacığıdır. Yani biz kodumuzun daha okunaklı olması için bir kaç yazı biliriz. Python yorum satırını çalıştırmaz. Python'da bir yorum hash(#) sembolü ile başlar.
This is how you write a comment in python

```shell
 # yorumlar hash ile başlar
 # bu bir python yorumu bu yüzden (#) sembolu ile başlıyor.
```

![Maths on python shell](./images/maths_on_python_shell.png)

Bi sonraki kısma ilerlemeden önce Python Etkileşimli Kabuk'da pratik yapalım.Kabuğa _exit()_ yazarak açık olan kabuğu kapatalım ve Python kabuğuna nasıl metin yazılacağını öğrenelim.

![Writing String on python shell](./images/writing_string_on_shell.png)

### Visual Studio Code Kurulumu

Python Etkileşimli Kabuğu küçük kod parçacıklarını denemede ve test etmekde iyidir fakat büyük projeler için iyi olmayacaktır. Gerçek çalışma ortamında, geliştiriciler kod yazmak için farklı kod editörleri kullanır. 30 günde python kodlama meydan okumasında Visual studio code kullanacağız . Visual studio code açık kaynaklı popüler bit text editörüdür. Ben vscode'un fanıyım ve Visual studio code'u  [indirmenizi](https://code.visualstudio.com/) tavsiye ederim, fakat diğer editörlerden yanaysanız, sahip olduklarınızla takip etmekten çekinmeyin.

[![Visual Studio Code](./images/vscode.png)](https://code.visualstudio.com/)

Eğer visual studio code'u kurduysanız nasıl kullanacağımızı görelim,

Eğer videyou tercih ederseniz, Linkten Visual Studio Code for Python [Video eğtimine](https://www.youtube.com/watch?v=bn7Cx4z-vSo) ulaşabilirsiniz.

#### visual studio code'u nasıl kullanırız

visual studio iconuna çift tıklayarak açalım. Açtığınızda bu tür bir arayüz elde edeceksiniz. Etiketli simgelerle etkileşim kurmayı deneyin.

![Visual studio Code](./images/vscode_ui.png)

 30GundePython adında masaüstünüze bir klasor oluşturun. sonra visual studio code kullanarak onu açın.

![Opening Project on Visual studio](./images/how_to_open_project_on_vscode.png)

![Opening a project](./images/opening_project.png)

Açtıktan sonra, 30GundePython projesinin dizini içinde dosya ve klasör oluşturmak için kısayollar göreceksiniz. aşşağıda gördüğünüz gibi ilk dosyamı yarattım: helloworld.py . Aynısını yapabilirsiniz.

![Creating a python file](./images/helloworld.png)

Uzun bir kodlama gününden sonra kod editörünüzü kapatmak istiyorsunuz. Öyle değil mi? Açılan projeyi bu şekilde kapatacaksınız.

![Closing project](./images/closing_opened_project.png)

Tebrikler! Geliştirme ortamınız kurmayı bitirdiniz. hadi kod yazmaya geçelim.

## Temel Python

### Python Syntax (Sözdizimi)

Bir Python script'i Python Etkileşimli Kabukda veya kod editöründe yazılabilir.  Python dosyasının uzantısı .py'dir.


### Python Girintisi

Girintimiz beyaz bir boşluktur. Girintiler çoğu yazılım dilinde okunabiriliği arttırmak için kullanılır. Ancak Python kod bloğu oluşturmak için kullanır. Diğer programlama dillerinde Küme parantezleri  girinti yerine kod blokları oluşturmak için kullanır. Pythonda yaygın bir hata ise kod yazarken yanlış girinti kullanımıdır.

![Indentation Error](./images/indentation.png)

### Yorumlar

Yorumşar kodunuzunu okunabilir olması ve  notlar bırakmak için çok önemlidir. Python Yorum satırını çalıştırmaz.
hash(#) ile başlayan herhangi bir text yorum satırıdır.

**Örnek: Tek Satır Yorum**

```shell
    # İlk python yorumum
    # İkinci python yorumum
    # Python dünyayı yiyor
```

**Örnek: Çok Satırlı Yorumlar**

Eğer Bir değişkene atanmamışşsa Üçlü Alıntı(```) Çok satırlı yorumnlar için kullanılır
```shell
"""İlk çok satırlı yorumum
çok satırlı yorumlar çok satır kullanır.
python dünyayı yiyor
"""
```

### Data Türleri

Pythonda bir kaç veri türü vardır.Hadi en yaygın olanlarıyla başlayalım. Farlı data türlerini gelecek bölümlerde detaylı bir şekilde göreceğiz. Şu an için, Sadece farklı veri türlerini gözden geçirelim ve onlara aşina olalım. Şimdi net bir anlayışa sahip olmak zorunda değilsin.

#### Sayılar

- Integer: Sayılar(negativ, sıfır ve pozitiv) sayılar
    Örnek:
    ... -3, -2, -1, 0, 1, 2, 3 ...
- Float: ondalık sayılar
    Örnek:
    ... -3.5, -2.25, -1.0, 0.0, 1.1, 2.2, 3.5 ...
- Complex: karmaşık sayılar
    Örnek
    1 + j, 2 + 4j

#### String

Tek veya çift tırnak altında bir veya daha fazla karakterden oluşan koleksiyon. Eğer String bir cümleden fazlaysa üçlü alıntı kullanırız.

**Örnek:**

```py
'Efe'
'Türkiye'
'Python'
'Öğretmeyi severim'
'Umarım 30GundePYthon Meydan okumasının ilk gününde eğleniyorsunuzdur'
```

#### Booleans

Boolean veri türü, True veya False değeridir. T ve F her zaman büyük harf olmalıdır.

**Örnek:**

```python
    True  #  Işık açık mı? Açıksa, değer True'dur
    False #  Işık açık mı? Kapalıysa, Değer False'dır
```

#### List

Python list is an ordered collection which allows to store different data type items. A list is similar to an array in JavaScript.

**Example:**

```py
[0, 1, 2, 3, 4, 5]  # all are the same data types - a list of numbers
['Banana', 'Orange', 'Mango', 'Avocado'] # all the same data types - a list of strings (fruits)
['Finland','Estonia', 'Sweden','Norway'] # all the same data types - a list of strings (countries)
['Banana', 10, False, 9.81] # different data types in the list - string, integer, boolean and float
```

#### Dictionary

A Python dictionary object is an unordered collection of data in a key value pair format. 

**Example:**

```py
{
'first_name':'Asabeneh',
'last_name':'Yetayeh',
'country':'Finland', 
'age':250, 
'is_married':True,
'skills':['JS', 'React', 'Node', 'Python']
}
```

#### Tuple

A tuple is an ordered collection of different data types like list but tuples can not be modified once they are created. They are immutable.

**Example:**

```py
('Asabeneh', 'Pawel', 'Brook', 'Abraham', 'Lidiya') # Names
```

```py
('Earth', 'Jupiter', 'Neptune', 'Mars', 'Venus', 'Saturn', 'Uranus', 'Mercury') # planets
```

#### Set

A set is a collection of data types similar to list and tuple. Unlike list and tuple, set is not an ordered collection of items. Like in Mathematics, set in Python stores only unique items.

In later sections, we will go in detail about each and every Python data type.

**Example:**

```py
{2, 4, 3, 5}
{3.14, 9.81, 2.7} # order is not important in set
```

### Checking Data types

To check the data type of certain data/variable we use the **type** function. In the following terminal you will see different python data types:

![Checking Data types](./images/checking_data_types.png)

### Python File

First open your project folder, 30DaysOfPython. If you don't have this folder, create a folder name called 30DaysOfPython. Inside this folder, create a file called helloworld.py. Now, let's do what we did on python interactive shell using visual studio code.

The Python interactive shell was printing without using **print** but on visual studio code to see our result we should use a built in function *print(). The *print()* built-in function takes one or more arguments as follows *print('arument1', 'argument2', 'argument3')*. See the examples below.

**Example:**

The file name is helloworld.py

```py
# Day 1 - 30DaysOfPython Challenge

print(2 + 3)             # addition(+)
print(3 - 1)             # subtraction(-)
print(2 * 3)             # multiplication(*)
print(3 / 2)             # division(/)
print(3 ** 2)            # exponential(**)
print(3 % 2)             # modulus(%)
print(3 // 2)            # Floor division operator(//)

# Checking data types
print(type(10))          # Int
print(type(3.14))        # Float
print(type(1 + 3j))      # Complex number
print(type('Asabeneh'))  # String
print(type([1, 2, 3]))   # List
print(type({'name':'Asabeneh'})) # Dictionary
print(type({9.8, 3.14, 2.7}))    # Set
print(type((9.8, 3.14, 2.7)))    # Tuple
```

To run the python file check the image below. You can run the python file either by running the green button on Visual Studio Code or by typing *python helloworld.py* in the terminal .

![Running python script](./images/running_python_script.png)

🌕  You are amazing. You have just completed day 1 challenge and you are on your way to greatness. Now do some exercises for your brain and muscles.

## 💻 Exercises - Day 1

### Exercise: Level 1

1. Check the python version you are using
2. Open the python interactive shell and do the following operations. The operands are 3 and 4.
   - addition(+)
   - subtraction(-)
   - multiplication(\*)
   - modulus(%)
   - division(/)
   - exponential(\*\*)
   - floor division operator(//)
3. Write strings on the python interactive shell. The strings are the following:
   - Your name
   - Your family name
   - Your country
   - I am enjoying 30 days of python
4. Check the data types of the following data:
   - 10
   - 9.8
   - 3.14
   - 4 - 4j
   - ['Asabeneh', 'Python', 'Finland']
   - Your name
   - Your family name
   - Your country

### Exercise: Level 2

1. Create a folder named day_1 inside 30DaysOfPython folder. Inside day_1 folder, create a python file helloworld.py and repeat questions 1, 2, 3 and 4. Remember to use _print()_ when you are working on a python file. Navigate to the directory where you have saved your file, and run it.

### Exercise: Level 3

1. Write an example for different Python data types such as Number(Integer, Float, Complex), String, Boolean, List, Tuple, Set and Dictionary.
2. Find an [Euclidian distance](https://en.wikipedia.org/wiki/Euclidean_distance#:~:text=In%20mathematics%2C%20the%20Euclidean%20distance,being%20called%20the%20Pythagorean%20distance.) between (2, 3) and (10, 8)

🎉 CONGRATULATIONS ! 🎉

[Day 2 >>](./02_Day_Variables_builtin_functions/02_variables_builtin_functions.md)
