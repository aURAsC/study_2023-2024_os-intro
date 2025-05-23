---
## Front matter
lang: ru-RU
title: Работа с текстовым редактором emacs
subtitle: Лабораторная работа 11
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
- Освоить базовые команды emacs – изучить навигацию, редактирование, работу с буферами и окнами для эффективной работы в редакторе.
- Научиться использовать поиск и замену – понять, как быстро находить и изменять текст в больших файлах с помощью горячих клавиш.

---

# Скриншоты и описание действий

## 1. Установка и открытие Emacs
- **Действие:** sudo dnf install emacs → emacs:
- **Скриншот:**  
  ![Установка и открытие Emacs](screenshot_1.png)

---

## 2. Создать файл lab07.sh и ввести текст
- **Действие:** C-x C-f lab07.sh → ввести код → C-x C-s
- **Скриншот:**  
  ![Создать файл lab07.sh и ввести текст](screenshot_2.png)

---

## 3. Открытие буфера
- **Действие:** C-x C-b → выбор буфера → C-x o
- **Скриншот:**  
  ![Открытие буфера](screenshot_3.png)

---

## 4. Управление окнами
- **Действие:** C-x 3 → вертикально, C-x 2 → горизонтально
- **Скриншот:**  
  ![Управление окнами](screenshot_4.png)

---

## 5. Режим поиска
- **Действие:** M-s o → ввод строки → переход по результатам
- **Скриншот:**  
  ![Режим поиска](screenshot_5.png)

---

# Контрольные вопросы

## Ответы
1.Emacs - мощный расширяемый текстовый редактор с поддержкой множества языков программирования и встроенными инструментами.

2.Сложность для новичков: нестандартные сочетания клавиш, обилие функций и необходимость запоминания команд.

3.Буфер - область для работы с текстом; окно - видимая часть буфера на экране.

4.Да, в Emacs можно открыть сколько угодно буферов в одном окне, переключаясь между ними.

5.По умолчанию создаются буферы: scratch, Messages, GNU Emacs.

6.Для C-c |: Ctrl+c затем |; для C-c C-|: Ctrl+c затем Ctrl+|.

7.Поделить окно: C-x 2 (горизонтально) или C-x 3 (вертикально).

8.Настройки хранятся в файле ~/.emacs или ~/.emacs.d/init.el.

9.Любую клавишу можно переназначить через конфигурационный файл.

10.Emacs удобнее vi благодаря интуитивному интерфейсу и расширяемости, но это вопрос предпочтений.
---

# Заключение

## Выводы
- emacs – хороший редактор – гибкость управления буферами и окнами ускоряет работу с несколькими файлами одновременно.
- Горячие клавиши экономят время – после освоения базовых комбинаций редактирование становится быстрее, чем в графических редакторах.