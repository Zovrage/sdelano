# Сделано — Android (APK)

Приложение уже настроено на ваш сервер https://main.hidebrovpn.ru (адрес подставляется в окне входа сам, в поле key оставьте local).

## Сборка APK через GitHub
1. Создайте на github.com пустой репозиторий (например sdelano), без README.
2. В папке sdelano-android выполните (USER — ваш логин GitHub):
   git init
   git add .
   git commit -m "init"
   git branch -M main
   git remote add origin https://github.com/USER/sdelano.git
   git push -u origin main
3. Вкладка Actions -> запуск "Build APK" стартует сам (5-10 минут). Если нет: Run workflow.
4. Откройте завершённый запуск -> внизу Artifacts -> sdelano-apk -> скачайте и распакуйте app-debug.apk.
5. Перенесите на телефон, разрешите установку из неизвестных источников, установите.
   Если Play Protect предупредит — "Всё равно установить".

## Вход
Значок ⇄ -> почта и пароль, которые вы создали на сервере -> Войти.
