# innoseti_test_task
### Репозиторий с тестовым заданием


Чтобы не загружать все зависимости, можно использовать докер:
```sh
docker build -t $name .
docker run -p 80:5000 $name
```

Тестовый запрос:
```sh
curl 127.0.0.1/api/login --json '{"password":"secret","username":"user"} -H 'Authorization: token'
```
---
Задание с SQL представлено в файле [task.sql](task.sql)

---
Текстовые задания представлены в файле [Текстовые задания](<Текстовые задания.txt>)
