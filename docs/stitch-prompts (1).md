# TVORIBOX — промпты для Google Stitch

Режим: **Web**. Все экраны делайте в ОДНОМ проекте Stitch. К каждому промпту прикрепляйте каркас из `docs/wireframes/`. Одна страница — один промпт.

## 01. Главная

```
Design a desktop web page for TVORIBOX — an online store of creative kits and art supplies with delivery across Kazakhstan.
Users: parents, kids' teachers and hobbyists in Almaty and Astana.
Page: Home page. Follow the attached wireframe layout exactly.
Blocks: [header with logo, menu (Каталог, Доставка, Контакты), language switcher RU | KK, cart icon, login button], [hero: title, short text, main button "Смотреть каталог"], [9 category cards], [4 popular product cards: photo, name, price, button "В корзину"], [delivery and payment: courier in Almaty and Astana, pickup only in Almaty, payment on receipt, order without registration], [footer with contacts].
Style: bright, warm, friendly. Main color: #F28C28.
No online card payment, no favorites, no reviews. All text on the page must be in Russian. Use realistic content, no lorem ipsum.
```

## 02. Каталог

```
Now create the Catalog page in the same style and design system as the Home page.
Follow the attached wireframe.
Blocks: [header with language switcher RU | KK], [page title "Каталог", search field], [left filter: 9 categories with checkboxes], [grid of product cards, 3 columns], [pagination], [footer].
Data on the page: product photo, name, short description, price, stock quantity, button "В корзину".
No sorting, no price filter, no discounts, no old prices.
Keep the same header, footer, colors, fonts and buttons. Text in Russian.
```

## 03. Корзина и оформление

```
Now create the Cart and Checkout page in the same style and design system as the Home page.
Follow the attached wireframe.
Blocks: [header], [list of cart items with photo, name, price per item, quantity control − / +, item total, remove button], [order total], [button "Продолжить покупки"], [checkout form: name, phone, delivery method courier or pickup (pickup only in Almaty), city Алматы or Астана, address, payment on receipt in cash or by transfer, total, main button "Оформить заказ"], [footer].
No online card payment, no card number fields. Guests can order with name and phone.
Keep the same header, footer, colors, fonts and buttons. Text in Russian.
```

## 04. Личный кабинет

```
Now create the Account page in the same style and design system as the Home page.
Follow the attached wireframe.
Blocks: [header], [left menu: "Мои заказы", "Мои данные", "Выйти"], [orders table with columns: № заказа, дата, состав, сумма, статус, action button "Повторить заказ"], [footer].
Order statuses as colored badges: Новый (#FBBF24), Подтверждён (#F28C28), В доставке (#2563EB), Готов к выдаче (#0D9488), Выполнен (#16A34A), Отменён (#DC2626). No "Оплачен" status.
Keep the same header, footer, colors, fonts and buttons. Text in Russian.
```

## 05. Панель администратора

```
Now create the Admin panel page in the same style and design system as the Home page.
Follow the attached wireframe.
This is an admin page: table of orders with columns [№, клиент, телефон, доставка, сумма, статус], status filter with the 6 statuses (Новый, Подтверждён, В доставке, Готов к выдаче, Выполнен, Отменён), search by number or phone, button to change status.
Second tab "Товары": form to add a product with fields [название RU, название KK, описание, категория, цена, остаток], photo upload, button "Сохранить товар". No discount field.
Keep the same header, footer, colors, fonts and buttons. Text in Russian.
```

## Исправить уже сделанные экраны (один промпт — одна правка)

- `Replace "Оплата картой" with "Оплата при получении" everywhere. Remove any card payment.`
- `Add a language switcher "RU | KK" to the header, left of the cart icon.`
- `Pickup is available only in Almaty. Courier delivery: Almaty and Astana.`
- `Remove the sort dropdown, the price filter and any discount badges from the catalog.`
- `Remove "Избранное" and reviews blocks. They are not in the MVP.`

## Экспорт дизайн-системы

В Stitch: Export → DESIGN.md. Если не нашли, попросите:

```
Describe the design system of this project as a markdown file: colors with HEX, fonts and sizes, buttons, cards, inputs, spacing.
```

Сверьте HEX с `docs/design.md` и впишите точные значения.
