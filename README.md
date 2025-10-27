# Моя UI Библиотека

![Version](https://img.shields.io/npm/v/biblioteka-kolenka)
![License](https://img.shields.io/npm/l/biblioteka-kolenka)

Современная библиотека React компонентов с красивыми стилями.

## Установка

```bash
npm install biblioteka-kolenka

## Использование
import React from 'react';
import { Button } from 'biblioteka-kolenka';

function App() {
  return 
    <div>
      <Button onClick={() => alert('Привет!')}>
        Нажми меня
      </Button>
    </div>
  ;

  ## Компоненты
  -Button
  -input
  -modal

  ## Разработка
  # Установка зависимостей
npm install

# Запуск в режиме разработки
npm run dev

# Сборка проекта
npm run build