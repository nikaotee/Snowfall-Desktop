/////// EN ////////

# ❄ Snowfall

Snow on your desktop for macOS and Windows. Snowflakes fall over windows and accumulate in drifts on their top edges, the Dock, and the taskbar. Little snowplows with fairy lights drive through the drifts, penguins wander around, snowmen build themselves, and occasionally Santa flies across the screen.

## Built With

Snowfall is written in **Rust** 🦀. It renders on the GPU (wgpu: Metal on Mac,
DirectX 12 on Windows) and uses winit for windows. That's why it's tiny (about 2 MB),
needs no installation, and has no heavy dependencies.

## Download

Check out the **[Releases](../../releases/latest)** section:

- **Mac** (Apple Silicon: M1 and newer)  `Snowfall.dmg`
- **Windows 10/11** — `Snowfall.exe`

No installation required: just open it, and let it snow.

### Verify Your Download

SHA-256 checksums for version 0.1.0:

| File | SHA-256 |
|---|---|
| `Snowfall.dmg` | `54e61479b59d26c06a1aa28ae561ffd0be0003510e88cf8643229e4f2a66c942` |
| `Snowfall.exe` | `852d0169c893f90d9f973434bd0854db4258603bd5940b02a68eac44db179b7c` |

How to check the file you downloaded:
- **Mac** (Terminal): `shasum -a 256 ~/Downloads/Snowfall.dmg`
- **Windows** (PowerShell): `Get-FileHash $HOME\Downloads\Snowfall.exe`

The result must match the table. If it doesn't, don't run the file.

## First Launch

**Mac.** Open `Snowfall.dmg` and drag Snowfall to your Applications folder (or run it directly from the disk image window). Since the app is not signed with an Apple developer certificate, macOS will block it on the first launch. Go to **System Settings** → **Privacy & Security**, scroll down, and click **Open Anyway**. You only need to do this once.

**Windows.** If you see a "Windows protected your PC" pop-up, click **More info** → **Run anyway**.

## How to Use

The app has no main window; all controls are available via the ❄ icon in the menu bar (Mac) or system tray (Windows):

- **Pause:** `⌃⌥S` on Mac, `Ctrl+Alt+S` on Windows.
- **Weather:** Snowfall intensity, wind, and blizzard settings.
- **Fairy Lights:** Click the fairy lights icon next to the snowflake to change colors; click and drag it to the top edge of a window to hang lights. On Windows, hover over the fairy lights, hold both the left and right mouse buttons, and drag them to the desired window.
- **Visitors:** Snowplows, snowmen, penguins, and Santa.
- **Folder Themes:** Winter icons for selected folders (revert to default at any time). Works somewhat unstably on Windows.
- **Exit:** Available right from the menu.

Quickly swipe your cursor across a snowdrift to brush the snow away.

## Privacy

Snowfall does not use the network and never sends any data anywhere. To know where the snow should land, it only reads the position and dimensions of windows—never their contents.
## Support the Project

Snowfall is free. If it made your winter a little cozier and you'd like to say thanks,
you can buy the author a cup of hot cocoa ☕

**[❤ Support Snowfall] with your stars!**

## Non-Commercial Project

- Snowfall is a **non-commercial** project made just for fun and for the holiday mood.
  The author is not trying to make money from it.
- The source code is not public yet, but the app **contains no malware, ads, or trackers**
  and does not connect to the internet.
- The app is provided **"as is"**, without any warranty. The author is not liable for any
  bugs, vulnerabilities, or consequences of using it. Use it at your own discretion.

/////// RU ////////

# ❄ Snowfall

Снег на рабочем столе для macOS и Windows. Снежинки падают поверх окон и ложатся
сугробами на их верхние края, на Dock и на панель задач. По сугробам ездят маленькие
снегоуборщики с гирляндами, гуляют пингвины, сами лепятся снеговики, а иногда
над экраном пролетает Санта.

## Технологии

Snowfall написан на **Rust** 🦀. Отрисовка — через видеокарту (wgpu: Metal на Mac,
DirectX 12 на Windows), окна — через winit. Поэтому программа маленькая (около 2 МБ),
работает без установки и не тянет за собой тяжёлых зависимостей.

## Скачать

Загляните в раздел **[Releases](../../releases/latest)**:

- **Mac** (Apple Silicon: M1 и новее)  `Snowfall.dmg`
- **Windows 10/11**  `Snowfall.exe`

Ничего устанавливать не нужно: открыли  снег пошёл.

### Проверка файла

Контрольные суммы (SHA-256) версии 0.1.0:

| Файл | SHA-256 |
|---|---|
| `Snowfall.dmg` | `54e61479b59d26c06a1aa28ae561ffd0be0003510e88cf8643229e4f2a66c942` |
| `Snowfall.exe` | `852d0169c893f90d9f973434bd0854db4258603bd5940b02a68eac44db179b7c` |

Как проверить скачанный файл:
- **Mac** (Терминал): `shasum -a 256 ~/Downloads/Snowfall.dmg`
- **Windows** (PowerShell): `Get-FileHash $HOME\Downloads\Snowfall.exe`

Результат должен совпасть с таблицей. Если не совпадает — не запускайте файл.

## Первый запуск

**Mac.** Откройте `Snowfall.dmg` и перетащите Snowfall в «Программы» (можно
запустить и прямо из окна). Приложение не подписано сертификатом Apple, поэтому
при первом запуске macOS его не откроет. Зайдите в «Системные настройки» →
«Конфиденциальность и безопасность» и внизу нажмите «Всё равно открыть». Это нужно
сделать один раз.

**Windows.** Если появится «Система Windows защитила ваш компьютер», нажмите
«Подробнее» → «Выполнить в любом случае».

## Как пользоваться

Окна у программы нет, всё управление через значок ❄ в строке меню (Mac) или в
трее (Windows):

- **Пауза**  `⌃⌥S` на Mac, `Ctrl+Alt+S` на Windows.
- **Погода**: сила снегопада, ветер, метель.
- **Гирлянды**: щёлкните по значку гирлянды рядом со снежинкой, чтобы сменить
  цвета; зажмите и перетащите его на верхний край окна, чтобы повесить гирлянду. На Windows наведите курсор на гирлянду зажмите ЛКМ и ПКМ и перетащиет на нужное окно.
- **Гости**: снегоуборщики, снеговики, пингвины, Санта.
- **Темы папок**: зимние иконки для выбранных папок, вернуть обычные можно в
  любой момент. На Windows работает немного нестабильно.
- **Выйти**  там же, в меню.

Быстро проведите курсором по сугробу, чтобы смахнуть снег.

## Конфиденциальность

Snowfall не использует сеть и ничего никуда не отправляет. Чтобы знать, куда
ложится снег, он читает только расположение и размеры окон, но не их содержимое.

## Поддержать проект

Snowfall бесплатный. Если он сделал вашу зиму чуточку уютнее и хочется сказать
спасибо, можно угостить автора чашкой горячего какао ☕

**[❤ Поддержать Snowfall] и студента из Узбекистана своими звездами!**

## Некоммерческий проект

- Snowfall  **некоммерческий** проект, сделанный для души и новогоднего
  настроения. Автор не преследует цели заработать на нём.
- Исходный код пока не опубликован, но программа **не содержит вредоносного ПО,
  рекламы и трекеров** и не подключается к интернету.
- Программа распространяется **«как есть»**, без каких-либо гарантий. Автор не
  несёт ответственности за ошибки, уязвимости и последствия её использования.
  Используйте её на своё усмотрение.
