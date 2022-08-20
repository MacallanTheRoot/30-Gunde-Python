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

Python list, farklı veri türü öğelerini depolamaya izin veren sıralı bir koleksiyondur. Bir list JavaScript içindeki diziye benzer.

**Örnek:**

```py
[0, 1, 2, 3, 4, 5]  # hepsi aynı data türü - sayıların bir listesi
['Muz', 'Portakal', 'Mango', 'Avokado'] # hepsi aynı data türü - (Meyvelerin) bir listesi
['Türkiye','Estonya', 'İsveç','Norveç'] # hepsi aynı data türü - String'lerin bir listesi (Ülkeler)
['Muz', 10, False, 9.81] # different data types in the list - string, sayı, boolean ve float
```

#### Dictionary

Python sözlük nesnesi, bir anahtar değer çifti biçiminde sıralanmamış bir veri koleksiyonudur.
  
**Örnek:**

```py
{
'first_name':'Efe',
'last_name':'Şahinbaş',
'country':'Türkiye', 
'age':18, 
'is_married':False,
'skills':['JS', 'HTML', 'CSS', 'Python']
}
```

#### Tuple

Bir demet, list gibi farklı veri türlerinin sıralı bir koleksiyonudur, ancak demetler oluşturulduktan sonra değiştirilemez. Değişmezler.

**Örnek:**

```py
('Efe', 'Ege', 'Hüseyin', 'Ali',) # İsimler
```

```py
('Dünya', 'Jupiter', 'Neptune', 'Mars', 'Venus', 'Saturn', 'Uranus', 'Mercury') # Gezegenler
```

#### Set

Setler list ve tupe benzeyen data türleridir. List ve tuple'nin aksine, set sıralı bir ürün koleksiyonu değildir. Matematikte olduğu gibi, set Pythonda sadece benzersiz öğeleri toplar.

Sonraki bölümlerde, Her bir Python veri türü hakkında ayrıntılı olarak gideceğiz.

**Örnek:**

```py
{2, 4, 3, 5}
{3.14, 9.81, 2.7} # sette sıra önemli değildir
```

### Data Türlerini Kontrol Etmek

Belirli verilerin/değişkenlerin veri türünü kontrol etmek için **type** işlevini kullanırız. Aşağıdaki terminalde farklı python veri türleri göreceksiniz:

![Checking Data types](./images/checking_data_types.png)

### Python Dosyası

Proje dosyanızı ilk açtığınızda, 30GundePython. Eğer bu dosyadan yoksa, 30GundePython adlı bir klasör oluşturun. klasorün içine helloworld.py adlı bir dosya oluşturun. Şimdi, Visual stüdyo kodunu kullanarak python interaktif kabuğunda yaptığımızı yapalım.

T
@MacallanTheRoot
Commit changes
Commit summary
Optional extended description
Commit directly to the master branch.
Create a new branch for this commit and start a pull request. Learn more about pull requests.
Footer
© 2022 GitHub, Inc.
Footer navigation

    Terms
    Privacy
    Security
    Status
    Docs
    Contact GitHub
    Pricing
    API
    Training
    Blog
    About

You have no unread notifications

Python etkileşimli kabuğu **print** kullanmadan yazdırıyordu, ancak sonucumuzu görmek için görsel stüdyo kodunda yerleşik bir *print() işlevi kullanmalıyız. *print()* yerleşik işlevi aşağıdaki gibi bir veya daha fazla argüman alır *print('argument1', 'argument2', 'argument3')*. Aşağıdaki örneklere bakın.

**Örnek:**

Dosya ismi: helloworld.py

```py
#Gün 1 - 30GundePython Meydan Okuması

print(2 + 3)             # Toplama(+)
print(3 - 1)             # Çıkarma(-)
print(2 * 3)             # Çarpma(*)
print(3 / 2)             # Bölme(/)
print(3 ** 2)            # Üstünü Alma(**)
print(3 % 2)             # Modül (%)
print(3 // 2)            # Ondalık operatörü(//)

# Data türlerini Kontrol Etmek
print(type(10))          # Int (sayı)
print(type(3.14))        # Float
print(type(1 + 3j))      # Complex number (karışık sayı)
print(type('Asabeneh'))  # String (dizi)
print(type([1, 2, 3]))   # List 
print(type({'name':'Asabeneh'})) # Dictionary (Sözlük)
print(type({9.8, 3.14, 2.7}))    # Set 
print(type((9.8, 3.14, 2.7)))    # Tuple
```

Python dosyasını çalıştırmak için aşağıdaki resmi kontrol edin. Python dosyasını Visual Studio Code üzerinde yeşil butonu çalıştırarak veya terminalde *python helloworld.py* yazarak çalıştırabilirsiniz. 
  
![Running python script](./images/running_python_script.png)

🌕  Efsanesin. 1. gün mücadelesini yeni tamamladınız ve mükemmellik yolundasınız. Şimdi beyniniz ve kaslarınız için bazı egzersizler yapın. 
## 💻 Egzersiz - Day 1

### Egzersiz: Level 1

1. Kullanıdığınız python versiyonunu kontrol edin.
 
2. Python etkileşimli kabuğunu açın ve aşağıdaki işlemleri yapın. Sayıları 3 ve 4 olarak alın.
   - addition(+)
   - subtraction(-)
   - multiplication(\*)
   - modulus(%)
   - division(/)
   - exponential(\*\*)
   - floor division operator(//)
  
3. Python etkileşimli kabuğuna dizeler yazın. Dizeler aşağıdaki gibidir:
   - İsmin
   - Soy ismin
   - Ülken
   - 30 Günde Python'dan Keyif Alıyorum
  
4. Bu dataları kontrol edin:
   - 10
   - 9.8
   - 3.14
   - 4 - 4j
   - ['Efe', 'Python', 'Türkiye']
   - İsmin
   - Soy ismin
   - Ülken

### Egzersiz: Level 2

1. 30GundePython klasörü içinde gun_1 adında bir klasör oluşturun. gun_1 klasörü içinde bir python dosyası helloworld.py oluşturun ve 1, 2, 3 ve 4. soruları tekrarlayın. Bir python dosyası üzerinde çalışırken _print()_ kullanmayı unutmayın. Dosyanızı kaydettiğiniz dizine gidin ve çalıştırın.

### Egzersiz: Level 3

1. Number(Integer, Float, Complex), String, Boolean, List, Tuple, Set ve Dictionary gibi farklı Python veri türleri için bir örnek yazın. 
 
2. [Öklid Uzaklığını](https://tr.wikipedia.org/wiki/%C3%96klid_uzakl%C4%B1%C4%9F%C4%B1) (2, 3) ve (10, 8) arasında bulun

🎉 TEBRİKLER ! 🎉

[Gün 2 >>](./02_Day_Variables_builtin_functions/02_variables_builtin_functions.md)
