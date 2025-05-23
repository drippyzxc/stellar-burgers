<div align="center">
<h1>Yandex Project - stellar-burgers
</h1>
<a href="https://drippyzxc.github.io/stellar-burgers/">
<img src="https://github.com/drippyzxc/appslogo/blob/main/Screenshot_23-May_17-57-22_22639.png">
</img>
</a>
</div>
<hr>

The Burger-Stellar project is a full-fledged frontend application-shop, with the ability to register, create an order and view both all orders and each order separately. It is also possible to edit your data in the user's personal account.


[Макет](<https://www.figma.com/file/vIywAvqfkOIRWGOkfOnReY/React-Fullstack_-Проектные-задачи-(3-месяца)_external_link?type=design&node-id=0-1&mode=design>)

[Чеклист](https://www.notion.so/praktikum/0527c10b723d4873aa75686bad54b32e?pvs=4)

## Этапы работы:

1. Разверните проект и ознакомьтесь с кодом. Все необходимые вам компоненты уже созданы и лежат в папке `src/components`

2. Настройте роутинг.

3. Напишите функционал запросов данных с сервера, используя `Redux` и глобальный `store`. Сами "ручки" уже прописаны и лежат в `utils/burger-api.ts`

4. Настройте авторизацию и создайте защищённые роуты.

## Важно:

Для корректной работы запросов к серверу необходимо добавить переменную BURGER_API_URL в окружение. Сама ссылка находится в файле `.env.example`.
