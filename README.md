# TextCardsMaker

Консольная программа, которая берёт список описаний и создает из них карточки. Например, есть список cards.md:
```
Что?
Куда?
Зачем?
Почему?
За что?
Точно?
```

И если запустить:
```
TextCardsMaker.exe --width=120 --height=120 --rows-count=2 --columns-count=2 cards.md
```

То программа создаст два файла:

![](./Docs/card0.png)

![](./Docs/card1.png)

## Параметры
```
TextCardsMaker.exe --help
```

## Почему это настольное приложение, а не браузерное?
Я тогда не умел делать браузерные приложения, возможно, в будущем доберусь и доделаю.

## Как это скомпилировать?
Достаточно запустить build.cmd для Windows или build.sh для Linux.
