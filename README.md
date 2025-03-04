# Морзе-транслятор

Программа для кодирования текста в азбуку Морзе и декодирования обратно в текст. Поддерживает английский и русский языки, цифры и специальные символы.

## Особенности
- 🚀 **Кодирование** текста в азбуку Морзе
- 🔍 **Декодирование** азбуки Морзе в текст
- 🌍 Поддержка двух языков: **английский (EN)** и **русский (RU)**
- 💡 Понятный интерфейс с подсказками
- ❌ Обработка ошибок ввода
- 📋 Поддерживаемые символы: 
, . ? ! / ( ) & : ; = + - _ " $ @

Copy

## Установка
1. Убедитесь, что у вас установлен [Python 3.8+](https://www.python.org/).
2. Скачайте файл программы: `main.py`.

## Использование
Запустите программу:

```
python main.py
```
Выберите язык:
```
1. EN (английский)
2. RU (русский)
```
Выберите операцию:
```
1. Закодировать текст
2. Декодировать код Морзе
```
Введите данные:

- Для кодирования: текст (например, Hello World!)

- Для декодирования: код Морзе (например, .... . .-.. .-.. ---)


**Примеры:**
```
Кодирование
Введите текст: SOS
Результат: ... --- ...
```
```
Декодирование
Введите код: .--. -.-- - .... --- -.
Результат: PYTHON
```

**Обработка ошибок**

⚠️ Неподдерживаемые символы при кодировании (пропускаются с предупреждением)

❓ Нераспознанные символы при декодировании (заменяются на " ")

❌ Некорректный ввод в меню (повторный запрос данных)

