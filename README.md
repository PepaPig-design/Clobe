# 1. Обновление системы
pkg update && pkg upgrade -y

# 2. Установка Python
pkg install python -y

# 3. Установка браузера Chromium и драйвера (обязательно для Selenium в Termux)
pkg install chromium chromedriver -y

# 4. Установка инструментов для компиляции (на случай ошибок установки библиотек)
pkg install binutils rust make -y
