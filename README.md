# my-static-webapp-template
my-static-webapp

Вітаю
Для створення статичного веб додатку на порталі Azure нам перш-за-все потрібно створити git
репозиторій на github.

![Alt text](https://i.imgur.com/Ut8cerj.png "Optional title")

![Alt text](https://i.imgur.com/d4l5onh.png "Optional title")

Після створення репозиторія переходимо за посиланням https://portal.azure.com/?
quickstart=True#home і в пошуку знаходимо розділ Services – Static Web Apps

![Alt text](https://i.imgur.com/azdlGtf.png "Optional title")

На знайденій сторінці знаходимо кнопку створення нового статичного веб застосунка.

![Alt text](https://i.imgur.com/whQP33s.png "Optional title")

Заповнюємо форму валідними значеннями

![Alt text](https://i.imgur.com/rv7qGKM.png "Optional title")

В нас буде простий статичний html додаток.
Якщо в вас не під’єднаний github до azure акаунта – під’єднайте і виберіть створений раніше репозиторій для подальшої роботи.

![Alt text](https://i.imgur.com/QLtptCd.png "Optional title")

Тиснемо "Review + Create" і "Create".

Після недовгого очікування ви отримаєте повідомлення що розміщення вашого додатку завершено і ви можете перейти на сторінку ресурсу  натиснувши “Go to resource”.

![Alt text](https://i.imgur.com/abtOY6f.png "Optional title")

Там ви знайдете всю необхідну інформацію для доступу до розміщеного додатку.

![Alt text](https://i.imgur.com/F2YYY8n.png "Optional title")

а URL буде знаходитися доступ до проекту який на даний момент часу актуальний в Source : main (Github).

Я розмістив у репозиторії простий файл:

/index.html

`hello from my index.html`

Зробив я це шляхом клонування гітхаб репозиторія.

`git clone <github url>`

Перемкнувся на гілку main

`git checkout main`

Створив /index.html з вищезазначеним наповненням за допомогою vim
Додав index.html до індексування git

`git add index.html`

Розмістив зміни у локальній версії репозиторія у форматі коміту

`git commit -m Added index.html`

і розмістив ці зміни у репозиторії що знаходиться на серверах github і пов'язаний з статичним веб застосунком.

`git push origin main`

Після проходження певного часу додаток оновився і тепер виглядає так.

![Alt text](https://i.imgur.com/XRdFLEZ.png "Optional title")