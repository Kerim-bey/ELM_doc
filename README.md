# Документация языка ELM

## Введение

__Elm__ - функциональный язык, предназначенный для декларативного создания графических интерфейсов, основанных на браузере. Elm предоставляет возможность описывать графические интерфейсы, не выходя за рамки функциональной парадигмы, используя функционально-реактивный стиль программирования.

Разработан в 2012 году программистом Эваном Чаплицким (Evan Czaplicki) для дипломной работы по функциональному реактивному программированию для веб-интерфейсов. С первого выпуска в документации на язык было много примеров и имелся онлайн-редактор, благодаря чему есть возможность быстро попробовать программировать на Elm прямо в браузере.

## Почему именно функциональный язык?

Вы можете получить некоторые преимущества в принципе от программирования в функциональном стиле, но есть некоторые вещи, которые вы можете получить только от функционального языка, такого как Elm:
  * Никаких ошибок выполнения на практике;
  * Дружелюбные сообщения ошибок;
  * Надежный рефакторинг;
  * Автоматическое принудительное семантическое управление версиями для всех пакетов Elm.
  
Никакая комбинация библиотек JS не сможет дать вам все эти возможности. Они приходят от дизайна самого языка! И благодаря этим возможностям программисты Elm часто говорят, что никогда не чувствовали себя так уверенно при программировании. Уверены, что быстро смогут добавить функции. Уверены в рефакторинге тысяч строк всякого беспокойства, что было пропущено что-то важное!

## Основы языка
### Переменные

Самый маленький строительный блок в Elm называется переменной. Она может быть такими значениями, как 42, True и «Привет!».
```
> 2 + 2
4
> "hello"
"hello"
> "hello " ++ "user"
"hello user"

```
 
