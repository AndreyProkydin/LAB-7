# Текстовый редактор «MiniWordPad»
### 1. Введение.
&ensp;&ensp;&ensp;Реализовать простейший текстовый редактор по аналогии с WordPad или Блокнот.
### 2. Требования к приложению
- #### 2.1. Требование к функциональным характеристикам.
    Приложение должно предоставлять следующие возможности:
    * создание файла;
    * открытие файла (форматы .txt, .rtf, .pdf);
    * сохранение файла (форматы .txt, .rtf, .pdf);
    * поиск по файлу;
    * форматирование текста (шрифты, цвета фона и текста, выделение текста курсив/жирный и так далее);
    * создание списков;
    * вставка изображений;
    * другие возможности.
- #### 2.2. Требования к внешнему виду приложения.
    ##### 2.2.1. Основное окно приложения
![Скриншот ](https://raw.githubusercontent.com/Shalena-Kachka/WordPad/gh-pages/mainapp.png)

### 3. Общая структура и описание работы приложения.
- #### 3.1. Обзор функций главного окна приложения:
    - Главное окно содержит кнопку «Вставить»    по нажатию на которую осуществляется возможность вставлять в документ изображения (*.jpg, *.png);
    - Кнопки «Вырезать»   и «Копировать»   соответственно функции копирования и вырезки фрагмента текста;
    - Кнопки    - выбор типа шрифта и его размера;
	- Кнопки   - сделать стиль текста жирный/курсив/подчеркнуть;
- #### 3.2. Обзор меню «Файл»
![Меню Файл](https://raw.githubusercontent.com/Shalena-Kachka/WordPad/gh-pages/FileMenu.png)
- **Кнопки:**
	* **Создать** – создать новый документ;
    * **Открыть** – открыть новый документ;
    * **Сохранить** – сохранить документ;
    * **Сохранить как** – сохранить документ под новым именем;
    * **Печать** – печать документа;
    * **Предварительный просмотр** – просмотр документа;
    * **Выход** – закрытие приложения;
- #### 3.3. Обзор меню «Правка»
![Меню Правка](https://raw.githubusercontent.com/Shalena-Kachka/WordPad/gh-pages/EditMenu.png)
- **Кнопки:**
	* **Отмена** – отмена действия;
    * **Повторить** – повтор действия;
    * **Вырезать** – вырезка выделенного текста;
    * **Копировать** – копирование текста;
    * **Вставка** – вставка заранее скопированного/вырезанного текста;
    * **Выделить все** – выделить весь текст в документе;
- #### 3.3. Обзор меню «Сервис»
![Меню Сервис](https://raw.githubusercontent.com/Shalena-Kachka/WordPad/gh-pages/ServiceMenu.png)
- **Кнопки:**
	* **Настройки** – настройка параметров сохранения документа и другое;
    * **Параметры** – настройка размера окна, фона приложение и другое;
- #### 3.3. Обзор меню «Справка»
![Меню Сервис](https://raw.githubusercontent.com/Shalena-Kachka/WordPad/gh-pages/HelpMenu.png)
- **Справка** – вывод краткой инструкции по работе приложения;

### 4. Дополнительные требования к разработке.
- #### 4.1. Операционная система обеспечивающие работу приложения.
	Приложение должно работать на устройствах под управлением Windows 10.
- #### 4.2. Язык программирования.
    При разработке приложения должен использоваться следующий язык 
    программирования - C# и технология Windows Forms;
- #### 4.3. Языковое представление приложения.
    Интерфейс приложения должен быть представлен следующими языками:
    -  Русский.
    
    В последствие в приложение могут быть добавлены новые языки.
