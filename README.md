# Aloscraper
Download courses from alomoves.com automatically.

## Installation

1. ```pip install selenium```
2. Download Chrome Webdriver according to your Version (probably 80) [HERE](https://chromedriver.chromium.org/downloads) and place into your working folder next to the .py (or add it to your PATH)
3. Adjust lines 8 to 12 depending on your OS and desired download paths.
4. Make sure you have a valid alomoves account on hand (2 week test accounts are fine).
5. Place the links of courses you want to download in **downloadlinks.txt**, one per line.
    - Example: https://www.alomoves.com/series/COURSENAME/workouts
    - You find these links by navigating to the course page and find the one where all the individual videos are shown with thumbnails.

## Usage
1. ```python3 downloader.py```
2. A chrome browser will open with the alomoves login page.
3. You have 25 seconds to login to your account.
4. After login just wait and the downloads will begin automatically.
5. You can minimize the browser and watch the console for progress.

              __
          ___( o)>
          \ <_. )
           `---'  for s