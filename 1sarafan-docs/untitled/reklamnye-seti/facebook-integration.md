# Интеграция с FB

Интеграция нужна, чтобы передавать события (инсталлы, регистрации, депозиты) в пиксель FB через Conversions API для оптимизации рекламных кампаний.

## Что нужно для отправки событий?

1. ID пикселя.
2. Access Token для Conversion API.

## Где взять ID пикселя?

Идем в Events Manager, выбираем **Источники данных**, далее — нужный пиксель. Кликаем по ID группы данных. Это и есть нужный ID.

<figure><img src="../.gitbook/assets/01-fb_1.webp" alt=""><figcaption></figcaption></figure>

## Где взять токен и что настроить в FB?

Предполагаем, что у тебя уже есть БМ, где создан датасет (пиксель). Идем в **Events Manager**, в настройках пикселя создаем токен.

<figure><img src="../.gitbook/assets/02-fb_2.webp" alt=""><figcaption></figcaption></figure>

Либо на главной странице пикселя в **Events Manager** добавляем интеграцию через **Conversions API.**

<figure><img src="../.gitbook/assets/03-fb_3.webp" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/04-fb_4.webp" alt=""><figcaption></figcaption></figure>

На следующем шаге выбери события **Завершенная регистрация** и **Покупка.**

<figure><img src="../.gitbook/assets/05-fb_5.webp" alt=""><figcaption></figcaption></figure>

Для обоих событий выбери **ID события** в **Сведениях о событиях**.

<figure><img src="../.gitbook/assets/06-fb_6.webp" alt=""><figcaption></figcaption></figure>

В информации о клиенте выбери указанные параметры.

<figure><img src="../.gitbook/assets/07-fb_7.webp" alt=""><figcaption></figcaption></figure>

Проверь настройки на заключительном этапе.

<figure><img src="../.gitbook/assets/08-fb_8.webp" alt=""><figcaption></figcaption></figure>
