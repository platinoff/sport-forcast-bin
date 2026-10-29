# sport-forcast

<p align="center">
  <img src="portable.svg" alt="Журнал прогнозів: прогноз за таблицею, коефіцієнт лише з локального запису, без вихідного коду." width="880">
</p>

Журнал футбольних прогнозів. Один файл, без встановлення і без облікового запису. Завантаження не містить вихідного коду: ліцензія пропрієтарна.

## Що видно на сторінці

П’ять країн: Україна, Польща, Англія, Канада, Німеччина. Мови сторінки: українська, польська, англійська.

**Прогноз** — сторона, у якої більше очок за зіграний матч у записаній таблиці тієї ліги. Список іде від найширшого розриву. Це не букмекерський коефіцієнт і не обіцянка результату.

**Коефіцієнт** — окрема колонка. Ціна з’являється лише тоді, коли поруч із програмою лежить локальний запис `odds.txt`: у ньому названо джерело `local`, примітку про дозволений показ і дату перевірки. Програма не відкриває сайт контори і не вигадує ціну. Немає такого запису — у колонці тире.

Контори на сторінці є лише там, де є друкований легальний список цієї країни. Для України, Англії та Канади посилання на контору немає.

## Як відкрити

Завантажте файл і запустіть його. Журнал слухає `http://127.0.0.1:9741`. Українська сторінка: `http://127.0.0.1:9741/?lang=uk`.

## Файли

| Файл | Для кого |
|------|----------|
| [sport-forcast.exe](https://github.com/platinoff/sport-forcast-bin/releases/download/v0.2.1/sport-forcast.exe) | Windows |
| [sport-forcast](https://github.com/platinoff/sport-forcast-bin/releases/download/v0.2.1/sport-forcast) | Linux x86_64, один файл без динамічних бібліотек |

Android apk у цьому випуску немає. Порожнього пакета тут не лежить.

## English

A proprietary football journal. One file, no installer, no account, and no source in the download.

The forecast is the side with more points per match on that league’s recorded table. It is not a betting price. The odds column shows a figure only from a local `odds.txt` beside the program, with source `local`, a terms note, and a check date. The program does not fetch a bookmaker and does not invent a price. Without that file the column is a dash.

Run the file and open `http://127.0.0.1:9741`.
