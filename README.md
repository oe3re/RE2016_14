# RE2016_14
Promena formata fajla- Projekat 14

M3U format plejliste ima format:
#EXTM3U
#EXTINF:213,Evanescence - Breathe No More
E:\Muzika\Evanescence Discography\Evanescence - Anywhere But Home\Evanescence -
Breathe No More.mp3
#EXTINF:283,Evanescence - Bring Me To Life
E:\Muzika\Evanescence Discography\Evanescence - Anywhere But Home\Evanescence -
Bring Me To Life.mp3,
gde je #EXTM3U ključna reč kojom počinje plejlista. Zatim slede redovi sa numerama koje počinju
ključnom re£i #EXTINF:, a potom sledi podatak o trajanju u sekundama i naziv numere. U
sledećem redu je data putanja do fajla numere.
PLS format plejliste ima format:
[playlist]
NumberOfEntries=50
File1=nesto-nesto.mp3
Title1=nesto- nesto.mp3
Length1=1
File2=E:\Muzika\Dream Theater\Falling Into Infinity\01_New Millennium.mp3
Title2=Dream Theater - New Millennium
Length2=500,
gde je [playlist] ključna reč kojom počinje plejlista, a drugi red je broj numera u plejlisti.
Zatim slede redovi sa numerama koje su date u tri reda, gde prvi predstavlja putanju do fajla,
drugi ime numere, a treći trajanje u sekunadama.
U folderu Plejlista su dati primeri plejliste u oba formata.
-----------------------------------------------------------------------------------------------------------------

Napisati program koji prevodi ulaznu M3U plejlistu u PLS plejlistu. Potrebno je da se po pokretanju
programa traži ime plejliste i da se formira plejlista drugog formata sa istim imenom, ali
drugom ekstenzijom.
