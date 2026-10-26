
Учебный инфраструктурный репозиторий: Git, Ansible и Docker.
Отредактировано через веб-интерфейс GitHub.
##Запуск в Docker
```bash
docker build -t infra-web:1.0 docker/
docker run -d --name infra-web -p 8080:80 infra-web:1.0
curl http://localhost:8080
```
