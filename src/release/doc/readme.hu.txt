                                 nnCron
                                 ~~~~~~

Az nncron egy fejlett, nagy tud�s� feladat�temez�, eml�keztet�,
automatiz�l� �s szkript-t�mogat�ssal rendelkez� eszk�z. Egy saj�t
(Forth-kompatibilis) be�p�tett szkriptnyelvvel rendelkezik, ezenk�v�l
lehet�v� teszi a VBScript/JScript haszn�lat�t, csak�gy mint a regul�ris
kifejez�sek�t, valamint tov�bb b�v�thet� pluginok haszn�lat�val.

Az nncron a standard cron t�blaform�tumot haszn�lja (Unix), �s k�nnyen
szerkeszthet� sz�veges crontab file-okkal vez�relhet�. A grafikus fel�letet
el�nyben r�szes�t�k sz�m�ra tartalmaz egy grafikus shell-t, amely
lehet�s�get ad feladatok hozz�ad�s�ra, szerkeszt�s�re, t�rl�s�re �s
futtat�s�ra, valamint eml�keztet�k hozz�ad�s�ra, a program be�ll�t�s�ra.

A szokv�nyos �temez� �s napt�ri funkci�k mellett (programind�t�s,
eml�keztet� �zenetek megjelen�t�se �s dokumentumok megnyit�sa megadott
id�pontban) az nncron sok m�s hasznos k�pess�ggel is rendelkezik:

  - k�pes programokat rendszerszolg�ltat�sk�nt futtatni
  - megadott felhaszn�l� nev�ben futtatni taszkokat
  - kezelni �s �jraind�tani elmulasztott taszkokat �s eml�keztet�ket
  - le�ll�tani �s hibern�lni a sz�m�t�g�pet, vagy "alv�" �zemm�dba 
    helyezni megadott id�pontban
  - "fel�breszteni" a g�pet egy feladat elv�gz�se c�lj�b�l
  - megjelen�teni, elrejteni, bez�rni, kil�ni, kicsiny�teni, nagy�tani
    megadott ablakokat a t�lc�ra �s ikonk�nt az �ra mell�
  - �zenetek megjelen�t�s�re a k�perny�n �s ezeket napl�f�jlban r�gz�teni
  - kezeli a v�g�lapot, f�jlokat �s a regisztr�ci�s adatb�zist
  - k�pes emul�lni billenty�zetr�l �s eg�rr�l �rkez� aktivit�st
  - t�rcs�z �s vonalat bont
  - hangjelz�seket tud adni a rendszer hangsz�r�n kereszt�l, ennek
    frekvenci�j�t �s hossz�t tetsz�s szerint megadhatjuk
  - hangf�jlokat tud lej�tszani
  - a rendszerid�t szinkroniz�lja
  - megadott szint� priorit�sokat k�pes rendelni folyamatokhoz
  - b�rmely folyamatot k�pes "kil�ni"
  - automatikusan �rjaind�t v�gzetes hib�k eset�n
  - k�pes file-ok, �llapotjelz�k, ablakok, folyamatok, eg�raktivit�sok
    nyomonk�vet�s�re, billenty�zet figyel�sre, �resj�rati id�tartamok
    figyel�s�re, billenyt�zetparancsokra, lemezcsatol�sra, hosztok 
    figyel�s�re a h�l�zatban (ping), szabad hely figyel�s�re a lemezen,
    stb. stb.

Az nncron megb�zhat�, kicsi �s k�nnyen haszn�lhat� alkalmaz�s. B�mulatos
gyorsas�ggal fut, �s hasznos szolg�ltat�sok sokas�g�t ny�jtja, amelyeket
m�s nncron felhaszn�l�kkal szoros egy�ttm�k�d�sben fejlesztettek ki.

---------------------------------------
Regisztr�ci�
---------------------------------------
Az nncron terjeszt�se shareware programk�nt t�rt�nik: ingyenesen
let�ltheted �s kibr�b�lhatod 30 napig. Ha �gy d�ntesz, hogy szeretn�d a 30
napos id�szak ut�n is haszn�lni, akkor regisztr�lnod kell.

Az nncron regisztr�l�sa csak 25 doll�r:
    http://www.nncron.ru/register.shtml
A regisztr�ci� ut�n kapsz majd egy e-mail-t, amely tartalmazza a saj�t
kulcsodat.
Ezt kell elhelyezned az nncron k�nyvt�r�ban, majd �jraind�tani az nncron-t.

Ingyenes a regisztr�ci�, ha leford�tod az nncron nyelvi f�jlokat
a saj�t nyelvedre, �s folyamatosan karban tartod �ket. A r�szletek�rt
l�togass el a http://www.nncron.ru/translation.shtml oldalra.

Oktat�si kedvezm�ny eset�n k�rlek, vedd fel a kapcsolatot a szerz�vel :
nemtsev@nncron.ru

-------------------------------------------------------
Rendszersz�ks�glet, install�l�s/elt�vol�t�s
--------------------------------------------------------
  - IBM PC vagy kopmatibilis
  - Intel Pentium processzor vagy nagyobb
  - Windows 95/98/ME/NT/2000/XP

Az nncron install�ci�j�hoz kattints dupl�n az eg�r bal gombj�val a
disztrib�ci� f�jlj�n. Az install�l�s folyam�n meg kell majd adnod a
telep�t�s c�lmapp�j�t.  Elt�vol�t�s�hoz haszn�ld a "Programok hozz�ad�sa �s
elt�vol�t�sa" ikont a Vez�rl�pultban.
A program be�ll�t�sai megmaradnak az "nncron.ini" f�jlban.

---------------------------------------
Az nnCron ind�t�sa �s le�ll�t�sa
---------------------------------------
Az nnCron szolg�ltat�s manu�lis elind�t�s�nak legmegfelel�bb m�dja a
'startnncron.bat' �llom�ny futtat�sa a feltelep�tett program k�nyvt�r�ban.
A mem�ri�b�l t�rt�n� elt�vol�t�shoz a 'stopnncron.bat' kell futtatnunk,
vagy az 'Exit' men�pontot is v�laszhatjuk az nncron kontext men�j�ben
(el�rhet� az �ra melleti nnCron ikonon jobb gombbal kattintva).

A fent eml�tett bat-f�jlokra mutat� parancsikon az nnCron programcsoportban
tal�lhat�, a Windows 'Start men�j�ben'.

---------------------------------------
nnCron dokument�ci�, felhaszn�l� t�mogat�s
---------------------------------------
A teljes angol nyelv� nnCron dokument�ci� ('help.chm') megtal�lhat� az
nnCron disztrib�ci�ban. Az nnCron orosz nyelv� dokument�ci�ja k�l�n,
ingyenesen let�lthet�.  Er�sen aj�nlott az nnCron dokument�ci�
�ttanulm�nyoz�sa annak �rdek�ben, hogy a felmer�l� k�rd�sekre �s
probl�m�kra gyors v�laszokat �s megold�sokat tal�ljunk.

Ha k�rd�se van az nnCron haszn�lat�val kapcsolatban, �s a v�lasz nem
tal�lhat� meg a dokument�ci�ban, k�rem iratkozzon fel (�s tegye fel
k�rd�s�t) az angol nyelv� nnCron levelez� list�ra. A feliratkoz�shoz
k�ldj�n egy levelet a k�vetkez� c�mre:
nncron-subscribe@nncron.ru. 

Az nnCron t�mogat�si e-mail c�me: support@nncron.ru

A szoftverrel kapcsolatos v�lem�ny�t �s a hibajelens�geket elk�ldheti a
szerz� c�m�re: nemtsev@nncron.ru


---------------------------------------
Linkek
---------------------------------------
nnCron honlap:
    http://www.nncron.ru/
nnCron dokument�ci�:
    http://www.nncron.ru/download/help.zip (English language)
    http://www.nncron.ru/download/help_ru.zip (Russian language)
    http://www.nncron.ru/download/faq.zip (English language)
    http://www.nncron.ru/download/faq_ru.zip (Russian language)
nnCron online dokument�ci�:
    http://www.nncron.ru/help/help.htm (English language)
    http://www.nncron.ru/help/help_ru.htm (Russian language)
nnCron ford�t�sok:
    http://www.nncron.ru/translation.shtml

---------------------------------------
Copyrights
---------------------------------------
Copyright (C) 2000-2002 nnSoft. E-mail: nemtsev@nncron.ru
    http://www.nncron.ru/
SP-Forth 3.75 Copyright (C) 1992-2000 A.Cherezov 
    http://www.forth.org.ru/
RegExp 4.0 (C) Cail Lomecb <ruiv@uic.nnov.ru> 
    http://www.uic.nnov.ru/~ruiv/
