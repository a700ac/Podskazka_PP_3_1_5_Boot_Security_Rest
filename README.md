# README для CRUD-приложения Spring Boot, Spring Security и Hibernate

## Описание проекта

Этот проект представляет собой CRUD-приложение, разработанное с использованием Spring Boot, Spring Security и Hibernate. Приложение позволяет управлять профилями пользователей, включая создание, чтение, обновление и удаление данных.

## Функциональность

### Авторизация
Пользователи могут войти в систему с использованием своих учетных данных. Учетные записи имеют две роли: администратор и обычный пользователь.

### Управление профилями
- **Администраторы**: Могут создавать, редактировать и удалять профили других пользователей.
- **Обычные пользователи**: Имеют доступ только к своей персональной странице.

### Безопасность
Приложение защищено с помощью Spring Security, обеспечивающего безопасность на уровне пользователей и ролей.

## Установка и запуск

1. Клонируйте репозиторий или скачайте исходный код проекта.
2. Откройте проект в среде разработки, поддерживающей Java и Maven.
3. Запустите приложение с помощью `Run SpringBootSecurityDemoApplication`.

## Доступные учетные записи

- **Администратор**:
  - Логин: `admin`
  - Пароль: `admin`
- **Обычный пользователь**:
  - Логин: `user`
  - Пароль: `user`

## Использование приложения

1. Перейдите по адресу `http://localhost:8080/` в браузере.
2. Войдите в систему, используя учетные данные одного из пользователей выше.
3. После входа в систему вы сможете управлять профилями в соответствии с вашей ролью.

## Технические детали

- **Spring Boot**: Используется для быстрой разработки и развертывания приложений на основе Spring.
- **Spring Security**: Предоставляет функции аутентификации и авторизации, а также защиту от различных типов атак.
- **Hibernate**: Инструмент для работы с базами данных, обеспечивающий объектно-реляционное отображение.

## Новые функции и изменения

### Использование Fetch API и REST

В этой версии проекта были добавлены новые функции, связанные с использованием Fetch API и REST для асинхронного взаимодействия с сервером. Это позволяет приложению динамически загружать данные пользователей без необходимости перезагружать страницу, а также обеспечивает более гибкую и эффективную обработку запросов к серверу.

#### Fetch API

Fetch API используется для выполнения асинхронных HTTP-запросов к серверу. Это позволяет приложению отправлять запросы на создание, чтение, обновление и удаление данных пользователей без перезагрузки страницы. Пример использования Fetch API для получения данных пользователя:

