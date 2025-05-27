# МебельЭко - Современная мебельная компания

![МебельЭко](https://img.shields.io/badge/Made%20with-React-blue?style=for-the-badge&logo=react)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)

## 🏠 О проекте

МебельЭко - это современный веб-сайт мебельной компании, специализирующейся на экологически чистой и стильной мебели. Сайт создан с использованием современных веб-технологий для обеспечения оптимальной производительности и пользовательского опыта.

## ✨ Особенности

- **Современный дизайн** - Чистый и привлекательный интерфейс
- **Адаптивность** - Оптимизировано для всех устройств
- **Высокая производительность** - Быстрая загрузка и отзывчивость
- **SEO-оптимизация** - Готово для поисковых систем
- **Интерактивные компоненты** - Галереи, формы обратной связи
- **Модульная архитектура** - Легко поддерживаемый код

## 🛠 Технологии

- **Frontend Framework**: React 18 + TypeScript
- **Build Tool**: Vite
- **Styling**: Tailwind CSS
- **Package Manager**: Bun
- **Deployment**: Netlify
- **Code Quality**: ESLint + Biome
- **Image Optimization**: Встроенный компонент оптимизации

## 🚀 Быстрый старт

### Предварительные требования

- Node.js 18+ или Bun
- Git

### Установка

1. Клонируйте репозиторий:
```bash
git clone https://github.com/Lyti4/dmitriy-bogomolov-fly.git
cd dmitriy-bogomolov-fly
```

2. Установите зависимости:
```bash
bun install
```

3. Запустите сервер разработки:
```bash
bun dev
```

4. Откройте [http://localhost:5173](http://localhost:5173) в браузере

## 📝 Доступные скрипты

- `bun dev` - Запуск сервера разработки
- `bun build` - Сборка проекта для продакшена
- `bun preview` - Предварительный просмотр собранного проекта
- `bun lint` - Проверка кода с помощью ESLint
- `bun format` - Форматирование кода с помощью Biome

## 📁 Структура проекта

```
src/
├── components/          # React компоненты
│   ├── Header.tsx      # Шапка сайта
│   ├── HeroBanner.tsx  # Главный баннер
│   ├── Benefits.tsx    # Преимущества
│   ├── Portfolio.tsx   # Портфолио
│   ├── Services.tsx    # Услуги
│   ├── About.tsx       # О компании
│   ├── Contacts.tsx    # Контакты
│   ├── Footer.tsx      # Подвал
│   └── OptimizedImage.tsx # Оптимизированные изображения
├── types/              # TypeScript типы
├── utils/              # Утилиты
│   └── analytics.ts    # Аналитика
├── styles/             # Стили
└── App.tsx            # Главный компонент
```

## 🎨 Компоненты

### OptimizedImage
Компонент для оптимизированной загрузки изображений с:
- Ленивой загрузкой
- Плейсхолдерами
- Обработкой ошибок
- Оптимизацией производительности

### Адаптивная навигация
- Мобильное меню
- Плавная навигация по секциям
- Интерактивные элементы

## 🌐 Деплой

Проект автоматически деплоится на Netlify при пуше в основную ветку.

### Ручной деплой

```bash
bun build
# Загрузите содержимое папки dist на ваш хостинг
```

## 📞 Контактная информация

- **Телефон**: +7 (XXX) XXX-XX-XX
- **Email**: info@mebeleco.ru
- **Адрес**: г. Москва, ул. Примерная, д. 1

## 🤝 Участие в разработке

1. Форкните проект
2. Создайте ветку для новой функции (`git checkout -b feature/AmazingFeature`)
3. Закоммитьте изменения (`git commit -m 'Add some AmazingFeature'`)
4. Запушьте в ветку (`git push origin feature/AmazingFeature`)
5. Откройте Pull Request

## 📄 Лицензия

Этот проект распространяется под лицензией MIT. См. файл `LICENSE` для деталей.

## 🔧 Поддержка

Если у вас возникли вопросы или проблемы, создайте [issue](https://github.com/Lyti4/dmitriy-bogomolov-fly/issues) в этом репозитории.

---

Создано с ❤️ для МебельЭко