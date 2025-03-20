# GCD Game (Laravel Edition)

**GCD Game** — это веб-приложение, в котором игроку предлагается вычислить наибольший общий делитель (НОД) двух чисел. Новая версия игры разработана на PHP с использованием фреймворка Laravel, базы данных SQLite и REST API для взаимодействия с сервером. 

<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

---

## О проекте

**GCD Game (Laravel Edition)** — это переработанная версия оригинальной игры "Наибольший общий делитель", теперь использующая мощь и элегантность фреймворка Laravel. Игра сохраняет свою суть: генерация случайных чисел, проверка ответа игрока и сохранение результатов, но теперь с улучшенной архитектурой и современным подходом к разработке.

---

## Установка и запуск

### Требования
- PHP 8.1 или выше
- Composer
- SQLite (встроен в PHP)

### Локальная установка
1. Клонируйте репозиторий (если он есть, иначе пропусти этот шаг):
   ```bash
   git clone https://github.com/shindasayonara/GCD_Game_Laravel.git Task04
   cd Task04
   ```

2. Установите зависимости через Composer:
    ```bash
    composer install
    ```

3. Запустите встроенный сервер Laravel:
    ```bash
    php artisan serve
    ```

4. Откройте в браузере:
    ```bash
    http://localhost:8000
    ```

### Используемые технологии
- PHP — основной язык разработки.

- Laravel — фреймворк для создания веб-приложения и REST API.

- SQLite — легковесная база данных для хранения игроков и игр.

- Eloquent ORM — для работы с базой данных.

- Blade — шаблонизатор для фронтенда.

- Composer — управление зависимостями.

- HTML/CSS/JavaScript — стилизация и интерактивность веб-интерфейса.


### Функции игры
- Генерация двух случайных чисел (от 10 до 100) и вычисление их НОД.

- Веб-интерфейс с поддержкой ввода имени игрока и ответа.

- Сохранение результатов игр в базу данных SQLite.

- REST API для создания игры (POST /games), отправки ответа (POST /step/{id}) и очистки базы (POST /clear).

- Просмотр истории всех игр в модальном окне.

- Очистка базы данных через веб-интерфейс.

### Как играть
- Откройте http://localhost:8000 в браузере.

- Введите своё имя (или оставьте "Player") и нажмите "Начать игру".

- Введите НОД для предложенных чисел и нажмите "Проверить".

- Увидите результат (верно или неверно) и правильный ответ.

- Нажмите "Показать историю" для просмотра всех игр.

- Используйте "Очистить базу данных" для удаления всех записей.


## Ссылки
- Packagist: [GCD Game](https://packagist.org/packages/shindasayonara/php_puchkin_iyu)
- [Репозиторий на GitHub](https://github.com/shindasayonara/GCD_Game_Laravel)
- Автор: **shindasayonara**
- Лицензия: **MIT**


