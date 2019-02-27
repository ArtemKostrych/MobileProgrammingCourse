# Курс "Програмне забезпечення мобільних пристроїв"

Курс складається з 15 лекцій (які у деяких групах згруповані у 7 лекцій), 6 лабораторних і одного проекту.
Під кінець курсу студенти пишуть контрольну роботу і отримують залік.

Кінцева оцінка складається з балів за лабораторні, власний проект і контрольну роботу.

Лабораторні - 6 лабораторних по 5 балів (максимум 30 балів)
Власний проект - 30 балів
Контрольна робота - 40 балів.

Лабораторні мають дедлайни для отримання максимальної кількості балів:
1 - до 15 березня включно
2 - до 29 березня включно
3 - до 12 квітня включно
4 - до 26 квітня включно
5 - до 10 травня включно
6 - до 24 травня включно
Проект - до 31 травня включно
За затримання термінів здавання лабораторних знімається 1 бал за кожен тиждень затримки.
УВАГА! Залікова відомість має закриватися до початку семестрового контролю.
Тобто до 7.06.2019 усі оцінки мають бути виставлені у відомість!!!

Теми для індивідуальних проектів студенти можуть придумати самостійно, або обрати зі списку.

Вимоги до проектів:
1. Це має бути native додаток. Додаток на JavaScript не приймається
1. Рекомендовані середовища розробки - Android Studio, XCode або Xamarin
1. Код додатку має бути розміщено на GitHub, код має компілюватися
1. Кожен студент працює з кодом на GitHub з власного акаунта, під зрозумілим іменем
1. Проект виконується студентом самостійно. Суперечки щодо авторства CopyCat-ів вирішуються за датою розміщення на GitHub
1. Додаток має вирішувати поставлене завдання, містити мережеву взаємодію. UX додатку має бути обгрунтований

Кожен проект складається з наступних етапів, які оціюються для отримання загальної оцінки:
1. Функціонал:
- (0 балів) Функціонал додатку не відповідає темі роботи, обраної студентом, або не визначено, хто будуть користувачі додатку, які задачі вони будуть вирішувати і в яких умовах. Або декілька студентів обрали однакову тему і запропонували однакове UX рішення
- (2 бали) Додаток дає змогу користувачу частково вирішити основну задачу, для якої спроектований додаток.
- (4 бали) Додаток  дає змогу користувачам цілком вирішити  основні задачі, для яких спроектований додаток. Задача не повинна бути примітивною (лише перегляд сторінок, лише одне вікно програми)
- (5 балів) Додаток дає змогу користувачу вирішити основні задачі, які виникають в процесі експлуатації додатку. Використовуються спеціальні можливості телефону (камера, GPS, акселерометр, OpenGL, тощо)
2. Інтерфейс додатку:
- (1 бал) Додаток містить лише одне вікно. Елементи не створюються динамічно. При зміні орієнтації з портретної на альбомну елементи розміщені неправильно.
- (2 бали) Додаток містить лише одне вікно, але деякі елементи інтерфейсу створюються динамічно, або використовуються анімації для появи і зникнення елементів.
- (4 бали) Додаток має декілька вікон, між якими відбуваються переходи. Елементи правильно розміщені при повороті екрану. Якщо додаток – мобільна гра, має бути реалізоване  ігрове меню (нова гра, пауза, вийти, тощо)
- (5 балів) Додаток має декілька вікон, між якими відбуваються анімовані переходи. Інтерфейс додатку виглядає гарно і збалансовано.
3. Збереження даних при завершенні програми
- (0 балів) Програма не зберігає дані між сеансами
- (2 бали) Програма частково зберігає дані з якими працював користувач (наприклад, ім’я користувача)
- (4 бали) У програмі є можливість продовжити виконання прямо з того місця, на якому  користувач завершив програму.
- (5 балів) Дані програми зберігаються локально на телефоні і віддалено, на сервері.
4. Авторизація користувачів
- (0 балів) Авторизація користувачів не реалізована
- (2 бали) Можуть авторизуватись лише користувачі з наперед заданого списку
- (4 бали) Користувач може створити аккаунт у додатку і/або зайти з використанням стороннього провайдера авторизації (Facebook, Google, etc.)
- (5 балів) Використовується підтвердження реєстрації користувача з використанням SMS або з використанням посилання в електронному листі
5. Обмін даними
- (0 балів) Додаток не читає і не передає дані на сервер.
- (2 бали) Додаток лише отримує дані з сервера або показує внутрішнє вікно з WebView для роботи з Web сторінкою
- (4 бали) Додаток працює з сервером, передає і читає дані.
- (5 балів) Додаток працює з сервером, передає і читає дані. За відсутності зв’язку з сервером, додаток зберігає дані локально і передає дані на сервер, коли зв’язок знову з’являється. Для мобільної гри – реалізовано гру по мережі.
6. Презентація і звіт:
- (+1 бал) Презентація містить аналіз Jobs to be Done
- (+1 бал) Презентація містить аналіз аналіз персон
- (+2 бали) Презентація містить аналіз 2-х варіантів UX і обгрунтоване рішення щодо вибору остаточної схеми
- (+1 бал) презентацію зроблено охайно


Приклади тем:
1. Розумна камера (треба придумати, чим вона може бути розумна, обов'язково - мережева взаємодія)
1. Розумна навігація користувача (треба придумати, чим вона може бути розумна: голосові підказки використання камери, QR коди, наклейки, використовувати акселерометр, гіроскоп)
1. Augmented reality - придумати і реалізувати власну ідею у доповненій реальності
1. Додаток для української жестової мови
1. Додаток для громадського транспорту. Своя версія EasyWay (чимось має бути ліпша)
1. Програма для читання аудіокниг (може містити опцію купівлі, підписки)
1. Розумний пошук аудиторії в НУ “Львівська політехніка”
1. Конструктор інтерфейсу програми для мобільного телефона
1. Програма для розподілення витрат на спільний проект (приклад – поїздка. Хтось купує продукти, хтось квитки) Передбачити можливість додавання витрат разом з фотографією чеку, розрахунок хто кому скільки винен)
1. Мобільна гра – власний варіант гри. Обов'язково - мережева взаємодія
1. Програма для малювання. Обов'язково - мережева взаємодія
1. Персональна база даних для мобільного телефону.
1. Мобільний додаток для online магазину
1. Електронний мобільний квиток для транспорту
1. Паркування з допомогою мобільного телефону - пошук, оплата
1. Музичний синтезатор
1. Додаток накладання відеоефектів у реальному часі
1. Додаток для редагування фотографій
1. Програма для того, щоб залишати відгуки і рейтинги про заклади Львова
1. Екскурсія пішки по Львову з використанням мобільного телефону
1. Мобільна програма для організації здорового способу життя
1. Програма для Bike-sharing
1. Пошук попутників
1. Програма для стрімінгу відео або презентацій з мобільного
1. Гра-опитування (аналог Kahoot)
1. Графічний додаток у 3D (власна ідея)
1. Органайзер нотаток
1. Органайзер фото галареї
1. Remote desktop
1. SSH для мобільного
