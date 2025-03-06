
# Станція Сихів - проєкт на тему "Система управління проєктами" з дисципліни "Організація баз даних"  

## 📌 Інструкції для роботи

## 📂 Робота з проєктом

В цьому репозиторії знаходиться виконання лабораторних робіт проєкту. 

Документація розміщується у відповідних файлах в ```./docs```.

### 🚀 Початок роботи
Клонуємо репозиторій на свій комп'ютер та переходимо в нього:
   ```git
   git clone https://github.com/unxwn/stantsiya-sykhiv.git
   ```
   ```git
   cd stantsiya-sykhiv
   ```

### 📝 Перше вступне завдання: Додати себе в автори проєкту.
Приклад виконання завдання (приклад використовувати в майбутньому завжди): 
1. Переходимо в основну гілку:
    ```git 
    git checkout main
    ``` 
2.  Отримуємо останні зміни:
    ```git
    git pull origin main
    ``` 
3.  Створюємо нову гілку для змін:
    ```git 
    git checkout -b add-author
    ```
4. У `book.toml` додаємо себе в автори.
5.  Додаємо зміни в коміт:
    ```git
    git add book.toml
    ```
    Додаємо зміни в стейдж:
    ```git
    git commit -m "Оновлено book.toml: добавлено автора"
    ``` 
6.  Відправляємо свою гілку у віддалений репозиторій:
    ```git 
    git push origin add-author
    ``` 
7. На GitHub відкрити Pull Request (PR)
Перейти в GitHub → stantsiya-sykhiv → вкладка Pull Requests → New Pull Request
Вибрати гілку add-author, порівняти з main і створити PR.
8. Дочекатися рев’ю та злиття в main
   Якщо зміни схвалені, main оновиться.
   Інші розробники перед новою роботою повинні зробити:
   ```git
   git checkout main
   ```
   ```git
   git pull origin main
   ```

### 📔 Робота з mdBook

Шаблон публікування проєкту підготовлено з використанням [mdBook](https://github.com/rust-lang/mdBook).

1. Встановіть Rust-тулчейн на свій комп'ютер за допомогою [rustup](https://rustup.rs). Слідуйте інструкціям указаним на сайті
2. Встановіть mdBook та допоміжну бібліотеку mdbook-plantuml за допомогою cargo:
    ```sh
   cargo install mdbook
   ```
   ```sh
   cargo install mdbook-plantuml
   ```

Щоб опублікувати проект у Github Pages:
  - ✅ (цей пункт виконується один раз тімлідом) на сторінці github вашого репозиторію переходите в ```Settings```-->```Pages```, в ```Source``` обираєте варіант ```Deploy from branch```, в ```Branch``` обираєте ```gh-pages``` та папку ```/root``` та натискаєте ```Save``` та повертаєтесь до головної сторінки репозиторію.
  - робите коміт у вітку main та пушите його на віддалений репозиторій github, автоматично спрацьовує  workflow та починається процес деплою
  - Почекайте поки на боковій панелі зʼявиться ```Deployments``` та в ньому ```github-pages```(може зайняти і більше хвилинни) та переходите по ньому, там ви побачите url до сторінки вашої документації.

Для відлагодження документації в локальному режимі запускаємо:
   ```sh
   mdbook serve
   ```

Доступ до локально опублікованої версії через localhost з портом який у вас виділить (все буде в консолі).

## 👥 Автори
- 🌸 [Поліщук Мирослав](https://github.com/unxwn) | 📩 TG: [@myroslav11](https://t.me/myroslav11)  
- 💠 [Чекун Миколій](https://github.com/chekunm) | 📩 TG: [@chekun_m](https://t.me/chekun_m)  
- 💠 [Рокицький Олександр](https://github.com/rokytskyii) | 📩 TG: [@rokytskyi](https://t.me/@rokytskyi)  
- 💠 [Скубко Артем](https://github.com/jacedaichi) | 📩 TG: [@jacedaichi](https://t.me/@jacedaichi)  
- 💠 [Бурденюк Дмитро](https://github.com/BuDi4ka) | 📩 TG: [@mar_kul](https://t.me/@mar_kul)  
- 💠 [Лісовський Назар](https://github.com/Lisovskiy14) | 📩 TG: [@NazikSB](https://t.me/@NazikSB)  
- 💠 [Шусторовчик Марк](https://github.com/hhyy28) | 📩 TG: [@Retrowaver1984](https://t.me/@Retrowaver1984)  

## 📌 Додаткова інформація

- 📜 [Теми проєктів](./guidelines/themes.md)
- 📖 [Методичні вказівки](./guidelines/guidelines.md)
- 📔 [Гайд користувача mdBook](https://rust-lang.github.io/mdBook/)
- 📄 [Документація Markdown](https://theme-hope.vuejs.press/cookbook/markdown/)

***Happy learning! Happy coding!*** 
