# technopark-highload-coursework

<a id="up"></a>

[<img src="./images/header/01_logo.png" height="60px">](http://vk.com/)[<img src="./images/header/02_theme.png" height="60px">](#section-one)[<img src="./images/header/03_nagr.png" height="60px">](#section-two)[<img src="./images/header/04_logic.png" height="60px">](#section-three)[<img src="./images/header/05_physical.png" height="60px">](#section-four)[<img src="./images/header/06_technologies.png" height="60px">](#section-five)[<img src="./images/header/07_scheme.png" height="60px">](#section-six)[<img src="./images/header/08_servers.png" height="60px">](#section-seven)[<img src="./images/header/09_conclusion.png" height="60px">](#section-last)

**ВКонтакте (*VK*)** — крупнейшая социальная сеть в России и странах СНГ. По данным *Alexa Internet*, vk.com занимает 36 место по посещаемости в мире и 3 место в России[<sup>1</sup>](#source-1). Социальная сеть доступна на 86 языках; пользователи сети обмениваются более 15 миллиардов сообщений в сутки и оставляют более 1 миллиардов отметок «*Нравится*» в сутки[<sup>2</sup>](#source-2).

<hr/>

## <a id="section-one"></a>1. Тема и целевая аудитория

<div style="text-align: right"> <a href="https://github.com/DPeshkoff/technopark-highload-coursework#technopark-highload-coursework"><img src="./images/up.png" height="25px"></a> </div>

Тип сервиса: *newsfeed social networking service*. 

Аналоги такого типа сервиса:

* *VK*;
* *Facebook*;
* *LiveJournal*;
* *Myspace*;
* *Odnoklassniki*;

Потенциальный размер аудитории: максимальный (общемировой) — 2,91 миллиарда пользователей в месяц (*Facebook*)[<sup>3</sup>](#source-3)

Оценка, учитывающая текущих пользователей в странах СНГ и ближнего зарубежья — 203,6 миллионов пользователей (активные интернет-пользователи России, Украины, Узбекистана, Казахстана, Азербайджана, Беларуси, Грузии, Молдавии, Армении, Таджикистана, Туркмении и Монголии)[<sup>А</sup>](#appendix-1)

Оценка с учетом потенциального роста числа пользователей сети Интернет до отметки в 95,5%: 269,5 миллионов пользователей[<sup>А</sup>](#appendix-1).

Для более справедливой оценки с учетом экономической ситуации возьмем число *0,8 **⋅** 269,5 = 215,6* (миллионов пользователей).

### MVP

Ключевой функционал сервиса:

* Регистрация/авторизация пользователей, личные профили, содержащие информацию о пользователе;
* Система личных сообщений между пользователями;
* Система сообществ, объединяющих пользователей;
* Новостная лента, содержащая обновления друзей и сообществ и состоящая из постов с возможностью комментирования и оценивания;

### Целевая аудитория

По данным официальной аудированная отчетности компании *VK*, cредняя месячная аудитория (*MAU*) в России составляет **72,5** миллиона пользователей, дневная аудитория (*DAU*) — **47** миллионов (четвертый квартал 2021 года)[<sup>4</sup>](#source-4).

В то же время, данные рейтингов превышают эти цифры. Так, согласно данным MediaScope, в январе 2022 года месячная аудитория в России составила **79,1** миллионов человек [<sup>5</sup>](#source-5).

По данным платформы Semrush, мировая месячная аудитория сайта составила более **148,3** миллионов пользователей, что почти вдвое превышает данные официальной отчетности компании. Для большей точности и учета пользователей мобильных приложений социальной сети для Android и iOS для расчетов были взяты данные платформы Semrush.

Расположение аудитории[<sup>6</sup>](#source-6):

| Позиция |       Страна      | MAU, млн | оценка DAU, млн[<sup>Б</sup>](#appendix-2) |
|:------: |:----------------- | --------:| --------:|
|  **1**  | 🇷🇺 Россия         | 109,1    | 70,73    |
|  **2**  | 🇺🇦 Украина        | 7,9      | 5,12     |
|  **3**  | 🇧🇾 Беларусь       | 7,0      | 4,54     |
|  **4**  | 🇰🇿 Казахстан      | 7,0      | 4,54     |
|  **5**  | 🇹🇷 Турция         | 4,9      | 3,18     |
|  **6**  | 🇺🇸 США            | 1,1      | 0,71     |
|  **7**  | 🇩🇪 Германия       | 0,7      | 0,45     |
|  **8**  | 🇫🇷 Франция        | 0,4      | 0,26     |
|  **9**  | 🇬🇧 Великобритания | 0,3      | 0,19     |
|    -    | 🇺🇳 Другие страны  | 9,9      | 6,42     |
|    -    | Всего:            | 148,3    | 96,14    |


<hr/>

## <a id="section-two"></a>2. Расчет нагрузки

<div style="text-align: right"> <a href="https://github.com/DPeshkoff/technopark-highload-coursework#technopark-highload-coursework"><img src="./images/up.png" height="25px"></a> </div>

<hr/>

## <a id="section-three"></a>3. Логическая схема

<div style="text-align: right"> <a href="https://github.com/DPeshkoff/technopark-highload-coursework#technopark-highload-coursework"><img src="./images/up.png" height="25px"></a> </div>

<hr/>

## <a id="section-four"></a>4. Физическая схема

<div style="text-align: right"> <a href="https://github.com/DPeshkoff/technopark-highload-coursework#technopark-highload-coursework"><img src="./images/up.png" height="25px"></a> </div>

<hr/>

## <a id="section-five"></a>5. Технологии

<div style="text-align: right"> <a href="https://github.com/DPeshkoff/technopark-highload-coursework#technopark-highload-coursework"><img src="./images/up.png" height="25px"></a> </div>

<hr/>

## <a id="section-six"></a>6. Схема проекта

<div style="text-align: right"> <a href="https://github.com/DPeshkoff/technopark-highload-coursework#technopark-highload-coursework"><img src="./images/up.png" height="25px"></a> </div>

<hr/>

## <a id="section-seven"></a>7. Список серверов

<div style="text-align: right"> <a href="https://github.com/DPeshkoff/technopark-highload-coursework#technopark-highload-coursework"><img src="./images/up.png" height="25px"></a> </div>

<hr/>

## <a id="section-last"></a>Заключение

<div style="text-align: right"> <a href="https://github.com/DPeshkoff/technopark-highload-coursework#technopark-highload-coursework"><img src="./images/up.png" height="25px"></a> </div>

<hr/>

## Список используемых источников

1. <a id="source-1"></a> [Данные веб-сайта alexa.com](https://www.alexa.com/siteinfo/vk.com) (дата обращения: 07.03.2022);

2. <a id="source-2"></a> [Раздел "О нас" на сайте социальной сети](https://vk.com/about) (дата обращения: 07.03.2022);
   
3. <a id="source-3"></a> [Слайды статистики Facebook за 3 квартал 2021 года](https://investor.fb.com/investor-events/event-details/2021/Facebook-Q2-2021-Earnings/) (дата обращения: 07.03.2022);

4. <a id="source-4"></a> [VK Company Limited: аудированная отчетность по МСФО за 2021 год](https://vk.company/ru/press/releases/11106/) (дата обращения: 07.03.2022);

5. <a id="source-5"></a> [Mediascope, WEB-Index, январь 2022, Россия 0+, население в возрасте 12+ лет](https://mediascope.net/data/) (дата обращения: 07.03.2022);

6. <a id="source-6"></a> [Статистика согласно сервису Semrush.com](https://www.semrush.com/analytics/overview/?q=vk.com) (дата обращения: 07.03.2022);

## <a id="appendix-1"></a> Приложение А. Оценка роста ЦА социальной сети

<div style="text-align: right"> <a href="https://github.com/DPeshkoff/technopark-highload-coursework#technopark-highload-coursework"><img src="./images/up.png" height="25px"></a> </div>

Был проведен анализ рынка стран СНГ и ближнего зарубежья, потенциально являющихся рынками для социальной сети.

| Рейтинг в мире | Страна | Активных пользователей сети Интернет, человек | Год проведения исследования | % населения |
|:---:|:----------- | :----------:| :--: | :--: |
|   5 | 🇷🇺 Россия      | 114 920 477 | 2018 | 80,9 |
|  29 | 🇺🇦 Украина     |  31 100 000 | 2022 | 71,8 |
|  42 | 🇺🇿 Узбекистан  |  15 705 402 | 2018 | 52,3 |
|  44 | 🇰🇿 Казахстан   |  14 789 448 | 2018 | 78,9 |
|  60 | 🇦🇿 Азербайджан |   8 017 120 | 2018 | 79,8 |
|  67 | 🇧🇾 Беларусь    |   7 539 145 | 2018 | 79,1 |
|  96 | 🇬🇪 Грузия      |   3 151 218 | 2018 | 64,0 |
| 105 | 🇲🇩 Молдавия    |   2 616 792 | 2018 | 76,1 |
| 118 | 🇦🇲 Армения     |   1 966 942 | 2018 | 64,7 |
| 119 | 🇹🇯 Таджикистан |   1 889 632 | 2018 | 22,0 |
| 130 | 🇹🇲 Туркмения   |   1 149 840 | 2018 | 21,3 |
| 142 | 🇲🇳 Монголия    |     735 823 | 2018 | 23,7 |
|  -  | Всего       | 203 581 839 |   -  |   -  |

Было расчитано максимальное число пользователей сети с учетом роста числа активных пользователей сети Интернет.

[Ссылка на анализ](./data/target-audience.ipynb)

## <a id="appendix-2"></a> Приложение Б. Оценка DAU

<div style="text-align: right"> <a href="https://github.com/DPeshkoff/technopark-highload-coursework#technopark-highload-coursework"><img src="./images/up.png" height="25px"></a> </div>

[Ссылка на анализ](./data/dau-average.ipynb)
