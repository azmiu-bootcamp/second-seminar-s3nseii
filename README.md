İkinci seminarın tapşırıqları aşağdakılardır:

1. n ədədin rəqəmlərinin cəmini hesablayan proqram yazın.
Məsələn n = 3451. Onda cavab 13 olsun.

2. 1-dən 100 -ə qədər olan hər hansı bir n ədədi daxil edirəm. Həmin ədədi sözlərlə ifadə etmək üçün proqram yazın
Məsələn n = 45. Onda cavab qırx beş olsun.

3. Zəngli saat proqramı qurun. Proqramın məntiqi aşağdakı kimidir:
İki dəyişənimiz var:
 - day (həftənin günü)
 - vocation (həmin günün tətil olub olmamağı).
**day(Günü)** dəyişənini belə daxil edirsiniz:
0 = Sunday, 1 = Monday, 2 = Tuesday, 3 = Wednesday, 4 = Thursday, 5 = Friday, 6 = Saturday
vocation dəyişənini belə daxil edirsiniz:
True yəni tətildir, False tətil deyil

Nəticə olaraq siz zəngli saatı aşağdakı kimi proqramlaşdırmalsızınız.
Əgər həftə içidirsə onda zəngli saat 07:00 - da işə düşsün, əgər həftə sonudursa onda 10:00-da işə düşsün. Əgər həm də tətildirsə zəngli saat həftə içi 10:00-da həftə sonu isə işə düşməsin (off olsun).

Programın əvvəli belədir.

**day = int(input()) # 0-dan 6 -ya qədər ədəd daxil edin** <br>
**vocation = input() # True və ya False daxil edin. Burada bool(input()) yazmağa ehtiyac yoxdur**<br>


**# davamı....**
