# Auth-Postman-

// 1. Регистрация

//Запрос: { "user": { "username": "kalushko26", "email": "vadim.kalushko26@yandex.ru", "password": "123Qwerty!" } }
//Ответ: 
{
    "user": {
        "username": "kalushko26",
        "email": "vadim.kalushko26@yandex.ru",
        "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjYzZmY2NWIxNmY4YmVlMWIwMDU1NWEyZSIsInVzZXJuYW1lIjoia2FsdXNoa28yNiIsImV4cCI6MTY4Mjg2NjA5NywiaWF0IjoxNjc3NjgyMDk3fQ.SmhV4EaEj_a3mYDSFHC445MQmAzdq9MMPHIiW_yT3iY"
    }
}

// 2. Авторизация

//Запрос { "user": { "email": "vadim.kalushko26@yandex.ru", "password": "123Qwerty!" } } 
//Ответ 
{
    "user": {
        "username": "kalushko26",
        "email": "vadim.kalushko26@yandex.ru",
        "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjYzZmY2NWIxNmY4YmVlMWIwMDU1NWEyZSIsInVzZXJuYW1lIjoia2FsdXNoa28yNiIsImV4cCI6MTY4Mjg2NjIwMSwiaWF0IjoxNjc3NjgyMjAxfQ.uSCRTYDHAg9liVbDLU8vFCkXYgZO9y8EJaerjyZLc0U"
    }
}

// 3. Данные

Ввожу токен в поле Авторизации (bearer token) из п.2
"token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjYzZmY2NWIxNmY4YmVlMWIwMDU1NWEyZSIsInVzZXJuYW1lIjoia2FsdXNoa28yNiIsImV4cCI6MTY4Mjg2NjIwMSwiaWF0IjoxNjc3NjgyMjAxfQ.uSCRTYDHAg9liVbDLU8vFCkXYgZO9y8EJaerjyZLc0U"

{
    "user": {
        "username": "kalushko26",
        "email": "vadim.kalushko26@yandex.ru",
        "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjYzZmY2NWIxNmY4YmVlMWIwMDU1NWEyZSIsInVzZXJuYW1lIjoia2FsdXNoa28yNiIsImV4cCI6MTY4Mjg2NjQ2OSwiaWF0IjoxNjc3NjgyNDY5fQ.cb8hzN2rXOiqph4VGv34sLF3R4zOV2F6J7r3oVUKpGw"
    }
}
