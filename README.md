# life-rpg
A gamified habit tracker system inspired by Solo Leveling - level up your life through daily quests and challenges

Я подготовлю для вас README на русском и английском языках для репозитория life-rpg с тематикой Solo Leveling.

## README.md (Русский)

```markdown
# Life RPG 🎮

**Система геймификации жизни, вдохновленная Solo Leveling**

Life RPG — это трекер привычек и целей, который превращает вашу повседневную жизнь в увлекательное RPG-приключение. Выполняйте ежедневные квесты, повышайте уровень персонажа и становитесь сильнее с каждым днем.

## ✨ Основные возможности

- **Система уровней**: Начните с 1-го уровня и поднимайтесь к вершине
- **Ежедневные квесты**: Создавайте привычки и отслеживайте их выполнение
- **Система опыта (XP)**: Получайте опыт за выполненные задачи
- **Статистика персонажа**: Здоровье (HP), Мана (MP), Сила (STR), Ловкость (AGI), Интеллект (INT)
- **Достижения**: Разблокируйте награды и бейджи за достижения
- **Рейтинговая система**: Конкурируйте с другими игроками в глобальном рейтинге
- **Темная тема**: Интерфейс в стиле Solo Leveling

## 🚀 Начало работы

### Требования
- Node.js 16+
- npm или yarn
- База данных (MongoDB/PostgreSQL)

### Установка

```bash
# Клонируйте репозиторий
git clone https://github.com/trawwa/life-rpg.git
cd life-rpg

# Установите зависимости
npm install

# Скопируйте файл конфигурации
cp .env.example .env

# Запустите приложение
npm start
```

## 📋 Структура проекта

```
life-rpg/
├── src/
│   ├── components/      # React компоненты
│   ├── pages/          # Страницы приложения
│   ├── services/       # API сервисы
│   ├── hooks/          # React hooks
│   ├── store/          # State management (Redux/Zustand)
│   └── utils/          # Вспомогательные функции
├── public/             # Статические файлы
├── docs/               # Документация
└── tests/              # Тесты
```

## 🎮 Как это работает

### Персонаж
Каждый пользователь имеет персонажа со следующими характеристиками:
- **Уровень (Level)**: Повышается при достижении определенного XP
- **Опыт (EXP)**: Накапливается за выполненные квесты
- **Здоровье (HP)**: Восстанавливается при выполнении здоровых привычек
- **Мана (MP)**: Восстанавливается при отдыхе и медитации

### Квесты
- **Ежедневные квесты**: Простые задачи на день (примеры: упражнения, чтение, медитация)
- **Еженедельные челленджи**: Более сложные задачи на неделю
- **Эпические квесты**: Долгосрочные цели и проекты

### Награды
При выполнении квестов вы получаете:
- Опыт (XP)
- Золото (в-игре валюта)
- Предметы и экипировку
- Достижения и бейджи

## 🤝 Вклад

Мы приветствуем вклад в развитие проекта! Пожалуйста:

1. Создайте fork репозитория
2. Создайте ветку для вашей функции (`git checkout -b feature/AmazingFeature`)
3. Commit ваши изменения (`git commit -m 'Add some AmazingFeature'`)
4. Push в ветку (`git push origin feature/AmazingFeature`)
5. Откройте Pull Request

## 📝 Лицензия

Этот проект лицензирован под MIT License - см. файл [LICENSE](LICENSE) для деталей.

## 📧 Контакты

- **Автор**: trawwa
- **GitHub**: [@trawwa](https://github.com/trawwa)
- **Вопросы?**: Откройте issue на GitHub

---

*"Никогда не сдавайся. Каждый день — новый шанс стать сильнее."* 💪
```

## README_EN.md (Английский)

```markdown
# Life RPG 🎮

**A Life Gamification System Inspired by Solo Leveling**

Life RPG is a habit tracker and goal management app that transforms your everyday life into an exciting RPG adventure. Complete daily quests, level up your character, and become stronger every day.

## ✨ Features

- **Leveling System**: Start at level 1 and climb to the top
- **Daily Quests**: Create habits and track their completion
- **Experience Points (XP)**: Earn XP for completed tasks
- **Character Stats**: Health (HP), Mana (MP), Strength (STR), Agility (AGI), Intelligence (INT)
- **Achievements**: Unlock rewards and badges for accomplishments
- **Ranking System**: Compete with other players in the global leaderboard
- **Dark Theme**: Solo Leveling-inspired interface

## 🚀 Getting Started

### Requirements
- Node.js 16+
- npm or yarn
- Database (MongoDB/PostgreSQL)

### Installation

```bash
# Clone the repository
git clone https://github.com/trawwa/life-rpg.git
cd life-rpg

# Install dependencies
npm install

# Copy configuration file
cp .env.example .env

# Start the application
npm start
```

## 📋 Project Structure

```
life-rpg/
├── src/
│   ├── components/      # React components
│   ├── pages/          # Application pages
│   ├── services/       # API services
│   ├── hooks/          # React hooks
│   ├── store/          # State management (Redux/Zustand)
│   └── utils/          # Utility functions
├── public/             # Static files
├── docs/               # Documentation
└── tests/              # Tests
```

## 🎮 How It Works

### Character
Each user has a character with the following stats:
- **Level**: Increases when reaching certain XP thresholds
- **Experience (EXP)**: Accumulated by completing quests
- **Health (HP)**: Recovered by completing healthy habits
- **Mana (MP)**: Recovered through rest and meditation

### Quests
- **Daily Quests**: Simple daily tasks (e.g., exercise, reading, meditation)
- **Weekly Challenges**: More complex weekly tasks
- **Epic Quests**: Long-term goals and projects

### Rewards
Upon completing quests, you earn:
- Experience Points (XP)
- Gold (in-game currency)
- Items and equipment
- Achievements and badges

## 🤝 Contributing

We welcome contributions to the project! Please:

1. Fork the repository
2. Create a branch for your feature (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📧 Contact

- **Author**: trawwa
- **GitHub**: [@trawwa](https://github.com/trawwa)
- **Questions?**: Open an issue on GitHub

---

*"Never give up. Every day is a new chance to become stronger."* 💪
```
