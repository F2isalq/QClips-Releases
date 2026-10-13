<p align="center"><img src="assets/logo.png" alt="QClips" width="96"></p>
<h1 align="center">QClips</h1>
<p align="center"><b>Play first. Clip it after.</b><br>Free game clipping for Windows.</p>
<p align="center">
  <a href="https://github.com/F2isalq/QClips-Releases/releases/latest/download/QClips-Setup.exe"><b>Download QClips for Windows</b></a>
  &nbsp;·&nbsp; <a href="https://f2isalq.github.io/">Website</a>
</p>
<p align="center"><img src="assets/library.webp" alt="The QClips clip library" width="100%"></p>

QClips is a light Windows app that keeps an instant replay of your game, saves a clip with a hotkey
or a voice command, and lets you trim, edit and share it in seconds. Everything runs on your PC.

[العربية](#بالعربي)

## Download

Get the newest version from the [latest release](https://github.com/F2isalq/QClips-Releases/releases/latest):

- **[QClips-Setup.exe](https://github.com/F2isalq/QClips-Releases/releases/latest/download/QClips-Setup.exe)**
  (about 5 MB): the small installer. It downloads the rest while it installs.
- **[QClips-Setup-Offline.exe](https://github.com/F2isalq/QClips-Releases/releases/latest/download/QClips-Setup-Offline.exe)**
  (about 88 MB): everything inside, for a PC without a good connection.

QClips installs for your user only, with no administrator rights, and keeps itself up to date. Its updates download
only what changed.

### Windows SmartScreen

The installers are not code-signed yet, so Windows may show "Windows protected your PC" the first time. Click
**More info → Run anyway**. Download QClips only from this page.

## Screenshots

<p align="center"><img src="assets/editor.webp" alt="The QClips editor in Simple mode" width="100%"></p>
<p align="center"><img src="assets/altz.webp" alt="The Alt+Z panel over a game" width="100%"></p>

Game names and gameplay footage belong to their owners; QClips isn't affiliated with or endorsed by them.

## Features

- **Instant replay:** the last minutes are always kept; save them with a hotkey, from the tray or the Alt+Z panel.
  Several save hotkeys, each with its own length, on keys or a mouse side button.
- **Voice commands in Arabic and English:** say a phrase ("clip it", "clip that" or your own) and QClips saves the
  length you chose for it. Recognition runs offline on your PC.
- **Sound in sync:** sound and picture line up in every player, including Windows' own player and Discord.
- **Separate audio tracks:** game, voice chat, microphone and any device on its own track, plus a Mixed track; a
  program's sound (Discord, Spotify, the current game) on its own track.
- **Editor, Simple and Advanced:** trim, split, speed, freeze frame, titles, effects, filters and transitions; tracks,
  keyframes and masks in Advanced. Export presets for Discord's 10, 25 and 50 MB limits, 1080p60 and the original
  quality.
- **Alt+Z panel** over your game: recent clips, a quick trim, and the main settings.
- **Storage page:** see your drive, move clips to another drive, name files your way, and an optional limit that
  sends the oldest clips to the Recycle Bin (favourites are kept).
- **Recording**, a performance overlay (FPS, GPU, CPU), "clip saved" notifications, and every monitor if you want.
- Uses your graphics card's encoder: NVIDIA NVENC, AMD AMF or Intel Quick Sync, with H.264, HEVC or AV1.

## Requirements

- Windows 10 version 2004 (build 19041) or later, or Windows 11, 64-bit (x64).
- A graphics card with a video encoder is recommended (NVIDIA NVENC, AMD AMF or Intel Quick Sync). Without one,
  QClips records with the processor (x264), which costs more CPU.
- About 250 MB for the app, plus room for your clips and the replay cache.
- Voice commands: a one-time model download from Settings → Voice commands (about 67 MB for English, about 164 MB
  for Arabic, about 210 MB for both).

## Privacy

- **Everything stays on your PC.** No account, no cloud, no upload, no ads.
- **No telemetry.** QClips sends no usage data, no analytics and no crash reports. It only goes online to check for
  and download updates from this page, and to download the voice models when you ask for them.
- **Voice runs offline.** What the microphone hears is recognized on your PC and never leaves it; only a matched
  phrase is written to QClips' own log.
- A diagnostic report is made only when you click Copy diagnostic report, and goes only where you paste it.

## Anti-cheat safety

QClips records the screen the way Windows' own tools do (Desktop Duplication) and the sound through Windows' audio
system. It does **not** hook into games, inject anything, read or open game processes, install keyboard or mouse
hooks, or need administrator rights. Per-app audio also works without opening the game's process.

## Licenses and credits

QClips is free to use. It is built with these projects (the full list and license texts are in
THIRD-PARTY-NOTICES.txt in the install folder):

- **FFmpeg**: QClips runs FFmpeg as a separate program. The bundled build includes x264 and is licensed under the GNU
  GPL version 2 or later; the license, the exact source archive and the build settings are in the ffmpeg folder of
  the install and in THIRD-PARTY-NOTICES.txt.
- **Moonshine** speech models: English (MIT License) and Arabic, used under the Moonshine AI Community
  License. **Powered by Moonshine AI.**
- **Silero VAD** (MIT License): finds speech in the microphone sound.
- **sherpa-onnx** (Apache License 2.0) and **ONNX Runtime** (MIT License): run the voice models.
- **Velopack** (MIT License): installs and updates.
- NAudio, Serilog, SQLite, Markdig, the Windows App SDK, Win2D and the .NET runtime.

---

## بالعربي

**QClips** برنامج خفيف لويندوز يحتفظ بآخر دقائق من لعبك، ويحفظ المقطع بزر أو بأمر صوتي، وتقدر
تقصّه وتعدّله وتشاركه بثواني. كل شيء يشتغل على جهازك.

### التنزيل

من [آخر إصدار](https://github.com/F2isalq/QClips-Releases/releases/latest):

- **QClips-Setup.exe** (حوالي 5 ميقا): المثبّت الصغير، يحمّل الباقي وهو يثبّت.
- **QClips-Setup-Offline.exe** (حوالي 88 ميقا): كل شيء بداخله، لجهاز اتصاله ضعيف.

يتثبّت لحسابك بدون صلاحيات مدير، وQClips يحدّث نفسه بعدها، والتحديث يحمّل اللي تغيّر بس.

**تنبيه SmartScreen:** المثبّت غير موقّع للحين، فممكن يطلع لك "Windows protected your PC". اضغط
**More info ← Run anyway**.

### المزايا

- إعادة فورية: آخر الدقائق محفوظة دايماً، احفظها بزر أو من الـ tray أو لوحة Alt+Z، وأكثر من زر حفظ كل واحد بطوله.
- أوامر صوتية بالعربي والإنجليزي: قل الجملة وQClips يحفظ الطول اللي اخترته لها، والتعرّف على جهازك بدون نت.
- الصوت متزامن مع الصورة في كل مشغّل، حتى مشغّل ويندوز وديسكورد.
- تراكات صوت منفصلة: اللعبة والمايك وكل جهاز بتراك، وصوت أي برنامج (ديسكورد، سبوتيفاي، اللعبة الحالية) بتراك لحاله.
- محرر بوضعين Simple وAdvanced، وإعدادات تصدير جاهزة لحدود ديسكورد 10 و25 و50 ميقا.
- لوحة Alt+Z فوق اللعبة، وصفحة التخزين (نقل المقاطع، تسمية الملفات، وحد اختياري يرسل الأقدم لسلة المحذوفات والمفضلة محمية).
- يستخدم معالج الرسوميات للترميز: NVIDIA NVENC أو AMD AMF أو Intel Quick Sync.

### المتطلبات

- ويندوز 10 إصدار 2004 أو أحدث، أو ويندوز 11، 64-بت.
- يُفضّل كرت شاشة فيه مرمّز فيديو (NVENC أو AMF أو Quick Sync)، وبدونه يسجّل بالمعالج (x264).
- الأوامر الصوتية تحتاج تحميل النموذج مرة وحدة من الإعدادات: حوالي 67 ميقا للإنجليزي، و164 للعربي، و210 للاثنين.

### الخصوصية

- كل شيء يبقى على جهازك: لا حساب ولا سحابة ولا رفع.
- لا يرسل أي بيانات استخدام ولا تحليلات. يتصل بالنت بس عشان التحديثات من هذي الصفحة، وتحميل نماذج الصوت إذا طلبتها.
- الصوت يتعرّف عليه على جهازك وما يطلع منه، وما ينكتب بالسجل إلا الجملة اللي تطابقت.

### الأمان مع أنظمة مكافحة الغش

QClips يسجّل الشاشة بطريقة ويندوز نفسها، وما يحقن شيء في الألعاب، ولا يفتح عملياتها، ولا يركّب hooks للكيبورد أو
الماوس، ولا يحتاج صلاحيات مدير.

### التراخيص

FFmpeg (رخصة GPL، التفاصيل في THIRD-PARTY-NOTICES.txt)، ونماذج Moonshine (العربي بموجب Moonshine AI Community
License، **Powered by Moonshine AI**)، وSilero VAD، وsherpa-onnx، وONNX Runtime، وVelopack، وغيرها في
THIRD-PARTY-NOTICES.txt.
