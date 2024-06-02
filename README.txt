# Інформація

Цей проєкт демонструє інформацію про користувачів, використовуючи дані з API [jsonplaceholder.typicode.com](https://jsonplaceholder.typicode.com/).


## Інструкція по запуску

1. Завантажте або скопіюйте файли проєкту на свій локальний комп'ютер.
2. Відкрийте файл `index.html` в своєму браузері.


## Структура проекту

├── index.html
├── css-index.css
├── js-index.js
├── user-details.html
├── css-user-details.css
├── js-user-details.js
├── post-details.html
├── css-post-details.css
├── js-post-details.js
├── task.txt
└── README.txt


## Учасники

Над цим проектом працювала Олена Темчук.


## Завдання

### index.html
1. Отримати масив об'єктів з endpoint`а `https://jsonplaceholder.typicode.com/users`.
2. Вивести `id` і `name` всіх користувачів на сторінці `index.html`. Окремий блок для кожного користувача.
3. Додати кожному блоку кнопку/посилання, при кліку на яку відбувається перехід на сторінку `user-details.html`, яка має детальну інформацію про об'єкт на який клікнули.

### user-details.html
4. Вивести всю, без виключення, інформацію про об'єкт `user`, на який клікнули.
5. Додати кнопку "posts of current user", при кліку на яку, з'являються `title` всіх постів поточного користувача (для отримання постів використовуйте endpoint `https://jsonplaceholder.typicode.com/users/USER_ID/posts`).
6. Кожному посту додати кнопку/посилання, при кліку на яку відбувається перехід на сторінку `post-details.html`, яка має детальну інформацію про поточний пост.

### post-details.html
7. Вивести всю, без виключення, інформацію про об'єкт `post`, на який клікнули.
8. Нижче інформації про пост, вивести всі коментарі поточного поста (endpoint - `https://jsonplaceholder.typicode.com/posts/POST_ID/comments`).

## Стилізація проєкту
- `index.html`: всі блоки з користувачами повинні бути розташовані по 2 в рядок. Кнопки/посилання розташувати під інформацією про користувача.
- `user-details.html`: блок з інформацією про користувача зверху сторінки. Кнопка повинна бути нижче, на 90% ширини сторінки, по центру. Блоки з короткою інформацією про пости повинні бути розташовані в ряд по 5.
- `post-details.html`: блок з інформацією про пост зверху. Коментарі повинні бути розташовані по 4 в ряд. Всі елементи, які характеризують користувачів, пости, коментарі повинні бути візуалізовані так, щоб було видно, що це блоки (дати фон, відступи тощо).



# Information

This project displays user information using data from the [jsonplaceholder.typicode.com](https://jsonplaceholder.typicode.com/) API.


## Start-up instructions

1. Download or copy the project files to your local computer.
2. Open the `index.html` file in your browser.


## Project structure

├── index.html
├── css-index.css
├── js-index.js
├── user-details.html
├── css-user-details.css
├── js-user-details.js
├── post-details.html
├── css-post-details.css
├── js-post-details.js
├── task.txt
└── README.txt


## Participants

Olena Temchuk worked on this project.


## Assignment

### index.html
1. Get an array of objects from the endpoint `https://jsonplaceholder.typicode.com/users'.
2. Display the `id' and `name' of all users on the `index.html' page. A separate block for each user.
3. Add a button/link to each block, when you click on it, you go to the ``user-details.html'' page, which has detailed information about the clicked object.

### user-details.html
4. Display all, without exception, information about the clicked user object.
5. Add the "posts of current user" button, when clicked, the `title' of all posts of the current user will appear (to receive posts, use the endpoint `https://jsonplaceholder.typicode.com/users/USER_ID/posts`) .
6. Add a button/link to each post, when clicked, you will be redirected to the `post-details.html' page, which has detailed information about the current post.

### post-details.html
7. Display all, without exception, information about the clicked `post' object.
8. Below the information about the post, display all comments of the current post (endpoint - `https://jsonplaceholder.typicode.com/posts/POST_ID/comments`).

## Stylization of the project
- `index.html`: all blocks with users should be placed 2 per line. Place the buttons/links below the user information.
- `user-details.html`: a block with information about the user at the top of the page. The button should be lower, 90% of the page width, in the center. Blocks with brief information about posts should be arranged in a row of 5.
- `post-details.html`: block with information about the post from above. Comments should be placed 4 in a row. All elements that characterize users, posts, comments must be visualized so that it is visible that they are blocks (give background, indents, etc.).