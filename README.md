# 5weel — Portfolio

Статическая витрина с проектами. Доступна через GitHub Pages.

## Проекты
- **CRM: Partners & Orders** (PySide6 + SQLAlchemy) → https://github.com/5wee1/crm-partners-orders
- **Task Manager Kanban** (PHP + MySQL + JS) → https://github.com/5wee1/task-manager-kanban-php
- **Yandex Log Analytics** (Python, pandas) → https://github.com/5weel/log-analytics

## Локальный просмотр
Откройте `index.html` в браузере или поднимите простой сервер:
```bash
python -m http.server 8000
```

## Публикация на GitHub Pages
1) Создайте репозиторий `portfolio`.
2) Запушьте файлы (см. команды ниже в этом README).
3) В GitHub: **Settings → Pages** → *Branch:* `main` — `/root` → **Save**.
4) Ваша страница будет по адресу: `https://5wee1.github.io/portfolio/`.

## Команды для публикации
```bash
git init
git add .
git commit -m "feat: portfolio showcase (static)"
git branch -M main
git remote add origin https://github.com/5wee1/portfolio.git
git push -u origin main
```

## Скриншоты
Положите изображения в `assets/` и обновите ссылки в `index.html` при необходимости.
По умолчанию используются плейсхолдеры: `crm.png`, `kanban.png`, `logs.png`.
