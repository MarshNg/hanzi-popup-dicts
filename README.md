# YomiLens Dictionaries

Dictionary packages for **YomiLens Popup Dictionary**, an Anki add-on that opens a fast popup lookup while reviewing cards.

This repository is used as the download source for the add-on's built-in dictionary manager. The files here are packaged in Yomitan/Yomichan-compatible ZIP format so they can be imported directly into YomiLens.

## Available Dictionaries

| File | Language | Description |
|---|---|---|
| `cedict-en.zip` | Chinese -> English | CC-CEDICT Chinese-English dictionary |
| `cedict-fr.zip` | Chinese -> French | CFDICT Chinese-French dictionary |
| `cedict-vi.zip` | Chinese -> Vietnamese | CVDICT Chinese-Vietnamese dictionary |
| `HanViet.Final.zip` | Chinese -> Vietnamese | Han-Viet dictionary package |
| `en-en-dict.zip` | English -> English | English dictionary with definitions and IPA data |
| `en-vi-dict.zip` | English -> Vietnamese | English-Vietnamese dictionary |
| `jitendex.zip` | Japanese -> English | Jitendex Japanese-English dictionary |
| `JMdict_english.zip` | Japanese -> English | JMdict Japanese-English dictionary |
| `JMnedict.zip` | Japanese names | JMnedict proper-name dictionary |
| `KANJIDIC_english.zip` | Japanese kanji | KANJIDIC kanji readings and English meanings |
| `KANJIDIC_french.zip` | Japanese kanji | KANJIDIC kanji readings and French meanings |

## How to Use

### From YomiLens

1. Open Anki.
2. Go to **Tools -> YomiLens Settings**.
3. Open the **Dictionaries** tab.
4. Choose a dictionary and click **Download**.
5. Enable the language you want in the **General** tab.
6. Review a card, select a word, and the popup will look it up.

### Manual Import

You can also download any ZIP file from this repository and import it manually:

1. Open **Tools -> YomiLens Settings**.
2. Go to **Dictionaries**.
3. Click **Import ZIP**.
4. Select the downloaded dictionary ZIP.

## Manifest

`manifest.json` lists the dictionaries shown inside the YomiLens download manager. Each entry contains:

- `id`: stable dictionary identifier
- `title`: display name
- `description`: short summary shown in the add-on
- `url`: download URL
- `size_mb`: approximate package size
- `lang`: language code used for grouping

## Credits and Licenses

These packages are built from open dictionary projects and community-maintained datasets. Please preserve the original credits and licenses when redistributing.

### Chinese Dictionaries

- **CC-CEDICT Chinese-English**: CC-CEDICT / MDBG contributors, licensed under CC BY-SA 4.0.
- **CFDICT Chinese-French**: CFDICT / Chine Informations, licensed under CC BY-SA 3.0.
- **CVDICT Chinese-Vietnamese**: CVDICT / Phong Phan, licensed under CC BY-SA 4.0.
- Chinese EN/VI/FR source data was prepared from the LingLook dictionary data project.

### Japanese Dictionaries

- **JMdict**, **JMnedict**, and **KANJIDIC** are maintained by the Electronic Dictionary Research and Development Group (EDRDG) and used under the EDRDG license.
- Yomitan-ready JMdict/JMnedict/KANJIDIC packages are from the Yomidevs dictionary build projects and conversion tooling.
- **Jitendex** is based on JMdict/EDRDG data and distributed by the Jitendex project.

### English Dictionaries

- **English Dictionary (EN->EN)** combines Open English WordNet, MongoDB english-words-definitions, and ipa-dict data.
- **English-Vietnamese Dictionary (EN->VI)** uses data from the Free Vietnamese Dictionary Project by Ho Ngoc Duc.

### Yomitan

YomiLens uses dictionary formats, language logic, and ideas inspired by the Yomitan ecosystem.

Special thanks to the [Yomitan project](https://github.com/yomidevs/yomitan) and the [Yomitan contributors](https://github.com/yomidevs/yomitan?tab=readme-ov-file#contributing) for building and maintaining the modern popup dictionary tooling that made this workflow possible.

## Related Links

- [Yomitan](https://github.com/yomidevs/yomitan)
- [Yomitan Import](https://github.com/yomidevs/yomitan-import)
- [Yomidevs JMdict Yomitan builds](https://github.com/yomidevs/jmdict-yomitan)
- [EDRDG](https://www.edrdg.org)
- [Jitendex](https://jitendex.org)
- [CC-CEDICT](https://cc-cedict.org)

## Support

If these dictionaries or YomiLens help your study workflow, you can support the project here:

[ko-fi.com/marshnguyen](https://ko-fi.com/marshnguyen)
