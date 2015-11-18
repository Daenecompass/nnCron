                                 nnCron
                                 ~~~~~~

nnCron on vahva ohjelmoitava suoritin, muistutin ja
automaatiopalikka eli lyhyesti turbo-windows-cron. Se on
ohjelmoitavissa omalla (Forth- yhteensopivalla) skriptikielell�,
tukee my�s VBScript/JScript:i� sek� vahvoja korvauslausekkeita
(regular expressions). Sen toimintoja voi laajentaa
plugin-palikoilla.

nnCron osaa lukea Unix crontab tiedostoformaattia. T�m�
tekstitiedosto hallinnoi sen toimintoja. Vaihtoehtoisesti voi my�s
k�ytt�� graaffista k�ytt�liittym�� tapahtumien
lis��miseen/poistoon/muokkaamiseen.

Perus cron toimintojen (ajallinen komentojen suoritus, muistutus ja
dokumenttien avaus), nnCron osaa my�s:
- k�ynnist�� ohjemia palveluina,
- k�ynnist�� komennot eri k�ytt�jin�,
- sammuuttaa/talvehtia tietokone tai nukuttaa tietokone m��r�ttyyn
  kellonaikaan,
- "her�tt��" tietokone tiettyyn aikaan suorittamaan komento
- n�ytt��/piilottaa/sulkea/pienent��/suurentaan sek� piilottaa
  ikkunoita alapalkkiin j�rjestelm�kaukaloon,
- luo tiedotus-ikkunaan viestiin tai kijoittaa lokitiedostoon,
- toimii v�limuistin, tiedostojen sek� rekisterin kanssa,
- emuloi/j�ljittelee n�pp�in sek� hiiri toimintoja,
- aloittaa/katkaista modeemi-yhteydet,
- soittaa eri pituusia ja taajuuksia tietokoneen omalla
  kova�insell�,
- soittaa audio tiedostoja,
- tarkistaa j�rjestelm�n kellon,
- m��rittelee eri prosessi-prioriteetej�,
- keskeytt�� ohjelmia ja prosesseja,
- k�ynnisty� itsest��n uudelleen tarvittaessa.
- seurata tiedostoja, lippuja, ikkunointa, prosesseja, hiiren
  liikkeit�, jouto-aikaa, n�pp�in oikoteit�, Internet yhteysi�,
  levykkeiden ja romppujen lis�yst�/poistoja, l�hiverkkoyhteyksi�
  (ping), levyjen k�ytt�astetta, jne...

nnCron on luotettava, helppok�ytt�inen v�h�n-muistia k�ytt�v�
sovellus. Se on nopea ja tarjoaa runsaasti hy�dyllisi�
ominaisuuksia joita edelleenkehitell��n yhteisty�ss� nnCron
k�ytt�jien kanssa.

---------------------------------------
Rekister�inti
---------------------------------------
nnCron jakelu on toteutettu shareware periaatteella: Sen voi
imuroida/asentaa/ kokeilla 30 p�iv��, jonka j�lkeen se on
rekister�it�v� jos sit� haluaa edelleen k�ytt��.

Register�inti maksaa US$25:
    http://www.nncron.ru/register.shtml
Rekister�innin j�lkeen sinulle l�hetet��n s�hk�postilla
avain-tiedosto. Laita t�m� tiedosto nnCron hakemistoon ja k�ynnist�
nnCron uudelleen.

Jokainen joka suostuu k��nt�m��n kolme tiedostoa uudelle kielelle
(omalle �idinkielelle) my�nnet��n ilmainen lisenssi. Lis�tietoja:
http://www.nncron.ru/translation.shtml

Oppilaitosalennuksia voi tiedustella ohjelmoitsijalta: 
nemtsev@nncron.ru

---------------------------------------
Laitteistovaatimukset, asennus ja poisto: nnCron
---------------------------------------
  - IBM PC yhteensopiva tietokone
  - Intel Pentium processori tai parempi
  - Windows 95/98/ME/NT/2000/XP

Aloita nnCron asennus tuplakilkkaamalla asennustiedosto. Asennuksen
yhteydess� on m��ritelt�v� asennuskansio. Ohjelman poistaan
hallintapaneelin "Lis��/Poista ohjelmia" ikoonista.
asennushakemistossa on tiedosto 'nncron.ini' jossa on kaikki ohjeman
asetukset.

---------------------------------------
nnCron k�ynnistys/lopetus
---------------------------------------

Helpoin tapa k�sin k�ynnist�� nnCron on 'startnncron.bat' ohjelmalla
asennushakemistosta. Tiedosto pys�ytet��n 'stopnncron.bat'
komennolla tai klikkaamalla oikealla hiirell� nnCron ikonia ja
valitsemalla 'Exit' eli 'Lopetus' valikosta.

Asennuksen yhteydess� nnCron ohjelmarym��n luodaan my�s oikopolut
n�ille bat-tiedostoille 'Start' eli 'Aloitus' painikkeseen.  You can
find shortcuts to above mentioned bat-files in nnCron program group,
located in Windows 'Start menu'.

---------------------------------------
nnCron dokumentit ja k�ytt�j�tuki
---------------------------------------

T�ydellinen enlanninkielinen windows-helppi tiedosto ('help.chm')
luodaan asennuksen yhteydess�. T�st� tiedostosta l�ytyy nopeasti
apua ja esimerrkeij� k�yt�st�.

Lis�ksi, jos helppi tiedosto ei riit�, kannattaa liitty�
postituslistaan (nncron-subscribe@nncron.ru).
josta voi hakea/kysy� lis�neuvoja (Englanninkielinen lista).
Virallinen s�hk�postituki toimii osoitteessa support@nncron.ru
Ohjelmoitsijalle voi my�s antaa palautetta tai l�hett�� virheraportteja
osoitteeseen nemtsev@nncron.ru

---------------------------------------
Linkkej�:
---------------------------------------

nnCron kotisivu:
    http://www.nncron.ru/
nnCron dokumentit:
    http://www.nncron.ru/download/help.zip (English language)
    http://www.nncron.ru/download/help_ru.zip (Russian language)
    http://www.nncron.ru/download/faq.zip (English language)
    http://www.nncron.ru/download/faq_ru.zip (Russian language)

nnCron dokumentit verkossa:
    http://www.nncron.ru/help/help.htm (English language)
    http://www.nncron.ru/help/help_ru.htm (Russian language)

---------------------------------------
Copyrights/Tekij�noikeudet:
---------------------------------------
Copyright (C) 2000-2002 nnSoft. E-mail: nemtsev@nncron.ru
    http://www.nncron.ru/
SP-Forth 3.75 Copyright (C) 1992-2000 A.Cherezov 
    http://www.forth.org.ru/
RegExp 4.0 (C) Cail Lomecb <ruiv@uic.nnov.ru> 
    http://www.uic.nnov.ru/~ruiv/
