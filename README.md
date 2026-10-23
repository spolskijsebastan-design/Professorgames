# Хвиля (APK)

## Збірка APK безкоштовно (GitHub Actions)
1. Створіть на github.com новий репозиторій і завантажте туди всі файли цієї папки (включно з прихованою `.github`).
2. Щоб працював Jamendo: безкоштовний ключ на https://devportal.jamendo.com, потім у репозиторії
   Settings → Secrets and variables → Actions → New repository secret, імʼя `JAMENDO_KEY`.
   Без ключа працює тільки Audius.
3. Вкладка Actions → Build APK → Run workflow. Через кілька хвилин у запуску зʼявиться файл `hvylia-apk`.
4. Розпакуйте, скопіюйте `app-debug.apk` на телефон і встановіть (дозвольте встановлення з невідомих джерел).

## Перевірка в браузері
`cd www && python3 -m http.server 8000`, відкрийте http://localhost:8000
