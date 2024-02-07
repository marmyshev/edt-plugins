# 1C:EDT plugins

Общрий репозиторий-агреггатор всех плагинов для 1C:EDT

## Установка плагинов

Скопируйте адрес сайта обновлений

```
https://marmyshev.github.io/edt-plugins/repository/
```

Вставьте адрес в помощщник установки плагинов в меню: 

`Help -> Install New Software... -> Work with:`

> Внимание!
> 
> Загрузка будет выполняться очень долго (несколько минут): сайт-агреггатор перенаправляет запросы на все сайты обновлений всех плагинов.


**Устанавливайте плагны по одному!!** Не все плагины могут быть адаптированы под вашу версию 1C:EDT - поэтому 
рекомендуется устанавливать плагины по череди и проверять работоспособность.


## Идеи новых плагинов [в Issues](https://github.com/marmyshev/edt-plugins/issues)

Идеи для разработки плагинов для 1C:EDT, платформы 1С:Предериятия и продуктов 1С, интересные плагины Eclipse которые можно/нужно использовать в 1C:EDT.


> Здесь разместим идеи most-wanted по лайкам

- [Интерфейсы в 1С](https://github.com/marmyshev/edt-plugins/issues/15)
- ["Избранное" из моих объектов метаданных в навигаторе 1C](https://github.com/marmyshev/edt-plugins/issues/2)
- [Консоль запросов](https://github.com/marmyshev/edt-plugins/issues/12)
- [Контроль орфографии в модулях и метаданных](https://github.com/marmyshev/edt-plugins/issues/4)
- [Подсветка измененных свойств палитре](https://github.com/marmyshev/edt-plugins/issues/7)
- [Плагин контроля реструктуризации БД](https://github.com/marmyshev/edt-plugins/issues/8)
- [Плагин для перенаправления чтения кода общего модуля и кода модуля формы из epf](https://github.com/marmyshev/edt-plugins/issues/11)
- [Контроль орфографии в модулях и метаданных](https://github.com/marmyshev/edt-plugins/issues/4)
- [Swagger для http-сервисов в 1С и генерация документации API сервисов](https://github.com/marmyshev/edt-plugins/issues/23)
- [Детализированная подсказка по типу](https://github.com/marmyshev/edt-plugins/issues/9)
- [Copyright Tool - помощник и контроль авторских прав на код приложений 1С](https://github.com/marmyshev/edt-plugins/issues/20)
- [Контроль наличия префиксов у метаданных](https://github.com/marmyshev/edt-plugins/issues/13)

## Плагины фирмы 1С

- [1С:Language Tool](https://its.1c.ru/db/edtplugins) - инструмент перевода исходного кода и локализации интерфейса
- [1C:SSL-support](https://github.com/1C-Company/ssl-support) - поддержка разработки конфигураций на базе БСП
- [1С:Стандарты разработки V8](https://github.com/1C-Company/v8-code-style) - разработка по стандартам 1С, проверки, инструменты
- [1cfresh review](https://releases.1c.ru/project/FreshPublic) - плагин проверок для 1С-Фреш

## Плагины специально для 1C:EDT

- [1Unit](https://github.com/DoublesunRUS/ru.capralow.dt.unit.launcher) - Запуск модульных тестов для 1C:Enterprise Development Tools
- [EDT CF-builder](https://github.com/YanSergey/edt.cf_builder) - Плагин для 1C:Enterprise Development Tools для работы с CF/CFE-файлами.
- [Коннектор BSLLS для 1С:EDT](https://github.com/otymko/bslls-connector-for-edt) - Плагин включает проверки BSL LS в среде разработки 1С:EDT. Это добавляет 128+ диагностик.
- [Disable Editing plugin for 1C:EDT](https://github.com/marmyshev/edt-editing)  - Плагин запрета редактирования для 1C:EDT
- [Проверка внедрения БСП](https://github.com/DoublesunRUS/ru.capralow.dt.ssl.checks) - Проверка внедрения БСП для 1C:Enterprise Development Tools
- [EDT External Designer Launcher](https://github.com/YanSergey/edt.externalDesignerLauncher) - Запускатель альтернативного Конфигуратора 1С для EDT
- [export-xml-for-request-console-1c](https://github.com/VitaliyVS-2020/export-xml-for-request-console-1c) - Плагин для 1C:EDT. Экспорт запроса в XML для Консоли запросов 1С. 
- [Помощник ЗУП](https://github.com/DoublesunRUS/ru.capralow.dt.hrm.support) - Помощник ЗУП для 1C:Enterprise Development Tools
- [VA для 1Unit](https://github.com/DoublesunRUS/ru.capralow.dt.framework.va) - Vanessa Automation для 1Unit для 1C:Enterprise Development Tools
- [Поддержка префиксов](https://github.com/DoublesunRUS/ru.capralow.dt.adaptation) - Поддержка префиксов для 1C:Enterprise Development Tools
- [Запуск тестов YAXunit](https://github.com/bia-technologies/edt-test-runner) - Плагин для работы с модульными (unit) тестами в среде разработки EDT

## Плагины Eclipse подходящие для 1C:EDT

- [LiClipseText](https://marketplace.eclipse.org/content/liclipsetext) - редактор с поддержкой множества синтаксиса
- [search-csv-export](https://github.com/marmyshev/search-csv-export) - Экспорт результатов поиска в CSV в кодировке UTF-8
- [Darkest Dark theme](https://marketplace.eclipse.org/content/darkest-dark-theme-devstyle) - плагин который добавляет новые темы (светлые и темные), кроме этого имеет свой стартер, который показывает последние отредактированные объекты и последние отредактированные файлы в нем, а так же заменяет стандартный поиск по ctrl+F - убирает отдельное диалоговое окно поиска, и делает такое же как и в VCS. **Внимание!** При использовании этого плагина с EDT может происходить потеря фокуса в поле заголовка в палитре свойств.
- [Open Editors](https://marketplace.eclipse.org/content/open-editors) - плагин позволяет в отдельном окне показать все открытые вкладки. По умолчанию - если вкладок много, то они скрываются под стрелочки вверху панели редактора, а этот плагин позволяет в отдельном окне вывести все редакторы и перелючаться между ними.

## Плагины Eclipse для JDT (помогающие разрабатывать плагины для 1C:EDT)

- [JAutodoc](https://marketplace.eclipse.org/node/246)
- [SonarLint](https://marketplace.eclipse.org/node/2568658)
- [Enhanced Class Decompiler](https://marketplace.eclipse.org/node/3644319)
- [EclEmma Java Code Coverage](https://marketplace.eclipse.org/node/264)
- [WindowBuilder](https://marketplace.eclipse.org/node/3085446)
- [ResourceBundle Editor](https://marketplace.eclipse.org/node/2628188)
- [EcliPaint](https://marketplace.eclipse.org/node/322221)
- [Image/Picture Viewer](https://marketplace.eclipse.org/node/3571619)
- [PDE Source Lookup](https://marketplace.eclipse.org/node/2844330)
- [Xtext Tools](https://github.com/OLibutzki/xtext.tools) - Node Model Outline, Semantic Model Outline

## Разработка плагинов в сторонних IDE

- [Разработка 1C:EDT Plugin в IntelliJ IDEA](https://skycorvette.com/knowledges/dccfd1f4-ef50-4242-8355-d62fb3675e13/)
