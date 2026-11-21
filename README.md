# Hex Fall

3D-игра Hex Fall, упакованная в Android APK через Capacitor + GitHub Actions.

## Как получить APK
1. Залей все файлы в репозиторий (ветка main).
2. Если папки `.github` нет — создай файл `.github/workflows/build-apk.yml` через GitHub
   (Add file → Create new file, в имени файла напиши `.github/workflows/build-apk.yml`)
   и вставь туда содержимое `build-apk.yml` из корня проекта.
3. Открой вкладку **Actions** → **Build Android APK** → дождись зелёной галочки (5–8 минут).
4. Внутри запуска внизу в разделе **Artifacts** скачай **HexFall-APK** → внутри `app-debug.apk`.
5. Установи APK на телефон (разреши установку из неизвестных источников).

Игра лежит в `www/index.html`. После правки игры просто делай commit — APK соберётся заново.
