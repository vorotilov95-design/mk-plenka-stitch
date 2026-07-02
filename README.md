# МК «Пленка» — Stitch landing

Статический лендинг предпродажи мастер-класса my.love.dom, собранный из Stitch-экрана:

`Полный лендинг (Мобайл) — Мастер-класс Пленка (RU) — Оптимизация Hero`

## Локальный запуск

```bash
python3 -m http.server 8080
```

После запуска откройте `http://localhost:8080`.

## Состав

- `index.html` — HTML из Stitch с локальными ссылками на изображения.
- `assets/image-01.jpg` ... `assets/image-09.jpg` — изображения из Stitch.
- Tailwind CDN и Google Fonts подключаются внешне, как в Stitch-экспорте.
