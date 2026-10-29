<div align="center">

<img src="assets/banner.svg" alt="VK Video Morphe" width="100%">

<p>
  <img src="https://img.shields.io/github/v/release/PerfLite/morphe-patches-vk-video?style=flat-square" alt="релиз">
  <img src="https://img.shields.io/github/license/PerfLite/morphe-patches-vk-video?style=flat-square" alt="лицензия">
  <img src="https://img.shields.io/github/languages/top/PerfLite/morphe-patches-vk-video?style=flat-square" alt="язык">
  <img src="https://img.shields.io/github/stars/PerfLite/morphe-patches-vk-video?style=flat-square" alt="звёзды">
  <img src="https://img.shields.io/github/downloads/PerfLite/morphe-patches-vk-video/total?style=flat-square" alt="скачивания">
</p>

<p>
  <a href="https://github.com/PerfLite/morphe-patches-vk-video/releases/latest"><b>⬇️ Скачать</b></a> ·
  <a href="https://github.com/PerfLite/morphe-patches-vk-video/releases">📦 Все релизы</a>
</p>

</div>

## ⬇️ Скачать

| Файл | Описание | Ссылка |
|---|---|---|
| `vk-video-morphe-cloned.apk` | Клонированная сборка без рекламы и с 1080p | [Скачать](https://github.com/PerfLite/morphe-patches-vk-video/releases/latest/download/vk-video-morphe-cloned.apk) |

> Старые версии и список изменений: [Релизы](https://github.com/PerfLite/morphe-patches-vk-video/releases)

---

## Описание

Набор патчей Morphe для официального Android-клиента «VK Видео» (`com.vk.vkvideo`).

### Возможности

- **Блокировка видео-рекламы**: Полное удаление прероллов, мидроллов, построллов и рекламных плашек в плеере.
- **Фиксированное качество**: Разрешение выбирается при патчинге (Авто, 1080p, 720p, 480p, 360p) вместо автоматического сброса в мыло. Качество, выбранное вручную в плеере, сохраняется.
- **Обход защит и проверок подписи**: Отключение проверки оригинальной подписи, нативных проверок целостности в `libvkcore.so` и `libvkmedia.so`, детектов root/отладки и ограничений окружения.
- **Отключение телеметрии**: Полная блокировка MyTracker и трекеров аналитики.
- **Обход детекта VPN**: Снятие ограничений на воспроизведение при подключении через VPN/прокси.
- **Клонирование приложения**: Пакет переименован в `com.vk.vkvideo.morphe` для параллельной установки рядом с оригинальным VK Видео.
- **Свои цвета иконки**: Перекраска фона и знака адаптивной иконки лаунчера, чтобы клон отличался от оригинала.

### Установка

Скачайте готовый APK-файл из раздела [Релизы](https://github.com/PerfLite/morphe-patches-vk-video/releases/latest) и установите на устройство.

```
https://github.com/PerfLite/morphe-patches-vk-video
```

### Сборка

```bash
# Сборка патчей и расширения
./gradlew build

# Патчинг VK Видео и создание подписанного APK
./gradlew :patches:patchVkVideo
```

### Лицензия

GNU General Public License v3.0 — см. [LICENSE](LICENSE).
