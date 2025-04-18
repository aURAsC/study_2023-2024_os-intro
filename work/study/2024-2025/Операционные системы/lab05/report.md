---
## Front matter
lang: ru-RU
title: Менеджер паролей pass
subtitle: Лабораторная работа 5
author:
  - Смольняков Данил Евгеньевич
institute:
  - Российский университет дружбы народов, Москва, Россия
date: Архитектура компьютеров и ОС

## i18n babel
babel-lang: russian
babel-otherlangs: english

## Formatting pdf
toc: false
toc-title: Содержание
slide_level: 2
aspectratio: 169
section-titles: true
theme: metropolis
header-includes:
 - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
---

# Цель работы

## Цель
- Настроить рабочую среду с использованием менеджера паролей pass и системы управления конфигурацией chezmoi.
- Установить и настроить дополнительные инструменты для работы с окружением.
- Организовать синхронизацию конфигурационных файлов и паролей между устройствами.

---

# Скриншоты и описание действий

## 1. Установка и настройка pass:
- **Действие:** Установить менеджер паролей pass и gopass sudo dnf install pass pass-otp gopass.
- **Скриншот:**  
  ![Установка и настройка pass](screenshot_1.png)

---

## 2. Синхронизация с Git:
- **Действие:** Инициализировать хранилище паролей и синхронизировать его с удалённым репозиторием на GitHub.
- **Скриншот:**  
  ![Синхронизация с Git](screenshot_2.png)

---

## 3. Создание пароля для пользователя:
- **Действие:** Создать новый пароль для пользователя и сохранить его в хранилище pass.pass insert example.com/user.
- **Скриншот:**  
  ![Создание пароля для пользователя](screenshot_3.png)

---

## 4. Создание репозитория dotfiles и настройка шаблонов:
- **Действие:** Создать репозиторий для хранения конфигурационных файлов и настроить шаблоны с помощью chezmoi.
- **Скриншот:**  
  ![Создание репозитория dotfiles и настройка шаблонов](screenshot_4.png)

---

## 5. Установка дополнительных пакетов:
- **Действие:** Установить необходимые пакеты для работы с окружением.
- **Скриншот:**  
  ![Установка дополнительных пакетов](screenshot_5.png)

---

## 6. Создание конфигурационного файла:
- **Действие:** Создать и настроить конфигурационный файл для Sway.
- **Скриншот:**  
  ![Создание конфигурационного файла](screenshot_6.png)

---

## 7. Установка Browserpass:
- **Действие:** Установить Browserpass для интеграции менеджера паролей с браузером.
- **Скриншот:**  
  ![Установка Browserpass](screenshot_7.png)

---

## 8. Изменение конфигурации для автообновления:
- **Действие:** Настроить автоматическое обновление конфигурации с помощью chezmoi.
- **Скриншот:**  
  ![Изменение конфигурации для автообновления](screenshot_8.png)

---

# Заключение

## Выводы
- Рабочая среда успешно настроена.
- Настроены инструменты для управления паролями и конфигурационными файлами.
- Обеспечена синхронизация между устройствами.