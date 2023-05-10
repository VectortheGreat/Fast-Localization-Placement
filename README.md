# Fast-Localization-Placement

## Description

Places files in a language localization in the same way and compatible with files in localization of all other languages you select.

![](info.gif)

## How to use?

You will need to download Node.js as it is a Javascript based program. [Download Here](https://nodejs.org/en/download)

Now add your localization files on source folder(vanilla is english), then run program.bat. It will create localizaiton folders and files.

## How to edit source folder and limit languages?

Open app.js

If you want to edit source folder. Change here: `const sourceFolder = "english";`

If you want to limit some localization folders or add new localization folders. Change here:

```
const languages = [
  "braz_por",
  "english",
  "french",
  "german",
  "japanese",
  "korean",
  "polish",
  "russian",
  "simp_chinese",
  "spanish",
  "turkish",
];
```

##

You can use it in every paradox games. If you spot any problem, report to me
