# Sneakers Database

![Sneakers Database](https://uploads-ssl.webflow.com/616f2956e7186acb32973338/6388c6d14f68dc766c6ab740_Business%20Home%20SVG.svg)

- Landing page of our [API](https://www.retailed.io/business-suite)
- Documentation API & collection [Postman](https://documenter.getpostman.com/view/9159115/2s8YzQVib9#5b2fb91c-9818-424b-954b-565a5eaa6d09) 
- Community on [Discord](http://discord.retailed.io)

## Product schema
```
{
    "id": "7d4c66bb-6cf2-4c43-98ca-14b031c2b9f6",
    "name": "Jordan 4 Retro Midnight Navy",
    "image": "https://retailed.fra1.digitaloceanspaces.com/product/jordan-4-retro-midnight-navy.webp",
    "releasedAt": "2022-10-29",
    "sizing": "man",
    "initialPrice": 210,
    "colorway": "White/Midnight Navy/Light Smoke Grey-Fire Red",
    "sku": "DH6927-140",
    "createdAt": "2022-12-08T21:19:03.199275+00:00",
    "updatedAt": null,
    "brand": {
        "id": "8560ea3d-0d41-4e9e-ba8f-6b19022841da",
        "name": "Jordan"
    }
}
```

## Prices schema
```
{
    "id": "e1eeb65a-3c75-44b9-981c-2e0b6aabbe6a",
    "sizeEu": "40",
    "sizeUs": "7",
    "sizeJp": "25",
    "sizeUk": "6",
    "priceEur": 246,
    "priceGbp": 212,
    "priceUsd": 259,
    "pricePln": 1152,
    "priceChf": 243,
    "priceDkk": 1829,
    "priceSek": 2681,
    "payoutEur": 209,
    "payoutGbp": 180,
    "payoutUsd": 220,
    "payoutPln": 979,
    "payoutChf": 206,
    "payoutDkk": 1554,
    "payoutSek": 2278,
    "createdAt": "2022-12-09T21:03:40.420085+00:00",
    "product": {
        "id": "1a02de24-b024-440e-a174-56b4cd8e6756",
        "name": "Jordan 9 Retro Fire Red (GS)",
        "sku": "302359-162"
    },
    "platform": {
        "id": "0e2752e4-4c67-4344-971e-732a3a7d2987",
        "name": "stockx"
    }
}
```
