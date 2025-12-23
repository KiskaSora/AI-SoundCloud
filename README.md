# 🎵 AI SoundCloud Music Extension for SillyTavern

Automatic music selection from SoundCloud based on conversation mood using keyword analysis.

Автоматический подбор музыки из SoundCloud по настроению диалога с использованием анализа ключевых слов.

![Version](https://img.shields.io/badge/version-1.0.0-blue)
![SillyTavern](https://img.shields.io/badge/SillyTavern-compatible-green)
![License](https://img.shields.io/badge/license-MIT-orange)

## ✨ Features / Особенности

- 🎭 **12 Mood Categories** - battle, epic, romantic, dark, calm, energetic, sad, mysterious, cozy, tense, hopeful, melancholic
- 🤖 **Automatic Analysis** - AI analyzes chat messages and selects appropriate music
- 🎨 **Beautiful Player Widget** - integrated music player with album art and controls
- 🌐 **Bilingual Support** - keyword detection in English and Russian
- ⚡ **Real-time Playback** - instant music switching based on conversation flow

---

- 🎭 **12 категорий настроений** - бой, эпика, романтика, тьма, спокойствие, энергия, грусть, мистика, уют, напряжение, надежда, меланхолия
- 🤖 **Автоматический анализ** - ИИ анализирует сообщения и подбирает музыку
- 🎨 **Красивый плеер** - встроенный музыкальный виджет с обложкой и управлением
- 🌐 **Двуязычная поддержка** - определение ключевых слов на английском и русском
- ⚡ **Воспроизведение в реальном времени** - мгновенная смена музыки по ходу диалога

## 📦 Installation / Установка

### Method 1: Auto-install (Recommended)

1. Open SillyTavern
2. Go to **Extensions** → **Download Extensions & Assets**
3. Paste this URL:
   ```
   https://github.com/KiskaSora/SillyTavern-AI-SoundCloud
   ```
4. Click **Download**

### Method 2: Manual Install

1. Download this repository as ZIP
2. Extract to:
   ```
   SillyTavern/public/scripts/extensions/third-party/AI-SoundCloud/
   ```
3. Refresh SillyTavern (F5)

---

### Метод 1: Автоустановка (Рекомендуется)

1. Откройте SillyTavern
2. Перейдите в **Расширения** → **Загрузить расширения и ассеты**
3. Вставьте URL:
   ```
   https://github.com/KiskaSora/SillyTavern-AI-SoundCloud
   ```
4. Нажмите **Загрузить**

### Метод 2: Ручная установка

1. Скачайте этот репозиторий как ZIP
2. Распакуйте в:
   ```
   SillyTavern/public/scripts/extensions/third-party/AI-SoundCloud/
   ```
3. Обновите SillyTavern (F5)

## 🎮 Usage / Использование

### 1. Setup Playlists / Настройка плейлистов

1. Open **Settings** → **Extensions** → **🎵 AI SoundCloud Music**
2. For each mood, add a SoundCloud playlist URL:
   ```
   https://soundcloud.com/user/sets/playlist-name
   ```
3. Click mood buttons to test playback

---

1. Откройте **Настройки** → **Расширения** → **🎵 AI SoundCloud Music**
2. Для каждого настроения добавьте URL плейлиста SoundCloud:
   ```
   https://soundcloud.com/user/sets/playlist-name
   ```
3. Нажмите кнопки настроений для проверки

### 2. Enable Auto-Analysis / Включите автоанализ

- ✅ **Enable extension** - turns the extension on/off
- ✅ **Auto-analyze chat** - automatically detects mood from messages

### 3. Chat and Enjoy! / Общайтесь!

Music will automatically change based on conversation mood!

Музыка будет автоматически меняться в зависимости от настроения диалога!

## 🎯 Mood Keywords / Ключевые слова

The extension detects mood using keywords:

| Mood | Keywords (EN) | Ключевые слова (RU) |
|------|---------------|---------------------|
| Battle | fight, battle, attack, sword | бой, битва, атака, меч |
| Romantic | love, kiss, heart, passion | любовь, поцелуй, сердце, страсть |
| Dark | dark, shadow, evil, fear | тьма, мрак, зло, страх |
| Sad | sad, tear, crying, lonely | грусть, слезы, плач, одиночество |
| Energetic | energy, fast, run, excitement | энергия, быстрый, бег, веселье |
| Calm | calm, quiet, peace, serene | спокойствие, тишина, мир |
| Epic | epic, grand, heroic, mighty | эпичный, величественный, героический |
| Mysterious | mystery, secret, strange, mystic | тайна, загадка, странный, мистика |
| Cozy | cozy, warm, comfort, peaceful | уют, тепло, комфорт, домашний |
| Tense | tension, anxiety, danger, threat | напряжение, тревога, опасность |
| Hopeful | hope, bright, joy, dream | надежда, светлый, радость, мечта |
| Melancholic | melancholy, pensive, nostalgia | меланхолия, задумчивость, ностальгия |

## 🎨 Features in Detail / Детали

### Player Widget

- 🖼️ Album artwork display
- ⏯️ Play/Pause control
- ⏭️ Skip track
- 🔀 Shuffle playlist
- 📊 Progress bar
- 🔊 Volume control (slider)

### Settings Panel

- 12 mood categories with URL inputs
- Quick test buttons for each mood
- Volume slider (0-100%)
- Toggle switches for enable/auto-analyze

## ⚙️ Requirements / Требования

- SillyTavern (latest version)
- SoundCloud account (free)
- SoundCloud playlists (public)

## 🐛 Troubleshooting / Решение проблем

**Music doesn't play?**
- Check if playlist URLs are correct and public
- Make sure extension is enabled
- Check browser console (F12) for errors

**No mood detection?**
- Ensure "Auto-analyze chat" is enabled
- Check if messages contain relevant keywords
- Try manual mood selection with buttons

---

**Музыка не играет?**
- Проверьте правильность и публичность URL плейлистов
- Убедитесь что расширение включено
- Проверьте консоль браузера (F12) на ошибки

**Настроение не определяется?**
- Убедитесь что "Автоанализ чата" включен
- Проверьте наличие ключевых слов в сообщениях
- Попробуйте ручной выбор настроения кнопками

## 📝 License / Лицензия

MIT License - free to use and modify

## 👤 Author / Автор

Created by **KiskaSora**

- GitHub: [@KiskaSora](https://github.com/KiskaSora)

## 🙏 Credits / Благодарности

- SillyTavern team for the amazing platform
- SoundCloud for the music API

## 📸 Screenshots / Скриншоты

![Extension Settings](docs/screenshot1.png)
*Settings panel with mood configuration*

![Music Player](docs/screenshot2.png)
*Integrated music player widget*

---

**Enjoy your AI-powered music experience! 🎵**
**Наслаждайтесь музыкой с искусственным интеллектом! 🎵**
