# Speaking Part 1 Practice

Answer everyday questions about home, work, study and interests, read aloud and recorded, as in Part 1.

Part of the [IELTS Study Suite](https://github.com/Apurba94/ielts-study-suite): 100 free study apps for IELTS. This one is for the IELTS Academic and General Training test. It works offline, as a Windows program or in the browser.

## Download and run

- **Windows:** download `Speaking Part 1 Practice.exe` from the [latest release](https://github.com/Apurba94/ielts-speaking-part1/releases/latest) and open it. Nothing to install. It opens in its own window and saves your progress in your user folder.
- **Browser:** open it online in the suite's web edition at https://ielts-study-suite.vercel.app/apps/ielts-speaking-part1/ . Progress stays in that browser.
- **From source:** `python launcher.py` (Python 3.10 or later, no packages needed).

## What it does

Speaking Part 1 lasts four to five minutes: the examiner asks questions about familiar topics such as your home, work, hobbies and daily life. Answers should be natural and extended a little: an answer, a reason, perhaps an example. Thirty topics with four questions each are read aloud by your computer, and each answer is recorded so you can listen back.

Sections: Practice, Topics, Recordings, Progress, About.

## How to use it

1. Choose a topic, or take a random one, and press **Start**.
2. Listen to the question and answer in about 20 to 30 seconds. Each answer is recorded.
3. Listen back at the end. Did you answer the question and add a reason or example?
4. Recordings stay on this device.

## Good to know

- All questions, passages, recordings and definitions were written for this suite. None are official IELTS questions. For official practice, use the materials on ielts.org and from the test partners.
- It follows IELTS as delivered on computer in 2026. Formats change, so check ielts.org before your test.
- Listening uses the voices installed on your computer, which sound less natural than real test recordings.
- Feedback on writing and speaking counts what a program can count honestly, such as length and linking words. It is not an IELTS band score. Band conversions for Listening and Reading are approximate.
- Not endorsed by or affiliated with the British Council, IDP or Cambridge University Press & Assessment. IELTS is a registered trademark of its owners.

## For developers

The app is plain HTML and JavaScript in `web/`, run by a small Python launcher that serves it on 127.0.0.1 only and needs a secret token for saving. Tests: `node --test "tests/*.test.js"` (29 tests) and `python -m unittest discover -s tests`. Build the .exe with `python build_exe.py`.

Built with AI assistance (Claude Code). MIT licence. By JANIN A APURBA.
