<div align="center">
  <img src="assets/banner.png" alt="Абенов Адис — product engineer: AI-инфраструктура, веб-платформы, 3D" width="100%" />
</div>

<p align="center">
  <sub><a href="README.md">EN</a> · <b>RU</b></sub>
</p>

<p align="center">
  <a href="https://novastep.tech"><img src="https://img.shields.io/badge/NeuroHub-live-000000?style=for-the-badge&logo=openai&logoColor=white" alt="NeuroHub"></a>
  <a href="https://x.com/qwer_GenZ"><img src="https://img.shields.io/badge/X-@qwer__GenZ-000000?style=for-the-badge&logo=x&logoColor=white" alt="X"></a>
  <a href="mailto:adisabenov2@gmail.com"><img src="https://img.shields.io/badge/Email-написать-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://adisabenov.vercel.app"><img src="https://img.shields.io/badge/Портфолио-сайт-7C3AED?style=for-the-badge&logo=vercel&logoColor=white" alt="Портфолио"></a>
</p>

<h3 align="center">Строю продукты целиком: архитектура, бэкенд, интерфейс, инференс, деплой</h3>

<p align="center"><em>AI-инфраструктура · веб-платформы · realtime и 3D · 30+ запусков</em></p>

---

## Привет, я Адис

Меня зовут **Абенов Адис**, я product-инженер. Беру идею и довожу до состояния «работает у реальных людей»: проектирую архитектуру, пишу бэкенд и фронтенд, подключаю инференс моделей, платежи и мониторинг, потом поддерживаю в проде.

**30+ запущенных продуктов за два года** — AI-маркетплейс с оплатой по токенам, автономный агент для Windows, 3D-игра в браузере, AR-инструмент, банковская платформа, клиентские кабинеты и брендовые сайты. Часть кода закрыта NDA или коммерческой тайной: там я показываю продукт и объясняю инженерные решения, а не исходники.

> **Принцип:** сначала работающий сценарий для пользователя, потом красивая архитектура. Продукт без пользователя — это папка с файлами.

<div align="center">
  <img src="assets/stats.png" alt="30+ продуктов, 890+ коммитов за год, 35 проектов с кодом, 6 закрытых продуктов" width="100%" />
</div>

<p align="center">
  <a href="https://adisabenov.vercel.app"><b>→ Сайт-портфолио</b></a>
</p>

---

## Избранное

### NeuroHub — инфраструктура AI-моделей

<div align="center">
  <a href="https://novastep.tech"><img src="assets/neurohub.png" alt="NeuroHub — каталог AI-моделей, чат и OpenAI-совместимый API" width="100%" /></a>
</div>

Маркетплейс, где авторы загружают веса моделей, а инференс идёт на собственных GPU: каталог с ценами за миллион токенов, веб-чат с оплатой по факту, OpenAI-совместимый API и единый счёт на все модели. Биллинг, оркестрация инференса, стриминг ответов, мультиарендность — всё с нуля.

**Роль:** архитектура, бэкенд, фронтенд, инфраструктура
**Статус:** работает, код закрыт — демо по запросу

<p>
  <a href="https://novastep.tech"><img src="https://img.shields.io/badge/Открыть-live-2EA043?style=flat-square" alt="Live"></a>
  <img src="https://img.shields.io/badge/Код-закрыт%20(NDA)-555555?style=flat-square&logo=lock&logoColor=white" alt="Код закрыт">
</p>

### Stratium AI — автономный агент для Windows

<div align="center">
  <a href="https://stratium-ai-landing.vercel.app"><img src="assets/stratium.png" alt="Stratium AI — лендинг автономного ИИ-агента" width="100%" /></a>
</div>

Агент, который управляет компьютером: ставит задачи, работает с приложениями и файлами, держит контекст между сессиями и живёт автономно до 10 дней. Сделал продукт целиком — позиционирование, лендинг, дизайн-систему, тексты, интерактив и сборку под Windows.

**Стек:** TypeScript, React, Vite, собственные анимации на CSS/Canvas
**Сложное:** объяснить «агента на компьютере» без магии — через сценарии, а не списки фич

<p>
  <a href="https://stratium-ai-landing.vercel.app"><img src="https://img.shields.io/badge/Открыть-live-0A66C2?style=flat-square" alt="Live"></a>
  <a href="https://github.com/Adis773/stratium-ai-landing"><img src="https://img.shields.io/badge/Код-открыт-2EA043?style=flat-square&logo=github&logoColor=white" alt="Код"></a>
  <img src="https://img.shields.io/badge/Платформа-Windows%2010%20%2F%2011-555555?style=flat-square" alt="Windows">
</p>

### Cyberpunk Megapolis — 3D-игра в браузере

<div align="center">
  <a href="https://cyberpunk-megapolis.vercel.app"><img src="assets/cyberpunk.png" alt="Cyberpunk Megapolis — 3D-игра с полётом на паутине" width="100%" /></a>
</div>

Полёт на паутине между небоскрёбами: собственная физика тросов, процедурная застройка, динамическое освещение и потоковая подгрузка моделей и текстур. Отдельная гордость — пайплайн ассетов: PBR-персонаж с нормалями и металличностью, который не убивает производительность.

**Стек:** JavaScript, Three.js/WebGL, GLSL-шейдеры, свой загрузчик ассетов
**Сложное:** удержать 60 FPS на слабых ноутбуках — бюджет полигонов, батчинг, ленивая загрузка секторов

<p>
  <a href="https://cyberpunk-megapolis.vercel.app"><img src="https://img.shields.io/badge/Играть-live-E4405F?style=flat-square" alt="Играть"></a>
  <a href="https://github.com/Adis773/cyberpunk-megapolis"><img src="https://img.shields.io/badge/Код-открыт-2EA043?style=flat-square&logo=github&logoColor=white" alt="Код"></a>
  <img src="https://img.shields.io/badge/3D-WebGL-9900EF?style=flat-square" alt="WebGL">
</p>

---

## Ещё запуски

<table>
<tr>
<td width="50%" valign="top">
  <a href="https://tradinbot.vercel.app"><img src="assets/alphabot.png" alt="AlphaBot Quantum" width="100%" /></a>
  <b>AlphaBot Quantum</b> — пульт трейдинг-агента: капитал, циклы анализа, живой поток событий, экспорт логов.<br />
  <sub>React · TypeScript · Firebase</sub><br />
  <a href="https://tradinbot.vercel.app"><b>Live</b></a> · <a href="https://github.com/Adis773/Tradinbot">Код</a>
</td>
<td width="50%" valign="top">
  <a href="https://vilis.vercel.app"><img src="assets/vilis.png" alt="VILIS — AI-очки" width="100%" /></a>
  <b>VILIS</b> — запуск премиальных AI-очков: съёмка 1080p, 8 часов работы, встроенный ассистент.<br />
  <sub>Бренд-сайт · конверсия · анимация</sub><br />
  <a href="https://vilis.vercel.app"><b>Live</b></a>
</td>
</tr>
<tr>
<td width="50%" valign="top">
  <a href="https://fg-self.vercel.app"><img src="assets/ar3d.png" alt="AR 3D Builder" width="100%" /></a>
  <b>AR 3D Builder</b> — AR-редактор с трекингом рук: жест ставит блок, жест удаляет, сцена выгружается в JSON.<br />
  <sub>WebXR · MediaPipe · Three.js</sub><br />
  <a href="https://fg-self.vercel.app"><b>Live</b></a>
</td>
<td width="50%" valign="top">
  <a href="https://abebabank.vercel.app"><img src="assets/abeba.png" alt="ABEBA Bank" width="100%" /></a>
  <b>ABEBA Bank</b> — мемный банк с нулевыми комиссиями: эксперимент с брендом, виральностью и конверсией.<br />
  <sub>React · лендинг · Web3</sub><br />
  <a href="https://abebabank.vercel.app"><b>Live</b></a> · <a href="https://github.com/Adis773/Abeba-bank-">Код</a>
</td>
</tr>
<tr>
<td width="50%" valign="top">
  <a href="https://v0-easgikcabinet-l5.vercel.app"><img src="assets/easgik.png" alt="Easgik" width="100%" /></a>
  <b>Easgik</b> — кабинет службы геодезии и кадастра: заявки, документы, личный кабинет.<br />
  <sub>Коммерческий клиент · Next.js · Postgres</sub><br />
  <a href="https://v0-easgikcabinet-l5.vercel.app"><b>Live</b></a>
</td>
<td width="50%" valign="top">
  <a href="https://barber2-eight.vercel.app"><img src="assets/barber.png" alt="Barber Boss" width="100%" /></a>
  <b>Barber Boss</b> — премиальный барбершоп в Астане: услуги, интерьер, запись, уведомления в Telegram.<br />
  <sub>Клиентский сайт · запись · бренд</sub><br />
  <a href="https://barber2-eight.vercel.app"><b>Live</b></a>
</td>
</tr>
<tr>
<td width="50%" valign="top">
  <img src="assets/gameviki.png" alt="GameViki" width="100%" />
  <b>GameViki</b> — энциклопедия видеоигр: каталог, рецензии, оценки, подборки, админка редакции.<br />
  <sub>React · Node · Postgres · Redis</sub><br />
  <sub>Код закрыт · приватная бета</sub>
</td>
<td width="50%" valign="top">
  <img src="assets/bankflow.png" alt="BankFlow" width="100%" />
  <b>BankFlow</b> — розничный цифровой банк: счета, платежи, карты, кредиты, инвестиции, аналитика.<br />
  <sub>FastAPI · Next.js · Kubernetes</sub><br />
  <sub>Код закрыт · коммерческая разработка</sub>
</td>
</tr>
</table>

---

## Также в портфолио

| Продукт | Что это | Ссылка |
| :-- | :-- | :-- |
| **AInvest Terminal** | Инвестиционный терминал: портфель, доход за день, автоинвест 10% в акции, лента идей | [Live](https://assistent-nine.vercel.app) |
| **SmartLearnix** | AI-платформа обучения: персональные треки, геймификация, аналитика | [Код](https://github.com/Adis773/SmartLearnix) |
| **TgClone** | Клиент мессенджера на React: чаты, медиа, realtime | [Код](https://github.com/Adis773/Tgclone) |
| **freeGPT** | Интерфейс доступа к моделям без настройки | [Код](https://github.com/Adis773/freeGPT) |
| **AirOS** | «Операционная система» в браузере: окна, файлы, приложения | [Код](https://github.com/Adis773/AirOs) |
| **CryptoMain** | Крипто-портфель с авторизацией и живыми курсами | [Live](https://cryptomain.vercel.app) |
| **Stranger Things Shop** | Магазин мерча по франшизе: каталог, корзина, оформление | [Live](https://strangerthings-shop.vercel.app) |
| **Alpha Barbershop** | Второй бренд барбершопа с онлайн-записью | [Live](https://barber-delta-five.vercel.app) |

---

## Про закрытый код

Шесть продуктов работают с приватными репозиториями — **NeuroHub**, **BankFlow**, **GameViki**, **AInvest** и две клиентские системы под NDA. Это нормальная часть коммерческой разработки: продукт публичен, код — актив клиента.

Если нужно увидеть инженерную глубину, а не лендинг, — разберу архитектуру, модели данных и компромиссы на созвоне или покажу открытые проекты выше: они настоящие и полностью рабочие.

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
  <img src="https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Vercel">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker">
</p>

Умею и то, что вокруг кода: продуктовые решения, дизайн интерфейсов, тексты, аналитика, деплой и поддержка в проде.

---

## Как я работаю

| Шаг | Что происходит |
| :--: | :-- |
| **01** | Разбираю задачу до пользовательского сценария: кто, зачем, что должно получиться на выходе |
| **02** | Собираю каркас: схема данных, API, ключевые экраны — на реальных данных, а не на мокапах |
| **03** | Довожу до продакшена: тесты на критичные пути, логи, метрики, обработка ошибок, деплой |
| **04** | Остаюсь после релиза: правки, развитие, передача кода и документации |

---

<div align="center">

### Есть задача, которую нужно довести до работающего продукта?

Пишите — отвечу решением, а не прайсом за человеко-часы.

<a href="mailto:adisabenov2@gmail.com"><img src="https://img.shields.io/badge/adisabenov2@gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
<a href="https://x.com/qwer_GenZ"><img src="https://img.shields.io/badge/@qwer__GenZ-000000?style=for-the-badge&logo=x&logoColor=white" alt="X"></a>
<a href="https://github.com/Adis773"><img src="https://img.shields.io/badge/Adis773-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"></a>

<sub>Открыт к интересным проектам · 2026</sub>

</div>
