### Postman-документация:
Интерактивная документация с mock сервером и настроенная коллекция с окружением доступны по ссылке:  
[Документация Postman — Petrushka Backend](https://www.postman.com/dark-flare-463733/task-2-rest-api/collection/vg6grdn/petrushka-backend?action=share&source=copy-link&creator=29498713)
### Пример запроса: 
```petrushka/api/v1/partner-stores```
### Пример JSON ответа:
```
{
    "meta": {
        "total": 4,
        "limit": 20,
        "offset": 0,
        "sort": "delivery_time"
    },
    "data": [
        {
            "id": "store_metro_001",
            "name": "METRO",
            "category": "grocery",
            "website_url": "https://metro.example.com",
            "store_url": "https://petrushka.example.com/partners/store_metro_001",
            "logo_url": "https://cdn.petrushka.example.com/stores/store_metro_001/logo.png",
            "is_available": true,
            "delivery": {
                "estimated_time_min": 20,
                "estimated_time_max": 35,
                "delivery_fee": {
                    "amount": 149,
                    "currency": "RUB"
                },
                "is_express": true
            },
            "location": {
                "address": "Moscow, Leningradsky Prospekt 37",
                "city": "Moscow",
                "lat": 55.7901,
                "lng": 37.5582,
                "distance_km": 5.1
            },
            "tags": [
                "express",
                "popular"
            ]
        },
        {
            "id": "store_auchan_002",
            "name": "Ашан",
            "category": "hypermarket",
            "website_url": "https://auchan.example.com",
            "store_url": "https://petrushka.example.com/partners/store_auchan_002",
            "logo_url": "https://cdn.petrushka.example.com/stores/store_auchan_002/logo.png",
            "is_available": true,
            "delivery": {
                "estimated_time_min": 35,
                "estimated_time_max": 60,
                "delivery_fee": {
                    "amount": 99,
                    "currency": "RUB"
                },
                "is_express": false
            },
            "location": {
                "address": "Moscow, Aviamotornaya 12",
                "city": "Moscow",
                "lat": 55.7517,
                "lng": 37.7175,
                "distance_km": 8.4
            },
            "tags": [
                "big-basket",
                "discounts"
            ]
        },
        {
            "id": "store_vkusvill_003",
            "name": "ВкусВилл",
            "category": "grocery",
            "website_url": "https://vkusvill.example.com",
            "store_url": "https://petrushka.example.com/partners/store_vkusvill_003",
            "logo_url": "https://cdn.petrushka.example.com/stores/store_vkusvill_003/logo.png",
            "is_available": true,
            "delivery": {
                "estimated_time_min": 25,
                "estimated_time_max": 45,
                "delivery_fee": {
                    "amount": 0,
                    "currency": "RUB"
                },
                "is_express": false
            },
            "location": {
                "address": "Moscow, Maroseyka 8",
                "city": "Moscow",
                "lat": 55.7573,
                "lng": 37.6351,
                "distance_km": 2.6
            },
            "tags": [
                "healthy-food",
                "free-delivery"
            ]
        },
        {
            "id": "store_victoria_004",
            "name": "ВИКТОРИЯ",
            "category": "supermarket",
            "website_url": "https://victoria.example.com",
            "store_url": "https://petrushka.example.com/partners/store_victoria_004",
            "logo_url": "https://cdn.petrushka.example.com/stores/store_victoria_004/logo.png",
            "is_available": true,
            "delivery": {
                "estimated_time_min": 30,
                "estimated_time_max": 50,
                "delivery_fee": {
                    "amount": 129,
                    "currency": "RUB"
                },
                "is_express": false
            },
            "location": {
                "address": "Moscow, Kutuzovsky Prospekt 19",
                "city": "Moscow",
                "lat": 55.7431,
                "lng": 37.535,
                "distance_km": 6.3
            },
            "tags": [
                "family",
                "weekend-deals"
            ]
        }
    ]
}
```