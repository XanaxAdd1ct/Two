# BookLib — Library Manager

CLI-приложение для управления личной библиотекой книг.

## Требования

- Go 1.21+

## Установка

```
git clone https://github.com/yourname/booklib.git
cd booklib
go mod init booklib
```

## Запуск

```
go run ./...
```

## Работа

```
add Название|Автор|Жанр|Рейтинг
edit ID|Название|Автор|Жанр|Рейтинг
delete ID
list
list title
list date
list rating
search запрос
stats
help
exit
```

## Примеры

```
add Мастер и Маргарита|Булгаков|Роман|5.0
edit a1b2c3d4|Мастер и Маргарита|Булгаков|Мистика|4.8
delete a1b2c3d4
list
list rating
search Булгаков
stats
exit
```
