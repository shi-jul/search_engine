# **Search engine**

## О проекте
Поисковой движок на **Spring Boot** позволяет осуществить индексацию выбранных пользователем сайтов в базу данных, получение статистической информации по сайтам, поиск ключевых слов в проиндексированных сайтах


## Стэк технологий
* **Spring Framework**
* **Lombok**
* **JSOUP**
* **JPA**
* **SQL**
* **Morphology Library Lucene**

## Инструкция
* Создайте схему **search_engine** в MySQL Workbench
* Укажите данные пользователя для доступа к MySQL Workbench в конфигурационном файле **application.yaml**
* Задайте адреса сайтов, по которым движок должен осуществить поиск, в конфигурационном файле **application.yaml**
* Запустите приложение с метода **main**, находящегося в классе **Application**
* Откройте приложение через браузер по адресу: http://localhost:8080/
* Запустите индексацию выбранных сайтов на вкладке **Management**
  ![se_title_manag](https://github.com/shi-jul/search_engine/assets/127664427/fe324e75-04d8-4ea2-a7d0-b9d8142d90bb)
* Отправьте запрос через API поискового движка на вкладке **Search**
  ![se_title_search](https://github.com/shi-jul/search_engine/assets/127664427/b8c04ed2-327b-4e28-b750-3a98956c64dc)
* Ознакомьтесь со статистикой на вкладке **Dashboard**
  ![se_title_dash](https://github.com/shi-jul/search_engine/assets/127664427/d9ddac7d-2f76-4d32-822f-bf445f923ff6)


