# 👋 Привет, я нест

💻 **Python-разработчик**, фокус: **Telegram-боты, автоматизация, чистая архитектура и быстрый запуск MVP**.

<p align="left">
  <a href="https://github.com/NESTREN">
    <img src="https://komarev.com/ghpvc/?username=NESTREN&label=Profile%20Views&color=0ea5e9&style=for-the-badge" alt="profile views"/>
  </a>
  <a href="https://github.com/NESTREN?tab=followers">
    <img src="https://img.shields.io/github/followers/NESTREN?label=Followers&style=for-the-badge&color=22c55e" alt="followers"/>
  </a>
  <a href="https://github.com/NESTREN?tab=repositories">
    <img src="https://img.shields.io/badge/Public%20Repos-view-6366f1?style=for-the-badge&logo=github" alt="public repos"/>
  </a>
</p>

<p>
  <a href="https://github.com/NESTREN/openttd-smart-advisor">
    <img src="https://img.shields.io/badge/New-openttd--smart--advisor-8b5cf6?style=for-the-badge&logo=github" alt="new openttd smart advisor"/>
  </a>
  <a href="https://github.com/NESTREN/afk-fish-mc">
    <img src="https://img.shields.io/badge/New-afk--fish--mc-f59e0b?style=for-the-badge&logo=github" alt="new afk fish mc"/>
  </a>
  <a href="https://github.com/NESTREN/chatgl-mc">
    <img src="https://img.shields.io/badge/New-chatgl--mc-22d3ee?style=for-the-badge&logo=github" alt="new chatgl mc"/>
  </a>
  <a href="https://github.com/NESTREN/nestren-protocol">
    <img src="https://img.shields.io/badge/New-nestren--protocol-a855f7?style=for-the-badge&logo=github" alt="new nestren protocol"/>
  </a>
  <a href="https://github.com/NESTREN/mesh-erl-protocol">
    <img src="https://img.shields.io/badge/New-mesh--erl--protocol-06b6d4?style=for-the-badge&logo=github" alt="new mesh erl protocol"/>
  </a>
  <a href="https://github.com/NESTREN/security-connect-protocol">
    <img src="https://img.shields.io/badge/New-security--connect--protocol-ef4444?style=for-the-badge&logo=github" alt="new security connect protocol"/>
  </a>
</p>

---

## 🧠 Профиль в 30 сек
- 🤖 Проектирую и разрабатываю Telegram-ботов на **aiogram**
- 🏗 Умею строить логику через **FSM**, сервисный слой и модульную архитектуру
- 🗄 Работаю с **SQLite**, постепенно усиливаю стек в сторону **PostgreSQL**
- 🚀 Делаю решения, которые можно быстро запустить и удобно поддерживать
- 🔧 Люблю чистый DX, понятную структуру проекта и аккуратный UX внутри Telegram

---

## 🛠 Технологический стек

### Основной
![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white)
![aiogram](https://img.shields.io/badge/aiogram-3.x-2CA5E0?style=for-the-badge)
![Telegram](https://img.shields.io/badge/Telegram-Bot-26A5E4?style=for-the-badge&logo=telegram&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-07405E?style=for-the-badge&logo=sqlite&logoColor=white)
![Git](https://img.shields.io/badge/Git-Version%20Control-F05032?style=for-the-badge&logo=git&logoColor=white)

### Изучаю / усиливаю
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-learning-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-learning-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-planned-DC382D?style=for-the-badge&logo=redis&logoColor=white)

---

## 🗺 Схема текущих репозиториев

> Визуальная карта портфолио: от прикладных Telegram-продуктов до Minecraft-плагинов, AI-утилит и протокольного слоя.

<div align="center">

```mermaid
flowchart TB
  classDef root fill:#111827,stroke:#38bdf8,stroke-width:3px,color:#f8fafc
  classDef telegram fill:#0f2742,stroke:#38bdf8,stroke-width:2px,color:#e0f2fe
  classDef minecraft fill:#20351f,stroke:#84cc16,stroke-width:2px,color:#ecfccb
  classDef ai fill:#2e1f47,stroke:#a78bfa,stroke-width:2px,color:#f3e8ff
  classDef protocol fill:#3b1f2a,stroke:#fb7185,stroke-width:2px,color:#ffe4e6
  classDef repo fill:#172033,stroke:#64748b,stroke-width:1.5px,color:#f8fafc
  classDef new fill:#312e81,stroke:#facc15,stroke-width:2px,color:#fef9c3
  classDef focus fill:#083344,stroke:#22d3ee,stroke-width:2px,color:#ecfeff

  N((🚀 NESTREN<br/>Repository Map)):::root

  N --> T[🤖 Telegram Bots<br/>продукты, автоматизация, бизнес-логика]:::telegram
  N --> M[☕ Java / Minecraft<br/>Paper-плагины и игровые утилиты]:::minecraft
  N --> A[🧠 AI / Utility<br/>помощники и прикладные инструменты]:::ai
  N --> P[🧩 Core / Protocol<br/>контракты, интеграции, безопасность]:::protocol

  T --> TW[aio-warehouse-bot<br/>📦 складской учет · отчеты · импорт]:::focus
  T --> TS[aio-sell-bot<br/>🛒 Telegram-магазин · каталог · заказы]:::focus
  T --> TH[support-bot-aio<br/>🎫 helpdesk · тикеты · админ-панель]:::repo
  T --> TB[aiobtcbottg<br/>₿ BTC/ETH курс по команде]:::repo
  T --> TC[aio-shifr-bot<br/>🔐 SHIFR1 шифрование сообщений]:::repo

  M --> MB[biome-nickname-plugin<br/>🌿 цвет ника по биому]:::repo
  M --> MF[afk-fish-mc<br/>🎣 AFK-рыбалка · авто-цикл]:::new
  M --> MG[chatgl-mc<br/>💬 чатовые механики / интеграция]:::new

  A --> AO[openttd-smart-advisor<br/>🛤 AI-советник: маршруты, города, узкие места]:::new

  P --> PN[nestren-protocol<br/>📜 базовый контракт обмена]:::new
  P --> PM[mesh-erl-protocol<br/>🕸 mesh/ERL взаимодействие узлов]:::new
  P --> PS[security-connect-protocol<br/>🛡 security-first подключение]:::new
```

</div>

### 🧭 Быстрая навигация по направлениям

| Направление | Для чего | Репозитории | Акцент |
|---|---|---|---|
| **🤖 Telegram Bots** | Автоматизация, магазины, helpdesk, утилиты внутри Telegram | `aio-warehouse-bot`, `aio-sell-bot`, `support-bot-aio`, `aiobtcbottg`, `aio-shifr-bot` | Python, aiogram, SQLite, FSM, сервисный слой |
| **☕ Java / Minecraft** | Игровые плагины и удобные механики для Minecraft-серверов | `biome-nickname-plugin`, `afk-fish-mc`, `chatgl-mc` | Java, Paper, чат, игровые циклы |
| **🧠 AI / Utility** | Инструменты-помощники для анализа и подсказок | `openttd-smart-advisor` | AI-advice layer, планирование, диагностика |
| **🧩 Core / Protocol** | Единые правила обмена, интеграций и безопасного подключения | `nestren-protocol`, `mesh-erl-protocol`, `security-connect-protocol` | Контракты, mesh-взаимодействие, security-first |

### 🎨 Легенда карты

| Маркер | Значение |
|---|---|
| **Бирюзовая рамка** | ключевые Telegram-проекты с практическим бизнес-сценарием |
| **Желтая рамка** | новые или активно расширяемые репозитории |
| **Розовая ветка** | протокольный и security-слой |
| **Фиолетовая ветка** | AI/utility-направление |


## 🆕 Последние репозитории

| Репозиторий | Статус | Что внутри | Ссылка |
|---|---|---|---|
| **openttd-smart-advisor** | New | AI-помощник для OpenTTD: подсказки по развитию города, планированию маршрутов и поиску узких мест транспортной сети. | [GitHub](https://github.com/NESTREN/openttd-smart-advisor) |
| **afk-fish-mc** | New | Minecraft-проект для AFK-рыбалки с упором на удобный сценарий использования и быструю настройку. | [GitHub](https://github.com/NESTREN/afk-fish-mc) |
| **chatgl-mc** | New | Новый Minecraft-репозиторий для чат-интеграции/геймплейных взаимодействий (Java/Paper-направление). | [GitHub](https://github.com/NESTREN/chatgl-mc) |
| **nestren-protocol** | New | Репозиторий протокола: единый контракт/формат взаимодействия между компонентами и интеграциями. | [GitHub](https://github.com/NESTREN/nestren-protocol) |
| **mesh-erl-protocol** | New | Протокол для mesh/ERL-взаимодействий между сервисами и интеграциями. | [GitHub](https://github.com/NESTREN/mesh-erl-protocol) |
| **security-connect-protocol** | New | Security-first протокол подключения и безопасного обмена между компонентами. | [GitHub](https://github.com/NESTREN/security-connect-protocol) |

---

## 🚀 Проекты

### ⭐ Ключевые проекты
| Проект | Что делает | Технологии | Ссылка |
|---|---|---|---|
| **aio-warehouse-bot** | Склад-бот для бизнеса: остатки, склады, отчеты, массовая загрузка | Python, aiogram, SQLite | [GitHub](https://github.com/NESTREN/aio-warehouse-bot) |
| **aio-sell-bot** | Готовый Telegram-магазин с чистой архитектурой и удобным UX | Python, aiogram, SQLite | [GitHub](https://github.com/NESTREN/aio-sell-bot) |

### 📦 Другие Telegram-проекты
| Проект | Кратко | Ссылка |
|---|---|---|
| **aiobtcbottg** | Бот с актуальным курсом BTC/ETH по `/price` | [GitHub](https://github.com/NESTREN/aiobtcbottg) |
| **support-bot-aio** | Helpdesk-бот: тикеты, админ-панель, изображения, SQLite | [GitHub](https://github.com/NESTREN/support-bot-aio) |
| **aio-shifr-bot** | Шифрование/расшифровка сообщений в формате `SHIFR1.<payload>` | [GitHub](https://github.com/NESTREN/aio-shifr-bot) |

### ☕ Java-проекты
| Проект | Кратко | Ссылка |
|---|---|---|
| **biome-nickname-plugin** | Плагин для Minecraft Paper: цветной индикатор в чате и табе | [GitHub](https://github.com/NESTREN/biome-nickname-plugin) |
| **afk-fish-mc** | Minecraft-проект для AFK-рыбалки | [GitHub](https://github.com/NESTREN/afk-fish-mc) |
| **chatgl-mc** | Minecraft-репозиторий для чатовых механик/интеграции | [GitHub](https://github.com/NESTREN/chatgl-mc) |

### 🧠 AI / Utility-проекты
| Проект | Развернутое описание | Ссылка |
|---|---|---|
| **openttd-smart-advisor** | AI-инструмент для OpenTTD, который помогает принимать решения по развитию транспортной сети: оценивает текущее состояние города/логистики, предлагает следующие шаги, подсказывает приоритеты по маршрутам и помогает находить потенциальные узкие места. Подходит как быстрый «advice layer» при планировании долгой партии. | [GitHub](https://github.com/NESTREN/openttd-smart-advisor) |

### 🧩 Core / Protocol
| Проект | Описание | Ссылка |
|---|---|---|
| **nestren-protocol** | Базовый протокол/контракт для обмена данными между сервисами и проектами: задаёт общую структуру взаимодействия и облегчает интеграции между репозиториями. | [GitHub](https://github.com/NESTREN/nestren-protocol) |
| **mesh-erl-protocol** | Протокол для mesh/ERL-модели взаимодействия сервисов: помогает стандартизировать интеграции и формат обмена между узлами системы. | [GitHub](https://github.com/NESTREN/mesh-erl-protocol) |
| **security-connect-protocol** | Протокол безопасного соединения с акцентом на security-first подход: единые правила подключения, обмена и валидации взаимодействий. | [GitHub](https://github.com/NESTREN/security-connect-protocol) |

---

## 📈 GitHub активность

<p>
  <img height="170" src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=nestren&theme=github_dark" alt="GitHub stats" />
  <img height="170" src="https://streak-stats.demolab.com?user=nestren&theme=tokyonight&hide_border=true" alt="GitHub streak" />
</p>

<p>
  <img width="100%" src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=nestren&theme=github_dark" alt="GitHub profile details" />
</p>

<p>
  <img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=nestren&theme=tokyo-night&hide_border=true" alt="GitHub activity graph" />
</p>

---

## 🧭 Roadmap
- [ ] Переводить новые проекты на PostgreSQL
- [ ] Контейнеризировать ботов через Docker
- [ ] Добавить фоновые задачи/очереди
- [ ] Настроить production-ready деплой на VPS
- [ ] Сделать свой boilerplate для Telegram-ботов

---

## 🎯 Цель
Расти как backend/Python-инженер и создавать полезные Telegram-продукты: от идеи до стабильного продакшн-решения.

## 📫 Контакты
- Telegram: **[@nestren](https://t.me/nestren)**
