# T-Rex-Pizza

## Оглавление
1. [Gateway Service](#gateway-service)
2. [Inventory Service](#inventory-service)
3. [Keycloak](#keycloak)
4. [Payment Service](#payment-service)
5. [Notification Service](#notification-service)

---

## Gateway Service

### Introduction
Краткое описание того, за что отвечает Gateway (маршрутизация, аутентификация и т.д.).

### Functional Requirements
* Требование 1
* Требование 2

### Non-Functional Requirements
* Производительность
* Безопасность

### High-Level Design
Описание архитектуры высокого уровня. Можно вставить диаграмму: `![HLD Diagram](path/to/image.png)`

### Low-Level Design
Детали реализации, классы, методы.

---

## Inventory Service

### Introduction
A service for creating and storing products, and also for working with a shopping cart.

### Functional Requirements
* The service must create, update, and get products.

### Non-Functional Requirements
* Consistency (согласованность данных)
* Availability

### High-Level Design
Архитектура Inventory сервиса.

### Low-Level Design
Схема БД, API контракты.

---

## Keycloak

### Introduction
Сервис авторизации и аутентификации (Identity Provider).

### Functional Requirements
* Логин/Регистрация
* SSO (Single Sign-On)

### Non-Functional Requirements
* Безопасность (OAuth2/OIDC)

### High-Level Design
Интеграция с другими сервисами.

### Low-Level Design
Настройки реалмов, клиентов и ролей.

---

## Payment Service

### Introduction
Сервис обработки платежей.

### Functional Requirements
* Проведение транзакций
* Возвраты

### Non-Functional Requirements
* PCI DSS compliance (если применимо)
* Надежность

### High-Level Design
Взаимодействие с платежным шлюзом.

### Low-Level Design
Машина состояний платежа (State Machine).

---

## Notification Service

### Introduction
Сервис отправки уведомлений (Email, SMS, Push).

### Functional Requirements
* Отправка чеков
* Уведомление о статусе заказа

### Non-Functional Requirements
* Асинхронность
* Очереди сообщений

### High-Level Design
Схема работы с брокером сообщений (RabbitMQ/Kafka).

### Low-Level Design
Шаблоны писем, провайдеры связи.
