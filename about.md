---
layout: page
title: Про предмет
description: Загальна інформація.
nav_order: 1
---

# Про предмет
{:.no_toc}

## Зміст
{: .no_toc .text-delta }

1. TOC
{:toc}

---

{% assign overview = site.slides | where: "title", "Огляд" | first %}
{{ overview.content }}


Потрiбнi навички
: - Рівень володіння англійською мовою не нижче А2.
- **Математика**: знання та вміння використовувати обчислення, аналітичну геометрію, лінійну алгебру та теорію ймовірностей.
- **Програмування**: вміння програмувати на Python.


Підручники
: 1. Кочура Ю. П., Гордієнко Ю. Г. (2024). [*Машинне навчання*](https://drive.google.com/file/d/130ruX0CGGNtX1E39Y622Bu_CThHjb9nc/view?usp=sharing).
1. Goodfellow, I., Bengio, Y., & Courville, A. (2016).  [*Deep Learning.* ](https://www.deeplearningbook.org/) MIT press.
1. Sutton, R. S., & Barto, A. G. (2018). [*Reinforcement learning: An introduction*](http://incompleteideas.net/book/the-book-2nd.html). MIT press.
1. Russell, S., & Norvig, P. (2021). [*Artificial Intelligence: A Modern Approach.*](https://www.amazon.com/Artificial-Intelligence-A-Modern-Approach/dp/0134610997#customerReviews)

Курс лекцій
: 1. Таран В. І., Гордієнко Ю. Г., Стіренко С. Г. (2024). [*Вступ до технологій штучного інтелекту*](https://ela.kpi.ua/bitstreams/034ae945-e7a1-4827-86c1-e89ec447a011/download).


## На випадок повітряної тривоги
{% assign specifics = site.slides | where: "title", "Повітряна тривога" | first %}
{{ specifics.content }}

## Особливостi
{% assign specifics = site.slides | where: "title", "Особливостi" | first %}
{{ specifics.content }}

## Система оцiнювання
{% assign grading = site.slides | where: "title", "Система оцiнювання" | first %}
{{ grading.content }}


## Кодекс честi
{% assign honorcode = site.slides | where: "title", "Кодекс честi" | first %}
{{ honorcode.content }}


## Як успішно завершити курс?
{% assign succeed = site.slides | where: "title", "Як успішно завершити курс?" | first %}
{{ succeed.content }}