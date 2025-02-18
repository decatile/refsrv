Проект исповедует чистую архитектуру, где FastAPI - лишь один из возможных портов, при помощи которого можно получить доступ к бизнес логике

Из этого также следует, что проект структурирован согласно этому концепту, поэтому папки находятся там, где вы ожидаете их увидеть

В docker-compose.yml подправьте переменные окружения (примеры находятся в .env.*.example)

Для запуска используйте `docker`, `podman` или `nerdctl`

```
> docker compose up
```

Для генерации OpenAPI документации используйте `python main.py -D`

Для просмотра документации во время работы проекта, используйте `/docs`, для ReDoc - `/redoc`
