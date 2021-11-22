# iTechArt

В данном проекте мы запускаем сайт https://www.google.com/ , вводим запрос и проверяем содержание данного запроса
в каждом блоке на первых двух страницах.

**Приступая к работе:**
Данный проект построен на языке Java, с использованием Maven и TestNG.

**Описание:**
В папке test cодержится класс "GoogleTest", который проверяет сайт https://www.google.com/.
В строке запроса вводится текст, который указывается в "resources/google.properties"
под названием "textToSearch".
Далее кликается "Поиск" и после запроса с помощью цикла while проверяется кол-во результатов
и время поиска.
После этого с помощью метода "checkResults" проверяется кол-во блоков на первых двух страницах
и содержание каждого блока. Далее делается проверка на содержание текста "textToSearch"
в каждом блоке.