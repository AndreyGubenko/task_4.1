[<--- к содержанию](./readme.md)


# Подготовительный этап

* ## Имя и электронная почта

Для начала необходимо провести установку имени и электронной почты.Делается это следующим образом:

```
git config --global user.name "Your Name"
git config --global user.email "your_email@whatever.com"
```

* ## Окончания строк

Для пользователей Windows:

```
git config --global core.autocrlf true
git config --global core.safecrlf warn
```

Для пользователей Unix/Mac:

```
git config --global core.autocrlf input
git config --global core.safecrlf warn
```

[следующая страница--->](./сreating.md)

