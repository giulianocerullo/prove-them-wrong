# Prove Them Wrong

A timer that shows your age in years with 9 decimal places, paired with motivational phrases that type themselves out on screen.

## How to use

1. Open `prove-them-wrong.html` in any browser.
2. Enter your date of birth (time is optional) and press **Start**.
3. The timer starts and the phrases begin to appear.

Your date of birth is saved in the browser, so the timer resumes on its own the next time you open the page.

## Controls

| Action | Effect |
| --- | --- |
| Click the phrase, `Space` or `→` | Skip to the next phrase |
| **Auto / Light / Dark** button | Change theme (Auto follows the system) |
| **Reset** button | Clear the date and ask for it again |

## Features

- Age calculated to 9 decimal places and updated in real time.
- 1000 motivational phrases in random order, with no repeats until all have been shown (about an hour and a half before the same phrase comes back).
- Letter-by-letter typing animation with a blinking cursor.
- Light or dark theme picked automatically from your system settings.
- Respects the system "reduce motion" setting.
- A single file, with no dependencies and nothing to install.

## Notes

The fonts (EB Garamond and DM Sans) load from Google Fonts. Without a connection the page still works and falls back to system fonts.

To add or change phrases, edit the `PHRASES` list inside the HTML file.

## Credits

This project is inspired by **[Age Timer](https://jacky-liang.github.io/age-timer/) by Jacky Liang** (itself adapted from "Motivation" by maccman). The age display with 9 decimal places, shown as a superscript, follows that project. A credit link to it is also visible on the page and in the HTML source.

The phrase typing animation is inspired by [why.com](https://why.com/).
