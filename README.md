#Описание проекта
Этот проект представляет собой CRUD-приложение, разработанное с использованием Spring Boot, Spring Security и Hibernate. Приложение позволяет управлять профилями пользователей, включая создание, чтение, обновление и удаление данных.

##Функциональность
###Авторизация: Пользователи могут войти в систему с использованием своих учетных данных. Учетные записи имеют две роли: администратор и обычный пользователь.
###Управление профилями: Администраторы могут создавать, редактировать и удалять профили других пользователей. Обычные пользователи имеют доступ только к своей персональной странице.
###Безопасность: Приложение защищено с помощью Spring Security, обеспечивающего безопасность на уровне пользователей и ролей.
##Установка и запуск
Клонируйте репозиторий или скачайте исходный код проекта.
Откройте проект в среде разработки, поддерживающей Java и Maven.
Запустите приложение с помощью Run SpringBootSecurityDemoApplication.
Доступные учетные записи
Администратор :
Авторизоваться:admin
Пароль:admin
Обычный пользователь:
Авторизоваться:user
Пароль:user
Использование приложения
Перейдите по адресу http://localhost:8080/user в браузере.
Войдите в систему, используя учетные данные одного из пользователей выше.
После входа в систему вы сможете управлять профилями в соответствии с вашей ролью.
Технические детали
Spring Boot: Используется для быстрой разработки и развертывания приложений на основе Spring.
Spring Security: Предоставляет функции аутентификации и авторизации, а также защиту от различных типов атак.
Hibernate: Инструмент для работы с базами данных, обеспечивающий объектно-реляционное отображение.
