# Anytone_HAM_SLO

Znotraj repozitorija lahko najdete CSV datoteke, ki se jih lahko uporabi pri programiranju Anytone HAM radijskih postaj kot: 
- Anytone AT-D878UV PLUS
- AT-D578UV

Datoteke vsebujejo vse simplex FM/DMR kanale in VHF/UHF DMR repetitorje. DMR repetitorji so razdeljeni glede na statistične regije v sloveniji, FM repetitorji so razdeljeni zgolj glede na frekvenčno območje. Na seznamu UHF FM repetitorjev je potrebnega še nekaj dela. Možno je, da na seznamu ni vseh repetitorjev.
Za vse DMR repetitorje sta vpisana po 2 kanala. Eden za TS1, drugi za TS2.
Poleg kanalov je znotraj repozitorija tudi datoteka, ki vsebuje vse SLO TGje in nekaj globalnih.

## Nujno
**Za Import uporabite datoteke znotraj datoteke ZIP: UseThis.zip**

Razlog za to je GitHub, ki pretvori zaključke vrstic znotraj csv datotek iz CRLF(Windows način) v LF(Unix način). GitHub datotek znotraj zipa ne spremeni. CPS ob branju datotek s tipom zaključkov vrstic LF javi napako.


--------------------------------------------------------------------------------------------------

This repository holds csv files used for programming of Anytone HAM radio stations such as:
- Anytone AT-D878UV PLUS
- AT-D578UV

It has all of the simplex FM/DMR Channels and VHF/UHF FM/DMR Repeaters. DMR Repeaters are sorted by regions, FM Repeaters are sorted just by frequency band. 
UFH FM Repeaters channel list is not finished yet, there might be some repeaters missing.
For each DMR Repeater there are 2 channels. One for TS1, one for TS2.
There is also an file with all of Slovenian talk groups and some of the global ones.

## Important
**When importing into the CPS use the files inside the ZIP: UseThis.zip**

This is because GitHub converts csv files line endings from CRLF(Windows format) to LF(Unix Format). Github does not edit files inside the zip. CPS responds with an error when importing files with LF line endings.