# bookstore
Описание проeкта.
Проект книжного интернет магазина.
В рамках курса будет реализованно следующее.
1. Регистрация пользователя,аутентификация и авторизация.
2. Административная часть для ведения каталога книг, издательств.
3. Просмотр, поиск, выбор книг и формирование заказа.
4. Сервис доставки.
5. Рассылка уведомлений о заказе.
6. История заказов.
7. Frontend пока под вопросом - недостаточно компетенций, если будет время - сделаю.


Сборка и запуск проекта
1. скачать этот репозиторий в любую папку<br>
  <b>'git clone https://github.com/rubanovmaxim/docker_init.git -b homework_8' .<br></b>
2. Перейти в корень репозитория.
3. Запустить <b>docker-compose up</b>

после старта сервера:
 1. - http://localhost:8082/authentication
    login/password -  admin/admin
 2. - http://localhost:8082/swagger-ui.html
     работа с самими сервисами.
     авторизация возможна  для  admin/admin, или через  добавление нового пользователя 
 3. http://localhost:8083/swagger-ui.html
    рест апи для кеша

 4. http://localhost:8084/swagger-ui.html
    рест апи сервиса уведомлений

если есть необходимость посмотреть исходники, то они находятся тут :
       https://github.com/rubanovmaxim/bookstore.git ветка homework_7
       для сервиса кеша 
       https://github.com/rubanovmaxim/caching/tree/homework_7
       для сервиса уведомлений 
       https://github.com/rubanovmaxim/notification/tree/homework_8
       

![alt text](Architecture_v1.png)

[Предварительная архитектура](Architecture_v1.png)

[Диаграмма взаимодействий](BookStore.png)




