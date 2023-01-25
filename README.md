# Подорож до Стародавнього Єгипту

#### Опис

{% hint style="success" %}
Вирушаймо в подорож Стародавнім світом! Першою зупинкою буде Стародавній Єгипет.&#x20;

Сьогодні ми дізнаємося все про систему координат у Minecraft і навчимося визначати своє місце у просторі за допомогою координат. Навчимося використовувати систему координат та за її допомогою будувати різні елементи відносно гравця. А ще — зробимо футбольне поле у Стародавньому Єгипті!
{% endhint %}

## Згадаймо🤔

1. Як створити квадрат потрібного розміру?&#x20;
2. Як розрахувати периметр та площу фігури?&#x20;
3. Чи для будь-якої фігури можливо розрахувати площу?

### Сьогодні ми:

1. Дізнаємося про систему координат в Minecraft.&#x20;
2. Навчимося створювати елементи за допомогою відносних координат.&#x20;
3. Самостійно прокладемо лінію з блоків із використанням відносних координат.&#x20;
4. Створимо квадрати та прямокутники з використанням відносних координат.&#x20;
5. Створимо футбольне поле та прапори різних країн.

> **Усі ці навички обов'язково знадобляться під час виконання вашого проєкту!**

### **Теорія**

**Координати** — це сукупність значень, що утворює систему координат, призначену для визначення місця розташування об'єктів в ігровому світі.

{% hint style="info" %}
**Система координат** — спосіб визначати положення та переміщення точки чи тіла за допомогою чисел або інших символів.
{% endhint %}

У Minecraft використовується тривимірна система координат, осі якої позначені як X, Y і Z. Осі Z і X відміряють горизонтальні напрямки, Y відміряє вертикальний напрямок (висота).&#x20;

Точка з координатами x=0, z=0, y=0 (точка) є початком відліку, у якому перетинаються три взаємно перпендикулярні осі.

![](<.gitbook/assets/image (14).png>)

![](.gitbook/assets/Координати.png)

Під час створення світу (а також після його створення) в налаштуваннях можна ввімкнути відображення координат:

![](<.gitbook/assets/image (20).png>)

Після увімкнення ми отримаємо відображення координат:

![](<.gitbook/assets/image (15).png>)

Ми бачимо три числа через кому. За замовчуванням гравець перебуває в точці з координатами (0; 4; 0).

Тобто це означає, що гравець перебуває в точці, у якій перша координата (X-координата) і третя координата (Z-координата) дорівнюють нулю. X- і Z-координати демонструватимуть напрямок руху вперед-назад (північ-південь) і вправо-вліво (захід-схід).

![](<.gitbook/assets/image (7).png>)



Кожна вісь має **додатний і від'ємний** напрямок. Додатні напрямки:

* Для осі X — схід
* Для осі Y — верх карти (висота)
* Для осі  Z — південь

Від'ємні напрямки (знак "-" перед числом):

* Для осі X — захід
* Для осі Y — низ карти (глибина)
* Для осі Z — північ

![](<.gitbook/assets/image (4).png>)

![](.gitbook/assets/telegram-cloud-photo-size-2-5420482988409470280-y.jpg)

### Потренуємося

| Завдання               | Код                                                                                                                                                                                                                                    |
| ---------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Насипаємо кругом пісок | ![](https://lh5.googleusercontent.com/G1SEBuxCEDZSbCwandl4PmdJjlLAyTVspxZsPSjEXlLWg8uRN4r4VxiQB5yWJJZ3lPETrjbRhGeDJyo3ust3Jz9j-1UYNmRioQHB269UJgI8nRBTETmGW-Y\_U90Hja6uo9ULyP0dF1ke0xieZa73aSL--xG61MTkg-F9nqXfBw7uvDqF7ANiwQutiQQO)   |
| Чистимо простір        | ![](https://lh6.googleusercontent.com/0ADq1uShcHYHfFE8OG-WTEemqPchMpXLtsGqE7GVERFcP64sSzxGL\_9s2TwECTukEeQ4l20gWpKqWwsiwKGGx\_32K3DyI18FShta5lnyQTymEQ3Wd-k-6ElCv9bvQXOcFY5WlUBVpSeFxSmECALxMfHiswX2cd5hdtKO3lByJAcHUyUw8cNinaPz4DK4)  |
| Тільки під ногами      | ![](https://lh5.googleusercontent.com/Wcw1CEFys3EjNeYtiNGtUDdPL7hsOi-2O5w1gy7k-xqclnHVSk1YFR0CizjR0\_ZHtNGwQ8qNXAe2f26BV4FvMstj9kyAfkSIJdLRvQwiLTubgL1YQmnS52HZM51djYrM3f3L3htywWsW5sZKIIPhs6g8XJTdvE4iRxmv2kELocOQQbYlMwVoPk5mzj42)   |
| Побудуємо стіну        | ![](https://lh3.googleusercontent.com/V6HxN3ksEW9kn\_kkHUllUOErONUYuycZcUzaZNldN2A\_Plw\_x4gTQdt2sxwTSMPbUalixT8tPC-kjFRLWnwR6Dju5GBMUiLmxw-f07M2CtmRP9s4cnC80CRJjF5T86WVbHVhz0ZK1BsEtUwCbYaOa0ZwzEB3UZ20D4F1xyhvJpIzZm57osLKrMjzrSZ7) |

## **МегаСтрибок**

<figure><img src="https://lh4.googleusercontent.com/8x25zHY1ZE8xzQ7BBU6795OpEKTAfJuwlnWvutWqFHYEsvIrSJl2WmyZXDyF8DbBOMppiSJzuAn21eTeg0UfUcw6K-HLQI-1ztCkQCj_cA7lQKv45Hu2fBuJPiaKTe_DnbddUpACrvewhe8M5ZAoMfwgxpO8rgXPHG0TuxLDe5FB2upzb6BPSsjcqR-t" alt=""><figcaption></figcaption></figure>

## Основні завдання

{% hint style="info" %}
Уявімо, що ми з вами потрапили у Стародавній Єгипет, який славиться своїми пірамідами. Їхнім будівництвом займалися тисячі людей, але завжди будь-яка піраміда починалась із одного блоку. Навчаймося їх будувати, щоб надалі створити власну піраміду!
{% endhint %}

Minecraft має спеціальну команду «Заповнити блоками», яка дозволяє ставити блоки по координатах. Координати прокладаються за допомогою відносних координат (де мають бути розміщені блоки відносно гравця).

| **Назва**     | **Блоки**                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| ------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Завдання**  | <ol><li>Прокладіть лінію з <strong>6 блоків піщаника</strong> від координати (~0;~0;~0) до координати (~5;~0;~0)</li><li>Прокладіть лінію з <strong>6 блоків граніту</strong> від координати (~0;~0;~0) до координати (~5;~0;~0)</li><li>Прокладіть лінію з <strong>5 блоків глини</strong> від координати (~0;~0;~1) до координати (~0;~0;~5)</li><li>Прокладіть лінію з <strong>5 блоків цегли</strong> від координати (~0;~0;~1) до координати (~0;~0;~5)</li></ol> |
| **Код**       | ![](<.gitbook/assets/image (18).png>)                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| **Результат** | ![](<.gitbook/assets/image (21).png>)                                                                                                                                                                                                                                                                                                                                                                                                                                  |

Якщо в команду «Заповнити блоками» вводити координати зі зміною не по одному напрямку, а по двох, то отримаємо прямокутник. Потренуймося!

| **Назва**     | **Блоки**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| ------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Завдання**  | <ol><li>Створіть квадрат <strong>5 x 5</strong> з блоків <strong>піщаника</strong> від координати (~1;~0;~1) до координати (~5;~0;~5)</li><li>Створіть квадрат <strong>4 х 4</strong> з блоків <strong>граніту</strong> від координати (~1;~0;~1) до координати (~4;~0;~4)</li><li>Створіть квадрат <strong>6 х 6</strong> з блоків <strong>глини</strong> від координати (2;~0;~2) до координати (~7;~0;~7)</li><li>Створіть квадрат <strong>7 х 7</strong> з блоків <strong>цегли</strong> (координати оберіть свої).</li></ol> |
| **Код**       | ![](<.gitbook/assets/image (19).png>)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
| **Результат** | ![](<.gitbook/assets/image (13).png>)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |

{% hint style="success" %}
Якщо ви впорались із усіма основними завданнями, перейдіть до додаткового. Його виконання дозволить вам удосконалити набуті навички!
{% endhint %}

## Додаткове завдання

### Футбольне поле

{% hint style="info" %}
Учені вважають, що батьківщиною футболу є Стародавній Єгипет! Факт ігор із м'ячем підтверджується археологічними знахідками у гробницях, збудованих кілька тисячоліть тому. Під час розкопок було знайдено багато м'ячів, набитих папірусом, деревиною пальм та обтягнутих шкірою чи тканиною. Як виявилось, представники цивілізацій, що існували задовго до початку нашої ери, були не лише чудовими воїнами, скотарями та землеробами, а й відмінними спортсменами! Але вони не мали справжнього футбольного поля, відомого нам. Допоможімо давнім єгиптянам пограти у сучасний футбол та зробімо поле!
{% endhint %}

Спочатку ми зробимо розмітку футбольного поля, а далі розмістимо збоку поля прапори різних країн.

![](<.gitbook/assets/image (11).png>)

### Код для розмітки футбольного поля:

| Частина 1                             | Частина 2                             |
| ------------------------------------- | ------------------------------------- |
| ![](<.gitbook/assets/image (12).png>) | ![](<.gitbook/assets/image (8).png>)  |
| ![](<.gitbook/assets/image (10).png>) | ![](<.gitbook/assets/image (6).png>)  |
|                                       | ![](<.gitbook/assets/image (16).png>) |

### Прапори

{% hint style="info" %}
**Прапори в Minecraft** — це кілька різнокольорових прямокутників, які розміщуються поряд.
{% endhint %}

Для розрахунку координат прапора можна використовувати два способи:

1. Побудувати аналогійний елемент «вручну» та порахувати координати в самому Minecraft.&#x20;
2. Зробити схему майбутніх елементів у електронних таблицях (про них поговоримо докладніше).&#x20;

Координати, вказані після символу, звітують про положення гравця (це називається відносними координатами). Програма відраховує від гравця відстань та ставить блок у відповідне місце.

Перша координата – це координата по осі X (ширина), Y (висота), Z (довжина). На першому етапі ми будемо працювати тільки з X та Z (блоки розміщуватимуться на тій же висоті, на якій знаходиться гравець).

![](<.gitbook/assets/image (9).png>)![](<.gitbook/assets/image (17).png>)

Лівий нижній кут синьої частини українського прапора (синього прямокутника) знаходиться у точці (-5; -3), а правий верхній у точці (-4; 3). Відповідно до команди з розміщення блоків ми напишемо, що необхідно заповнити блоками простір від точки (-5; 0; -3) до точки (-4; 0; 3). Аналогійно розраховуються координати жовтої частини прапора.

| **Назва**     | **Линія блоків**                                                                                                              |
| ------------- | ----------------------------------------------------------------------------------------------------------------------------- |
| **Завдання**  | <ol><li>Прапор України</li><li>Прапор Польщі</li><li>Прапор Угорщині</li><li>Прапор Болгарії</li><li>Прапор Австрії</li></ol> |
| **Код**       | <p><img src=".gitbook/assets/image (2).png" alt=""><br><img src=".gitbook/assets/image (1).png" alt=""></p>                   |
| **Результат** | <p><img src=".gitbook/assets/image.png" alt=""><br><img src=".gitbook/assets/image (3).png" alt=""></p>                       |

## Творче завдання

З'єднайте створене футбольне поле та підготовлені прапори:

![](<.gitbook/assets/image (5).png>)

## Супертворче завдання

Поставте прапори на флагштоках.

## [**Ліхтар з використанням координат**](https://makecode.com/\_0LjY9W0tV5pD)

| Завдання  | Розмістіть ліхтарі на вежах з використанням координат                                                                                                                                                                                                                                                                                                                                                                                                                         |
| --------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Код       | ![](https://lh4.googleusercontent.com/bmb0P4C-GUJ9jLj7FymUhgevFNqY0HFZ18cSlym1PpgnBLCNcZ2e1rXv1rbidZKmiTpEPt4pUN8hc81quLGpNzXKfTYT741R7hzG-Ka8DXnjyffXDueUUGhhrZ6eYVBap9O0XBHff4F397f5zYmm1y2qZy-r\_ketfzCRfQQ2cb1bTbyJJr\_0-zcZnf7L)![](https://lh4.googleusercontent.com/n\_FAnoLCdCZvMVY8\_COlKwUcoX2VNH61FSd69JI7iACltbY4ZuRFf\_b9BfTBJy-XtJjTi\_gta3di7RIVIHEUm2AnHJxEpsWVssU98zYFM3MKCyR-tCze8zG1jdGY6ZZMqyetMjHvNE9t3t\_AMbbsmoilAOpQdQWN9IvoUeZvqobwWnAJuLCY5QdTDVT6) |
| Результат | ![](https://lh5.googleusercontent.com/fibWCyNJb8kXEJBBaQSAAxH4wIgK355-kJWYW25OFVlLYGQMTd7y01OtxIYJ9bw208RXWLqSwg-WQIAxCnpL7IBt2Y43eSKmKM0H4vet3YicknGReDIC3Xaf-Dc44X2FJyJP18ZLu8yhNeuuZwZdw0tfZHUGn1t2KYxl\_PWhz79q0CqvW2ndnxd8r5-i)![](https://lh5.googleusercontent.com/uqdfFFwMjqo28BJyGo3Q1PNAVBUTacW0FoDyI2-Ewn8cJmPAfRJFwRmYZ7tfn4whkhtmm8VT7haF8zzI-Y41wbrgwve1oVZWiVCLhebwT6QTHxx3\_svNBOwrWxHtj3CIEOpovQkotBh3peYS3UmMO-m2liMd5ZrCcDdxHImk9UsELQLp26y\_5jrPXwXx)     |

### [Голем](https://makecode.com/\_9jkPW1PE05DU)

|            |                                         |
| ---------- | --------------------------------------- |
| Завдання:  | Використовуючи агента, побудуйте голема |
| Результат: | ![](.gitbook/assets/3.png)              |
| Код:       | ![](.gitbook/assets/4.png)              |

## Самостійно

1. Напишіть код, щоб було прокладено лінію з **5 блоків** **цегли** від координати (0;0;1) до координати ( 0; 0; 5)&#x20;
2. Напишіть код, щоб було прокладено лінію з **7 блоків ТНТ**

### [Можлива відповідь](https://sun-rabbit-493.notion.site/3-d9328af5e2a34b76a64684aa958f8a3d)

{% hint style="success" %}
Готово! Ви чудові!:tada:
{% endhint %}

![Підсумки заняття](<.gitbook/assets/Group 2395 укр.png>)

## **Домашнє завдання**

### Завдання 1

Прокладіть лінію з 5 блоків Багаття від координати (\~0;\~0;\~1) до координати (\~0;\~0;\~5)

### Завдання 2

Створіть квадрат 4 х 4 з блоків води у землі від координати (\~1;\~1;\~1) до координати (\~4;\~-1;\~4)

### **Завдання 3 (додатково)** 💃🕺

Побудувати підлогу, що світиться (танцпол)

### Завдання 4 **** (додатково) 🤾🏻‍♀️

Побудова Батут, де Герой при умові «відскок» буде телепортуватися в координати (0,5,0).

{% hint style="success" %}
На наступному занятті ми продовжимо подорож Стародавнім Єгиптом і побудуємо одне з чудес світу! Ви отримаєте навички, необхідні для вашого проєкту😉
{% endhint %}
