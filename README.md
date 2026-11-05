<div align="center">
  <img src="assets/banner.png" alt="Адис Абенов — Product Engineer: AI-инфраструктура, веб-платформы, 3D" width="100%" />
</div>

<br />

<p align="center">
  <sub><b>RU</b> · <a href="README.en.md">EN</a></sub>
</p>


<p align="center">
  <a href="https://novastep.tech"><img src="https://img.shields.io/badge/NeuroHub-AI%20Infrastructure-000000?style=for-the-badge&logo=openai&logoColor=white" alt="NeuroHub"></a>
  <a href="https://stratium-ai-landing.vercel.app"><img src="https://img.shields.io/badge/Stratium%20AI-Windows%20Agent-1A1A1A?style=for-the-badge&logo=windows&logoColor=white" alt="Stratium AI"></a>
  <a href="mailto:adis040512@gmail.com"><img src="https://img.shields.io/badge/Email-Написать-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
</p>

<h3 align="center">Строю продукты целиком: от архитектуры и бэкенда до интерфейса и деплоя</h3>

<p align="center">
  <em>AI-инфраструктура · веб-платформы · realtime и 3D · 24 продукта в работе</em>
</p>

---

## Коротко о себе

Меня зовут **Адис Абенов**, я product-инженер. Беру задачу на уровне идеи и довожу до состояния «работает у людей»: проектирую архитектуру, пишу бэкенд и фронтенд, настраиваю инференс моделей, платежи, деплой и мониторинг.

За два года — **35 репозиториев с коммитами и 24 запущенных продукта**: от AI-маркетплейса с оплатой по токенам до 3D-игры в браузере и банковской платформы. Часть кода закрыта коммерческой тайной и NDA — в таких случаях я показываю продукт и описываю инженерные решения, но не исходники.

> **Принцип:** сначала работающий сценарий для пользователя, потом красивая архитектура. Продукт без пользователя — это папка с файлами.

---

## Избранные проекты

### Stratium AI — автономный агент для Windows

<div align="center">
  <a href="https://stratium-ai-landing.vercel.app"><img src="assets/stratium.png" alt="Stratium AI — лендинг автономного ИИ-агента" width="100%" /></a>
</div>

Агент, который управляет компьютером: ставит задачи, работает с приложениями и файлами, держит контекст между сессиями и умеет жить автономно до 10 дней. Я сделал продукт целиком — позиционирование, лендинг, дизайн-систему, тексты, интерактив и сборку под Windows.

**Стек:** TypeScript, React, Vite, собственные анимации на CSS/Canvas
**Что было сложным:** объяснить «агента на компьютере» без магии — через демонстрацию сценариев, а не через список фич

<p>
  <a href="https://github.com/Adis773/stratium-ai-landing"><img src="https://img.shields.io/badge/Код-открыт-2EA043?style=flat-square&logo=github&logoColor=white" alt="Код открыт"></a>
  <a href="https://stratium-ai-landing.vercel.app"><img src="https://img.shields.io/badge/Демо-live-0A66C2?style=flat-square" alt="Демо"></a>
  <img src="https://img.shields.io/badge/Платформа-Windows%2010%20%2F%2011-555555?style=flat-square" alt="Windows 10 / 11">
</p>

### Cyberpunk Megapolis — 3D-игра в браузере

<div align="center">
  <a href="https://cyberpunk-megapolis.vercel.app"><img src="assets/cyberpunk.png" alt="Cyberpunk Megapolis — 3D-игра с полётом на паутине" width="100%" /></a>
</div>

Полёт на паутине между небоскрёбами: собственная физика тросов, процедурная застройка, динамическое освещение и потоковая подгрузка моделей и текстур. Отдельная гордость — пайплайн ассетов: персонаж с PBR-текстурами, нормалями и металличностью, который не убивает производительность.

**Стек:** JavaScript, Three.js/WebGL, GLSL-шейдеры, кастомный загрузчик ассетов
**Что было сложным:** удержать 60 FPS на слабых ноутбуках — бюджет полигонов, батчинг, ленивая загрузка секторов города

<p>
  <a href="https://github.com/Adis773/cyberpunk-megapolis"><img src="https://img.shields.io/badge/Код-открыт-2EA043?style=flat-square&logo=github&logoColor=white" alt="Код открыт"></a>
  <a href="https://cyberpunk-megapolis.vercel.app"><img src="https://img.shields.io/badge/Играть-live-E4405F?style=flat-square" alt="Играть"></a>
  <img src="https://img.shields.io/badge/3D-WebGL-9900EF?style=flat-square" alt="WebGL">
</p>

### AlphaBot Quantum — панель автономного трейдинг-агента

<div align="center">
  <a href="https://tradinbot.vercel.app"><img src="assets/alphabot.png" alt="AlphaBot Quantum — панель управления торговым агентом" width="100%" /></a>
</div>

Интерфейс управления торговым агентом: стартовый капитал, запуск цикла анализа, живой поток событий, экспорт логов. Задача была не «нарисовать дашборд», а сделать прозрачным то, что обычно скрыто: видно каждый шаг решения и каждую сделку.

**Стек:** TypeScript, React, realtime-стрим событий, Firebase
**Что было сложным:** визуализировать работу агента так, чтобы трейдер доверял, а не гадал

<p>
  <a href="https://github.com/Adis773/Tradinbot"><img src="https://img.shields.io/badge/Код-открыт-2EA043?style=flat-square&logo=github&logoColor=white" alt="Код открыт"></a>
  <a href="https://tradinbot.vercel.app"><img src="https://img.shields.io/badge/Демо-live-0A66C2?style=flat-square" alt="Демо"></a>
</p>

---

## Закрытые продукты

> Здесь исходный код закрыт: NDA, коммерческая разработка или подготовка к релизу. Могу показать продукт и разобрать архитектуру на созвоне — код по договорённости.

### NeuroHub — инфраструктура AI-моделей

<div align="center">
  <img src="assets/neurohub.png" alt="NeuroHub — каталог AI-моделей, чат и OpenAI-совместимый API" width="100%" />
</div>

Платформа, где авторы загружают веса моделей, а инференс идёт на собственных GPU: каталог с ценами за миллион токенов, веб-чат с оплатой по факту, OpenAI-совместимый API и единый счёт на все модели. Флагманский проект: биллинг, оркестрация инференса, стриминг ответов, мультиарендность.

**Роль:** архитектура, бэкенд, фронтенд, инфраструктура
**Статус:** закрытая разработка, демо по запросу

<p>
  <img src="https://img.shields.io/badge/NeuroHub-live-000000?style=flat-square" alt="NeuroHub live">
  <img src="https://img.shields.io/badge/Код-закрыт%20(NDA)-555555?style=flat-square&logo=lock&logoColor=white" alt="Код закрыт">
</p>

### BankFlow — розничная банковская платформа

<div align="center">
  <img src="assets/bankflow.png" alt="BankFlow — банковская платформа: счета, платежи, карты, инвестиции" width="100%" />
</div>

Модульный монолит на FastAPI плюс Next.js-кабинет: счета, переводы, карты, кредиты, бюджеты и цели, инвестиции, аналитика. Отдельно — выделение нагруженных доменов в сервисы за API-шлюзом и Kubernetes-манифесты.

**Стек:** Python/FastAPI, Next.js, PostgreSQL, Kubernetes
**Статус:** коммерческая разработка, код закрыт

### GameViki — энциклопедия видеоигр

<div align="center">
  <img src="assets/gameviki.png" alt="GameViki — каталог игр, рецензии, оценки, подборки" width="100%" />
</div>

Каталог игр с рецензиями, оценками и подборками: админка для редакции, полнотекстовый поиск, медиа-пайплайн и модерация пользовательского контента. Продукт про контент, а не про «ещё один сайт с карточками».

**Стек:** React, Node.js, PostgreSQL, Redis
**Статус:** закрытая разработка

---

## Ещё в работе

| Проект | Что это | Статус |
| :-- | :-- | :-- |
| **Easgik** | Кабинет единой службы геодезии и кадастра: заявки, документы, личный кабинет | Коммерческий клиент, [демо](https://v0-easgikcabinet-l5.vercel.app) |
| **SmartLearnix** | AI-платформа обучения с персональной программой, геймификацией и аналитикой | [Открытый код](https://github.com/Adis773/SmartLearnix) |
| **ABEBA Bank** | Мемный банк с нулевыми комиссиями — продуктовый эксперимент про бренд и виральность | [Открытый код](https://github.com/Adis773/Abeba-bank-) |
| **TgClone** | Клиент мессенджера на React: чаты, медиа, realtime-обновления | [Открытый код](https://github.com/Adis773/Tgclone) |
| **freeGPT** | Интерфейс доступа к моделям без ключей и настройки | [Открытый код](https://github.com/Adis773/freeGPT) |
| **AirOS** | Веб-«операционная система» в браузере: окна, файлы, приложения | [Открытый код](https://github.com/Adis773/AirOs) |

---

## Стек

<p>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript">
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React">
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" alt="Next.js">
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI">
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL">
  <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" alt="Redis">
  <img src="https://img.shields.io/badge/Three.js-000000?style=for-the-badge&logo=threedotjs&logoColor=white" alt="Three.js">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker">
</p>

Умею и то, что вокруг кода: продуктовые решения, дизайн интерфейсов, тексты, аналитика, деплой и поддержка в проде.

---

## GitHub в цифрах

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=Adis773&show_icons=true&theme=tokyonight&hide_border=true&rank_icon=github&include_all_commits=true" alt="Статистика GitHub" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Adis773&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" alt="Основные языки" />
</p>

---

## Как я работаю

| Шаг | Что происходит |
| :--: | :-- |
| **01** | Разбираю задачу до пользовательского сценария: кто, зачем, что должно получиться на выходе |
| **02** | Собираю каркас: схема данных, API, ключевые экраны. Проверяю на реальных данных, а не на мокапах |
| **03** | Довожу до продакшена: тесты на критичные пути, логи, метрики, обработка ошибок, деплой |
| **04** | Остаюсь на связи после релиза: правки, развитие, передача кода и документации |

---

<div align="center">

### Есть задача, которую нужно довести до работающего продукта?

Пишите — отвечу и предложу решение, а не прайс на человеко-часы.

<a href="mailto:adis040512@gmail.com"><img src="https://img.shields.io/badge/adis040512@gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
<a href="https://github.com/Adis773"><img src="https://img.shields.io/badge/github.com/Adis773-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"></a>

<sub>Открыт к интересным проектам · 2026</sub>

</div>
