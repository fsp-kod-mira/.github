# Хакатон "Код мира" в Сеавстополе

## Деплой

### BACKEND

Деплой бекенд части решения можно осуществить при помощи репозитория [backend-app](https://github.com/fsp-kod-mira/backend-app).

Следующая команда клонирует репозиторий со всеми сабмодулями
```
git clone --recursive https://github.com/fsp-kod-mira/backend-app.git
```

В этом репозитории описаны все компоненты системы. Локальный деплой приложения можно осуществить с помощью Docker
```
docker compose up --build
```

### FRONTEND

Фронтенд был написан с использованием Next.JS и находится в репозитории [frontend](https://github.com/fsp-kod-mira/frontend-main)
