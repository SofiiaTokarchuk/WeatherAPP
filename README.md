# WEATHER APPLICATION 🌦

## Зміст

1. [Модулі проєкту](#модулі-проєкту)  
2. [Розгортання проєкту](#розгортання-проєкту)  
3. [Створення віртуального оточення](#створення-віртуального-оточення)  
   - [Для Windows](#для-windows)  
   - [Для Mac OS / Linux](#для-mac-os--linux)  
4. [Завантаження модулів](#завантаження-модулів)  
   - [За допомогою requirements.txt](#за-допомогою-requirementstxt)  
   - [Окремі модулі](#окремі-модулі)  
5. [Старт проєкту](#старт-проєкту)  
6. [Основні механіки проєкту](#основні-механіки-проєкту)  
7. [Висновок](#висновок)

---

## Модулі проєкту

- customtkinter
- json
- colorama
- os
- requests
- pillow
- datetime 

---

## Розгортання проєкту

Завантаження:

Git clone:
Отримати посилання для клонування проєкту

Відкрити VSCode > у Explorer VSCode відкрити папку для збереження склонованого проєкту > у терміналі прописати команду:
git clone https://github.com/SofiiaTokarchuk/WeatherAPP.git

Відкрити каталог, який ви склонували у Explorer VSCode
Download ZIP

---

## Створення віртуального оточення

### Для Windows:

python -m venv venv
venv\Scripts\activate

### Для Mac OS / Linux:

python3 -m venv venv
source venv/bin/activate

---

## Завантаження модулів

### За допомогою requirements.txt:

pip install -r requirements.txt

### Окремі модулі:

pip install requests
pip install customtkinter

---

## Старт проєкту

python main.py

---

## Основні механіки проєкту

- Пошук погоди за назвою міста
- Отримання та обробка даних з API OpenWeatherMap
- Стильний інтерфейс із CustomTkinter
- Обробка відповіді JSON
- Вивід інформації у графічному інтерфейсі (GUI)
- Збереження даних у data_base.json

## Висновок

У результаті виконання цього проєкту було засвоєно ключові навички роботи з API, структурованими даними у форматі JSON, а також створення графічного інтерфейсу користувача. Робота допомогла закріпити принципи побудови клієнт-серверної взаємодії та показала, як можна створити практичний і зручний застосунок для щоденного використання. Цей досвід стане чудовою основою для майбутніх, більш складних Python-проєктів.
