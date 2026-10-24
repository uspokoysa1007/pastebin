# pastebin

Self-hosted pastebin на Go: вставка текста по ссылке с истекающим сроком.

## Возможности (план)

- HTTP-сервер с REST API и простым веб-интерфейсом;
- создание паст с произвольным сроком жизни;
- подсветка синтаксиса;
- хранение в SQLite/PostgreSQL;
- rate limit и защита от спама;
- опция «сжечь после прочтения».

## Стек

- Язык: Go
- Планируемые библиотеки: stdlib `net/http`, `modernc.org/sqlite` или `lib/pq`

## Сборка и запуск

```bash
go build -o bin/pastebin .
./bin/pastebin -addr :8080
```

## Лицензия

MIT
