# Goethe Institute A1 Wordlist

## About this Deck

This is the Goethe Institute's A1 wordlist (including example sentences), translated into English, using double-sided cards and machine-generated audio.
The original document is available [here](https://www.goethe.de/pro/relaunch/prf/de/A1_SD1_Wortliste_02.pdf) as a PDF.
This deck is maintained in a public GitHub repository [here](https://github.com/patsytau/anki_german_a1_vocab).

I translated the words and sentences personally, and a professional German->English translator proofread the results.
Both of us are native English speakers, so there are unlikely to be errors, but we are only human.


## How it was created.

I created this deck by opening the wordlist document and exporting the list of words and associated example sentences.
This was not a scripted process, and involved quite a lot of spreadsheet and text editor adjustments to get things into a reasonable state.

I included the additional snippets of vocabulary that appear before the list proper, but without example sentences since none were provided.
This extra vocabulary is primarily colours, months, days, numbers, units, and other elementary concepts that will likely be useful.
These do not have any audio, as the TTS does not handle the plural notation gracefully.
The [Advanced Browser](https://ankiweb.net/shared/info/874215009) plugin was invaluable for finding these entries when adding the audio.

The audio was created using the high-quality [Thorsten-Voice](https://github.com/thorstenMueller/Thorsten-Voice) TTS, which saved me a tremendous amount of work, and saved everyone else from having to listen to my voice :)

Finally, I used the [Add note id](https://ankiweb.net/shared/info/1672832404) plugin to add ids to the notes in case I need to make future corrections.


## Card format

The front of each card is a german word with an example sentence.
Verbs are provided in the infinitive and nouns with their definite articles.
The back of each card is a translation of the german word and example sentence.
Some cards have an additional comment to clarify the context, for instance, indicating if a colleague is male or female.

Note that sometimes there are set phrases in which transating the word directly does not make sense.
In such cases the word is not translated, but an ellipsis ('...') is given in place of the word's translation.

Where a word has multiple translations and sample sentences, these were split into individual notes.
This avoids a word having only one translation, which may not appear in the translated sample sentence (without it being a tortured rephrasing).




## Deviations from the Goethe Institute

Some of the sentences from the Goethe Institute were not brilliant example of the use of a word in context - for instance, "Platz" had an example of "I wohne am Messeplatz 5.".
However, since addresses are not translated, this would not have been a useful sentence to translate, so I changed it to "Ich wohne neben dem Platz."

There are a small number of modifications of this nature, or instance, where I have added an additional sentence to distinguish between two common usages of a word.
These cases are listed below:

* Replacement: "Herr Ober, kann ich bitte Salz haben?" replaced with "Entschuldigung, kann ich bitte das Salz haben?" after feedback from a native German speaker ("Herr Ober is an outdated way of addressing a waiter at a restaurant.").
* Replacement: "Haben Sie Telefon?" replaced with "Haben Sie ein Telefon?" following feedback from a native German speaker.
* Replacement: "Hören Sie die Ansagen." replaced with "Hören Sie auf die Ansagen." following feedback from a native German speaker.
* Replacement: "Ich wohne Messeplatz 5." replaced with "Ich wohne neben dem Platz." - since addresses are not translated, this would not demonstrate the noun "Platz".
* Replacement: "einmal" replaced with "noch einmal" to better fit the example sentence.
* Replacement: "bei" -> "bei uns" to better fit the example sentence.
* Replacement: "kulturell" -> "kulturell interessiert" to better fit the example sentence.
* Replacement: "Zahlen, bitte!" -> "Wir möchten zahlen, bitte!" to ensure the word "pay" is used in the sentence.
* Replacement: "8.00 Uhr" -> "8:00 Uhr" to allow the text-to-speach to speak as expected.
* Replacement: "Wir müssen jetzt Schluss machen. Also auf Wiederhören!" -> "Auf Wiederhören!" - to match the example of "Auf Wiedersehen!"
* New: "Ich wasche mich morgens." - to indicate the reflexive form of waschen.
* New: "Er arbeitet mit Vorsicht." - the sentence was meant to demonstrate the noun "Vorsicht", but there is a difference between "Vorsicht" as "caution" or "attention" and the exclamatory "Vorsicht!" ("Watch out!" or "Careful!").
* New: "Die Geschichte ist kulturell wichtig." - illustrates meaning of "kulturell" in isolation, as opposed to "kulturell interessiert".
* New: "Das Glas ist kaputt." -> illustrates meaning of "kaputt" in insolation, as opposed to "kaputt gehen".
* New: "Sie dürfen diese Prüfung nur einmal machen." -> to illustrate the meaning of "einmal" instead of "noch einmal".
* New: "dort" -> separate entries for "dort", "dorther" and "dorthin".
* New: "sich ausziehen" -> to clarify when "sich" should be added to "ausziehen"
* New: "Ich mag das Buch." -> so that "das" has a translation to "the" (not just "that") in line with "der" and "die"


## Additions and fixes (2026)

### 1. Added the missing first page (46 new notes)

The original deck starts at *die Ansage*. The official list's first page, *ab* through *der Anrufbeantworter*, was missing
(reported upstream in [issue #16](https://github.com/patsytau/anki_german_a1_vocab/issues/16)).
All 46 entries from that page are now included, one note per example sentence, as in the rest of the deck:

*ab, aber, abfahren, die Abfahrt, abgeben, abholen, der Absender, Achtung, die Adresse, all-, allein, also, alt, das Alter,
an, anbieten, das Angebot, ander-, anfangen, der Anfang, anklicken, ankommen, die Ankunft, ankreuzen, anmachen,
(sich) anmelden, die Anmeldung, die Anrede, anrufen, der Anruf, der Anrufbeantworter*

- German words and sentences are taken verbatim from the official Goethe PDF. The English translations and notes are new.
- Audio for these notes is Google TTS (German), because the Thorsten-Voice setup wasn't available. All other audio is unchanged.
- The new notes are tagged `goethe-page1-added` and placed at the **front** of the new-card queue, since they are core A1 words.
- They are also added at the top of `Goethe Institute A1 Wordlist.txt`, and their audio files are in `audio/goethe-p1-*.mp3`.

### 2. Corrections

| Word | Before | After |
|---|---|---|
| heißen | `ßt das auf Deutsch?` (corrupted) | `Wie heißt das auf Deutsch?` |
| der Kollege | `ßt die neue Kollegin?` (corrupted) | `Wie heißt die neue Kollegin?` |
| die Haltestelle | `die Haltestelle, -en,` | `die Haltestelle, -n` |
| die Hochzeit | marriage | wedding |
| lieber | to prefer | rather (prefer to): see [issue #11](https://github.com/patsytau/anki_german_a1_vocab/issues/11) |
| fehlen | *Was fehlt Ihnen?* = "What are you missing?" | "What's the matter with you?" (doctor's question) |
| vierzig | fourty | forty |
| die Woche | `die Woche, -e` (a typo copied from the Goethe PDF) | `die Woche, -n` |

Two formal/informal tags were also wrong and are fixed:
- *Sie ist böse auf mich*: here *Sie* means "she", so it is not formal.
- *Deine Tasche kannst du dorthin stellen*: this is informal (*du*), not formal.

### 3. Context hints (`en_note`) on ~130 more notes

These hints aim at the mistakes A1 learners make most often:

- **Formal vs informal:** tags added wherever the sentence uses *Sie*, *du* or *ihr* but had no tag.
- **False friends:**
  - *bekommen* = to get, not "become"
  - *ich will* = I want, not "I will"
  - *das Gift* = poison
  - *Termin* = appointment
  - *Prospekt* = brochure
  - *Hochzeit* = wedding
  - *selbstständig* usually means "self-employed"
- **Confusable pairs:**
  - *kennen / wissen*
  - *möchte / mögen*
  - *nach Hause / zu Hause*
  - *lang / lange*
  - *legen / stellen*, *liegen / stehen*
  - *besuchen / besichtigen*
  - *mieten / vermieten*
  - *billig / günstig*
  - *Stunde / Uhr*
  - *wo / woher / wohin*
  - *Schüler / Student*, *studieren / lernen*
  - *Bank* (pl. *Banken*) / *Bank* (pl. *Bänke*)
- **Grammar traps:**
  - *muss nicht* = don't have to (not "must not"), and *nicht dürfen* = must not
  - *Mir ist kalt* (never *Ich bin kalt*)
  - *Das gefällt mir*: the thing is the subject
  - *seit* + present tense
  - *vor* = ago
  - *das Mädchen* is neuter
  - *dich/dir*, *ihn/ihm* cases
  - *zum/zur*, *ins*, *am*
  - adjectival nouns (*ein Bekannter / der Bekannte*)
  - words that are always plural (*Möbel*, *Leute*)
- **Female forms** where the example sentence uses one (*Ärztin, Chefin, Beamtin, Lehrerin, Verkäuferin*).
- **Numbers and time:**
  - *halb drei* = 2:30, not 3:30
  - *Viertel vor/nach*
  - *einundzwanzig* puts the units first
  - years before 2000 are said in hundreds

### 4. Removed duplicates

These notes duplicated other notes and had no example sentence, so they were removed:
- the second *die Stunde* in the extra vocabulary (it is already in the main list with a sentence)
- the second *der Tag* in the extra vocabulary

### 5. English → German cards and a cleaner design

- **New card type, "Card 2 (English → German)":** each note now also produces a card that shows the English word and sentence and asks for the German.
  - The note (`en_note`) sits behind a **show hint** link on this card's question side. Many notes name the German word (e.g. *"false friend: bekommen = to get"*), so showing them automatically would give the answer away.
  - The answer side shows the note in full, plus the German word, the sentence, and the audio.
  - Each reverse card shares its forward card's position in the new-card queue, so both directions of a word are introduced together.
- **Card design:** a cleaner font and softer colours, with night-mode support.
- **Template files:** `reverse_front_template.txt`, `reverse_back_template.txt`, and `style.css` sit next to the existing template files.

If you only want German → English, suspend the reverse cards: in the Browser, search `card:2`, select all, then **Cards → Toggle Suspend**.

### Updating an existing copy of the deck

The package keeps the original note type and note IDs. If you already use an earlier version of this deck, import this `.apkg`
and tick **"Merge note types"** in the import dialog. This is needed because the note type gained a second card type.
Your existing notes are then updated in place, and the new notes and reverse cards are added. Your review progress is kept.
Anki doesn't delete notes on import, so the two removed duplicates stay in your collection unless you delete them yourself.


## Last words

I hope this deck is useful. If you find any errors then please let me know by either creating an issue on [the github page](https://github.com/patsytau/anki_german_a1_vocab) or emailing ankistuff@ethernull.org and I'll take a look.
Before you email though, please consider whether what is already in the deck is an equally valid (albeit alternative) translation.
In such cases I would not update the deck, as adding a second sample sentence would reduce format consistency and make the note less accessible for users who are just getting started.

