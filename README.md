# GAINS

GAINS is a voice assistant for Windows. You say **"Hey Jarvis"**, ask for
something, and it answers out loud. It can tell you the time and the weather,
read your PDFs and worksheets, write an essay into a Word document, and, if you
let it, check your email and calendar. What it remembers about you stays on
your own computer.

It is a small personal project that is still being tested. That is why you
will see three warnings on the way in. All three are expected.

## Download

**[Download GAINS-Setup-v1.0.exe](https://github.com/ss-savari/GAINS-releases/releases/download/v1.0/GAINS-Setup-v1.0.exe)** (about 85 MB)

If that link doesn't work, open the
[latest release](https://github.com/ss-savari/GAINS-releases/releases/latest)
and click the file ending in `.exe` under **Assets**.

You need Windows 10 or 11, a microphone, and about ten minutes. You don't need
to install anything else.

## The three warnings

| When | What you see | What to click |
|---|---|---|
| Right after downloading | Your browser says the file "isn't commonly downloaded" | **Keep**. You may have to open the **...** menu next to the download first, and Edge may ask once more: **Show more**, then **Keep anyway**. |
| When you open the installer | A blue box: "Windows protected your PC" | **More info**, then **Run anyway** |
| If you sign in with Google | "Google hasn't verified this app" | **Advanced**, then **Go to GAINS** |

These appear for any program from someone who hasn't paid for a publisher
certificate or been through Google's review. They don't mean something is wrong
with the file.

## The keys you need

The first time GAINS starts, it opens a **Settings** window. A key is a long
code you copy from a website and paste in. Click **Check** after pasting and
GAINS tells you straight away whether it works.

| | Cost | What it does | Where to get it |
|---|---|---|---|
| **Groq** | Free. **Required** | Understands what you say and thinks of the answer | <https://console.groq.com/keys>, then **Create API Key** |
| **Gemini** | Free. Recommended | Reads PDFs, photos of pages and your screen; searches the web; takes over when Groq's free daily limit runs out | <https://aistudio.google.com/apikey>, then **Create API key** |
| **ElevenLabs** | Free tier. Optional | A natural-sounding voice. Without it GAINS uses the voice built into Windows | <https://elevenlabs.io/app/settings/api-keys> |
| **Google sign-in** | Free. Optional | Email, calendar and to-do list. There is no key: click **Sign in with Google** in Settings | |

Only Groq is required. Everything else can be added later from the tray icon:
right-click the blue **G** near the clock, then **Settings...**

GAINS never sends an email without asking you first.

## Using it

After setup a small blue **G** sits near the clock (it may be under the **^**
arrow). Say **"Hey Jarvis"**, wait for the screen edges to glow, then ask:

- "What's the weather like today?"
- "Summarise the chemistry PDF in my downloads."
- "Write a short essay about the water cycle."

The free keys have daily limits. If GAINS says it has hit its limit, it also
says when it will be back.

## Removing it

Windows **Settings**, then **Apps**, then **GAINS**, then **Uninstall**. It asks
whether to delete your saved memory and settings as well.

## Something not working?

Tell me. Either message me the same way I sent you this link, or
[open an issue here](https://github.com/ss-savari/GAINS-releases/issues/new)
(you need a free GitHub account for that).

It helps to know what you said, what GAINS did, and what you expected. Please
don't post GAINS's log file publicly, because it contains what you said to it.
If I need it I'll ask you to send it to me directly: right-click the **G**,
then **Open Logs**.
