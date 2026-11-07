# Urban Chaos — русская локализация

Полный русский перевод и озвучка Urban Chaos (1999) для [OpenChaos](https://github.com/UltimaBeaR/OpenChaos), открытого порта игры на современные системы.

- Переведены все тексты: меню, брифинги, сообщения миссий, реплики прохожих.
- Озвучено больше 1500 реплик: сюжетные персонажи, диспетчер, банды и второстепенные роли. У каждого персонажа свой голос.
- Своя звуковая дорожка для сюжетного ролика.
- Свои кириллические шрифты в стиле оригинала.

Мод ничего не заменяет в файлах игры. Его можно в любой момент выключить в меню.

## Что нужно

1. **Своя копия Urban Chaos** (GOG, Steam или диск). Мод не содержит игровых данных.
2. **OpenChaos с поддержкой локализаций.** Это наш форк, последний релиз: https://github.com/GamesDevProjects/OpenChaos/releases/latest

## Установка

Мод кладётся в папку `localizations` рядом с `OpenChaos.exe`. Подойдёт и папка пользователя `%APPDATA%\OpenChaos\localizations`.

**Архивом.** Скачайте `UrbanChaos-Russian-<версия>.zip` из [релизов](https://github.com/GamesDevProjects/UrbanChaos-Russian/releases/latest) и распакуйте в `localizations`. Должно получиться `localizations\russian\mod.json`.

**Через git.** Удобно для обновлений:

```
cd <папка игры>\localizations
git clone https://github.com/GamesDevProjects/UrbanChaos-Russian.git russian
```

Обновление — `git pull` в папке `russian`.

Дальше в игре: **Options → Options → Language → RUSSIAN**, нажмите Okay и перезапустите игру.

Текст меняется только после рестарта миссии: загрузка из сохранения покажет старый текст.

## Версия 18+

Есть вторая версия перевода, «НеДетсад»: без цензуры, с матом в речи бандитов. Она не выкладывается в свободный доступ. Её можно получить на Бусти: https://boosty.to/gamesdev

## Об авторах

Перевод и озвучка сделаны с нуля, без использования старых пиратских переводов. Голоса созданы в ElevenLabs. Звук оригинала мод не содержит.

Сделано проектом GamesDev вместе с [AIDE](https://get-aide.org). Поддержать работу: https://boosty.to/gamesdev

Шрифты построены на Finlandica Headline и Fira Sans Extra Condensed. Оба распространяются по SIL Open Font License, тексты лицензий лежат в `LICENSE-fonts/`.

---

*English:* a complete Russian translation and voice-over of Urban Chaos for OpenChaos. You need your own copy of the game and an OpenChaos build with localization support (https://github.com/GamesDevProjects/OpenChaos/releases/latest). Clone or unpack this repository into `localizations/russian`, then choose RUSSIAN under Options → Options → Language and restart.
