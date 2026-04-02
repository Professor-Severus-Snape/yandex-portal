[![Vite CI/CD](https://github.com/professor-severus-snape/yandex-portal/actions/workflows/vite_ci-cd.yml/badge.svg)](https://github.com/professor-severus-snape/yandex-portal/actions/workflows/vite_ci-cd.yml)

# Yandex портал

Небольшое React-приложение, представляющее собой главную страницу контентного портала с модульной архитектурой и переиспользуемыми компонентами.

![Preview](./docs/yandex-portal.png)

## Демо

Посмотреть демо можно [здесь](https://professor-severus-snape.github.io/yandex-portal/).

## Возможности

- модульная архитектура интерфейса (декомпозиция на независимые компоненты)  
- переиспользуемые UI-блоки (новости, списки, статьи, карточки)  
- конфигурирование компонентов через `props`  
- работа с данными из JSON (новости, погода, курсы валют и др.)  
- композиция компонентов через `children`  
- простая масштабируемая структура проекта  

## Технологии

- React 18
  - JSX
  - functional components
  - props
  - children
  - композиция компонентов  
- типизация - TypeScript
- линтинг - ESLint 
- сборка - Vite 

## CI/CD

- GitHub Actions — линтинг и сборка проекта (CI)  
- GitHub Pages — автоматический деплой приложения (CD)  
