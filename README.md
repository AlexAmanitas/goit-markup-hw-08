# goit-markup-hw-08

ДЗ-08 Адаптивна верстка

1.  Стоит ли задать контейнеру "header menu" ширину чтобы можно было использовать margin-left:auto; для блока контактов? Задал "header menu", width: 100%; из-за этого стало складываться лого, задал лого flex-shrink: 0;, всё работает, это сильно костыль?

2.  Решил добавить в блок постоянных клиентов медиа-запрос для ширины экрана менее 480рх

3.  проблема с ховером и фокусом мобильного меню, крестик и меню остаются синими пока не тапнуть где-нибудь ещё

4.  В портфолио мобильной версии, в блоке кнопок сделал верхний отступ для всех кнопок и уменьшил padding для секции. Чтобы при узких экранах и трёх строчках кнопок не ломалась вёрстка

5.  Какую картинку ставить по умолчанию? Удалять ли старые, и оставлять только в папках mobile, tablet и desktop?

6.  $tablet: 767px; Почему то только при такой точке перегиба нет проблем, при $tablet: 768px; именно на этой ширине ломается совсем всё, а при 767 нормально и при ширине экрана 767рх в том числе. Мистика какая-то

7.  В разделе benefits не хватает 4рх высоты в .benefits\_\_description, могу добавить падингом снизу, нужно ли?

8.  В мобильном меню для ссылок соц сетей добавлен flex-wrap: wrap; и margi-top:10px; для лучшего отображения на узких экранах. Соответственно уменьшен общий верхний отступ блока

9.  Мне не нравится структура scss файлов, их слишком много, мне неудобно с ними работать. Стоит ли все файлы разных разрешений для одного элемента перенести в один файл, как было в 7м дз? Хотя неудобно писать, зато возможно удобно "поддерживать",я пока не решил как лучше. Подскажите как принято на больших проектах, интересует именно разделение scss файлов по разрешениям?

10. Пропустил 2ю лекцию по 5му модулю, сейчас смотрю, возник вопрос: получается
<div class="card-list__overlay"> у меня лишний, и всё, что у меня на него "навешено", можно "перевесить" на
<p class="card-list__body">
