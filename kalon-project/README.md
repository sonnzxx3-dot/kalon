# Kalon

Дневник калорий с поиском продуктов, сканером штрих-кодов, своей базой продуктов и графиками прогресса.

**Synax Sword AI**

## Быстрый старт (сборка APK)

### Вариант 1 — локально
```bash
npm install
npx cap add android
npx cap sync
npx cap open android   # дальше Run или Build APK в Android Studio
```

### Вариант 2 — облако (GitHub Actions)
Залей этот репозиторий на GitHub → открой вкладку **Actions** → дождись сборки → скачай `app-debug.apk` из **Artifacts**.

Полное руководство (публикация в Google Play, монетизация, фото-AI, названия) — в файле **ЗАПУСК_И_МОНЕТИЗАЦИЯ.md**.

## Структура
```
www/                     веб-приложение (вся логика тут, index.html)
capacitor.config.json    конфигурация приложения (appId, имя)
package.json             зависимости Capacitor
.github/workflows/       автосборка APK в облаке
```

## App ID
`ai.synaxsword.kalon`
