# TVORIBOX — этап «Дизайн»: чек-лист сдачи

## Что нужно сдать

| № | Что сделать | Куда сохранить | Где делать | Баллы | Готово |
|---|---|---|---|---|---|
| 1 | Загрузить `design.md` | `docs/design.md` | GitHub: Add file → Upload files | 15 + 5 | ☐ |
| 2 | Сделать в Stitch 4 оставшихся экрана: каталог, корзина и оформление, личный кабинет, админка | (экраны остаются в Stitch) | stitch.withgoogle.com | | ☐ |
| 3 | Сохранить скриншоты 4–5 экранов: `01-home.png`, `02-catalog.png` и так далее | `docs/screens/` | Stitch, затем GitHub | 20 | ☐ |
| 4 | Нарисовать 5 каркасов: блоки подписаны, кнопки соединены стрелками | `docs/wireframes/` | excalidraw.com, затем GitHub | 15 | ☐ |
| 5 | Загрузить папки `screens` и `wireframes` | `docs/` | GitHub: Add file → Upload files | | ☐ |
| 6 | Скопировать ссылку на последний commit и отправить в чат группы | WhatsApp-чат | GitHub, затем WhatsApp | 10 | ☐ |

Ссылку в чат отправляйте только после шага 5, когда в `docs/` будут все три части.

## Структура папки docs

```
docs/
├── architecture.md
├── design.md
├── wireframes/
│   ├── 01-home.png
│   ├── 02-catalog.png
│   ├── 03-cart.png
│   ├── 04-account.png
│   └── 05-admin.png
└── screens/
    ├── 01-home.png
    ├── 02-catalog.png
    ├── 03-cart.png
    ├── 04-account.png
    └── 05-admin.png
```

## Как загрузить через сайт GitHub

1. Откройте репозиторий `tvoribox` и перейдите в папку `docs`.
2. Нажмите **Add file → Upload files**.
3. Перетащите файлы или папки.
4. Нажмите **Commit changes**.
5. Откройте последний commit и скопируйте адрес из браузера.

## Как загрузить через терминал

```
git add docs/
git commit -m "design: wireframes, screens, design.md"
git push
```

## Вопросы к защите (35%)

1. Почему на главной странице такие блоки и такая главная кнопка? (12)
2. Как экран связан с базой данных: откуда берутся поля на карточке? (12)
3. Что вы изменили после ИИ и почему? (11)
