# VK Quick
[![Downloads](https://static.pepy.tech/personalized-badge/vkquick?period=total&units=international_system&left_color=black&right_color=orange&left_text=Downloads)](https://pepy.tech/project/vkquick)

> Хорошие инструменты порождают не только творения, но и идеи

Можно много говорить о нем, но сразу перейдем к созданию бота ВК.

# Установка
```bash
python -m pip install vkquick
```
> "Я новичок, плохо представляю себе, как работают боты и REST API/как что-то делать в терминале/что такое `async def`/мне кажется это сложным". Для
> тебя есть подробнейший гид, рассказывающий про все, что скрывается за красивым примером в пару строк, каким-то чудом запускающий бота. Он здесь: {later}

# Использование
Насколько VK Quick позволяет быть ленивым?

```python
import vkquick as vq


bot =  vq.Bot.init_via_token("token")


@bot.add_command(names="hello")
def hello():
    return "hi!"


bot.run()
```

Мы же не пришли сюда смотреть на hello world, верно? Давайте что-нибудь по-серьезнее

```shell script
vq new Mybot
cd MyBot
```

Мои поздравления, теперь мы готовы писать ботов в стиле фласка под архитектурой джанги!
Вместо монотонного копипаста у нас есть CLI — терминальный интерфейс, который сделает нам
все что угодно. И команда для терминала выше сделает нам заготовку с двумя командами: помощь по всем командам
и сводку на самого бота. Давайте запустим и посмотрим, что же из этого вышло

```shell script
python -m src
```

Скорее бежим в лс боту...
***
Я подожду
***
Готовы?
***
Пишем ему `::readme`
***
Еще?)
***
`/help readme`
***
А если попробовать `/help`? 
***
... А оно само? А как свое? А так везде?
***
{doc link}

***
***

PS: Установка до релиза:
```shell script
python -m pip install git+https://github.com/Rhinik/vkquick@1.0
```