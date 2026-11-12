# American Idioms Flashcards

A single-page flashcard app for memorizing American idioms, everyday expressions and vocabulary. The deck has 816 cards. Each card shows a word or phrase on the front and its meaning plus an example sentence on the back.

Published page (private to the owner until shared): https://claude.ai/artifact/QjBKdvhhaZegSxAZWrHfBJ

## Files

| File | What it is |
| --- | --- |
| `index.html` | The whole app in one file. Use this name when you host the page on a website, so it loads at the site's root address. |
| `american-idioms-flashcards.html` | The same page under a descriptive name, for keeping on your computer. Open it in any browser. |
| `idiom-deck.txt` | The card list in plain text, one card per line. Saved in the "American Idioms" Claude project. |
| `README.md` | This file. |

## How to use it

1. Open `index.html` in a browser, or open the published page.
2. Read the front of the card and say the meaning out loud.
3. Flip the card to check yourself, then move to the next one.

| Action | Mouse or touch | Keyboard |
| --- | --- | --- |
| Flip the card | Click or tap the card, or press **Flip** | `Space` |
| Next card | **Next** button, or swipe left | `→` |
| Previous card | **Previous** button, or swipe right | `←` |
| Mark a card as learned | **Mark learned** button | `L` |

## Features

- **3D flip cards.** Blank index-card style, with the meaning and an example on the back.
- **Shuffle and Reset.** Shuffle randomizes the order. Reset returns to the original order and clears the search and filters.
- **Search.** Type any word to narrow the deck. It searches the phrase, its meaning and the original spelling from the sheet.
- **Filters.** All, Idioms and phrases, Words, and Say it better.
- **Learned marks.** Mark cards you know, then tick **Hide learned** to study only the rest.
- **Browse the list.** Open the list under the card to see every card and jump to one.
- **Light and dark themes.** The page follows the device setting.
- **Works on phones.** The layout fits a narrow screen.

## What is in the deck

| Group | Cards | Contents |
| --- | --- | --- |
| Idioms and phrases | 614 | Idioms, sayings and expressions |
| Words | 132 | Single vocabulary words |
| Say it better | 70 | Natural or more advanced ways to say basic things, such as "I'm all ears" for "I'm listening" |
| **Total** | **816** | |



## Adding or changing cards

The card list is `idiom-deck.txt`. Each line is one card, with the parts separated by ` | `:

```
term | meaning | example sentence | category | original spelling (optional)
```

The category is `i` for an idiom or phrase, `w` for a word, or `s` for a "say it better" card. For example:

```
Break the ice | To say or do something that makes people relax and start talking. | He told a joke to break the ice at the meeting. | i
```

The HTML file carries its own copy of the deck, so editing `idiom-deck.txt` does not change the page by itself. To update the page, ask Claude in the "American Idioms" project to add the cards and republish.

## Good to know

- **Learned marks stay in one browser.** They are saved on the device you study on and do not follow you to another browser or device. Clearing the browser's site data removes them.
- **Fonts need a connection.** The page loads its two typefaces from Google Fonts. Offline it still works and uses the device's own fonts.
- **Sharing.** The published page is private. Use the page's Share menu to let someone else open it.
