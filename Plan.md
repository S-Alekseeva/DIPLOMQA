# **План по проверке и автоматизации мобильного приложения "Мобильный хоспис:**

1. Ручное тестирование мобильного приложения "Мобильный хоспис";
2. Составление чек-листа для проверки приложения;
3. Составление тест-кейсов для проверки приложения;
4. Написание автоматизированных тестов для проверки приложения;
5. Создание отчета о тестировании.

# **Виды тестирования:**
+ Функциональное тестирование;
+ Интеграционное тестирование;
+ Тестирование пользовательского интерфейса.

# ***Позитивные сценарии:***
1. Заполнение полей приложения валиными значениями.

# ***Негативные сценарии:***
1. Заполнение полей приложения невалидными значениями.

# **Функционал приложения:**

# 1. Авторизация в приложении
+ Поле "Login";
+ Поле "Password".

# 2. Вкладка "Main"
+ Просмотр новостей;
+ Переход по ссылку "All news".

# 3. Navigation Drawer
+ Переход между вкладками приложения.

# 4. Вкладка "News"
+ Просмотр новостей;
+ Сортировка новостей;
+ Фильтр новостей по категориям и дате.    

# 5. Раздел "Control panel" во вкладке "News"
+ Просмотр новостей;
+ Удаление новостей;
+ Редакция новостей и статуса;
+ Сортировка новостей;
+ Фильтр новостей по категориям, дате и статусу;
+ Создание новостей.

# 6. Вкладка "About"
+ Переход по ссылке и просмотр "Privacy policy";
+ Переход по ссылке и просмотр "Terms of use".

# 7. Вкладка "Love is all"
+ Просмотр цитат.

# 8. Выход из приложения

# **Инструменты:**
1. Android Studio Jellyfish | 2023.3.1 - интегрированная среда разработки (IDE) для работы с платформой Android;
2. Java 11 - язык программирования, который имеет набор готового ПО для разработки и запуска приложений;
3. Gradle - система автоматической сборки проекта;
4. JUnit – фреймворк, который предоставляет множество улучшений и новых функций для написания тестов;
5. Espresso - нативный фреймворк для тестированияс открытым исходным кодом;
6. Allure – фреймворк для сбора данных и построения отчетов о тестировании кода.

# **Перечень и описание возможных рисков при автоматизации:**
1. Тесты могут не покрыть все возможные негативные сценарии (пользователь может повести себя так, как мы не можем предвидеть);
2. Падение автотестов UI даже при незначительном изменении кода (изменения: структуры приложения, локаторов элементов);
3. При изменении полей, текста, заголовков и т.д. тесты необходимо будет редактировать. 