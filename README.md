# flask_simple_chat
This is first simple chat on Flask + socketio + VanillaJS

В файле requirements.txt указаны все необходимые модули и библиотеки для запуска
Запускать просто - введите в терминале python chat.py 
Если запуск на маке, то, наверное, $python3 chat.py
Сделано на python 3.7 
Поддерживается возможность создания нескольких комнат.
Чтобы работало корректно, второму человеку желательно входить в комнату с другого браузера 
или через режим "инкогнито". 
Количество пользователей в комнате не ограничивается.
При авторизации высвечивается уведомление о том, что новый пользователь вошел в чат.
Отправка сообщений по Enter. Есть кнопка для выхода из комнаты и создания новой.

Ответы на вопросы:

1) Почему FLask? Потому что больше опыта работы с сокетами на Flask, 
да и в целом фреймворк в плане создания простых приложений комфортный.
Пытался реализовать на Django, возникали проблемы при присоединении второго человека.
2) Чем пользовались? Пользовался документацией и собственными наработками.
3)С чем пришлось столкнуться впервые? Ни с чем, все технологии знакомы. Потраченное время - порядка 2-3 часов.