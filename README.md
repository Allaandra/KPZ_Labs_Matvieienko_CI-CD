# KPZ_Labs_Matvieienko_CI-CD

## ℹ️ Опис проєкту

[Hello GitHub Actions](https://github.com/Allaandra/skills-hello-github-actions/tree/main?tab=readme-ov-file#hello-github-actions-)  
[Publish Packages](https://github.com/Allaandra/skills-publish-packages?tab=readme-ov-file#finish)

## 👩‍💻 Автор

- Виконала: Матвєєнко Олександра  
- Група: ІПЗ-3.03  
- Дисципліна: "Конструювання програмного забезпечення" (КПЗ)

## 📦 Стек технологій
- **Vite + React**
- **Docker**
- **Nginx**
- **GitHub Actions**
- **GitHub Container Registry (GHCR)**

## Структура проекту
```
.
├─ src/
├─ Dockerfile
└─ .github/workflows/docker-build.yml
```

## Запуск контейнера
```
npm install
docker pull ghcr.io/allaandra/kpz_labs_matvieienko_ci-cd:latest
docker run -p 4173:4173 ghcr.io/allaandra/kpz_labs_matvieienko_ci-cd:latest npm run preview -- --host
```

## Скриншоти
Успішний запуск
<img src="images/success_build_push.png">
GHCR пакет
<img src="images/package.png">
Докер контейнер
<img src="images/docker.png">
Сторінка
<img src="images/page.png">

## Висновок
У ході виконання практичної роботи я закріпила навички роботи з технологією контейнеризації Docker. Я навчилася створювати коректний Dockerfile з необхідними директивами для збірки образу Python-застосунку. Також я опанувала інструмент Docker Compose для опису та запуску багатосервісної архітектури. В результаті мною було успішно розгорнуто вебзастосунок на Flask у зв’язці з базою даних Redis, що забезпечило коректну роботу лічильника відвідувань у ізольованому середовищі.
