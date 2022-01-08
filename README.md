# Strings 💻

## Task 1 🎯

### Tənbəl Mişa

<img src="https://static.e-olymp.com/content/e0/e012bb1a52365737631c9929086a323293b92df8.jpg"/>

Mişa uşaqlarla futbol oynamaq qərarına gəldi və evdən çixmağa hazırlaşırdı ki, bu zaman anası onu yaxaladı və dedi ki, nə qədər ki, Mişa ona ev işlərində kömək etməsə, futbol oynamağa getməyəcək. Seçim üçün anası Mişaya üç işdən birini görməsini təklif etdi: ya qabları yumalı, ya tozsoran ilə mənzili təmizləməli, ya da anası dükana gedənə qədər kiçik bacısı Mariya ilə oynamalı. Mişa hər bir işin nə qədər vaxt alacağını hesabladı:

- Qabların yuyulmasına t1 saniyə
- Mənzilin tozsoran ilə təmizlənməsinə t2 saniyə
- Mariya ilə oynamaq t3 saniyə vaxt alacaq


Aydındır ki, Mişa ən az vaxt alacaq işi seçir. Sizin proqram Mişanın anasının tapşırığını yerinə yetirməsi üçün minimal vaxtı hesablamalıdır.

### Input
Üç tam ədəd: t1, t2, t3 (1 ≤ t1, t2, t3 ≤ 1000).
### Output
Anasının tapşırığını yerinə yetirmək üçün Mişaya lazım olan minimal vaxtı verməli.

:clock2: Time limit 1 second

:floppy_disk: Memory limit 128 MiB

#### Input example 1 

    31 15 40

#### Output example 1

    15
    

---

## Task 2 🎯

### Birinci, yoxsa axırıncı?

Üçrəqəmli ədəd verilmişdir. Onun rəqəmlərindən hansının - birincinin, yoxsa axırıncının böyük olduğunu müəyyənləşdirin.


### Input
Yeganə sətirdə üçrəqəmli ədəd verilir.

### Output
Çıxışa göstərilən rəqəmlərdən böyüyünü verin. Onlar bərabər olduqda "=" işarəsini (dırnaqsız) verin.

:clock2: Time limit 1 second

:floppy_disk: Memory limit 128 MiB

#### Input example 1 

    328

#### Output example 1

    8
    
#### Input example 2

    832

#### Output example 2

    8
    
---

## Task 3 🎯

### Qiymətlər
Pənah məktəbdə yalnız iki və beş qiymətlər alır. Hansı qiymətin daha çox olduğunu təyin edin.


### Input
Tək sətirdə Pənahın qiymətləri verilir. Məlumdur ki, Pənah yalnız iki və beş qiymətlər alır, qiymətlər boşluqsuz verilib və onların sayı 1000-i aşmır.

### Output
Beşlərin sayı ikilərin sayından çoxdursa, 5 çap edin. İkilərin sayı beşlərin sayından çoxdursa, 2 çap edin. Əgər ikilərin sayı beşlərin sayına bərabərdirsə, '=' simvolunu çap edin.

:clock2: Time limit 1 second

:floppy_disk: Memory limit 128 MiB

#### Input example 1 

    255222

#### Output example 1

    2
    
#### Input example 2

    555522

#### Output example 2

    5
    
#### Input example 3

    525522

#### Output example 3

    =
    
---

## Task 4 🎯

### Cümlələrin sayı
Verilmiş mətn fraqmentində cümlələrin sayını müəyyənləşdirin.

### Input
Yeganə sətirdə ingilis dilində simvollarının sayı 250-ni aşmayan mətn fraqmenti verilir. Zəmanət verilir ki, mətndə tire, defis, rəqəm və ədəd yoxdur.

### Output
Yeganə ədəd - fraqmentdə cümlələrin sayı.

:clock2: Time limit 1 second

:floppy_disk: Memory limit 128 MiB

#### Input example 1 

    Hello world!

#### Output example 1

    1
    
#### Input example 2

    Hi!!!

#### Output example 2

    1
    
---

## Task 5 🎯

### Əməllərin sayı
Verilmiş hesabi ifadədə toplama (+), çıxma (-) və vurma (*) əməllərinin ümumi sayını müəyyənləşdirin.

### Input
Yeganə sətirdə mötərizə və boşluq işarəsi olmayan hesabi ifadə verilir. İfadədə simvolların sayı 250-ni aşmır.

### Output
Yeganə ədəd - göstərilən əməllərin sayı.

:clock2: Time limit 1 second

:floppy_disk: Memory limit 128 MiB

#### Input example 1 

    -1+2*3+a

#### Output example 1

    3
    
#### Input example 2

    +5-2+4-m/n*2:4

#### Output example 2

    4
    
---

## Task 6 🎯

### Sözlərin sayı
Verilmiş mətn fraqmentində sözlərin sayını müəyyənləşdirin.

### Input
Yeganə sətirdə ingilis dilində simvollarının sayı 250-ni aşmayan mətn fraqmenti verilir. Zəmanət verilir ki, mətndə tire, defis, rəqəm və ədəd yoxdur.

### Output
Yeganə ədəd - fraqmentdə sözlərin sayı.

:clock2: Time limit 1 second

:floppy_disk: Memory limit 128 MiB

#### Input example 1 

    Hello world!

#### Output example 1

    2
    
#### Input example 2

     Hello world! Hello,    country!

#### Output example 2

    4
    
---

## Task 7 🎯

### Sleeping cars
A train contains sleeping cars, marked with letter k, and sitting cars, marked with letter p. Find the biggest number of sleeping cars that follow each other in the train.

### Input
One line contains a sequence of letters k and p, with length from 1 to 1000 characters.

### Output
Print the maximum number of seeping cars that follow each other.

:clock2: Time limit 1 second

:floppy_disk: Memory limit 128 MiB

#### Input example 1 

    kpkkp

#### Output example 1

    2
    
---

## Task 8 🎯

### Baş hərfli sözlər sətri
Mətnlərin emalına aid sadə məsələlərdən biri sətirdəki hər bir sözün birinci hərfini baş hərfə çevirməkdir. Bir və ya bir neçə boşluqla ayrılmış kiçik hərflərdən ibarət sətir verilmişdir. Eyni sətri, hər sözün birinci hərfini baş hərfə çevirərək çap edin.

### Input
Bir və ya bir neçə boşluqla ayrılmış, 'a' - 'z' diapazonunda kiçik latın hərflər verilir. Sətrin uzunluğu 50 simvolu aşmır.

### Output
Eyni sətri, hər sözün birinci hərfini baş hərfə çevirərək çap edin.

:clock2: Time limit 1 second

:floppy_disk: Memory limit 128 MiB

#### Input example 1 

    introduction to algorithms

#### Output example 1

    Introduction To Algorithms

    
---

## Task 9 🎯

### Hərfləri saymalı
s sətri və c hərfi verilmişdir. Bu hərfə sətirdə neçə dəfə rast gəlinir?

### Input
İlk sətirdə uzunluğu 100 simvolu aşmayan s sətri verilir. İkinci sətirdə kicik c latın hərfi verilir.

### Output
c hərfinin s sətrində rast gəlmə sayını çap edin. Baş və kiçik hərf eyni sayılır. Yəni 'a' və 'A' eyni hərflərdir.

:clock2: Time limit 1 second

:floppy_disk: Memory limit 128 MiB

#### Input example 1 

    Programming Principles 1
    p


#### Output example 1

    3
    
    
#### Input example 2

    This is a cat sitting on a table
    t



#### Output example 2

    5
---

## Task 10 🎯

### Boşluqların indeksləri
Verilmiş sətirdə birinci və sonuncu boşluq işarəsinin indekslərini çap edin. Nəzərə alın ki, sətrin ilk simvolunun indeksi 0-dan başlayır.

### Input
Latın hərfləri, durğu işarələri və boşluqlardan ibarət tək sətir.

### Output
İlk və sonuncu boşluğun indekslərini çap edin. Sətirdə boşluq yoxdursa, -1 çap edin.

:clock2: Time limit 1 second

:floppy_disk: Memory limit 128 MiB

#### Input example 1 

    I am programming on Python.

#### Output example 1

    1 19
    
    
#### Input example 2

    abrakadabra


#### Output example 2

    -1
---

## Task 11 🎯

### Boşluqların indeksləri
Verilmiş sətirdə birinci və sonuncu boşluq işarəsinin indekslərini çap edin. Nəzərə alın ki, sətrin ilk simvolunun indeksi 0-dan başlayır.

### Input
Latın hərfləri, durğu işarələri və boşluqlardan ibarət tək sətir.

### Output
İlk və sonuncu boşluğun indekslərini çap edin. Sətirdə boşluq yoxdursa, -1 çap edin.

:clock2: Time limit 1 second

:floppy_disk: Memory limit 128 MiB

#### Input example 1 

    I am programming on Python.

#### Output example 1

    1 19
    
    
#### Input example 2

    abrakadabra


#### Output example 2

    -1
---
