# Название проекта: NewsExplorer

## Стек технологий: HTML, CSS, Node.JS, JS, webpack.

### Описание

*Сайт с возможностью регистрации, поиска и добавления статей в сохраненные по ключевым словам*

### Адрес на GitHub:

*https://github.com/Vladimir2011/news-explorer-frontend/tree/level-2*

### Адрес на gh-pages:

*https://vladimir2011.github.io/news-explorer-frontend/*

### Сборки

1. dev - для разработки, запускается с автоматическим открытием вкладки и хот-релоудом, команда: npm run dev*
2. build - создает сборку в папке dist для выкладки на сервер, команда: npm run build, при каждом запуске - пересобирается, стирая предыдущие файлы*
3. start - автоматически открывает сайт в браузере на http://localhost:8080, без хот-релоуда, команда: npm run start*
4. deploy - публикует сборку из папки dist на gh-pages, команда: npm run deploy*

## Инструкция к просмотру разных состояний страницы

*Все виды сверстаны для критических размеров (ширин) - 1440px (и более - монитор), 768px (планшет=Ipad Pro ) и до 320px (экран мобильного телефона) + промежутки*

### Главная странница index.html

*Кнопки форм по умолчанию указаны как "disabled" в HTML, чтобы посмотреть формат активной кнопки, "disabled" необходимо убрать (элементы с классом "form__button")*

*Для отображения сообщений об ошибках в заполнении формы - изменить свойство "visibility: hidden" класса "error-message" на "visibility: visible"*

*Для отображения каждого поп-апа, нужно после класса popup в строке добавить класс popup_is-opened*

*Страница изначально сверстана для залогиненого пользователя. Сменить на незалогиненного - закомментировать элемент button с классом menu__logout и убрать из класс menu__login св-во display: none;*

*Чтобы просмотреть скрытые блоки, необходимо из свойств соответствующего класса убрать/закомментировать "display: none".*

1. preloader-not-found - секция при отсутствии результатов
2. preloader-searching - секция поиска статей с лоадером
3. results - секция с результатами

*Закладка отмечена синим(активна) на 2ой карточке, на остальных нет. Чтобы добавить или убрать эффект активной закладки, нужно добавить класс bookmark_marked классу bookmark*

*По умолчанию, в меньших отображениях мобильное меню скрыто. Чтобы просмотреть открытое меню, необходимо:*

1. После класса header__wrapper добавть класс header_menu_mobile
2. После класса header__logo добавить класс header__logo_menu
3. После класса menu__list добавить класс menu__list_mobile

### Страница с сохраненными статьями articles.html

*По умолчанию, в меньших отображениях мобильное меню скрыто. Чтобы просмотреть открытое меню, необходимо:*

1. После класса header__wrapper добавть класс header_menu_mobile
2. После класса header__logo header__logo_white_theme добавить класс header__logo_menu
3. После класса menu__list добавить класс menu__list_mobile

### Версия проекта: 1.2.1
