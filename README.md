### Hexlet tests and linter status:
[![Actions Status](https://github.com/kirzep/devops-for-developers-project-74/actions/workflows/hexlet-check.yml/badge.svg)](https://github.com/kirzep/devops-for-developers-project-74/actions)

[![CI](https://github.com/kirzep/devops-for-developers-project-74/actions/workflows/push.yml/badge.svg)](https://github.com/kirzep/devops-for-developers-project-74/actions/workflows/push.yml)

## Требования

- Docker
- Docker Compose
- Make

## Установка и запуск

Клонируйте репозиторий:

```bash
git clone https://github.com/kirzep/devops-for-developers-project-74.git
cd devops-for-developers-project-74
```

Создайте файл `.env` на основе примера:

```bash
cp .env.example .env
```

Запуск в режиме разработки:

```bash
make dev
```

Приложение будет доступно по адресу https://localhost (через Caddy) или http://localhost:8080 напрямую.

## Тесты

```bash
make test
```

## Продакшен-образ

Образ на DockerHub: `kirzep/devops-for-developers-project-74`
