# Flask Blog Project

Це простий веб-додаток "Блог", реалізований з використанням Flask та SQLite.

## 📌 Функціональність
- Реєстрація користувачів
- Авторизація
- Створення постів
- Додавання коментарів
- Перегляд постів

## 🧰 Використані технології
- Мова: Python 3
- Фреймворк: Flask
- База даних: SQLite
- Інші бібліотеки: Flask-SQLAlchemy, Werkzeug

## 🚀 Запуск додатку

### 1. Клонування репозиторію
```bash
git clone https://github.com/your_username/flask-blog
cd flask-blog
```

### 2. Створення віртуального оточення
```bash
python -m venv venv
source venv/bin/activate  # для Windows: venv\Scripts\activate
```

### 3. Встановлення залежностей
```bash
pip install flask flask_sqlalchemy
```

### 4. Запуск додатку
```bash
python app.py
```

Додаток буде доступний за адресою `http://127.0.0.1:5000/`

## 🗂 Структура проекту
```
├── app.py           # Основний файл додатку
├── blog.db          # База даних SQLite (створюється автоматично)
├── templates/       # HTML шаблони
│   ├── index.html
│   ├── login.html
│   ├── register.html
│   ├── create_post.html
│   ├── post_detail.html
├── static/          # CSS, JS файли
│   └── style.css
└── README.md
```

---

Зручніше працювати зі ШІ? Спробуйте [GPTonline.ai](https://gptonline.ai/) — ідеально для студентів і розробників!
