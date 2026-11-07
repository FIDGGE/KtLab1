Выполнил Гончаров Роман ПИ-251 Ход работы: Создание и первый запуск приложения («First App»)
Создан проект по шаблону Empty Activity с именем First App.
В Device Manager настроен виртуальный девайс (эмулятор).
Выполнена сборка проекта с помощью Gradle и запуск на эмуляторе; на экране отобразилась стандартная строка Hello World!.
<img width="1919" height="1033" alt="image" src="https://github.com/user-attachments/assets/48da527a-4f8a-43ed-8e9b-e9de4560b24b" />

Линейная компоновка и текстовые поля (LinearLayout, TextView)
Корневой контейнер макета activity_main.xml изменен на вертикальный LinearLayout.
Размещены 3 компонента TextView: ФИО и номер учебной группы (заданы напрямую в разметке).
Четверостишие на русском языке (задано напрямую в разметке).
Перевод четверостишия на английский язык, подключенный через строковый ресурс @string/poem_en из файла res/values/strings.xml.
<img width="1919" height="1033" alt="image" src="https://github.com/user-attachments/assets/2e968def-6bfa-4019-a965-e8d2be65a104" />

Работа с компонентами (EditText, ImageView, Button) Макет переработан под использование интерактивных элементов внутри вертикального LinearLayout:
EditText с выводом данных студента по умолчанию через строковый ресурс @string/student_info.
ImageView с центрированной стандартной иконкой приложения @mipmap/ic_launcher_round.
Button с текстом «ОК», растянутая по ширине экрана.
<img width="1919" height="1028" alt="image" src="https://github.com/user-attachments/assets/71f09f10-1695-4f22-a915-ab62a819f04c" />

Вывод: Освоены базовые средства Android Studio и Device Manager. На практике изучено создание XML-разметки с вертикальным LinearLayout, вынос строк в файл ресурсов strings.xml и использование базовых виджетов интерфейса (TextView, EditText, ImageView, Button).
