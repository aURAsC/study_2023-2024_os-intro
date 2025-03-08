---
## Front matter
lang: ru-RU
title: Настройка Git и GitHub
subtitle: Лабораторная работа по системам контроля версий
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
- Установка и настройка Git flow и pnpm.
- Создание branch-ей.
- Настройка подписи коммитов.
- Настройка тегов.

---

# Скриншоты и описание действий

## 1. Установка Gitflow
- **Действие:** Установка Gitflow с помощью команды `sudo dnf install gitflow`.
- **Скриншот:**  
  ![Установка Gitflow](image/screenshot_1.png)

---

## 2. Установка Node.js и pnpm
- **Действие:** Установка Node.js и pnpm с помощью команды `sudo dnf install nodejs pnpm`.
- **Скриншот:**  
  ![Установка Node.js и pnpm](image/screenshot_2.png)

---

## 3. Настройка pnpm
- **Действие:** Настройка pnpm с помощью команды `pnpm setup`.
- **Скриншот:**  
  ![Настройка pnpm](image/screenshot_3.png)

---

## 4. Создание ветки develop
- **Действие:** Создание ветки `develop` с помощью команды `git flow init`.
- **Скриншот:**  
  ![Создание ветки develop](image/screenshot_4.png)

---

## 5. Git push первой версии
- **Действие:** Отправка первой версии на GitHub с помощью команды `git push --all`.
- **Скриншот:**  
  ![Git push первой версии](image/screenshot_5.png)

---

## 6. Добавление feature_branch
- **Действие:** Создание и завершение функциональной ветки `feature_branch` с помощью команд `git flow feature start feature_branch` и `git flow feature finish feature_branch`.
- **Скриншот:**  
  ![Добавление feature_branch](image/screenshot_6.png)

---

## 7. Git push версий 1.2.3
- **Действие:** Создание и отправка версий 1.2.3 на GitHub с помощью команд `git flow release start 1.2.3` и `git flow release finish 1.2.3`.
- **Скриншот:**  
  ![Git push версий 1.2.3](image/screenshot_7.png)

---

## 8. Добавление bugfix
- **Действие:** Создание и завершение ветки исправления `bugfix` с помощью команд `git flow hotfix start bugfix` и `git flow hotfix finish bugfix`.
- **Скриншот:**  
  ![Добавление bugfix](image/screenshot_8.png)

---

# Заключение

## Выводы
- Установлены и настроены Git flow, pnpm.
- Созданы branch-и.
- Настроена подпись коммитов.
- Успешно созданы теги.
- Освоен процесс работы с Gitflow и Conventional Commits.

---
