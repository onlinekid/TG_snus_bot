<h1 align="center">Снюс Telegram Bot👋</h1>
<a href="https://github.com/daveusa31/TG_snus_bot/releases">Скачать последнюю версию бота</a>

## 💁‍♀️ Скриншоты:
<a href="https://lolzteam.online/threads/1379277/">Офф. продажник на LZT</a>

![](https://i2.imageban.ru/out/2020/03/02/0401c4e3243ef03d4b2bc3bb7d62b802.png)

Уведомления об действиях

![](https://i5.imageban.ru/out/2020/03/02/a6e99361ed32c7ac0d50c7595ed3f7fb.png)



![](https://i1.imageban.ru/out/2020/03/02/e7af0b988ac77f4282fc4b46509b902b.png)![](https://i3.imageban.ru/out/2020/03/02/d28040e4b13ae6a5eef101dd5d2f7fce.png)
![](https://i4.imageban.ru/out/2020/03/02/91ec076df40d377eb326b7b77f37ad73.png)![](https://i4.imageban.ru/out/2020/03/02/2dedff3763c999652225bb11041a6cfa.png)
![](https://i2.imageban.ru/out/2020/03/02/42249d05b853635290c07faf80408901.png)



## 🚀 Установка
1. Устанавливаем пейтон(Python 3.7):
	<h3>Для Windows</h3>

	Скачиваем инсталятор с [официального сайта](https://www.python.org/ftp/python/3.7.3/python-3.7.3.exe) и запускаем.

    Ставим галочки

    ![](https://telegra.ph/file/eda752da317fa1fe9679d.png)


    <h3>Для Android</h3>

    Установите приложение [Termux](https://play.google.com/store/apps/details?id=com.termux), запустите его и введите следующие команды поочерёдно:
    ```sh
    pkg install python
    pkg install clang
    ```



2. Устанавливаем зависимость:
	win + r -> cmd 

	В консоль вводим
	```sh
	pip install PyTelegramBotApi
	```



3. Редактируем config.py:
	Получаем токен от киви <a href="https://qiwi.com/api">qiwi.com/api</a>
	
	И заполяем config.py.

	![](https://i2.imageban.ru/out/2020/03/02/96fcb4ffa60056f18bfe72c56fad2176.png)



4. Запускаем скрипт:
	<h3>Для Windows</h3>
	win + r -> cmd 

	В консоль вводите

	```sh
	cd путь до папки с ботом
	python run.py
	```


	<h3>Для Android</h3>

	В temux вводите:
	```sh
	termux-setup-storage
	cd путь до папки с ботом
	python run.py
	```





## 🚿 Использование
1. Уведомления:
	Приходят при:
		Новом юзере и пишется, перешёл ли он по реф.ссылке или нет.
		При тестовой оплате
		При нормальной оплате

	Заполните строку group_id, если хотите, чтобы уведомления приходили в чат.
	Если строку оставить пустой, то всё пойдёт в лс к админу.


2. Создание реферальной ссылки:
	```https://t.me/bot_username?start=referer```

	Вместе bot_username должен быть юзернейм бота без @.
	А вместе referer любой идентефикатор рефовода


3. Получение списка всех юзеров:
	Введите команду ```/user```(доступна только админам)

	![](https://i1.imageban.ru/out/2020/03/02/f30ed793c83590aa047097f637214a98.png)



## Сообщить об ошибках и задать вопросы:
Если бот остановился и в консоли появились ошибки, то лучшим решением будет заскринить консоль и написать мне.


Я в [Telegram](https://t.me/j0pa228). 

Мой [бложик](https://t.me/nnn_blog), там буду освещать всю ситуацию с ботом.

