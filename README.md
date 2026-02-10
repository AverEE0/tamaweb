# Tamaweb — виртуальный питомец (русский интерфейс)

Полноценная игра-тамагочи на основе [Tamaweb](https://github.com/autosam/Tamaweb). Часть интерфейса переведена на русский.

## Как открыть по ссылке (GitHub Pages)

1. Создай на GitHub репозиторий **tamaweb**: https://github.com/new (имя: `tamaweb`, без README).
2. Выполни в папке проекта:
   ```
   git remote add origin https://github.com/ТВОЙ_ЛОГИН/tamaweb.git
   git push -u origin main
   ```
3. В репозитории: **Settings** → **Pages** → **Source**: **Deploy from a branch** → **Branch**: **main** → **/ (root)** → Save.
4. Через 1–2 минуты игра будет доступна по адресу: **https://ТВОЙ_ЛОГИН.github.io/tamaweb/**

## Локальный запуск

Раздай папку любым статическим сервером, например:
```bash
npx serve -l 5000
```
Открой в браузере: http://localhost:5000

## Лицензия

Оригинал Tamaweb: CC BY-NC-SA 4.0 (autosam). См. LICENSE в репозитории.
