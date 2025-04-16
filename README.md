Шаги для реализации тестового задания:
Шаг 1. Ознакомилась с документацией для метода создания комментария под фото Вконтакте: https://dev.vk.com/ru/method/photos.createComment
Шаг 2. Составила и отправила запрос в Postman:
```
https://api.vk.com/method/photos.createComment?owner_id=189704458&photo_id=303057922&message=TagesJump&access_token=vk1.a.nlwxB0jIAmx6akFTC9AW_K99Q8RfMAUwQBLG5SwFBg5P14wnEatyD8aloKxXCtBdLDV7Xeyb6I1Unvlr2-7PZQ2jJQFB7COi93lhSTxY-H4MABjHJBsN21EK3At_neXRrlgCLGtRf7xXPt7eK0GsrZ02yd9Ka7ufXXG-1_yJH9qn55_U1jFzacAGs2G0STm6kxRl4g3BvZqusWZilTqE1A&v=5.199
```
Где параметры:
owner_id – Идентификатор пользователя, которому принадлежит фотография.
photo_id – Идентификатор фотографии.
message – Текст комментария.
access_token – токен доступа.
v – версия.
Шаг 3. Составила и отправила запрос для добавления комментария через виджет в документации:
https://github.com/Guzel-bes/Qatest/blob/main/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202025-04-16%20%D0%B2%2018.34.33.png
Шаг 4: Создала репозиторий в GitHub и загрузила в него проект:
https://github.com/Guzel-bes/Qatest
