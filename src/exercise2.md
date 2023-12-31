![CRUD](https://bestprogrammer.ru/wp-content/uploads/2020/10/Algoritm-CRUD.jpg)


***CRUD*** — акроним ( вид аббревиатуры, образованной начальными звуками), обозначающий четыре базовые функции, используемые при работе с базами данных: создание (англ. create ), чтение ( read ), модификация ( update ), удаление ( delete ).
Операции CRUD предназначены для редактирования данных программы.

**Create**
Создание новых данных — ключевая функция всего CRUD. Остальные операции не имеют смысла без создания новой записи в базе данных.
**Read**
Чтение данных — операция, которая доступна всем пользователям. Зачастую, чтение — единственная операция, которая доступна пользователю без прав администратора. 
В операции чтения важно контролировать доступ к информации. Пользователь не должен видеть информацию, к которой у него нет доступа. Например, как владелец банковского счета вы можете увидеть только свой баланс, доступа к чужим счетам у вас нет.
**Update**
Операция обновления похожа на создание — с ее помощью мы вносим изменения в базу данных. В случае с обновлением важно корректно сохранять ранее внесенные данные. Например, если вы меняете свой логин на сайте, то при этом не должна затрагиваться информация о пароле и электронной почте.
**Delete**
Удаление — последняя операция для CRUD. Она удаляет записи из базы данных, будь то информация о картине или метка на карте.
Обычно удаление выполняется после проверки прав доступа к данным. Например, если пользователь не имеет право удалять записи, запрос не сработает. Если право есть, система начинает удалять данные.
С точки зрения реализации удаление делится на два типа:
Физическое — запись стирается из базы данных без возможности восстановления
Логическое — к записи закрывается доступ на чтение, то есть она скрывается. Доступ всегда можно восстановить при необходимости. Логическое удаление больше похоже обновление, потому что физически запись в базе данных остается.

**REST API** сопоставляет операции **CRUD** с методами HTTP. В следующей таблице указывается, какой метод HTTP сопоставляется с какой операцией.


|         Операция CRUD                  |       Метод HTTP                  |
|:--------------------------------------:|:---------------------------------:|
|   Создание                             |     POST                          |
|   Чтение                               |     GET                           |
|    Обновление                          |     PATCH/PUT                     |
|    Удаление                            |     DELETE                        |


GET нужен для извлечения данных
POST — для создания и отправки форм
PATCH — для обновления
DELETE — для удаления 



ЧТО ОБЩЕГО?
Приложения REST разрабатываются с сохранением определенного набора ресурсов в смысловом центре. Эти ресурсы, как и ресурсы CRUD, можно легко создавать, читать, модифицировать и удалять. Просто вместо Create, Read, Update и Delete в REST используются ресурсы PUT/POST, GET, PATCH/POST и DELETE.

В ЧЕМ РАЗНИЦА?
Абсолютно точно, то у этих двоих больше различий, чем сходств. Взгляните на ключевые различия между ними.

В части определения REST упоминается как архитектурная система, а CRUD – как функция.
REST «крутится» вокруг ресурсов, основанных на компонентах HTTP.
CRUD «крутится» вокруг информации, хранящейся в настройках базы данных.
CRUD может быть частью REST, но REST не может быть частью CRUD. REST – это независимый подход, который может правильно функционировать и без CRUD.

ЧТО ТАКОЕ CRUD-ТЕСТИРОВАНИЕ?
CRUD-тестирование – это оригинальная методология тестирования методом «черного ящика», которая широко используется для подтверждения полезности данного программного обеспечения в режиме реального времени. Это понятие используется для SQL и других ресурсов СУБД, для которых гарантируется точное отображение данных, сквозное обслуживание ACID-свойств и несравнимая целостность данных.
