## **Golang Developer · HSE University · 3nd-year Student**

<div style="display: flex; flex-direction: column; gap: 5px;">
  <div>
    Резюме: <a href="https://github.com/ilyaytrewq/ilyaytrewq/blob/master/Tikhonov_Ilya.pdf" target="_blank">Tikhonov_Ilya_CV</a>
  </div>
  <div>
    Почта: <a href="mailto:tixonovilya324@gmail.com">tixonovilya324@gmail.com</a>
  </div>
  <div>
    Телеграм: <a href="https://t.me/ilyaytrewq" target="_blank">@ilyaytrewq</a>
  </div>
</div>




---



## Tech Stack

![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Apache Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=for-the-badge&logo=apache-kafka&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

---

## Projects


* **partner-api-llm-reports** — Сервис на Go: собирает данные из партнёрского API, агрегирует и генерирует email-отчёты с помощью LLM (асинхронно через Kafka)\
  *Tech Stack:* Go, Kafka, PostgreSQL, Ollama, Qwen2.5, SMTP, Prometheus/Grafana

* **anti-plagiarism-service** — Микросервисный антиплагиат: загрузка файлов, асинхронный анализ, поиск похожих фрагментов через embeddings + Qdrant \
  **[anti-plagiarism-service](https://github.com/ilyaytrewq/Anti-Plagiarism-Service)**\
  *Tech Stack:* Go, PostgreSQL, Qdrant, S3, Docker, CI/CD

* **payments-service** — Микросервисы заказов и платежей: асинхронные платежи через Kafka, Outbox/Inbox, Idempotency-Key для POST, API gateway (HTTP) + внутренний gRPC\
    **[payments-service](https://github.com/ilyaytrewq/Payments-Service)**  \
  *Tech Stack:* Go, Kafka, gRPC, PostgreSQL, Redis, Docker, GitHub Actions (CI/CD)

* **metricsys** — Микросервисная система веб-метрик на C++: REST приём, RabbitMQ очередь, хранение в PostgreSQL; агрегация по gRPC в 5-минутные бакеты + health-check сервис\
  **[metricsys](https://github.com/ilyaytrewq/MetricService)**\
Tech Stack: C++23, gRPC/Protobuf, RabbitMQ, PostgreSQL, Docker, CMake

* **weather-service** — Подписки на погоду: планирование рассылок, RabbitMQ, отправка SMTP/Telegram\
 **[weather-service](https://github.com/ilyaytrewq/WeatherService)**
  \
  *Tech Stack:* Go, PostgreSQL, RabbitMQ, Docker, SMTP, Telegram Bot, Migrations (goose), Cron



