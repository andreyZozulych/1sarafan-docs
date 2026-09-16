# Быстрый старт

## Шаг 1. Регистрация

Перейди на <mark style="color:blue;">1sarafan.com,</mark> введи E-mail, пароль и Telegram. Нажми **Зарегистрироваться.** Также возможна регистрация через Telegram, для этого кликни **With Telegram.**

<figure><img src=".gitbook/assets/1 (1).png" alt=""><figcaption></figcaption></figure>

## Шаг 2. Добавление домена

Перейди на вкладку **Traffic\&Routing** и нажмите кнопку **Add domain.**

<figure><img src=".gitbook/assets/2.png" alt=""><figcaption></figcaption></figure>

Для работы с доменами доступно 3 варианта:

1. Покупка домена
2. Использование системного для создания поддомена
3. Подключение своего

<figure><img src=".gitbook/assets/Screenshot 2026-09-08 at 12.53.56 PM.png" alt=""><figcaption></figcaption></figure>

Выбери желаемый вариант и следуйте инструкции.

## Шаг 3. Заполнение данных в PWA

Откройте вкладку **PWA** и нажмите **Create PWA**

<figure><img src=".gitbook/assets/Screenshot 2026-09-08 at 12.54.30 PM.png" alt=""><figcaption></figcaption></figure>

Во вкладке **General** подключите добавленный вами домен

<figure><img src=".gitbook/assets/Screenshot 2026-09-08 at 12.55.40 PM.png" alt=""><figcaption></figcaption></figure>

Во вкладке **Tracker укажите странну и ссылку** на оффер

<figure><img src=".gitbook/assets/Screenshot 2026-09-08 at 1.02.34 PM.png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
**Важно:** Как подключить свой домен описано [здесь](setup-1sarafan/connect-domain.md). Или обращайся в [<mark style="color:blue;">поддержку 1sarafan.com</mark>](https://t.me/PWA1saravan_manager)
{% endhint %}

## Шаг 4. Оформление PWA

### Шаблоны PWA и AI

Наша команда дизайнеров регулярно разрабатывает новые шаблоны для PWA. Чтобы выбрать один из них — нажми кнопку **Шаблоны.** Ты увидишь актуальный каталог бесплатных дизайнов. Также можно сгенерировать PWA с помощью AI. Для этого нажми **Generate AI**.

{% hint style="info" %}
**Важно:** Для корректной генерации PWA с помощью AI вернись в раздел "**Design**" и выберите язык, который AI должен использовать для генерации контента.
{% endhint %}

<figure><img src=".gitbook/assets/Screenshot 2026-09-08 at 1.03.34 PM.png" alt=""><figcaption></figcaption></figure>

### Собственный дизайн

Всё интуитивно понятно, но есть нюансы, на которые стоит обратить внимание для корректной работы и более высокого конверта.

{% hint style="info" %}
**Иконка приложения:** соответствие сторон для логотипа — 1:1, вес картинки — до 1-2 МБ.

Помни, что в Tier-3 гео Интернет работает медленно — долгая загрузка картинок может негативно повлиять на Click2Install.
{% endhint %}

Чем меньше вес основных картинок — тем лучше. Соотношение сторон — 16:9 или 9:16.

{% hint style="warning" %}
Все картинки должны идти друг за другом, в противном случае — ошибка генерации PWA, корректный пример ниже.
{% endhint %}

<figure><img src=".gitbook/assets/Screenshot 2026-09-08 at 1.12.04 PM.png" alt=""><figcaption></figcaption></figure>

## Шаг 5. Комментарии

Переходим в раздел **Комментарии.** Можно генерировать их с помощью AI или вручную. Обрати внимание: во время генерации комментария с помощью AI за основу будет взят язык, выбранный в разделе **Трекер.**

<figure><img src=".gitbook/assets/Screenshot 2026-09-08 at 1.16.23 PM.png" alt=""><figcaption></figcaption></figure>

## Шаг 6. Интеграция с вашим трекером

### Интеграция с Keitaro

Создай новый источник и заполни параметры вручную. При необходимости ты сможешь добавить другие параметры или отредактировать текущие.

Перейди в свою кампанию и выбери созданный источник — все необходимые настройки будут применены автоматически.

<figure><img src=".gitbook/assets/10-Screenshot 2025-02-26 at 11.32.09 PM.png" alt=""><figcaption></figcaption></figure>

### Интеграция с Binom

Создай новый источник и укажи [https://api.1sarafan.com/v1/postbacks?subid={external\_id}\&tid={clickid}\&status={cnv\_status}\&payout={payout}\&currency=usd ](https://api.1sarafan.com/v1/postbacks?subid={external_id}\&tid={clickid}\&status={cnv_status}\&payout={payout}\&currency=usd)как **Postback Url,** проставь следующие параметры:

<figure><img src=".gitbook/assets/11-Screenshot 2025-02-26 at 11.46.35 PM.png" alt=""><figcaption></figcaption></figure>

После этого выбери данный источник в своей кампании.

{% hint style="info" %}
Как правильно настроить исходящие постбеки и макросы читай [здесь](/broken/pages/Ie8G4oplYZGhIryXG0JA).
{% endhint %}

## Шаг 7. Аналитика

👉 Больше информации о интеграции с FB, Google, Tiktok, Kwai, Bigo можно найти [здесь](/broken/pages/BoXPxoejSMNcXrEWdSHl).

В разделе **Аналитика** мы выбираем ранее созданный пиксель из выпадающего списка.

<figure><img src=".gitbook/assets/Screenshot 2026-09-08 at 1.17.37 PM.png" alt=""><figcaption></figcaption></figure>

### 🚨 Важно! Подключение пикселя в PWA

После создания пикселя для корректной передачи ивентов нужно **обязательно** указать в ссылке PWA.\
\
К примеру: домен PWA — `horangonik.store` , ты работаешь с FB-пикселем с идентификатором `7489092067849184` . Тогда ссылка должна выглядеть следующим образом: `https://horangonik.store?fbp=7489092067849184`

Это касается и других пикселей. Вот список параметров:

```
fbp - Facebook pixel
ttp - Tiktok pixel
bgp - Bigo pixel
kwp - Kwai pixel
gcid - Google conversion id
```

## Шаг 8. Дополнительные настройки

Базово этот раздел можно пропустить: по дефолту все настройки уже выставлены для получения максимального перформанса от трафика. Но мы подготовили дополнительный материал о работе iOS и PC трафика — читай [здесь](/broken/pages/n5cdf3HOi9Qd69wjRhKk).

## 🎉 Финал. Активация PWA

После выставления настроек можно смело нажимать **Запустить.** PWA будет создана в течение 2-х минут. Если процесс занимает дольше — обратись в [саппорт](https://t.me/PWA1saravan_manager).

<figure><img src=".gitbook/assets/Screenshot 2026-09-08 at 1.18.38 PM.png" alt=""><figcaption></figcaption></figure>

Полную ссылку для запуска приложения можно скопировать внутри PWA

<figure><img src=".gitbook/assets/Screenshot 2026-09-08 at 1.22.01 PM.png" alt=""><figcaption></figcaption></figure>
