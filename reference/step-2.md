# Этап 2. Проработка моделей данных

## Критерии достижения:

1. Созданы модели и их дополнительные методы.

## Порядок выполнения
Данная структура может быть изменена под конретные цели вашего дипломного проекта.

1. Создать модели:
    1. Shop
        - name
        - url
        - filename
    2. Category
        - shops (m2m)
        - name
    3. Product
        - category
        - name
    4. ProductInfo
        - product
        - shop
        - name
        - quantity
        - price
        - price_rrc
    5. Parameter
        - name
    6. ProductParameter
        - product_info
        - parameter
        - value
    7. Order
        - user
        - dt
        - status
    8. OrderItem
        - order
        - product
        - shop
        - quantity
    9. Contact
        - type
        - user
        - value

