# Roborace Rules & Regulations

[Правила соревнований](https://github.com/roborace-org/roborace-regulations/tree/master/ru)

# Генерация регламента в pdf

1. Установка grip
```
pip install grip
```
или
```
sudo apt install grip
```

2. Генерация pdf
```
rm ru/Содержание.md
cat ru/*.md > Roborace-Regulations.md
grip Roborace-Regulations.md
```

Запускаем в браузере -> Печать страницы -> Сохраняем в pdf
