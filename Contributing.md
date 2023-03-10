## Техническое задание

1. Общие технические требования

* Сетка: определена в макете.
* Адаптивность сетки: мобильная, планшетная и десктопная версии («фикс» или «резина»).
* Адаптивность графики: ретинизация, векторные изображения.
* Используемая методология: БЭМ.
* Используемый препроцессор: Less или Sass.
* Используемый инструмент автоматизации: Gulp.
* Используемые библиотеки: нет.
* Кроссбраузерность: Chrome, Firefox, Safari.
* Типографика: частично определена в макете (прочее — на усмотрение разработчика).
* Используемый шрифт: Oswald, Arial.

2. Пояснения для учащихся

* Обязательными к вёрстке являются все 3 страницы (главная страница, страница с формой, страница каталога).
* Макеты верстаются постепенно: сначала мобильная версия, далее от мобильной версии к планшетной, а затем и к десктопной.
Требования к поведению блоков

3. Все макеты

* Между версиями (мобильная, планшетная, десктопная) сетка может быть как резиновой, так и фиксированной.
* При фиксированной сетке контентная область центруется и не может быть уже макетной ширины. Фоны, которые упираются в края макета должны тянуться на всю страницу.
* Логотип на внутренних страницах — это ссылка на главную страницу.
* Мобильное меню может быть реализовано двумя способами:
                    реализация без JS;
                    реализация с использованием JS.
* При реализации без использования JS главное меню в мобильной версии должно быть открыто, а иконка с крестиком — скрыта. Должны быть предусмотрены классы для скрытого и открытого состояний меню.
* При реализации с использованием JS блок с главным меню в мобильной версии должен открываться при нажатии на иконку «гамбургера». Когда меню открыто, иконка «гамбургера» заменяется на крестик. При нажатии на иконку с крестиком меню закрывается.
* Все состояния элементов при наведении и нажатии указаны в стайлгайде. Состояние ошибки должно быть реализовано только для обязательных полей формы (в макете они помечены звёздочкой).
* Логотип и текст HTML Academy в футере являются ссылкой на лендинг интенсива «HTML и CSS. Адаптивная вёрстка и автоматизация».

4. Главная
Мобильная версия (Index > Mobile):
* Логотип состоит из упрощённой иконки и названия магазина «Кэт энерджи».
* Кнопка «Подобрать программу» должна вести на страницу формы для подбора программы.
* В блоках «Похудение» и «Набор массы» ссылкой должна быть строка, начинающаяся со слова «Каталог». При нажатии должен осуществляться переход на соответствующие разделы каталога. Страницы разделов реализовывать не нужно.
* В блоке «Живой пример» достаточно вёрстки, соответствующей макету. По желанию можно сделать «Было» и «Стало» кнопками переключения фотографий кота.
* Блок карты: необходимая реализация — интерактивная карта (карты Google или Яндекса), ширина подстраивается под ширину вьюпорта (но не уже контентной ширины макета), на карте размещён маркер (может быть как кастомным, так и дефолтным), центр карты соответствует центру блока в макете.
Планшетная версия (Index > Tablet):
* Блоки меняют размеры и расположение согласно макету.
* В состав иконки логотипа добавляются новые элементы.
* Главное меню всегда открыто вне зависимости от его состояния на мобильной версии.
* В блоке «Живой пример» котов становится двое. Логику слайдера реализовывать не обязательно.
Десктопная версия (Index > Desktop):
* Блоки меняют размеры и расположение согласно макету.
* В составе логотипа добавляются новые элементы.
* Фон первого блока под шапкой тянется на всю ширину экрана и состоит из двух равных частей: левая — с белым фоном, правая — с зелёным фоном и изображением кота, которое упирается в правую границу экрана.

5. Форма
Мобильная версия (Form > Mobile):
* Должны быть реализованы кастомные элементы форм.
* У полей ввода телефона и почты должны быть указаны соответствующие типы для удобного заполнения с телефона.
Планшетная версия (Form > Tablet):
* Блоки меняют размеры и расположение согласно макету.
Десктопная версия (Form > Desktop):
* Блоки меняют размеры и расположение согласно макету.

6. Страница каталога
Мобильная версия (Catalog > Mobile):
* Изображение и название товара — ссылки на страницу с описанием товара. Страницу с описанием товара реализовывать не нужно.
* Кнопка «Заказать» открывает страницу оформления заказа.
* Кнопка «Показать все» показывает новые товары. При отключенном JS должен осуществляться переход на страницу новых товаров. Показ новых товаров и их страницу реализовывать не нужно.
Планшетная версия (Catalog > Tablet):
* Блоки меняют размеры и расположение согласно макету.
Десктопная версия (Catalog > Desktop):
* Блоки меняют размеры и расположение согласно макету.
