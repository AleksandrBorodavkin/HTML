# Bootstrap 5 Шпаргалка - Полное руководство

## 📋 Содержание

1. [Навигационная панель (Navbar)](#навигационная-панель-navbar)
2. [Цвета фона (Background)](#цвета-фона-background)
3. [Цвета текста (Text)](#цвета-текста-text)
4. [Flexbox утилиты](#flexbox-утилиты)
5. [Отступы (Spacing)](#отступы-spacing)
6. [Размеры и позиционирование](#размеры-и-позиционирование)
7. [Формы и границы](#формы-и-границы)
8. [Тени и эффекты](#тени-и-эффекты)
9. [Размеры шрифта](#размеры-шрифта)
10. [Кнопки](#кнопки)
11. [Сетка (Grid)](#сетка-grid)
12. [Формы](#формы)
13. [Дополнительные утилиты](#дополнительные-утилиты)
14. [Bootstrap Icons](#bootstrap-icons)
15. [Примеры использования](#примеры-использования)

---

## Навигационная панель (Navbar)

### Основные классы

- `navbar` - базовый класс навигационной панели
- `navbar-expand-lg` - расширяется на больших экранах
- `navbar-dark` - темная тема навигации
- `bg-primary` - синий фон
- `container` - контейнер с отступами

### Элементы навигации

- `navbar-brand` - логотип/бренд
- `navbar-nav` - контейнер для навигационных ссылок
- `nav-link` - стиль ссылок навигации
- `active` - активная ссылка
- `fw-bold` - жирный шрифт
- `text-white` - белый цвет текста
- `ms-auto` - автоматический отступ слева (выравнивание вправо)

## Цвета фона (Background)

- `bg-primary` - синий (основной)
- `bg-danger` - красный
- `bg-white` - белый
- `bg-secondary` - серый
- `bg-info` - синий (информационный)
- `bg-success` - зеленый
- `bg-opacity-10` - прозрачность фона 10%

## Цвета текста (Text)

- `text-white` - белый
- `text-dark` - темный
- `text-muted` - приглушенный серый
- `text-success` - зеленый
- `text-danger` - красный

## Flexbox утилиты

- `d-flex` - display: flex
- `flex-grow-1` - flex-grow: 1
- `flex-shrink-0` - flex-shrink: 0
- `align-items-center` - выравнивание по центру по вертикали
- `justify-content-center` - выравнивание по центру по горизонтали
- `justify-content-between` - пространство между элементами
- `align-self-center` - выравнивание элемента по центру

## Отступы (Spacing)

- `me-2` - margin-end: 0.5rem
- `me-3` - margin-end: 1rem
- `mb-1` - margin-bottom: 0.25rem
- `mb-2` - margin-bottom: 0.5rem
- `mb-3` - margin-bottom: 1rem
- `mb-4` - margin-bottom: 1.5rem
- `mb-5` - margin-bottom: 3rem
- `my-4` - margin по Y (top/bottom): 1.5rem
- `mt-3` - margin-top: 1rem
- `m-3` - margin: 1rem
- `p-3` - padding: 1rem
- `p-5` - padding: 3rem
- `px-2` - padding по X (left/right): 0.5rem
- `py-1` - padding по Y (top/bottom): 0.25rem
- `py-2` - padding по Y (top/bottom): 0.5rem

## Размеры и позиционирование

- `w-40` - width: 40px (если доступно)
- `h-40` - height: 40px (если доступно)
- `text-center` - text-align: center
- `text-end` - text-align: right
- `position-absolute` - position: absolute
- `position-relative` - position: relative
- `top-0` - top: 0
- `end-0` - right: 0 (Bootstrap 5)

## Формы и границы

### Границы (Borders)

- `border` - граница
- `border-start` - левая граница
- `border-4` - толщина границы 4px
- `border-secondary` - серый цвет границы
- `border-info` - синий цвет границы
- `border-success` - зеленый цвет границы
- `border-danger` - красный цвет границы

### Скругления (Border Radius)

- `rounded` - скругленные углы
- `rounded-circle` - круглые углы (полностью круглый)
- `rounded-pill` - скругленные как таблетка

## Тени и эффекты

- `shadow-sm` - маленькая тень

## Размеры шрифта

- `fs-3` - font-size: 1.75rem
- `fs-4` - font-size: 1.5rem (для Font Awesome иконок)
- `fs-5` - font-size: 1.25rem
- `small` - маленький размер шрифта

## Кнопки

- `btn` - базовый класс кнопки
- `btn-secondary` - вторичная кнопка
- `btn-outline-secondary` - контурная вторичная кнопка
- `btn-outline-primary` - контурная основная кнопка
- `btn-outline-danger` - контурная красная кнопка
- `btn-outline-success` - контурная зеленая кнопка
- `btn-sm` - маленькая кнопка
- `btn-group` - группа кнопок

## Сетка (Grid)

### Основные классы

- `container` - контейнер с отступами
- `row` - строка сетки
- `col-12` - полная ширина колонки
- `col-md-4` - колонка на средних экранах (33% ширины)
- `col-md-6` - колонка на средних экранах (50% ширины)

## Формы

### Основные элементы форм

- `form` - базовый класс формы
- `form-control` - стиль поля ввода
- `input-group` - группа элементов ввода
- `mb-3` - отступ снизу для полей формы

### Типы полей ввода

- `type="text"` - текстовое поле
- `type="email"` - поле для email
- `type="tel"` - поле для телефона
- `type="url"` - поле для URL
- `type="password"` - поле для пароля

## Дополнительные утилиты

### Display утилиты

- `d-flex` - display: flex
- `d-grid` - display: grid

### Spacing утилиты

- `gap-2` - gap: 0.5rem

### Typography утилиты

- `fw-semibold` - font-weight: 600 (полужирный)
- `mb-0` - margin-bottom: 0 (убирает отступ снизу)

## Bootstrap Icons

- `bi` - базовый класс Bootstrap Icons
- `bi-laptop` - иконка ноутбука
- `bi-calendar-event` - иконка календаря
- `bi-building` - иконка здания
- `bi-award` - иконка награды
- `bi-person-fill` - иконка пользователя (заполненная)

### Подключение Bootstrap Icons

```html
<link
  rel="stylesheet"
  href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.1/font/bootstrap-icons.css"
/>
```

## Примеры использования

### Навигационная панель

```html
<nav class="navbar navbar-expand-lg bg-primary navbar-dark">
  <div class="container">
    <a class="navbar-brand" href="#">
      <i class="bi bi-laptop me-2"></i>
    </a>
    <div class="navbar-nav">
      <a class="nav-link text-white" href="#">Home</a>
      <a class="nav-link active fw-bold" href="#">Settings</a>
    </div>
    <div class="ms-auto">
      <img src="avatar.jpg" class="rounded-circle" width="40" height="40" />
    </div>
  </div>
</nav>
```

### Форма с полями ввода

```html
<form>
  <div class="mb-3">
    <input type="text" class="form-control" placeholder="First name" />
  </div>
  <div class="mb-3">
    <input type="email" class="form-control" placeholder="Email" />
  </div>
  <div class="mb-3">
    <input type="password" class="form-control" placeholder="Password" />
  </div>
  <button type="submit" class="btn btn-secondary">Save changes</button>
</form>
```

### Трехколоночная сетка

```html
<div class="container">
  <div class="row">
    <div class="col-md-4">
      <!-- Колонка 1 -->
    </div>
    <div class="col-md-4">
      <!-- Колонка 2 -->
    </div>
    <div class="col-md-4">
      <!-- Колонка 3 -->
    </div>
  </div>
</div>
```

### Заголовки секций с фоном

```html
<div class="bg-info bg-opacity-10 p-3 mb-4">
  <div class="row text-center">
    <div class="col-md-4">
      <h6 class="mb-0 fw-bold text-dark">SECTION 1</h6>
    </div>
    <div class="col-md-4">
      <h6 class="mb-0 fw-bold text-dark">SECTION 2</h6>
    </div>
    <div class="col-md-4">
      <h6 class="mb-0 fw-bold text-dark">SECTION 3</h6>
    </div>
  </div>
</div>
```

### Круглая иконка с фоном

```html
<div
  class="d-flex align-items-center justify-content-center me-3 flex-shrink-0 bg-danger rounded-circle p-3 align-self-center"
>
  <i class="bi bi-calendar-event text-white fs-4"></i>
</div>
```

### Карточка с тенью

```html
<div class="bg-white border rounded p-3 mb-3 shadow-sm">
  <!-- содержимое -->
</div>
```

### Flex контейнер с выравниванием

```html
<div class="d-flex justify-content-between align-items-start mb-2">
  <!-- содержимое -->
</div>
```

### Карточка с цветной левой границей

```html
<div class="card mb-3 border-start border-4 border-info bg-info bg-opacity-10">
  <div class="card-body">
    <h5 class="card-title">Заголовок</h5>
    <p class="text-muted small">Дата</p>
  </div>
</div>
```

### Аватар пользователя с иконкой

```html
<div
  class="bg-primary text-white rounded-circle d-flex align-items-center justify-content-center"
  style="width: 40px; height: 40px;"
>
  <i class="bi bi-person-fill"></i>
</div>
```

### Абсолютно позиционированный элемент

```html
<div
  class="position-absolute top-0 end-0 bg-success text-white rounded-circle d-flex align-items-center justify-content-center fw-bold"
  style="width: 30px; height: 30px; font-size: 12px; margin: 15px;"
>
  12
</div>
```
