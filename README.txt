================================================================================
  ITALIAN LEARNING CENTER - User Guide
  Created by John R. & Claude (Anthropic)
================================================================================

TABLE OF CONTENTS
-----------------
1. Getting Started
2. Dashboard
3. Quick Import
4. Word Bank
5. Flashcards
6. Memory Game
7. Audio Scripts
8. Keyboard Shortcuts
9. Backing Up Your Data
10. Troubleshooting

================================================================================
1. GETTING STARTED
================================================================================

Step 1: Open index.html in your web browser (Chrome recommended).

Step 2: You'll see the Dashboard tab. It will show that your word bank is empty.

Step 3: Click the "Quick Import" tab at the top.

Step 4: Click the "Load Built-in Dictionary" button. This instantly loads 6,000+
        Italian-English word pairs into your word bank. No internet required.

Step 5: You're ready to learn! Go to Flashcards, Memory Game, or Audio Scripts
        to start studying.

OPTIONAL - AI-Powered Translations:
   If you want to import your own words with AI translation, you'll need an
   Anthropic API key:
   a. Go to console.anthropic.com and create an account
   b. Generate an API key
   c. In the Quick Import tab, click "API Settings"
   d. Paste your key and click "Save Key"
   e. Select a model (Haiku 4.5 is cheapest and fastest)

================================================================================
2. DASHBOARD
================================================================================

The Dashboard is your home screen. It shows:

- Total Words: How many words are in your word bank
- Easy/Learned: Words you've marked as learned
- Hard: Words you've marked as difficult
- Normal: Words that are neither easy nor hard

- Learned Today/This Week/This Month: How many words you marked as "easy"
  in that time period

- Remaining to Learn: Words not yet marked easy
- Words Per Day: How many words you need to learn per day to finish in 1 year

- Progress Bar: Visual display of your overall progress (easy / total)

================================================================================
3. QUICK IMPORT
================================================================================

This tab lets you add words to your word bank in several ways:

LOAD BUILT-IN DICTIONARY:
   Click "Load Built-in Dictionary" to instantly add 6,000+ pre-translated
   Italian-English word pairs. Words already in your bank are skipped.

TRANSLATE WITH AI (requires API key):
   a. Select direction: "Italian to English" or "English to Italian"
   b. Paste words into the text box (one per line, or comma-separated)
   c. Click "Translate & Import All"
   d. Review the results - each word shows its translation
   e. Click "Save All to Word Bank" or "Save Selected"

   Tips:
   - You can click "Stop" during import to pause and keep what's done so far
   - Failed translations show as "?" and won't be selected for saving
   - Duplicates are automatically detected and skipped

REMOVE UNTRANSLATED:
   Click this to clean up any words in your bank where the Italian and
   English are identical (failed translations).

IMPORT/EXPORT CSV:
   In the Word Bank tab, use "Export CSV" to save your words as a spreadsheet
   file, and "Import CSV" to load words from a CSV file.

================================================================================
4. WORD BANK
================================================================================

Your personal vocabulary database. All words you import or add end up here.

FEATURES:
- Search: Type in the search box to filter words
- Sort: Click column headers (Italian, English, Date) to sort
- Add Word: Manually add a single word with its translation and notes
- Edit: Click "Edit" to add notes to any word
- Delete: Remove individual words

EASY/HARD MARKERS:
   Each word has two small buttons next to it:
   - E (green when active): Mark as Easy/Learned
   - H (gold when active): Mark as Hard/Needs Practice
   These affect how the word appears in Flashcards, Audio Scripts, and
   the Dashboard statistics.

BACKUP & RESTORE:
   - "Backup All Data": Saves everything (words, settings, easy/hard marks)
     as a JSON file. Use this to back up your progress or move to another
     computer.
   - "Restore Data": Load a previously saved backup file. You can choose to
     merge with existing data or replace it entirely.

================================================================================
5. FLASHCARDS
================================================================================

Study your vocabulary with interactive flip cards.

HOW TO USE:
   a. Cards show one side (Italian or English depending on mode)
   b. Click the card or press SPACE to flip and reveal the answer
   c. Click again (or press SPACE again) to advance to the next card
   d. Use arrow keys for Previous/Next

CONTROLS:
   - Italian/English toggle: Switch which language shows first
   - Filter dropdown: Show All, Hard Only, Easy Only, or Normal Only
   - Shuffle: Randomizes the deck. Hard words appear more often, easy words
     appear less often (controlled by the multiplier setting)
   - Mark Easy: Press 0 or click the button. Word will appear less in shuffle.
   - Mark Hard: Press Ctrl or H or click the button. Word will appear more.
   - Replay Last 50: Creates a deck from your last 50 reviewed cards
   - Restart: Go back to the beginning of the current deck
   - Send Last 50 to Memory Game: Stages your recent cards for the Memory Game

CONJUGATIONS:
   If grammar info has been loaded, verbs will show their conjugation tables
   on the Italian side of the card. The base/infinitive form appears at the
   top with tenses displayed underneath.

LOAD GRAMMAR INFO:
   Click this button to fetch conjugation and grammar data for all words via
   Claude AI (requires API key). This adds verb tenses, noun plurals, etc.

HARD/EASY FREQUENCY:
   The multiplier (default 5x) controls how much more/less often hard/easy
   words appear when you shuffle. Adjustable from 2x to 20x.

================================================================================
6. MEMORY GAME
================================================================================

A card-matching game that pairs Italian words with their English translations.

HOW TO PLAY:
   a. Select how many pairs you want (6, 10, 15, 20, or 30)
   b. Choose where to draw words from:
      - All Words: Random selection from your entire word bank
      - Hard Only: Only hard-marked words
      - Normal Only: Only normal words
      - Easy Only: Only easy-marked words
      - Flashcard Last 50: Words you sent from the Flashcards tab
   c. Click "Load Words" to start a new game
   d. Click cards to flip them - find the matching Italian/English pair
   e. Match all pairs to win!

WORD SET SIDEBAR (left side):
   Shows all words in the current game set, sorted alphabetically.
   - Use the "Show" dropdown to display Italian Only, English Only, or Both
   - Click "Hard" to mark a word as hard
   - Click "Easy" to mark a word as easy AND replace it with a new word

REPLAY:
   - "Replay Same Words": Reshuffles the same word set for another round
   - "New Words": Picks a fresh random set
   - After winning, choose "Play Again (Same Words)" or "New Words"

TIP: Use this game to drill words you're struggling with. Mark easy words
to swap them out and keep practicing the harder ones.

================================================================================
7. AUDIO SCRIPTS
================================================================================

Generate audio study scripts that read Italian words and their English
translations aloud using your browser's text-to-speech.

GENERATING A SCRIPT:
   a. Select Order: Alphabetical or Shuffled
   b. Select Filter: All, Hard Only, Easy Only, or Normal Only
   c. Set letter range (From/To) to limit to specific letters (e.g., A-G)
   d. Set word Limit (25, 50, 100, 250, or All)
   e. Click "Generate Script"

VOICE SETTINGS:
   - Italian Voice: Choose from available Italian voices on your system
   - English Voice: Choose from available English voices
   Tip: Look for voices with "Neural" or "Natural" in the name for the
   most human-sounding pronunciation.

SPEED SETTINGS:
   - Speed: Base playback speed (0.5x to 1.5x)
   - Slowdown per earlier repeat: Each repetition starts slower and builds
     up to the target speed. Example at 25% slowdown with 3 repeats:
     1st play = 50% speed, 2nd = 75%, 3rd = 100% (full speed)

REPEAT SETTINGS:
   Each word can repeat multiple times based on its difficulty:
   - Hard: Default 3 repetitions
   - Normal: Default 2 repetitions
   - Easy: Default 1 repetition
   All adjustable from 1 to 10.

PLAYBACK CONTROLS:
   - Play: Start reading the script aloud
   - Pause/Resume: Pause and resume playback
   - Stop: Stop playback completely
   - The current word is highlighted in the script as it plays

RECORDING:
   - "Record as Audio File": Captures the audio as the script plays and
     saves it as a downloadable .webm file
   - When prompted, select the current tab and check "Share tab audio"
   - Tip: Turn your speaker volume to zero (not mute the tab) if you don't
     want to hear it while recording - the file will still capture the audio

EXPORT:
   - "Export Script (.txt)": Downloads the script as a text file for use
     with external text-to-speech tools

================================================================================
8. KEYBOARD SHORTCUTS
================================================================================

FLASHCARDS:
   Space / Enter    Flip card, then advance to next
   Left Arrow       Previous card
   Right Arrow      Next card
   0 (zero)         Toggle Easy
   Ctrl or H        Toggle Hard

================================================================================
9. BACKING UP YOUR DATA
================================================================================

All your data is stored in your browser's localStorage. This means:
- Your data stays on your computer
- Clearing browser data will erase it
- Different browsers have separate data

TO BACK UP:
   Go to Word Bank tab > click "Backup All Data"
   This saves a .json file with all your words, easy/hard marks, settings,
   and API key.

TO RESTORE:
   Go to Word Bank tab > click "Restore Data" > select your backup file
   Choose "Merge" to add to existing data, or "Replace" to overwrite.

TO MOVE TO ANOTHER COMPUTER:
   a. Backup on the old computer
   b. Copy the .json file to the new computer
   c. Open the app on the new computer
   d. Restore from the .json file

================================================================================
10. TROUBLESHOOTING
================================================================================

APP WON'T LOAD:
   - Make sure you're opening index.html in Chrome or a modern browser
   - Check that all files are in the same folder (app.js, styles.css,
     dictionary-5000.js, index.html)

WORDS NOT LOADING:
   - Click "Load Built-in Dictionary" in the Quick Import tab
   - If using AI translation, check that your API key is saved in Settings

AI TRANSLATION FAILS:
   - Verify your API key is correct (Settings in Quick Import tab)
   - Check your Anthropic account has available credits
   - Try the Haiku 4.5 model (cheapest and fastest)

NO AUDIO VOICES:
   - Make sure you're using Chrome
   - On Windows: Settings > Time & Language > Speech > Manage Voices
     to install additional voices
   - Look for "Neural" or "Natural" voices for better quality

RECORDING PRODUCES SILENT FILE:
   - Don't mute the browser tab - instead turn your physical volume to zero
   - Make sure you selected "Share tab audio" when the dialog appeared

DATA DISAPPEARED:
   - Check you're using the same browser
   - If you cleared browser data, restore from a backup file
   - Always keep regular backups using "Backup All Data"

================================================================================
  Thank you for using Italian Learning Center!
  Buono studio! (Happy studying!)
================================================================================
