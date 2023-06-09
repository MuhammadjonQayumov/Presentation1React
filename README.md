> # What is React?
>
> React - это библиотека JavaScript, созданная Facebook

React - это библиотека пользовательского интерфейса (UI)

React - это инструмент для создания компонентов пользовательского интерфейса

React - это инструмент для создания компонентов пользовательского интерфейса React (также известный как React.js или ReactJS) - бесплатная библиотека JavaScript с открытым исходным кодом для создания пользовательских интерфейсов на основе компонентов пользовательского интерфейса. Он поддерживается компанией Meta (ранее Facebook) и сообществом индивидуальных разработчиков и компаний. React можно использовать в качестве основы при разработке одностраничных, мобильных или серверных приложений с использованием таких фреймворков, как Next.js

![](https://camo.githubusercontent.com/f4311a2cc31ec28b404d8e6c0e9c12d9d6a594ea7bc1dc38bca4659a19a0bad4/68747470733a2f2f70312d6a75656a696e2e62797465696d672e636f6d2f746f732d636e2d692d6b3375316662706663702f66633235303134356338623134373362386639656438663037646663376164617e74706c762d6b3375316662706663702d7a6f6f6d2d63726f702d6d61726b3a343533363a343533363a343533363a323535332e696d616765)

> # Why we learn React?
>
> React использует декларативный, а не императивный синтаксис. Это более простой способ разработки приложений, и вы можете узнать почему здесь.

По сути, с React быстрее разрабатывать, потому что вам не нужно указывать приложению, как представлять состояние — вам просто нужно сказать, что вы хотели бы, чтобы произошло. Это быстро, это просто, и здесь меньше места для человеческой ошибки.

![](https://camo.githubusercontent.com/72ea0f99f563ea5b9b0995541a2bc276e95560f16b754b67706d6086ad06d44c/68747470733a2f2f6369747275736275672e636f6d2f73746f726167652f75706c6f6164732f626c6f672f426573742d31302d7765622d646576656c6f706d656e742d6672616d65776f726b732f52656163742d7765622d617070732d6578616d706c652e6a706567)

> # What is npm?
>
> npm - крупнейшая в мире библиотека программного обеспечения (реестр)

npm также является менеджером пакетов программного обеспечения и установщиком

Менеджер пакетов, входящий в состав Node.js. Установка пакета производится при помощи команды: npm install Все доступные для установки пакеты и их краткое описание: npm search Этой же командой можно производить выборочный поиск пакетов

![](https://camo.githubusercontent.com/537c2c636cea60e38d71c27c2977e1542f851f29454e9bedfa68328688da5f03/68747470733a2f2f75706c6f6164732e746f7074616c2e696f2f626c6f672f696d6167652f3132323036372f746f7074616c2d626c6f672d696d6167652d313438353838303734353935322d30643830386461373334383334346561643936323130626230623765396535312e706e67)

> # What is DOM?
>
> Объектная модель документа (DOM) - это программный интерфейс для веб-документов. Он представляет страницу таким образом, чтобы программы могли изменять структуру, стиль и содержимое документа.

DOM - это интерфейс прикладного программирования для четко определенных структур HTML и XML (согласно документу W3C). Он используется в любом месте, где вы взаимодействуете с элементами веб-страницы (любым элементом - стилем, текстом, атрибутами и т.д.). Вы много услышите о DOM с помощью JavaScript и/или библиотек JavaScript, таких как jQuery (который, конечно же, является JavaScript). На него также ссылаются Java, ECMAScript, JScript и VBScript.

![](https://github.com/Muhammadi02062720/firstReactPres/raw/master/Screenshot_1.png)

> # What is Virtual DOM?
>
> Виртуальный DOM (VDOM) - это концепция программирования, в которой идеальное, или “виртуальное”, представление пользовательского интерфейса хранится в памяти и синхронизируется с “реальным” DOM с помощью библиотеки, такой как ReactDOM. Этот процесс называется примирением. Такой подход позволяет использовать декларативный API React: Вы сообщаете React, в каком состоянии вы хотите, чтобы пользовательский интерфейс находился, и он проверяет, соответствует ли DOM этому состоянию.
>
>Если обновление объекта DOM происходит медленно, что ускоряет обновление виртуального DOM? Разве виртуальный DOM не является другим объектом DOM? Безусловно, да. Виртуальный DOM - это просто еще один объект DOM. Но это не связано тесно с веб-страницей, на которой оно отображается. Давайте посмотрим, что происходит под капотом.

Каждая веб-страница, которую вы видите, имеет эквивалентное представление DOM, представляющее собой древовидную структуру, содержащую все компоненты пользовательского интерфейса. Для любого небольшого изменения состояния в пользовательском интерфейсе необходимо изменить его соответствующее представление DOM и повторно отобразить пользовательский интерфейс. Обновление самого DOM не является дорогостоящим процессом, но рендеринг и повторная визуализация пользовательского интерфейса - это то, что делает его дорогостоящим. Учитывая размер большинства SPA (одностраничных приложений), которые мы видим в наши дни, рендеринг пользовательского интерфейса отнимает много времени не из-за сложности элементов, а из-за размера древовидной структуры, содержащей эти элементы.

![](https://github.com/Muhammadi02062720/firstReactPres/raw/master/Screenshot_2.png) 

> # What is JSX ?
>
> Мы уже говорили в нашей статье о введении в ReactJS, что React - это декларативная, эффективная и гибкая библиотека JavaScript для создания пользовательских интерфейсов. Но вместо использования обычного JavaScript код React должен быть написан на чем-то, называемом JSX. Давайте посмотрим пример JSX-кода:

const ele =

Это пример JSX

; Приведенный выше фрагмент кода чем-то похож на HTML, и он также использует переменную, подобную JavaScript, но не является ни HTML, ни JavaScript, это JSX. JSX по сути является синтаксическим расширением обычного JavaScript и используется для создания элементов React. Затем эти элементы отображаются в React DOM. Мы подробно узнаем о рендеринге и DOM в следующей статье. Почему именно JSX?

Это быстрее, чем обычный JavaScript, поскольку он выполняет оптимизацию при переводе на обычный JavaScript. Это облегчает нам создание шаблонов.

![](https://github.com/Muhammadi02062720/firstReactPres/raw/master/Screenshot_3.png)