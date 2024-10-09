# Інструкція з встановлення Git

## Windows

1. Завантажте інсталятор Git з офіційного сайту:  
   [https://git-scm.com/download/win](https://git-scm.com/download/win)

2. Запустіть інсталятор та дотримуйтесь інструкцій на екрані. Для більшості користувачів підходять налаштування за замовчуванням.

## macOS

1. Відкрийте **Terminal** та введіть наступну команду для встановлення Git через Homebrew (якщо Homebrew ще не встановлений, спершу [встановіть його](https://brew.sh/)):

```bash
brew install git
```

2. Якщо ви хочете встановити Git через графічний інсталятор, завантажте його тут:  
   [https://git-scm.com/download/mac](https://git-scm.com/download/mac)

## Linux

### Ubuntu / Debian

1. Відкрийте термінал і виконайте команду:
   ```bash
   sudo apt update
   sudo apt install git
   ```

### Fedora

1. Виконайте наступну команду:
   ```bash
   sudo dnf install git
   ```

### Arch Linux

1. Виконайте команду:
   ```bash
   sudo pacman -S git
   ```

## Перевірка встановлення

Після встановлення Git, ви можете перевірити успішність, запустивши в терміналі наступну команду:

```bash
git --version
```

Якщо Git встановлений, ви побачите повідомлення про версію Git, наприклад:

```
git version 2.47.0
```
