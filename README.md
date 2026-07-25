<p align="center">
  <img src="screenshots/Logo.png" alt="SLauncher" width="500">
</p>

<p align="center">
  <a href="https://github.com/Soryyz-Project/SLauncher-by-Soryyz/releases/latest"><img src="https://img.shields.io/badge/%D0%A1%D0%BA%D0%B0%D1%87%D0%B0%D1%82%D1%8C-%D0%BF%D0%BE%D1%81%D0%BB%D0%B5%D0%B4%D0%BD%D1%8F%D1%8F%20%D0%B2%D0%B5%D1%80%D1%81%D0%B8%D1%8F-2d7aff?style=for-the-badge" alt="Download"></a>
  <a href="https://soryyz-project.github.io/slauncher-site/"><img src="https://img.shields.io/badge/%D0%A1%D0%B0%D0%B9%D1%82-%D0%9A%D0%B0%D1%82%D0%B0%D0%BB%D0%BE%D0%B3%20%D1%82%D0%B5%D0%BC%20%D0%B8%20%D0%BF%D0%BB%D0%B0%D0%B3%D0%B8%D0%BD%D0%BE%D0%B2-8B5CF6?style=for-the-badge" alt="Site"></a>
</p>

---

**SLauncher** — бесплатный игровой лаунчер для Windows. Умный поиск игр, геймпад, темы, плагины, Discord RPC.  
Создан для удобства — работает сразу после установки.

---

## Возможности

| | |
|---|---|
| 🎮 **Геймпад** | DualSense, DualShock, Xbox — полноценное управление, вибрация, тактильная отдача |
| 🖥️ **Интерфейс** | Полноэкранный, тёмная/светлая темы, плавные анимации, blur-панели |
| 🔍 **Автопоиск игр** | Сканирует Steam, Epic Games, реестр Windows и пользовательские папки |
| 🎬 **Медиа** | Скриншоты и видео в сетке, превью, полноэкранный плеер |
| 🌍 **Мультиязычность** | Русский, English, українська, беларуская, қазақша, oʻzbekcha |
| 🎨 **Кастомизация** | 100+ тем, CSS-темы, цвет акцента, прозрачность, фоновое видео |
| 🔌 **Плагины** | Lua-скрипты: бэкапы, трекеры, скриншоты, стриминг, макросы и 50+ других |
| 💬 **Discord RPC** | Показывает статус в Discord (в лаунчере / просматривает / играет) |
| 🗂️ **Трей** | Сворачивание в трей при запуске игры |

---

## Скриншоты

<p align="center">
  <img src="screenshots/Main.png" alt="Главный экран" width="45%">
  <img src="screenshots/Library.png" alt="Библиотека" width="45%">
</p>
<p align="center">
  <img src="screenshots/AboutGame.png" alt="Детали игры" width="45%">
  <img src="screenshots/Theme1.png" alt="Тема" width="45%">
  <img src="screenshots/Theme2.png" alt="Тема" width="30%">
  <img src="screenshots/Theme3.png" alt="Тема" width="30%">
  <img src="screenshots/Theme4.png" alt="Тема" width="30%">
  <img src="screenshots/Theme5.png" alt="Тема" width="30%">
  <img src="screenshots/Theme6.png" alt="Тема" width="30%">
</p>

---

## Системные требования

| Компонент | Минимальные | Рекомендуемые |
|-----------|-------------|---------------|
| **ОС** | Windows 10 64-bit | Windows 11 64-bit |
| **Процессор** | Intel Core i3 / AMD Ryzen 3 | Intel Core i5 / AMD Ryzen 5 |
| **ОЗУ** | 4 GB | 8 GB |
| **Видеокарта** | Intel HD Graphics / 1 GB VRAM | NVIDIA GTX 1060 / 2 GB VRAM |
| **Диск** | 500 MB свободно | 1 GB SSD |
| **Интернет** | Требуется для Discord RPC и каталога | Широкополосное соединение |
| **DirectX** | Версия 11 | Версия 12 |

---

## Установка

1. Скачай последнюю версию со **[страницы релизов](https://github.com/Soryyz-Project/SLauncher-by-Soryyz/releases/latest)**
2. Запусти установщик — всё настроится автоматически
3. Запускай SLauncher и играй

После установки лаунчер сам найдёт все твои игры.

---

## Каталог тем и плагинов

На сайте **[soryyz-project.github.io/slauncher-site](https://soryyz-project.github.io/slauncher-site/)** доступны:

- **100+ тем** — скачай CSS и примени в один клик
- **50+ плагинов** — Lua-скрипты с автоматическими хуками
- **Документация** — как создать свою тему или плагин

Установка темы: положи `.css` в `%USERPROFILE%\Documents\SLauncher\themes\` → выбери в настройках.  
Установка плагина: положи `.lua` в `%USERPROFILE%\Documents\SLauncher\plugins\` → включи в настройках.

---

## Управление с геймпада

| Кнопка | Действие |
|--------|----------|
| **Cross / A** | Подтвердить / запустить игру |
| **Circle / B** | Назад |
| **Square / X** | Поиск (библиотека) / добавить/удалить тег |
| **Triangle / Y** | Скрыть/показать подсказки |
| **LB / RB** | Переключение вкладок |
| **Крестовина / Стики** | Навигация |
| **Select / View** | Фильтр по тегам / открыть редактор тегов |

---

## Разработка

### Требования
- [Node.js](https://nodejs.org/) 18+
- [Rust](https://rustup.rs/)
- [Tauri CLI](https://v2.tauri.app/start/cli/): `cargo install tauri-cli --version "^2"`

### Сборка
```bash
npm install
npm run tauri build
```

Готовый установщик появится в `src-tauri/target/release/bundle/`.

---

<p align="center">
  <b>SLauncher</b> — проект <a href="https://github.com/Soryyz-Project">Soryyz Project</a><br>
  <a href="https://github.com/Soryyz-Project/SLauncher-by-Soryyz">GitHub</a> ·
  <a href="https://soryyz-project.github.io/slauncher-site/">Сайт</a> ·
  <a href="https://github.com/Soryyz-Project/SLauncher-by-Soryyz/releases">Скачать</a>
</p>
