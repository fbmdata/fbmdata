# FBM Analytics

![FBM Analytics](assets/fbm-logo.svg)

## Data products for social media, APIs and AI agents

**FBM Analytics · ООО «ФБМ Аналитикс»** is an accredited Russian IT company.
We build products that collect public social-media data, turn it into
structured metrics and automate research, monitoring and reporting.

[![Website](https://img.shields.io/badge/Website-fbmdata.ru-4830E6)](https://fbmdata.ru)
[![MaxStat](https://img.shields.io/badge/MAX_analytics-MaxStat-4830E6)](https://maxstat.ru)
[![Telegram](https://img.shields.io/badge/Telegram-@fbmdata-26A5E4)](https://t.me/fbmdata)
[![MAX](https://img.shields.io/badge/MAX-@fbm-000000)](https://max.ru/fbm)

## Products

| Product | What it does |
| --- | --- |
| [MaxStat](https://maxstat.ru) | Analytics, discovery and monitoring for channels and publications in the MAX messenger — with a web interface, API and MCP server. |
| [FBM API](https://fbmapi.ru) | Structured data on more than one million blogs across ten platforms, refreshed every two weeks for influencer research and campaign planning. |
| [OnLook](https://onlookbot.ru) | Automated publication screenshots, engagement metrics and social-media reports without repetitive manual work. |

We also build custom dashboards, data-collection systems, API integrations and
on-premises analytics solutions for businesses, agencies and public-sector
organizations.

## MaxStat MCP: what an AI agent can get

[MaxStat MCP](https://github.com/fbmdata/maxstat-mcp) gives Codex, Claude,
Cursor and other MCP clients direct access to the live MaxStat index.

| Verified on 2026-07-28 | Live index |
| --- | ---: |
| MAX channels | **367,759** |
| Publications | **85,720,012** |
| Channel categories | **42** |

The index keeps growing; current totals are available through the MCP itself.

### Channels

- Search by name, description, URL, category, access type, audience size and
  publication count.
- Get the channel name, description, avatar, link, public/private access,
  categories, subscriber count, post count and RKN status when available.
- Retrieve daily subscriber history, absolute growth and growth percentage.
- Analyze total, average and maximum views and reactions per post.
- Measure publishing frequency and the distribution of text, photo, video,
  file and other post formats.
- Add a public or invite-only MAX channel to the tracking queue.

### Publications

- Full-text search by channel, format, date, views and reactions.
- Get the publication text, URL, type, attachments, views, detailed reaction
  breakdown and timestamps.
- Retrieve daily view and reaction histories for an individual publication.
- Discover forwards and see which channels republished the original post.

### Monitoring and operations

- Subscribe a webhook to every new post from a channel.
- Subscribe a webhook to posts matching a keyword, optionally within a
  category.
- List, inspect, pause, resume, update and delete webhook subscriptions.
- Check the current API plan, credit balance and request-level usage history.

The server exposes **21 MCP tools**. See the
[complete data contract and setup guide](https://github.com/fbmdata/maxstat-mcp)
or [get an API token](https://maxstat.ru/dashboard/api). A Test Drive provides
1,000 credits every 30 days and activates with the first API request.

## Engineering

Our team designs and operates:

- high-volume public-data collection and processing;
- developer APIs and Model Context Protocol integrations;
- analytics dashboards and automated reporting;
- ClickHouse, PostgreSQL, BI and CRM integrations;
- on-premises deployments for corporate customers.

We combine engineering, product thinking and hands-on knowledge of social
platforms. The result is software that saves analysts and communications teams
hours of routine work.

## По-русски

### Данные и аналитические продукты для России и СНГ

**ООО «ФБМ Аналитикс»** — аккредитованная российская ИТ-компания. Мы создаём
продукты для сбора и анализа публичных данных из социальных платформ,
автоматизируем мониторинг и отчётность, выпускаем API и MCP-интеграции и
разрабатываем корпоративные системы под ключ.

Нашими решениями могут пользоваться коммуникационные и маркетинговые команды,
агентства, аналитики, разработчики, крупные компании и государственные
организации в России и странах СНГ. Мы превращаем разрозненные публичные данные
в структурированные метрики, которые можно использовать в исследованиях,
дашбордах, отчётах и AI-агентах.

### Продукты

| Продукт | Какие задачи решает |
| --- | --- |
| [MaxStat](https://maxstat.ru) | Поиск, аналитика и мониторинг каналов и публикаций MAX через веб-интерфейс, API и MCP. |
| [FBM API](https://fbmapi.ru) | Структурированные данные более чем о миллионе блогов на десяти платформах для поиска авторов, анализа рынка и планирования кампаний. |
| [OnLook](https://onlookbot.ru) | Автоматические скриншоты публикаций, сбор метрик и подготовка отчётов по социальным платформам без ручной рутины. |

### MaxStat MCP: какие данные получает AI-агент

[MaxStat MCP](https://github.com/fbmdata/maxstat-mcp) подключает Codex, Claude,
Cursor и другие MCP-клиенты к живому индексу MaxStat. AI-агент получает не
«общую аналитику», а конкретные данные, которые можно проверить, сравнить и
включить в исследование или отчёт.

| Проверено 28 июля 2026 года | Живой индекс |
| --- | ---: |
| Каналы MAX | **367,759** |
| Публикации | **85,720,012** |
| Категории каналов | **42** |

Индекс постоянно растёт. Актуальное количество каналов, публикаций и категорий
можно запросить через сам MCP.

#### Каналы

- Поиск по названию, описанию, ссылке, категории, типу доступа, размеру
  аудитории и количеству публикаций.
- Карточка канала с названием, описанием, аватаром, ссылкой, категориями,
  публичностью, числом подписчиков и публикаций и статусом РКН, если он
  доступен.
- Дневная история аудитории, абсолютный и процентный прирост подписчиков.
- Суммарные, средние и максимальные просмотры и реакции на публикацию.
- Частота публикаций и распределение контента по форматам: текст, фото, видео,
  файлы и другие типы.
- Добавление публичного или доступного по приглашению канала MAX в очередь
  отслеживания.

#### Публикации

- Полнотекстовый поиск по каналу, формату, периоду, просмотрам и реакциям.
- Текст, ссылка, тип публикации, вложения, просмотры, подробная разбивка
  реакций и временные метки.
- Дневная история просмотров и реакций отдельной публикации.
- Найденные пересылки и список каналов, которые разместили исходный материал.

#### Мониторинг и работа с API

- Webhook-подписка на все новые публикации выбранного канала.
- Webhook-подписка на публикации с ключевым словом, в том числе внутри
  конкретной категории.
- Просмотр, приостановка, возобновление, изменение и удаление подписок.
- Проверка тарифа, остатка кредитов и истории списаний по отдельным запросам.

Сервер предоставляет **21 MCP-инструмент**. Полный контракт данных и инструкции
по подключению находятся в
[репозитории MaxStat MCP](https://github.com/fbmdata/maxstat-mcp). Получить
токен можно в [личном кабинете MaxStat API](https://maxstat.ru/dashboard/api).
Test Drive активируется первым API-запросом и предоставляет 1 000 кредитов
каждые 30 дней.

### Разработка и интеграции под задачи бизнеса

Команда ФБМ Аналитикс проектирует и поддерживает:

- высоконагруженные системы сбора и обработки публичных данных;
- корпоративные API и интеграции с MCP и AI-агентами;
- аналитические дашборды и автоматизированную отчётность;
- интеграции с ClickHouse, PostgreSQL, BI-системами и CRM;
- on-premises-развёртывания в инфраструктуре заказчика.

Мы соединяем инженерную разработку, продуктовый подход и практическое знание
социальных платформ. Такие решения сокращают ручную работу, ускоряют
исследования и помогают получать воспроизводимые данные для управленческих
решений.

## Contact

- Website: [fbmdata.ru](https://fbmdata.ru)
- Email: [info@fbmdata.ru](mailto:info@fbmdata.ru)
- Press: [pr@fbmdata.ru](mailto:pr@fbmdata.ru)
- Telegram: [@fbmdata](https://t.me/fbmdata)
- MAX: [@fbm](https://max.ru/fbm)

**Legal name:** ООО «ФБМ Аналитикс»  
**ИНН:** 9704231353 · **ОГРН:** 1237700900216
