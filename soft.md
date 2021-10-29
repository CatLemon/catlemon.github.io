# zspotify

### Описание
Python-скрипт для скачивания музыки с Spotify
Нужен установленный Python3 и аккаунт в Spotify

### Как поставить?
>1. pip install -r requirements.txt
>2. Рекомендую с Chocolatey скачать ffmpeg (поставить сначала сам шоколетей, и потом написать в повершелл от админки choco install ffmpeg)
>3.  python zspotify.py
>4. Залогиниться в Spotify аккаунте
>5. И искать нужные треки для скачивания

### Установка на Termux

>1. pkg install ffmpeg git python3
>2. termux-setup-storage
>3. Далее cd storage
>cd music

И делаем git clone https://github.com/Footsiefat/zspotify

Так мы клонируем zspotify в папку Внутренняя память/Music
>4. После клонирования  cd zspotify
>5. Затем pip install -r requirements.txt
>6.  Затем python zspotify.py
>7. Логинимся и качаем

При перезаходе в термукс пишем
>cd storage
>cd music
>cd zpotify
>python zspotify.py

####[Ссылка на репозиторий](https://github.com/Footsiefat/zspotify)
