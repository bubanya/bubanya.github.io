# bubanya.github.io

Статический сайт Bubanya для GitHub Pages.

## Публикация

1. Создай на GitHub репозиторий `bubanya.github.io` (public).
2. Запушь этот репозиторий в `main`.
3. Settings → Pages → Source: Deploy from a branch → `main` / `(root)` → Save.
4. Сайт появится на https://bubanya.github.io/

## Ссылки на скачивание

Сайт ссылается на стабильные имена ассетов из релизов основного репозитория
`bubanya/bubanya`:

- `Bubanya-linux-x86_64.AppImage`
- `Bubanya-windows-x64-setup.exe`
- `Bubanya-windows-x64.zip`

Их создаёт workflow `.github/workflows/release.yml` при пуше тега `v*`.
