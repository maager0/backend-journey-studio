# Backend Journey

Личный учебный трекер Python Backend, статический сайт в `index.html`: 10 учебных недель, задачи и тренажёр, заметки, таймер, статистика и локальное сохранение.

## GitHub Pages
1. Сделайте репозиторий публичным (Settings → General → Change repository visibility).
2. Settings → Pages → Build and deployment → Deploy from a branch → main / (root) → Save.
3. После успешной публикации адрес: https://maager0.github.io/backend-journey-studio/

## Supabase
Облачный вход пока **не настроен**. Приложение работает локально, но облачная регистрация требует отдельного проекта Supabase. Бесплатный лимит активных проектов достигнут, существующие проекты не затронуты.

Когда отдельный проект станет доступен: выполните `supabase_setup.sql`, настройте Email Auth, Site URL и Redirect URLs, затем укажите Project URL и Publishable Key в `CLOUD_URL` и `CLOUD_PUBLISHABLE_KEY` в `index.html`. Не публикуйте secret/service_role key.

## Сохранение
Прогресс хранится в localStorage браузера; экспорт и импорт JSON работают для резервного копирования и переноса с локального файла на GitHub Pages.