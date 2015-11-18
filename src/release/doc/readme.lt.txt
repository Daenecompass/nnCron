                                 nnCron
                                 ~~~~~~

nnCron yra pa�angus galingas planuotojas, primin�jas, skript�
�rankis ir automatizatorius. nnCron turi savo (suderinam� su Forth)
skript� kalb�, leid�ia naudoti VBScript/JScript, taip pat paprastuosius
rei�kinius ir gali b�ti i�pl�stas intarpais.

nnCron supranta cron lentel�s format� (Unix) ir yra valdomas
lengvai redaguojamais crontab failais. Ta�iau tiems, kas teikia
pirmenyb� GVS aplinkai, programa turi grafin� s�saj�, kuria galima
�alinti, prid�ti, redaguoti u�duotis, nustatyti priminimus, keisti
programos nustatymus.

Be tradicini� planuotojo ypatybi� (program� paleidimas, priminim� rodymas
ir dokument� nurodytu laiku atidarymas),
nnCron taip pat gali:
  - vykdyti bet kuri� program� kaip servis�;
  - vykdyti u�duotis kito naudotojo paskyroje;
  - valdyti ir i� naujo vykdyti praleistas u�duotis ir priminimus
  - i�jungti ar i�saugoti (hibernate) kompiuter�, arba u�migdyti nurodytu laiku;
  - "pri�adinti" kompiuter� u�duoties vykdymui;
  - rodyti/sl�pti/u�daryti/naikinti/sutraukti/i�skleisti langus bei sl�pti nurodytus
    langus sistemin�je juostoje;
  - rodyti prane�imus ekrane ir i�saugoti juos � registro fail�;
  - dirbti su i�karp� krep�eliu, failais, sistemos registru;
  - emuliuoti klaviat�ros �vedim� ir pel�s aktyvum�;
  - skambinti ir nutraukti ry��;
  - naudoti sistemos garsiakalb� nurodyto ilgio ir da�nio pyps�jimams;
  - groti garso failus;
  - sinchronizuoti sistemos laik�;
  - procesui priskirti nurodyt� prioritet�;
  - nutraukti bet kur� vykdom� proces�;
  - automati�kai persikrauti po kritini� klaid�.
  - steb�ti failus, parametrus, langus, procesus, pel�s aktyvum�,
    bud�jimo periodus, spar�iuosius klavi�us, prisijungim�/atsijungim� nuo Interneto,
    disko �d�jim� � diskasuk�, kito kompiuterio buvim� tinkle (ping), 
    laisvos vietos diske kiek� ir t. t.

nnCron yra labai patikima, ma�a ir lengvai naudojama programa. Ji veikia
liepsnojan�iai greitai ir si�lo daugyb� nauding� ypatybi�, i�vystyt�
kartu su kitais nnCron naudotojais.

---------------------------------------
Registracija
---------------------------------------
nnCron yra platinamas kaip s�lyginai nemokama programa: j�s galite atsisi�sti
nemokamai ir vertinti j� 30 dien�. Jei nusprend�iate toliau naudoti nnCron
po 30 dien� vertinimo laikotarpio, tur�tum�te j� u�registruoti.

J�s galite u�registruoti nnCron tik u� $25:
    http://www.nncron.ru/register.shtml
Po registracijos j�s gausite savo nuosav� rakto fail� elektroniniu pa�tu.
�kelkite j� � nnCron katalog� ir perkraukite nnCron.

J�s galite gauti nemokam� nnCron registracij� i�versdami nnCron kalbos failus
� j�s� gimt�j� kalb� ir palaikydami juos naujais. Detalesn� informacij� rasite
http://www.nncron.ru/translation.shtml

Pra�au susisiekti su autoriumi d�l mokom�j� nuolaid�: nemtsev@nncron.ru

---------------------------------------
Sisteminiai reikalavimai, nnCron diegimas/�alinimas
---------------------------------------
  - IBM PC ar suderinamas
  - Intel Pentium procesorius ar geresnis
  - Windows 95/98/ME/NT/2000/XP

Nor�dami paleisti nnCron diegim�, dukart spustel�kite kairiuoju pel�s
klavi�u ant platinamo failo. Diegimo metu bus papra�yta parinkti
diegimo katalog�.
Nor�dami pa�alinti nnCron, naudokite 'Add or remove programs' esant� 'Control Panel'.
nnCron laiko savo nustatymus 'nncron.ini' faile.

---------------------------------------
nnCron paleidimas ir stabdymas
---------------------------------------
Patogiausias b�das rankiniu b�du paleisti nnCron servis� yra paleisti
'startnncron.bat' esant� nnCron prad�ios kataloge. Nor�dami i�jungti
nnCron, paleiskite 'stopnncron.bat' arba spauskite ant 'I�eiti' meniu
punkto nnCron meniu (pasiekiamo paspaudus de�in� pel�s klavi�� ant
nnCron piktogramos sistemin�je juostoje).

Nuorodas � anks�iau nurodytus bat failus rasite nnCron programos grup�je,
esan�ioje Windows 'Start menu'.

---------------------------------------
nnCron dokumentacija, naudotoj� palaikymas
---------------------------------------
Visa nnCron dokumentacija angl� kalba ('help.chm') yra platinama nnCron
platinimo faile. nnCron dokumentacija rus� kalba yra pasiekiama kaip
atskiras nemokamas atsisiuntimas. � bet kokius klausimus ar problemas,
galin�ias kilti naudojant nnCron, atsakymo ie�koti rekomenduojama
nnCron dokumentacijoje, platinamoje kartu su nnCron.

Jei i�kilo klausim� d�l nnCron naudojimo ir negalite rasti atsakym�
dokumentacijoje, pra�ome apsilankyti m�s� forumuose
(http://www.nncron.ru/forums/) ar prenumeruoti (bei klausti klausim�)
nnCron elektronin� konferencij�. Oficiali konferencijos kalba yra angl�.
Nor�dami u�siprenumeruoti, si�skite el. lai�k� �
nncron-subscribe@nncron.ru.
nnCron palaikymo el. pa�tas: support@nncron.ru
Nesivar�ykite ir si�skite komentarus ir klaid� prane�imus nnCron autoriui:
nemtsev@nncron.ru

---------------------------------------
Nuorodos
---------------------------------------
nnCron pradinis puslapis:
    http://www.nncron.ru/
nnCron dokumentacija:
    http://www.nncron.ru/download/help.zip (angl� kalba)
    http://www.nncron.ru/download/help_ru.zip (rus� kalba)
    http://www.nncron.ru/download/faq.zip (angl� kalba)
    http://www.nncron.ru/download/faq_ru.zip (rus� kalba)
nnCron dokumentacija Internete:
    http://www.nncron.ru/help/help.htm (angl� kalba)
    http://www.nncron.ru/help/help_ru.htm (rus� kalba)
nnCron forumai:
http://wwww.nncron.ru/forums/
nnCron vertimai:
    http://www.nncron.ru/translation.shtml

---------------------------------------
Autorin�s teis�s
---------------------------------------
Copyright (C) 2000-2002 nnSoft. E-mail: nemtsev@nncron.ru
    http://www.nncron.ru/
SP-Forth 3.75 Copyright (C) 1992-2000 A.Cherezov 
    http://www.forth.org.ru/
RegExp 4.0 (C) Cail Lomecb <ruiv@uic.nnov.ru> 
    http://www.uic.nnov.ru/~ruiv/
