# nekxd.ru-closed

Заглушка для [nekxd.ru](https://nekxd.ru) — сайт переехал на [old.ynd.su](https://old.ynd.su).

## Страницы

| Файл | Описание |
|------|----------|
| `index.html` | Главная — сайт переехал |
| `404.html` | Страница ошибки 404 — сайт переехал |

## Дизайн

Используется [Holo Web](https://github.com/ZMYaro/holo-web) — CSS-библиотека в стиле Android ICS Dark.  
Работает на старых устройствах (Android 2.3+, IE9+, старые WebKit).

## Деплой

- **Apache**: `.htaccess` настроен для `ErrorDocument 404 /404.html`
- **Netlify / Cloudflare Pages**: `_redirects` настроен для кастомного 404
- **GitHub Pages**: переименуйте `404.html` — GitHub Pages автоматически подхватит его
