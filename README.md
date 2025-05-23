![image](https://github.com/user-attachments/assets/e1f4003a-c8eb-4943-b422-ca83bb79509b)! Конфігурація робочого середовища Arch Linux

Цей документ описує налаштування мого робочого середовища на базі Arch Linux із використанням Hyprland як віконного менеджера та кількох додаткових утиліт для створення зручного та функціонального десктопу.

## Складові системи

### 1. Hyprland
Hyprland — це динамічний тайловий віконний менеджер із підтримкою Wayland. Він швидкий, легкий і пропонує гнучкі можливості налаштування.

- **Файл конфігурації**: `~/.config/hypr/hyprland.conf`
- **Опис**: Налаштування гарячих клавіш, правил вікон, анімацій, прозорості та поведінки робочих столів.

### 2. Kitty
Kitty — швидкий і сучасний термінальний емулятор із підтримкою GPU-прискорення.

- **Файл конфігурації**: `~/.config/kitty/kitty.conf`
- **Опис**: Налаштування шрифтів, кольорової теми, розміру вікна та гарячих клавіш для терміналу.

### 3. Waybar
Waybar — це легка та налаштовувана панель задач для Wayland-середовищ.

- **Файл конфігурації**: `~/.config/waybar/config` та `~/.config/waybar/style.css`
- **Опис**: Відображення системної інформації (час, батарея, мережа), робочих просторів Hyprland і трею.

### 4. Wofi
Wofi — це простий і швидкий лаунчер програм для Wayland.

- **Файл конфігурації**: `~/.config/wofi/config` та `~/.config/wofi/style.css`
- **Опис**: Налаштування вигляду меню запуску програм, кольорів і розмірів.

### 5. Thunar
Thunar — легкий і швидкий файловий менеджер від XFCE.

- **Файл конфігурації**: `~/.config/Thunar/thunar.rc`
- **Опис**: Налаштування поведінки файлового менеджера, таких як вигляд, сортування та контекстне меню.

### 6. Wlogout
Wlogout — утиліта для створення стильного меню завершення сеансу (вихід, перезавантаження, вимкнення).

- **Файл конфігурації**: `~/.config/wlogout/config` та `~/.config/wlogout/style.css`
- **Опис**: Налаштування кнопок завершення сеансу та їхнього вигляду.

### 7. Hyprlock
Hyprlock — утиліта для блокування екрана, спеціально розроблена для Hyprland.

- **Файл конфігурації**: `~/.config/hypr/hyprlock.conf`
- **Опис**: Налаштування екрана блокування, включаючи фон, введення пароля та анімації.

### 8. Hyprpaper
Hyprpaper — утиліта для управління шпалерами в Hyprland.

- **Файл конфігурації**: `~/.config/hypr/hyprpaper.conf`
- **Опис**: Встановлення шпалер для різних робочих просторів або моніторів.

## Встановлення
Для використання цієї конфігурації потрібно встановити всі перелічені пакети через пакетний менеджер Arch Linux (наприклад, `pacman` або AUR):

```bash
sudo pacman -S hyprland kitty waybar thunar
yay -S wofi wlogout hyprlock hyprpaper
