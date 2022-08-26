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

Let us print and also find the length of the variables declared at the top:

**Example:**

```py
# Printing the values stored in the variables

print('First name:', first_name)
print('First name length:', len(first_name))
print('Last name: ', last_name)
print('Last name length: ', len(last_name))
print('Country: ', country)
print('City: ', city)
print('Age: ', age)
print('Married: ', is_married)
print('Skills: ', skills)
print('Person information: ', person_info)
```

### Declaring Multiple Variable in a Line

Multiple variables can also be declared in one line:

**Example:**

```py
first_name, last_name, country, age, is_married = 'Asabeneh', 'Yetayeh', 'Helsink', 250, True

print(first_name, last_name, country, age, is_married)
print('First name:', first_name)
print('Last name: ', last_name)
print('Country: ', country)
print('Age: ', age)
print('Married: ', is_married)
```

Getting user input using the _input()_ built-in function. Let us assign the data we get from a user into first_name and age variables.
**Example:**

```py
first_name = input('What is your name: ')
age = input('How old are you? ')

print(first_name)
print(age)
```

## Data Types

There are several data types in Python. To identify the data type we use the _type_ built-in function. I would like to ask you to focus on understanding different data types very well. When it comes to programming, it is all about data types. I introduced data types at the very beginning and it comes again, because every topic is related to data types. We will cover data types in more detail in their respective sections.

## Checking Data types and Casting

- Check Data types: To check the data type of certain data/variable we use the _type_
  **Example:**

```py
# Different python data types
# Let's declare variables with various data types

first_name = 'Asabeneh'     # str
last_name = 'Yetayeh'       # str
country = 'Finland'         # str
city= 'Helsinki'            # str
age = 250                   # int, it is not my real age, don't worry about it

# Printing out types
print(type('Asabeneh'))     # str
print(type(first_name))     # str
print(type(10))             # int
print(type(3.14))           # float
print(type(1 + 1j))         # complex
print(type(True))           # bool
print(type([1, 2, 3, 4]))     # list
print(type({'name':'Asabeneh','age':250, 'is_married':250}))    # dict
print(type((1,2)))                                              # tuple
print(type(zip([1,2],[3,4])))                                   # set
```

- Casting: Converting one data type to another data type. We use _int()_, _float()_, _str()_, _list_, _set_
  When we do arithmetic operations string numbers should be first converted to int or float otherwise it will return an error. If we concatenate a number with a string, the number should be first converted to a string. We will talk about concatenation in String section.

  **Example:**

```py
# int to float
num_int = 10
print('num_int',num_int)         # 10
num_float = float(num_int)
print('num_float:', num_float)   # 10.0

# float to int
gravity = 9.81
print(int(gravity))             # 9

# int to str
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

## Numbers

Number data types in Python:

1. Integers: Integer(negative, zero and positive) numbers
   Example:
   ... -3, -2, -1, 0, 1, 2, 3 ...

2. Floating Point Numbers(Decimal numbers)
   Example:
   ... -3.5, -2.25, -1.0, 0.0, 1.1, 2.2, 3.5 ...

3. Complex Numbers
   Example:
   1 + j, 2 + 4j, 1 - 1j

🌕 You are awesome. You have just completed day 2 challenges and you are two steps ahead on your way to greatness. Now do some exercises for your brain and muscles.

## 💻 Exercises - Day 2

### Exercises: Level 1

1. Inside 30DaysOfPython create a folder called day_2. Inside this folder create a file named variables.py
2. Write a python comment saying 'Day 2: 30 Days of python programming'
3. Declare a first name variable and assign a value to it
4. Declare a last name variable and assign a value to it
5. Declare a full name variable and assign a value to it
6. Declare a country variable and assign a value to it
7. Declare a city variable and assign a value to it
8. Declare an age variable and assign a value to it
9. Declare a year variable and assign a value to it
10. Declare a variable is_married and assign a value to it
11. Declare a variable is_true and assign a value to it
12. Declare a variable is_light_on and assign a value to it
13. Declare multiple variable on one line

### Exercises: Level 2

1. Check the data type of all your variables using type() built-in function
1. Using the _len()_ built-in function, find the length of your first name
1. Compare the length of your first name and your last name
1. Declare 5 as num_one and 4 as num_two
    1. Add num_one and num_two and assign the value to a variable total
    2. Subtract num_two from num_one and assign the value to a variable diff
    3. Multiply num_two and num_one and assign the value to a variable product
    4. Divide num_one by num_two and assign the value to a variable division
    5. Use modulus division to find num_two divided by num_one and assign the value to a variable remainder
    6. Calculate num_one to the power of num_two and assign the value to a variable exp
    7. Find floor division of num_one by num_two and assign the value to a variable floor_division
1. The radius of a circle is 30 meters.
    1. Calculate the area of a circle and assign the value to a variable name of _area_of_circle_
    2. Calculate the circumference of a circle and assign the value to a variable name of _circum_of_circle_
    3. Take radius as user input and calculate the area.
1. Use the built-in input function to get first name, last name, country and age from a user and store the value to their corresponding variable names
1. Run help('keywords') in Python shell or in your file to check for the Python reserved words or keywords

🎉 CONGRATULATIONS ! 🎉

[<< Day 1](../readme.md) | [Day 3 >>](../03_Day_Operators/03_operators.md)
