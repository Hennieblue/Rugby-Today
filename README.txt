RUGBY TODAY - GITHUB PAGES
===========================

This folder creates a phone-friendly rugby page from your Rugby365 V5 program.

FILES
-----
index.html       The page opened on iPhone or Samsung.
update_rugby.py  Reads Rugby365 using hidden Chrome.
data.json        Latest match information.
requirements.txt Installs Selenium on GitHub.
.github folder   Updates and publishes the page automatically.

GITHUB SETUP
------------
1. Sign in at github.com.
2. Create a NEW repository named: Rugby-Today
3. Choose PUBLIC.
4. Upload ALL the files and folders from this Rugby-Today folder.
   Important: upload the hidden .github folder too.
5. Open repository Settings.
6. Open Pages.
7. At Build and deployment, set Source to: GitHub Actions.
8. Open the Actions tab and wait for Update Rugby Today to finish.

YOUR LINK
---------
https://YOUR-GITHUB-NAME.github.io/Rugby-Today/

Replace YOUR-GITHUB-NAME with your real GitHub username.

The GitHub updater runs about every 5 minutes. The phone page checks data.json
every 30 seconds. GitHub schedules can occasionally start a little late.

IPHONE
------
Open the link in Safari. Use Share, then Add to Home Screen.

SAMSUNG
-------
Open the link in Chrome. Open the Chrome menu, then Add to Home screen.

The page starts in English for your friend. Press Afrikaans to change language.
The selected language is remembered on that phone.
