# Макросы и Sub ID для postback

При формировании URL для рекламных кампаний и исходящих S2S-постбеков рекомендуется использовать предопределённые макросы и sub ID для повышения эффективности отслеживания и аналитики.

#### Базовые

* `{user_id}` — ID пользователя
* `{pwa_id}` — ID PWA приложения
* `{event}` — Тип события (install, lead, sale, и т.д.)

#### Tracking данные (analytics)

**Facebook (Meta)**

* `{fbp}` — Facebook Browser ID (fbp)
* `{{campaign.name}}` — Название кампании
* `{{site_source_name}}` — Источник трафика
* `{{campaign.id}}` — ID кампании
* `{{ad.id}}` — ID объявления
* `{{ad.name}}` — Название объявления
* `{{adset.name}}` — Название группы объявлений
* `{{adset.id}}` — ID группы объявлений
* `{{placement}}` — Плейсмент
* `{fbclid}` — Facebook Click ID
* `{_fbp}` — Facebook Browser Pixel
* `{_fbc}` — Facebook Click Cookie

**Google**

* `{gaid}` — Google Analytics ID
* `{gclid}` — Google Click ID

**TikTok**

* `{ttp}` — TikTok Pixel
* `__CLICKID__` — TikTok Click ID
* `__CAMPAIGN_NAME__` — Название кампании
* `__CID__` — ID кампании
* `__AID_NAME__` — Название группы объявлений
* `__AID__` — ID группы объявлений
* `__CID_NAME__` — Название объявления
* `__PLACEMENT__` — Плейсмент

**Snapchat**

* `{{ad_id}}` — Snapchat Click ID
* `{{campaign_name}}` — Название кампании
* `{{campaign_id}}` — ID кампании
* `{{ad_squad_name}}` — Название группы объявлений
* `{{ad_squad_id}}` — ID группы объявлений
* `{{ad_name}}` — Название объявления
* `{{placement}}` — Плейсмент

**Kwai**

* `{kwp}` — Kwai Pixel
* `{kwai_click_id}` — Kwai Click ID

**Bigo**

* `{bgp}` — Bigo Pixel
* `{bigo_click_id}` — Bigo Click ID

#### Информация о пользователе

* `{ip}` — IP адрес пользователя
* `{user_agent}` — User Agent браузера (автоматически URL-encoded)
* `{language}` — Язык пользователя
* `{device}` — Устройство
* `{os_name}` — Название операционной системы
* `{os_version}` — Версия операционной системы

#### Геолокация

* `{country}` — Код страны

#### Дополнительные данные

* `{sub1}` — Sub ID 1
* `{sub2}` — Sub ID 2
* `{sub3}` — Sub ID 3
* `{sub4}` — Sub ID 4
* `{yandex_webvisor}` — Yandex Webvisor

Если передаваемое значение не входит в перечень, его можно получить в postback, указав в следующем формате: {любое\_название\_параметра}.

<br>
