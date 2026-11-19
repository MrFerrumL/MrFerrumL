![MrFerrumL — Павел, Applied ML / Backend](./profile-banner.svg)

**[Портфолио на GitHub Pages](https://mrferruml.github.io/)**

## Обо мне

Привет, я Павел. Занимаюсь **прикладным машинным обучением и Python-разработкой**. Мне интересно, как модель становится частью приложения. В своих проектах работаю с табличными данными, проверяю модели на отложенных выборках и подключаю их к поиску или API.

**ML и данные** · `Python` · `pandas` · `scikit-learn` · `ONNX Runtime`  
**Разработка** · `Django` · `FastAPI` · `PostgreSQL` · `Docker`

[Прикладной ML](#прикладной-ml) · [Другие проекты](#другие-проекты) · [Достижения](#соревнования-и-форумы) · [Telegram](https://t.me/Fucject)

## Прикладной ML

### Инфокод — поиск похожих задач по смыслу

Рабочая платформа для подготовки к ЕГЭ по информатике и физике с банком задач, курсами и кабинетом преподавателя. Для подбора похожих заданий `multilingual-e5-small` в формате ONNX преобразует условия в эмбеддинги. Платформа ранжирует задания по косинусному сходству, а векторы для новых и изменённых задач обновляет в фоне.

[Сайт ↗](https://infocode1.ru/) · [Кейс и архитектура](https://github.com/MrFerrumL/infocode/blob/main/docs/CASE_STUDY.md) · [Скриншоты](https://github.com/MrFerrumL/infocode/blob/main/docs/SCREENSHOTS.md)

### Умный кредитный кабинет — воспроизводимый ML-эксперимент

Добавил к хакатонному прототипу модель риска на логистической регрессии. Эксперимент включает генерацию 12 000 синтетических записей, обучение, подбор порога на валидации и экспорт модели в JSON. На отложенной синтетической выборке **ROC-AUC составил 0,784** против **0,500** у базового прогноза. Отдельный API показывает аналитику прогноз и вклад признаков.

[Репозиторий](https://github.com/MrFerrumL/alpha-smart-credit-cabinet) · [Карточка модели](https://github.com/MrFerrumL/alpha-smart-credit-cabinet/blob/main/docs/ml-model-card.md) · [Отчёт с метриками](https://github.com/MrFerrumL/alpha-smart-credit-cabinet/blob/main/backend/app/ml/artifacts/evaluation.json)

### PostCode Challenge — планирование и прогноз для команд

Командный проект хакатона Почтатеха. Сервис превращает данные из Excel в квартальный план на шесть спринтов, учитывает компетенции и объясняет, почему задачи переносятся. Отдельный ML-эксперимент использует `Ridge` для прогноза выполненных story points. Ошибку измеряет на более поздних наблюдениях и сравнивает по MAE с базовым прогнозом на основе среднего по команде.

[Репозиторий](https://github.com/MrFerrumL/postcode-challenge) · [Код прогноза](https://github.com/MrFerrumL/postcode-challenge/blob/main/app/ml.py)

## Другие проекты

- **[Прогноз цены недвижимости](https://github.com/MrFerrumL/ND_prod_ML_sber)** — учебное сравнение линейной регрессии, Ridge и Lasso по RMSE с подбором параметров через `GridSearchCV`.
- **[Подготовка данных велопроката](https://github.com/MrFerrumL/Project_AI_test)** — работа с табличными данными в pandas и NumPy, извлечение часа из даты и кодирование категорий.
- **[Claude VPN Guard](https://github.com/MrFerrumL/claude-vpn-guard)** — приложение в трее Windows на C# и WinForms, которое проверяет состояние VPN при запуске Claude Desktop и следит за соединением.
- **[TT Bot Downloader](https://github.com/MrFerrumL/TT_bot_downloader)** — Telegram-бот на aiogram, который обрабатывает ссылки на видео через `yt-dlp` и позволяет выбрать качество.
- **[Лабораторные по ООП](https://github.com/MrFerrumL/oop-labs-1-3)** — задачи на Java 17 с Maven, от инкапсуляции и конструкторов до наследования и полиморфизма.

## Соревнования и форумы

- **1-е место в «Коде спорта» от Т‑Образования** в составе команды «Алгосы».
- **PostCode Challenge от Почтатеха** — участник команды «ИИ-плееры» в треке «Планирование команд и звездная карта». [Сертификат в репозитории](https://github.com/MrFerrumL/postcode-challenge#участие-в-хакатоне)
- **Молодёжный трек «ИИ прорыв»** — участник Всероссийского форума по подготовке кадров в области ИИ на базе КубГУ, Краснодар, октябрь 2026 года.

---

[Написать в Telegram ↗](https://t.me/Fucject) · [Все репозитории ↗](https://github.com/MrFerrumL?tab=repositories)
