<<<<<<< HEAD
<<<<<<< HEAD
# Блочна модель і позиціонування 
### Блочна модель
1. Блочні і текстові елементи.
1. `display`
  - `none`
  - `block`
  - `inline`
  - `inline-block`
  - `table-row`
  - `table-cell`
1. `width`
1. `height`
1. `margin`
  - накладання відступів
  - вихід відступів за межі батьківського елемента
1. `padding`
1. `border`
1. `box-sizing`
1. `overflow`

### Позиціонування
1. `vertical-align`
1. `position`
  - `static`
  - `relative`
  - `absolute`
  - `fixed`
1. `float`
1. `clear`

---
# Домашнє завдання
1. Зверстати шапку даного [макету](https://www.dropbox.com/s/oq6apyqrara7b4a/09_contact.psd?dl=0). А саме блоки з даного [скріншоту](http://screencast.com/t/gN7BwG27mdP)
1. Для верстки текту користуватись напрацюваннями з попереднього уроку:
  - Підключити файл стилів `normalize.css`.
  - Підключити нестандартний шрифт, що використовується на сторінці.


---
# Лінки
- [CSS для JavaScript-разработчика](https://learn.javascript.ru/css-for-js)
- [Блочная модель](http://xiper.net/learn/css/box-model/what-is-the-box-model)
- [Варианты «clearfix-хака» и его замен: сводная таблица](http://css-live.ru/articles-css/clearfix-block-formatting-context-methods-cheatsheet.html)
- [CSS позиционирование](http://html5book.ru/css-position/)
- [Как работает автоматическое позиционирование в CSS?](http://frontender.info/how-does-auto-positioning-work-in-css/)
- [Магические числа в CSS](http://frontender.info/magic-numbers-in-css/)
- [Generator vertical rhythm](https://www.gridlover.net/try)
=======
# Адаптивний веб-дизайн
### Поняття `viewport`
1. `<meta name="viewport" content="width=device-width, initial-scale=1">`
1. `width`
1. `initial-scale`
1. `minimum-scale`
1. `maximum-scale`
1. `user-scalable`

### Синтаксис
1. `<link rel="stylesheet" media="(max-width: 992px)" href="example.css" />`
1. `@media (max-width: 992px) {}`
1. `@supports` [?](https://habrahabr.ru/post/178021/)
1. Логічні оператори
  - `and`
  - `not`
  - `,`
1. Типи пристроїв [?](https://webref.ru/css/media)
  - `all`
  - `print`
  - `speech`
  - `screen`
1. Media Features
  - `width`
  - `height`
  - `orientation`
  - `resolution`

---
# Домашнє завдання
1. Адаптувати результат ДЗ з 6-го уроку для мобільних пристроїв.
1. Мінімальна ширина екрану — `320px`.

---
# Лінки
- [5 распространенных проблем, которые решает адаптивная верстка](https://habrahabr.ru/company/yandex/blog/307064/)
- [Разработка дизайна по контрольным точкам](http://frontender.info/designing-for-breakpoints/)
- [Выбираем решение для изображений в отзывчивом дизайне](http://frontender.info/choosing-a-responsive-image-solution/)
- [Простой способ сделать отзывчивые изображения с помощью фоновых картинок в CSS](http://frontender.info/simple-responsive-images-with-css-backgrounds/)
- [Теперь WebKit поддерживает srcset, и это здорово!](http://frontender.info/webkit-implements-srcset-and-why-its-a-good-thing/)
- [MDN. @media](https://developer.mozilla.org/en-US/docs/Web/CSS/@media)
- [Responsive Display Text](https://24ways.org/2016/responsive-display-text/)
- [На 100% правильный способ делать контрольные точки в CSS](http://css-live.ru/articles-css/pravilnye-kontrolnye-tochki-v-css.html)
=======
# Основи FlexBox
### Властивості `flex`-контейнера
1. `display: flex`
1. `flex-direction`
  - `row`
  - `row-reverse`
  - `column`
  - `column-reverse`
1. `flex-wrap`
  - `nowrap`
  - `wrap`
  - `wrap-reverse`
1. `justify-content`
  - `flex-start`
  - `flex-end`
  - `center`
  - `space-between`
  - `space-around`
1. `align-items`
  - `flex-start`
  - `flex-end`
  - `center`
  - `stretch`
1. `align-content`
  - `flex-start`
  - `flex-end`
  - `center`
  - `space-between`
  - `space-around`
  - `stretch`

### Властивості `flex`-елемента
1. `order`
1. `flex-grow`
1. `flex-shrink`
1. `align-self`
1. `flex-basis` vs `width`

---
# Домашнє завдання
1. Зверстати шапку даного [макету](https://www.dropbox.com/s/oq6apyqrara7b4a/09_contact.psd?dl=0). А саме блоки з даного [скріншоту](http://screencast.com/t/gN7BwG27mdP) не використовуючи `float`. Лише FlexBox.

---
### Лінки
- [Автопрефиксер онлайн](https://autoprefixer.github.io/)
- [flexbox playground and code generator](http://the-echoplex.net/flexyboxes/)
- [Flexible Boxes](http://flexible-boxes.wstone.io/)
- [Размер flex-элемента](http://shpargalkablog.ru/2016/05/flex.html)
- [Полное руководство по Flexbox](http://frontender.info/a-guide-to-flexbox/)
- [A Visual Guide to CSS3 Flexbox Properties](https://scotch.io/tutorials/a-visual-guide-to-css3-flexbox-properties)
- [A Complete Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
- [Знакомство с CSS Flexbox](https://youtu.be/7Lg-438gAc8?list=PLqHlAwsJRxAPs942EdJ1akeWpOg2yatiM)
- [Шпаргалка по шпаргалке по Flexbox](http://css-live.ru/articles-css/shpargalka-po-shpargalke-po-flexbox.html)
- [Грядут гриды!](http://css-live.ru/verstka/gryadut-gridy.html)
>>>>>>> 3342ffe381fb0260d6cd6694fa30c9fdfbd53e15
=======
## Курс по основах Front end від [IT Академії stfalcon.com](http://academy.stfalcon.com) 
> Ця вітка створення для того, щоб заливати фінальну роботу.
>>>>>>> b9fea004830082f33d433b03bacda47b121398ac
