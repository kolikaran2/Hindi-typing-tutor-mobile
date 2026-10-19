# Kruti Typing Pad (कृति टाइपिंग पैड)

A Kruti Dev 010 Hindi typing tutor for a mobile phone held in landscape with a keyboard attached (Bluetooth or USB OTG). It also works on a desktop browser.

The whole app is one HTML file with the Kruti Dev 010 font built in. It needs no installation and no internet connection after it loads.

## Features

- **Three-word view:** the screen shows the previous, current and next word, with the current word large in the centre. A cursor moves through the word, correct letters turn green and wrong ones turn red.
- **Real Kruti Dev typing:** you type with the Remington (Kruti Dev) layout. Unicode Hindi text is converted to Kruti Dev automatically, and text already in Kruti Dev is accepted as it is.
- **Alt codes:** hold Alt, type the code, then release Alt. For example, Alt+0161 gives ँ and Alt+0170 gives the र of ट्र. The app reads Alt codes itself, so they work on Android too. Tab can also insert the next Alt-code character (this can be switched off).
- **Two modes:**
  - Practice: stops on a mistake until you press the right key.
  - Exam: carries on after a mistake, with Backspace allowed or blocked.
- **Timer:** set any time limit, for example 400 words in 10 minutes. The timer starts on the first key you press.
- **Results:** shows net and gross speed (5 keystrokes = 1 word), accuracy, errors, the list of wrong words and the time taken.
- **Difficult keys:** the app tracks which keys you get wrong and which are slow. The report lists your weakest keys, and one key builds a practice set from words that use them.
- **Hint strip:** shows the key (or Alt code) for the next letter and the key sequence for the whole word.
- **Keyboard map:** shows every key with its Kruti Dev letter, and highlights the next key you need.
- **Passages from a ZIP:** upload `passages.zip` and pick a passage by number (1–100). There is also a random-passage option.
- **Passage import:** paste from the clipboard, open a .txt file, or use the built-in sample passages.
- **Other:** text size controls (+ / − buttons), dark and light themes, fullscreen with a landscape lock, an error sound and vibration, and the screen stays awake while you type.
- **Saved on the device:** settings, key statistics and your last 30 results are kept in the browser.

**Notes**

- Reading the zip works only through the GitHub Pages link. If you open the HTML file directly from phone storage, the browser blocks reading other files. In that case use **Settings → "फ़ोन से ZIP चुनें"** (choose ZIP from phone) to load the zip from the device.
- A new or replaced zip may take a few minutes to show up on GitHub Pages.
- The zip may hold any number of passages. Name them `1.txt`, `2.txt`, `3.txt` and so on, save them as UTF-8, and write them in Unicode Hindi or Kruti Dev.
- If there is no zip, the app also looks for loose files at `passages/23.txt` or `23.txt`.

## The 100 passages

- 405–455 words each, written in original Hindi.
- Topics include school life, Rajasthan, Bundi, festivals, the constitution, health, technology, environment, government schemes, an office letter and a leave application.
- Each passage covers most Kruti Dev keys, matras, reph, joined letters, punctuation and the common Alt-code characters (ँ, ट्र, ऊ, ॉ, क्र, त्त, ट्ट, फ्, ह्म, brackets and quotes).

## Keyboard shortcuts

| Key | Alternative | Action |
|---|---|---|
| F1 | Ctrl+1 | Settings / passage import |
| F2 | Ctrl+2 | Back to typing (closes any panel) |
| F3 | Ctrl+3 | Hint strip on/off |
| F4 | Ctrl+4 | Keyboard map on/off |
| F5 | Ctrl+5 | Restart passage |
| Alt+P | Ctrl+6 | Pause / resume |
| Alt+R | Ctrl+7 | Difficult-keys report and past results |
| F8 | Ctrl+8 | Build a practice set from difficult keys |
| F9 | Ctrl+9 | Smaller letters |
| F10 | Ctrl+0 | Bigger letters |
| F11 | | Fullscreen + landscape lock |
| F12 | | Dark / light theme |
| Alt+S | | In Settings: apply the passage and start |
| Tab | | Insert the next Alt-code character (if enabled) |
| Alt + code | | Type a special character, e.g. Alt+0161 = ँ |
| Alt + one digit | | Same as Ctrl + that digit (press the digit, release Alt) |
| Backspace | | Correct a mistake (exam mode only) |
| Enter | | Results screen: restart · exam mode: next word |
| N | | Results screen: next passage number |
| PgUp / PgDn | | Switch tabs in Settings |

F6, F7, Esc and Ctrl+Enter are not used, because the browser needs them.

## Common Alt codes (Kruti Dev 010)

| Code | Character | Code | Character |
|---|---|---|---|
| Alt+0161 | ँ | Alt+0216 | क्र |
| Alt+0170 | ्र (ट्र, ड्र) | Alt+0217 | त्त् |
| Alt+0197 | ऊ | Alt+0234 | ट्ट |
| Alt+0130 | ॉ | Alt+0236 | ड्ड |
| Alt+0182 | फ् | Alt+0239 | ड्ढ |
| Alt+0184 | य् | Alt+0233 | न्न |
| Alt+0186 | ह् | Alt+0237 | द्द |
| Alt+0227 | ह्म | Alt+0224 | ह्न |
| Alt+0225 | ह्य | Alt+0221 | फ्र |
| Alt+0188 / 0189 | ( ) | Alt+0223 / 0222 | “ ” |

## Settings

- Time limit in minutes (0 = no limit)
- Practice or exam mode
- Allow Backspace in exam mode
- Tab inserts Alt-code characters
- Simple form, which uses fewer Alt codes (for example त्त → Rr, ट्ट → V~V)
- Convert Hindi digits ०–९ to 1–9
- Automatic hint after two wrong presses
- Error sound and vibration
- Text size, 3 or 5 visible words, the upcoming-words line, and the theme

## Tips for a phone with a keyboard

- Set the phone's keyboard layout to **English (US)**.
- Turn the phone sideways (landscape) and press F11 for fullscreen.
- Practise for at least 30 minutes a day, and focus on accuracy before speed.

---

crafted with ♥ by Karan Kumar Koli
