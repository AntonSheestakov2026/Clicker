КЛИКЕР: МИРЫ — Android-проект

Важно: это исходный Android Studio проект, не собранный APK.

Как получить APK:
1. Установи Android Studio на компьютер.
2. Открой папку ClickerAndroidProject через Open.
3. Дождись Gradle Sync.
4. Выбери Build → Build Bundle(s) / APK(s) → Build APK(s).
5. APK обычно появится в app/build/outputs/apk/debug/app-debug.apk.

В игре есть 4 мира, магазин, улучшение силы клика, автокликер, виртуальная криптобиржа,
скин «Райская монета» и промокоды Anton и Klik. Прогресс хранится на устройстве.


СБОРКА APK ЧЕРЕЗ GITHUB ACTIONS С ТЕЛЕФОНА
1. Загрузите все файлы проекта в репозиторий GitHub в корень репозитория (чтобы app, build.gradle и settings.gradle были в корне).
2. Убедитесь, что файл .github/workflows/build-apk.yml тоже загружен.
3. Откройте вкладку Actions в репозитории.
4. Если появится запрос, разрешите запуск workflows.
5. Откройте запуск Build Android APK и дождитесь зелёной галочки.
6. Внизу страницы запуска в разделе Artifacts скачайте Clicker-Miry-APK.zip.
7. Распакуйте этот ZIP на телефоне — внутри будет app-debug.apk.
