Курс пишется. Заходите позже. (но можно потыкать в меню слева)

![Alt Text](https://media.giphy.com/media/LmNwrBhejkK9EFP504/giphy.gif)


## Ниже просто кусок чего-то:
Создайте директорию `routers` со следующей структурой:

    .
    ├── app
    │   ├── __init__.py
    │   ├── main.py
    │   └── routers
    │       ├── __init__.py
    │       ├── reviews.py
    │       ├── books.py
    │       └── authors.py
    

Откройте файл `routers/reviews` и создайте заглушки для функций, в следующих уроках мы опишем эти функции, чтобы они возвращали данные:

    from fastapi import APIRouter
    
    
    router = APIRouter()
    
    @router.post("/reviews/")
    def create_review():
        pass
    
    @router.get("/reviews/")
    def read_reviews():
        pass
    
    @router.put("/reviews/")
    def update_review():
        pass
    
    @router.delete("/reviews/")
    def delete_review():
        pass
    

- Задание 1

    Создайте роутеры и опишите функции-заглушки для сущностей books и authors.

### ТУП

Вы создали каркас для приложения, но он пока не возвращает никаких данных. В следующем уроке вы начнете добавлять в проект реальные данные.