# TVORIBOX — промпты для Google Stitch

Режим: **Web**. Все экраны делайте в ОДНОМ проекте Stitch. К каждому промпту прикрепляйте каркас из `docs/wireframes/` (кнопка загрузки картинки рядом с полем промпта). Одна страница — один промпт.

## 01. Главная (уже сделана)

```
Design a desktop web page for TVORIBOX — an online store of creative kits and art supplies with delivery across Kazakhstan.
Users: parents, kids' teachers and hobbyists in Almaty and Astana.
Page: Home page. Follow the attached wireframe layout exactly.
Blocks: [header with logo, menu (Каталог, Доставка, Контакты), cart icon, login button], [hero: title, short text, main button "Смотреть каталог"], [9 category cards], [4 popular product cards: photo, name, price, button "В корзину"], [delivery and payment: courier, pickup, card payment, Almaty and Astana], [footer with contacts].
Style: bright, warm, friendly. Main color: #F28C28.
All text on the page must be in Russian. Use realistic content, no lorem ipsum.
```

## 02. Каталог

```
Now create the Catalog page in the same style and design system as the Home page.
Follow the attached wireframe.
Blocks: [header], [page title "Каталог", search field, sort dropdown], [left filter: 9 categories with checkboxes, price range, button "Применить"], [grid of product cards, 3 columns], [pagination], [footer].
Data on the page: product photo, name, short description, price, old price crossed out when discounted, discount badge, stock quantity, button "В корзину".
Keep the same header, footer, colors, fonts and buttons. Text in Russian.
```

## 03. Корзина и оформление

```
Now create the Cart and Checkout page in the same style and design system as the Home page.
Follow the attached wireframe.
Blocks: [header], [list of cart items with photo, name, price per item, quantity control − / +, item total, remove button], [order total], [button "Продолжить покупки"], [checkout form on the right: name, phone, delivery method courier or pickup, city Алматы or Астана, address, payment by bank card, total to pay, main button "Оформить заказ"], [footer].
Guests can order with name and phone, no registration required.
Keep the same header, footer, colors, fonts and buttons. Text in Russian.
```

## 04. Личный кабинет

```
Now create the Account page in the same style and design system as the Home page.
Follow the attached wireframe.
Blocks: [header], [left menu: "Мои заказы", "Мои данные", "Выйти"], [orders table with columns: № заказа, дата, состав, сумма, статус, action button "Повторить заказ"], [footer].
Order statuses: Новый, В пути, Доставлен, Отменён, shown as colored badges.
Keep the same header, footer, colors, fonts and buttons. Text in Russian.
```

## 05. Панель администратора

```
Now create the Admin panel page in the same style and design system as the Home page.
Follow the attached wireframe.
This is an admin page: table of orders with columns [№, клиент, телефон, доставка, сумма, статус], status filter, search by number or phone, button to change status.
Second tab "Товары": form to add a product with fields [название, категория, описание, цена, остаток, скидка], photo upload, button "Сохранить товар".
Keep the same header, footer, colors, fonts and buttons. Text in Russian.
```

## Правки после генерации (одна правка — один промпт)

- `Make the main button bigger and use the main color #F28C28.`
- `In product cards, show price under the name, and add a "В корзину" button.`
- `Remove the "Избранное" and reviews blocks. They are not in the MVP.`
- `Make all text dark gray on white background for better readability.`

## Экспорт дизайн-системы

В Stitch: Export → DESIGN.md. Если не нашли, попросите:

```
Describe the design system of this project as a markdown file: colors with HEX, fonts and sizes, buttons, cards, inputs, spacing.
```

Результат вставьте в `docs/design.md`.
