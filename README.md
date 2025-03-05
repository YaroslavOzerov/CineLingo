# CineLingo 🎥📖 **|** Изучайте английский через кино с ИИ-контекстом!  
**Open-source платформа для погружения в язык через фильмы: разбор слов, идиом и скрытых смыслов в субтитрах.**

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://github.com/yourusername/CineLingo/pulls)
[![Open in Gitpod](https://img.shields.io/badge/Open%20in-Gitpod-908a85?logo=gitpod)](https://gitpod.io/#https://github.com/yourusername/CineLingo)

![CineLingo Demo](https://via.placeholder.com/1280x600.png?text=Demo+Screen+Recording+Here)  
*(Скоро добавим скриншоты/гифки!)*

## ✨ Особенности
- 🎬 **Интеллектуальный разбор субтитров**  
  Автоматическая сегментация по сценам + выделение сложных слов.
- 📚 **Объяснения от словаря до поп-культуры**  
  GPT-4 + локальные модели (Mixtral) для контекстных примеров.  
- 🔍 **Кликабельные субтитры**  
  Мгновенные определения, синонимы и произношение (Forvo API).
- 📊 **Персональная статистика**  
  Трекер прогресса: какие слова выучили, сколько идиом поняли.
- 🌍 **Сообщество переводчиков**  
  Краудсорсинговая база объяснений с рейтингами.

## 🛠 Технологии
```bash
# Фронтенд
├─ React + TypeScript
├─ Tauri (для десктопа)
└─ shadcn/ui

# Бэкенд
├─ Go (Fiber)
├─ Python (FastAPI для NLP)
└─ PostgreSQL

# NLP-стек
├─ spaCy
├─ Hugging Face Transformers
└─ Ollama (для локальных LLM)
