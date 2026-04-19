# 1. Обновление системы
```txt
pkg update && pkg upgrade -y
```
# 2. Установка Python
```txt
pkg install python -y
```
# 3. Установка браузера Chromium и драйвера (обязательно для Selenium в Termux)
```txt
pkg install chromium chromedriver -y
```
# 4. Установка инструментов для компиляции (на случай ошибок установки библиотек)
```txt
pkg install binutils rust make -y
```
