# bubanya.github.io

Статическая сборка лендинга Bubanya для GitHub Pages.

## Источник

Исходник сайта: `/home/ebalai/Проекты/bubanya-site` (Vite + React + TypeScript).
Здесь лежит только собранный `dist/`.

Пересборка:

```bash
cd /home/ebalai/Проекты/bubanya-site
npm run build
cp -a dist/. /home/ebalai/11/bubanya.github.io/
```

## Скачивание сборок

Сайт не хранит большие файлы. Кнопки ведут на GitHub Releases:

- `Bubanya-linux-x86_64.AppImage`
- `Bubanya-windows-x64-setup.exe`
- `Bubanya-windows-x64.zip`

Прямые ссылки:

```
https://github.com/bubanya/bubanya/releases/latest/download/Bubanya-linux-x86_64.AppImage
https://github.com/bubanya/bubanya/releases/latest/download/Bubanya-windows-x64-setup.exe
https://github.com/bubanya/bubanya/releases/latest/download/Bubanya-windows-x64.zip
```

## Публикация

Settings → Pages → Deploy from a branch → `main` / `(root)`.
Сайт: https://bubanya.github.io/
