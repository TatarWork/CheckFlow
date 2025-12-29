# 🔍 CheckFlow - Professional Due Diligence System

[![.NET 8](https://img.shields.io/badge/.NET-8-512BD4)](https://dotnet.microsoft.com/)
[![Vue 3](https://img.shields.io/badge/Vue-3-42b883)](https://vuejs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5-blue)](https://www.typescriptlang.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

**Enterprise-уровень система проверки контрагентов для юристов, бухгалтеров и финансовых отделов.**

> ⚡ **30 секунд** на проверку вместо 5 минут у конкурентов  
> 🎯 **Точность 99%** по данным ФНС, арбитражных судов, ФССП  
> 💰 **Экономит 15+ часов/месяц** на рутинных проверках

---

## 🚀 Быстрый старт

### Требования
- .NET 8 SDK
- Node.js 18+
- SQLite / PostgreSQL 14+
- Docker & Docker Compose (опционально)

### Установка за 5 минут

```bash
# 1. Клонируем репозиторий
git clone https://github.com/your-username/checkflow.git
cd checkflow

# 2. Запускаем инфраструктуру (Docker)
docker-compose up -d

# 3. Настраиваем бэкенд
cd src/CheckFlow.API
dotnet restore
dotnet run

# 4. Настраиваем фронтенд
cd ../CheckFlow.Web
npm install
npm run dev

# 5. Открываем в браузере
open http://localhost:5173
