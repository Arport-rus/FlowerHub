#  FlowerHub

Интернет-магазин цветов с каталогом по категориям, поиском, страницей букета и корзиной. Адаптивный дизайн: удобно и на телефоне, и на компьютере.
##Главная страница
<img width="1903" height="1078" alt="а1" src="https://github.com/user-attachments/assets/847110ea-56e2-4bb2-9859-b1640a67ce04" />
<img width="1904" height="1080" alt="а2" src="https://github.com/user-attachments/assets/16e6ad9f-f16c-4dae-94a5-480e1304255f" />
<img width="1905" height="1080" alt="а3" src="https://github.com/user-attachments/assets/63c75f41-0245-4147-93b7-6e37aaa15c7f" />
<img width="1905" height="929" alt="а4" src="https://github.com/user-attachments/assets/9d970057-ecbe-4075-be33-f27cfa83de6e" />
<img width="1904" height="1079" alt="а5" src="https://github.com/user-attachments/assets/26dde509-719f-4fd1-999c-75a499d0e49b" />

##Мобильная версия

<img width="377" height="816" alt="а6" src="https://github.com/user-attachments/assets/a7e83362-2072-486f-8ff4-da79f8a6d0bd" />
<img width="376" height="817" alt="а7" src="https://github.com/user-attachments/assets/650c76fb-4925-4ba0-99bd-22f56729e4da" />
<img width="377" height="817" alt="а8" src="https://github.com/user-attachments/assets/0dc374c7-80cf-4e5f-a8e4-e3cc1d85e4fd" />

##Поиск
<img width="1904" height="1080" alt="ф1" src="https://github.com/user-attachments/assets/e54b01c5-c52e-4fcf-ae13-48c057225e28" />
после выбора появляется карточка нужного букета по которой можно перейти на подробную и информацию
<img width="1903" height="1077" alt="ф2" src="https://github.com/user-attachments/assets/e27fd0ee-e174-4fd6-b2e3-9e6e877b1014" />

##Страница конкретного букета

<img width="1903" height="1078" alt="ф3" src="https://github.com/user-attachments/assets/7515f9b3-58a6-4ff9-bed3-aee4e143880a" />
<img width="1901" height="1076" alt="ф4" src="https://github.com/user-attachments/assets/434a2464-3e3a-47ba-854c-d5846f3d9d2b" />
<img width="1903" height="1075" alt="ф5" src="https://github.com/user-attachments/assets/abd5b13e-5092-4fa7-8c19-486c35f88027" />

##Мобильная версия

<img width="378" height="818" alt="ф6" src="https://github.com/user-attachments/assets/dbc0172c-e8fc-402b-bc4c-354eaee38655" />
<img width="370" height="817" alt="ф7" src="https://github.com/user-attachments/assets/f52f8108-d72d-403c-8be4-bc17d7b3edd9" />
<img width="376" height="818" alt="ф8" src="https://github.com/user-attachments/assets/daffd543-cf15-4cd4-8ad0-36409878420e" />
<img width="369" height="813" alt="ф9" src="https://github.com/user-attachments/assets/d518f437-8b0d-44a5-ad2f-409ee39ab62b" />

##Корзина и оформление заказа

<img width="1905" height="1080" alt="з1" src="https://github.com/user-attachments/assets/323d02f4-6d9a-40dd-be0c-cc2edf49d177" />

<img width="1905" height="1043" alt="з2" src="https://github.com/user-attachments/assets/9e2c0c97-7570-4f09-9182-836c338334c1" />

##Мобильная версия

<img width="426" height="931" alt="з3" src="https://github.com/user-attachments/assets/528d7d01-80ed-4ceb-ab61-c57d62a42afb" />
<img width="426" height="846" alt="з4" src="https://github.com/user-attachments/assets/d699eda3-2bc6-499e-a478-bf3ff8a67444" />
<img width="427" height="847" alt="з5" src="https://github.com/user-attachments/assets/05cd393a-3d9b-434c-94e8-8584eac77c73" />

## Возможности

- **Каталог по категориям**: розы, тюльпаны, пионы, гортензии и смешанные букеты.
- **Поиск с подсказками**: при вводе появляется список подходящих букетов, а найденная карточка раскрывается под поиском.
- **Страница букета**: описание, цена, размеры, упаковка и отзывы покупателей.
- **Корзина**: добавление букетов, изменение количества, удаление, подсчёт итоговой суммы.
- **Адаптивная вёрстка**: на телефоне карточки идут по две в ряд, навигация превращается в плавающую стеклянную панель внизу экрана.

## Технологии

| Технология | Для чего |
| --- | --- |
| [Vue 3](https://vuejs.org/) (Composition API, `<script setup>`) | интерфейс |
| [Vite](https://vite.dev/) | сборка и dev-сервер |
| [Vue Router](https://router.vuejs.org/) | маршрутизация |
| [Tailwind CSS v4](https://tailwindcss.com/) | стили |
| [Axios](https://axios-http.com/) | запросы к API |
| [json-server](https://github.com/typicode/json-server) | REST API на основе `db.json` |

## Быстрый старт

Нужен [Node.js](https://nodejs.org/) 18 или новее.

```bash
# 1. Клонировать репозиторий
https://github.com/Arport-rus/FlowerHub.git
cd FlowerHub

# 2. Установить зависимости
npm install
```

Для работы нужны **два запущенных процесса** (в двух терминалах):

```bash
# Терминал 1: API (http://localhost:3000)
npx json-server db.json

# Терминал 2: сайт (http://localhost:5173)
npm run dev
```

> Если у тебя json-server версии 0.17, команда другая:
> `npx json-server --watch db.json --port 3000`

## Модель данных (`db.json`)

```text
categories   id, slug, title
bouquets     id, categoryId, title, flowersCount, price, width, height,
             packagingType, packagingStyle, image, description,
             reviews[ { id, author, rating, text } ]
cart         id, bouquetId, title, price, image, quantity
```

`categoryId` связывает букет с категорией, а `bouquetId` в корзине хранит, какой именно букет туда добавили.

## API

| Метод | Адрес | Что делает |
| --- | --- | --- |
| `GET` | `/bouquets` | все букеты |
| `GET` | `/bouquets/:id` | один букет |
| `GET` | `/categories` | категории |
| `GET` | `/cart` | содержимое корзины |
| `POST` | `/cart` | добавить букет в корзину |
| `PATCH` | `/cart/:id` | изменить количество |
| `DELETE` | `/cart/:id` | удалить из корзины |

Все запросы вынесены в `src/service/flowerHub.js`.

## Структура проекта

```text
src/
├── assets/
│   └── main.css          # Tailwind, тема, подключение шрифтов
├── component/
│   ├── AppHeader.vue     # шапка и навигация
│   ├── AppFooter.vue     # подвал
│   ├── CardFlower.vue    # карточка букета
│   └── CategorySection.vue  # раздел категории
├── fonts/                # локальные шрифты
├── service/
│   └── flowerHub.js      # работа с API (axios)
├── store/
│   └── cart.js           # состояние корзины (composable useCart)
├── pages/                # HomePage, CartPage, страница букета
├── router/               # маршруты
├── App.vue
└── main.js
```

Корзина реализована как composable `useCart()`: массив объявлен вне функции, поэтому состояние общее для карточек, шапки и страницы корзины.

## Маршруты

| Путь | Страница |
| --- | --- |
| `/` | главная: hero, поиск, каталог, карта |
| `/flower/:id` | страница букета |
| `/cart-page` | корзина |

## Известные ограничения

- Корзина общая для всех посетителей, потому что хранится в `db.json`. 
- Фотографии букетов подгружаются с внешних сайтов и могут пропасть, если источник недоступен.


## Планы

- [ ] Перенос состояния корзины на Pinia
- [ ] Слайдер популярных букетов (Swiper)
- [ ] Свои фотографии вместо внешних ссылок
- [ ] Деплой

