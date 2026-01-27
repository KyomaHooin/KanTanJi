---
name: Kanji Entry
about: Přidej nový požadavek na chybějící znak kanji
title: "[KANJI] "
labels: kanji
assignees: 'Aiosa'
---
# Kanji Request
Tento formulář slouží k zadání požadavku o vložení kanji do databáze.

### Kanji - Kontrola Korektnosti
Přidávám do databáze chybějící znak kanji. Rozumím tomu, že zadávání se striktně řídí 
[požadavky definovanými v syntaxi databáze](blob/main/DATA_INPUT.md), a to zejména:
 - furigana je vyplněna u všech záznamů po jednotlivých kanji vyjma `kanji` první hodnoty (například `禁＜きん＞止＜し＞`), s výjimkou nerozdělitelnosti (`＜大人＞＜おとな＞`)
 - onyomi, pokud existuje, zadáváme katakanou; kunyomi hiraganou
 - každé slovíčko obsahuje příkladovou větu
 - slovíčka jsou vhodně vybrána, obecně je dobré mít zhruba 5 slovíček (výjimky existují)
   - nechybí základní slovíčko, tedy pokud není definováno u jiného kanji v tom slově
   - neobsahuje nerelevantní či nepoužívaná slovíčka
 - nechybí labely
 - většina klíčů může (a někdy musí) být zadávána vícekrát (např. více labelů), výjimkou jsou ``kanji``, `tango`, `imi` - tyto mohou být pouze jednou
 - poznámky jsou zadávány klíčem ``備<び>考<こう>`` pro konzistentnost, pokud není důvod udělat jinak

## Zadávám Kanji [nahraď znakem]
Kanji lze vyplnit do tabulky níže, nebo tabulku nahradit přiloženým souborem (CSV, Excel..). 

|klíč|hodnota|klíč| hodnota       | klíč   | hodnota                      | klíč       | hodnota                         |
|-----|---|-------|---------------|--------|------------------------------|------------|---------------------------------|
|kanji| ○ | imi   | [uveď význam] | onyomi | [čtení nebo smaž i s klíčem] | kunyomi    | [čtení nebo smaž i s klíčem]    |
|kanji| ○ | tango | ○<○>○<○>      | imi    | [význam slovíčka]            | tsukaikata | [příkladová věta i s překladem] |
|kanji| ○ | tango | ○<○>○<○>      | imi    | [význam slovíčka]            | tsukaikata | [příkladová věta i s překladem] |
|kanji| ○ | tango | ○<○>○<○>      | imi    | [význam slovíčka]            | tsukaikata | [příkladová věta i s překladem] |
|kanji| ○ | tango | ○<○>○<○>      | imi    | [význam slovíčka]            | tsukaikata | [příkladová věta i s překladem] |