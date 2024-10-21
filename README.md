# Работа с LaTeX 

Для выполнения L1
Был использован Overleaf

Для регистрации можно перейти по ссылке:
[OverLeaf](https://www.overleaf.com)

*OverLeaf — онлайн редактор Latex* 
## Использованные пакеты Latex

Для корректной работы в LaTeX нужно подключить специальные пакеты, в данной работе были использованы следующие:

```
\usepackage{scn} — Подключение scn-пакета
\usepackage{graphicx} —   В данном случае для управления картинками
\usepackage{multicol}  — Даёт возможность разделить страницу на 2 и более коллонны 
 \usepackage{setspace} — Позволяет легко управлять межстрочным интервалом 
 \usepackage{subcaption} — Подключает пакет subcaption, который позволяет создавать подрисунки и подтаблицы внутри фигур и таблиц
\setlength{\columnsep}{5mm}  — Устанавливает расстояние между колонками в многоколоночном документе. 
\usepackage{microtype} — Улучшает типографику документа
\captionsetup{justification=justified}  — используется для настройки выравнивания текста в подписях к рисункам и таблица
\usepackage{caption} — Предоставляет расширенные возможности для настройки подписей к рисункам и таблицам
\backgroundsetup{contents={}} — Используется в контексте пакета background, который позволяет добавлять фоновое содержимое на страницы документа. 
\pagestyle{plain} — Устанавливает стиль страницы для всего документа или для текущего раздела. 
\usepackage{amsmath,amssymb} — Подключает два пакета, предоставляемых Американским математическим обществом (AMS), которые значительно расширяют возможности работы с математическими формулами и символами.
 \geometry{
 a4paper,
 total={170mm,257mm},
 left=20mm,
 top=20mm,
 } — Используется для настройки параметров страницы документа
```

 ## Вставка фото

```\includegraphics[width=0.9\linewidth]{image/picture.png}
\includegraphics[width=0.9\linewidth]{image/picture1.png}
\includegraphics[width=1\linewidth]{image/picture2.png}
\includegraphics[width=1\linewidth]{image/picture3.png}
\includegraphics[width=0.95\linewidth]{image/picture3.png}```

## Римские цифры
 Была введена новая команда для нумерации заголовков с помощью римских цифр

```\newcommand{\upperRomannumeral}[1]{\uppercase\expandafter{\romannumeral#1}}```
Для использования нужно ввести команду вида
```\upperRomannumeral{}```

# Работа с Git'ом

Для выполнения L3
Были использованы Github & Git

*Github — веб-сервис хостинга проектов и их совместной разработки на базе Git*

[Github](https://github.com/)

*Git — система управления версиями*

[Git](https://git-scm.com/)
