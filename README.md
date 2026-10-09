Репозиторий технической поддержки ресурсов Международной лаборатории языковой конвергенции.

- [получить доступ к NAS](https://github.com/LingConLab/conlab-technical-issues/issues/new?template=nas-user-creation.yml)
- [получить доступ к серверу](https://github.com/LingConLab/conlab-technical-issues/issues/new?template=server-user-creation.yml)

## Подключение к NAS

Из сети Вышки

- наберите в браузере `http://172.16.232.30:5000/` и введите логин и пароль
- наберите в файловом менеджере `smb://172.16.232.30` и введите логин и пароль

## Подключение к серверу

Для подключения к серверу наберите в консоли:

```
ssh username@lingconlab.ru -p 42 -i username.key
```

Может понадобиться смена прав ключа авторизации (ошибка public.key access too open):

```
chmod 700 username.key
```
