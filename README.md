## Проекты

Каждый проект выложен рабочим: с тестами, CI, релизом и (где есть браузерная часть) живой демо-страницей. Релизы содержат контрольные суммы и подтверждение происхождения сборки (`gh attestation verify`).

| Проект | Что это | Стек | Демо |
|---|---|---|---|
| [ru-kit](https://github.com/Oleg4311/ru-kit) | Русская локаль без зависимостей: числа и суммы прописью, склонение по числу, проверка ИНН/СНИЛС/ОГРН, транслитерация, телефоны. `npm i @oleg4311/ru-kit` | TypeScript | [песочница](https://oleg4311.github.io/ru-kit/) |
| [pg-job-queue](https://github.com/Oleg4311/pg-job-queue) | Очередь задач на одном PostgreSQL: `SKIP LOCKED`, аренда с heartbeat, ретраи, транзакционный enqueue | Go, PostgreSQL | — |
| [rate-limiter-lab](https://github.com/Oleg4311/rate-limiter-lab) | Сравнение алгоритмов ограничения частоты (Go-библиотека, сервис, WASM-демо в браузере, нагрузка k6) | Go, WASM | [демо](https://oleg4311.github.io/rate-limiter-lab/) |
| [byo-redis-go](https://github.com/Oleg4311/byo-redis-go) | Свой Redis-совместимый сервер: протокол RESP, журнал AOF, проверяется настоящим `redis-cli` | Go | [демо](https://oleg4311.github.io/byo-redis-go/) |
| [logpulse](https://github.com/Oleg4311/logpulse) | Анализатор access-логов: rps, перцентили задержки, топ эндпоинтов, аномалии. CLI и демо на WebAssembly | Go, WASM | [демо](https://oleg4311.github.io/logpulse/) |
| [release-receipt](https://github.com/Oleg4311/release-receipt) | Сверка коммита, CI и реально развёрнутой версии сайта: CLI и JSON-квитанция выпуска | TypeScript, Node.js | [демо](https://oleg4311.github.io/release-receipt/) |
| [race-replay](https://github.com/Oleg4311/race-replay) | Интерактивный разбор гонки запросов в React | React, TypeScript | [демо](https://oleg4311.github.io/race-replay/) |
| [secret-santa](https://github.com/Oleg4311/secret-santa) | Тайный Санта без сервера: пары живут в личных ссылках | TypeScript | [демо](https://oleg4311.github.io/secret-santa/) |
| [contrast-lab](https://github.com/Oleg4311/contrast-lab) | Проверка контраста цветов по WCAG с подбором ближайшего доступного цвета | JavaScript | [демо](https://oleg4311.github.io/contrast-lab/) |
| [photo-recovery](https://github.com/Oleg4311/photo-recovery) | Восстановление удалённых фото из образов дисков | Python | — |
| [ai-media-telegram-bot](https://github.com/Oleg4311/ai-media-telegram-bot) | Telegram-бот для генерации изображений и видео | NestJS, PostgreSQL, Redis | — |

---

## Projects (English)

Production-minded side projects in TypeScript, Go and Python — each with tests, CI, a release with checksums and build provenance, and a live demo where there is a browser part. Highlights: a PostgreSQL job queue in Go (`SKIP LOCKED`, leases, transactional enqueue), a Redis-compatible server verified with the real `redis-cli`, a rate-limiter lab with a WASM demo, and a zero-dependency Russian-locale toolkit published on npm as `@oleg4311/ru-kit`.
