# Hyprland config (Caelestia-flavoured)

Language: **English** (default) · [Русский](#русский) · [فارسی](#فارسی) · [Тоҷикӣ](#тоҷикӣ)

This repository contains a modular **Hyprland** configuration.

## What’s inside

- **Entry point**: `hyprland.conf`
  - Sources theme + variables: `scheme/current.conf`, `variables.conf`
  - Sources modules from `hyprland/`: `env.conf`, `general.conf`, `input.conf`, `misc.conf`, `animations.conf`,
    `decoration.conf`, `group.conf`, `execs.conf`, `rules.conf`, `gestures.conf`, `keybinds.conf`
  - Allows user overrides (sourced last):
    - `~/.config/caelestia/hypr-vars.conf`
    - `~/.config/caelestia/hypr-user.conf`
- **Notes/cheatsheet (multilingual)**: `config-notes.html`

## Usage

1. Put (or symlink) this repo into `~/.config/hypr`.
2. Make sure Hyprland loads `~/.config/hypr/hyprland.conf` (as your main config).
3. Prefer local overrides instead of editing the repo:
   - Variables: `~/.config/caelestia/hypr-vars.conf`
   - Extra config: `~/.config/caelestia/hypr-user.conf`

## Key places to edit

- **Keybinds**: `hyprland/keybinds.conf`
- **Gestures**: `hyprland/gestures.conf`
- **Window/workspace/layer rules**: `hyprland/rules.conf`
- **Theme**: `scheme/default.conf` → copied to `scheme/current.conf` on start

---

## Русский

Этот репозиторий содержит модульный конфиг **Hyprland**.

### Что внутри

- **Точка входа**: `hyprland.conf`
  - Подключает тему + переменные: `scheme/current.conf`, `variables.conf`
  - Подключает модули из `hyprland/`: `env.conf`, `general.conf`, `input.conf`, `misc.conf`, `animations.conf`,
    `decoration.conf`, `group.conf`, `execs.conf`, `rules.conf`, `gestures.conf`, `keybinds.conf`
  - Поддерживает пользовательские оверрайды (подключаются последними):
    - `~/.config/caelestia/hypr-vars.conf`
    - `~/.config/caelestia/hypr-user.conf`
- **Конспект/шпаргалка (мультиязычная)**: `config-notes.html`

### Использование

1. Положи (или сделай симлинк) этот репозиторий в `~/.config/hypr`.
2. Убедись, что Hyprland читает `~/.config/hypr/hyprland.conf` как основной конфиг.
3. Для локальных правок лучше использовать оверрайды:
   - Переменные: `~/.config/caelestia/hypr-vars.conf`
   - Доп. настройки: `~/.config/caelestia/hypr-user.conf`

### Где править чаще всего

- **Бинды**: `hyprland/keybinds.conf`
- **Жесты**: `hyprland/gestures.conf`
- **Правила (окна/воркспейсы/слои)**: `hyprland/rules.conf`
- **Тема**: `scheme/default.conf` → копируется в `scheme/current.conf` при старте

---

## فارسی

<div dir="rtl">

این مخزن شامل یک کانفیگ ماژولار برای **Hyprland** است.

### محتوا

- **نقطهٔ ورود**: `hyprland.conf`
  - بارگذاری تم + متغیرها: `scheme/current.conf`, `variables.conf`
  - بارگذاری ماژول‌ها از `hyprland/`: `env.conf`, `general.conf`, `input.conf`, `misc.conf`, `animations.conf`,
    `decoration.conf`, `group.conf`, `execs.conf`, `rules.conf`, `gestures.conf`, `keybinds.conf`
  - پشتیبانی از overrideهای کاربر (در انتها بارگذاری می‌شوند):
    - `~/.config/caelestia/hypr-vars.conf`
    - `~/.config/caelestia/hypr-user.conf`
- **یادداشت/چیت‌شیت (چندزبانه)**: `config-notes.html`

### استفاده

1. این ریپو را داخل `~/.config/hypr` قرار بده (یا symlink کن).
2. مطمئن شو Hyprland فایل `~/.config/hypr/hyprland.conf` را به‌عنوان کانفیگ اصلی می‌خواند.
3. به‌جای تغییر مستقیم ریپو، overrideهای محلی را ترجیح بده:
   - متغیرها: `~/.config/caelestia/hypr-vars.conf`
   - کانفیگ اضافی: `~/.config/caelestia/hypr-user.conf`

### جاهای مهم برای تغییر

- **Keybindها**: `hyprland/keybinds.conf`
- **Gestureها**: `hyprland/gestures.conf`
- **Ruleها (پنجره/ورک‌اسپیس/لایه)**: `hyprland/rules.conf`
- **تم**: `scheme/default.conf` → هنگام شروع به `scheme/current.conf` کپی می‌شود

</div>

---

## Тоҷикӣ

Ин репозиторӣ конфиги модулӣ барои **Hyprland** аст.

### Дарун чӣ ҳаст

- **Нуқтаи оғоз**: `hyprland.conf`
  - Мавзӯъ + тағйирёбандаҳоро пайваст мекунад: `scheme/current.conf`, `variables.conf`
  - Модулҳоро аз `hyprland/` пайваст мекунад: `env.conf`, `general.conf`, `input.conf`, `misc.conf`, `animations.conf`,
    `decoration.conf`, `group.conf`, `execs.conf`, `rules.conf`, `gestures.conf`, `keybinds.conf`
  - Override-и корбарро дастгирӣ мекунад (охирин бор source мешавад):
    - `~/.config/caelestia/hypr-vars.conf`
    - `~/.config/caelestia/hypr-user.conf`
- **Ёддошт/шпаргалка (бисёрзабона)**: `config-notes.html`

### Истифода

1. Ин репозиториро ба `~/.config/hypr` гузор (ё symlink кун).
2. Боварӣ ҳосил кун, ки Hyprland `~/.config/hypr/hyprland.conf`-ро ҳамчун конфиги асосӣ мехонад.
3. Барои тағйироти маҳаллӣ беҳтар аст override истифода шавад:
   - Тағйирёбандаҳо: `~/.config/caelestia/hypr-vars.conf`
   - Танзимоти иловагӣ: `~/.config/caelestia/hypr-user.conf`

### Ҷойҳои асосӣ барои таҳрир

- **Keybind-ҳо**: `hyprland/keybinds.conf`
- **Gesture-ҳо**: `hyprland/gestures.conf`
- **Қоидаҳо (тиреза/workspace/layer)**: `hyprland/rules.conf`
- **Мавзӯъ**: `scheme/default.conf` → ҳангоми оғоз ба `scheme/current.conf` нусха мешавад

