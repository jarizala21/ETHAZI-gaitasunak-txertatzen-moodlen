\# Moodle Autoebaluazioa — Konpetentzien tabla interaktiboa



Plantilla Moodle Database modulurako, ikasleen autoebaluazioa konpetentzien matrize batean egiteko. Ikasleak eta tutoreak gelaxka bakoitzean checkbox bat marka dezakete ("Lortuta") eta testua/lotura bat gehitu. Edizio guztiak automatikoki erregistratzen dira historikoan (nork eta noiz aldatu duen, zer markatu/desmarkatu duen eta zein gelaxkatan idatzi duen).



\## Funtzionalitateak



\- Konpetentzien tabla bisuala (G6, M1-M4) lorpen-adierazleekin

\- Checkbox bakoitzeko, gelaxka berde bihurtzen da markatzean

\- Testu-eremu bat gelaxka bakoitzaren barruan (oharrak, estekak...)

\- Edizio-historikoa automatikoa: erabiltzailea + data + aldaketak

\- Bi txantiloi: sarrera berria gehitzeko eta ikusteko



\## Instalazioa Moodlen



1\. Sortu \*\*Datu-base\*\* jarduera bat Moodle ikastaroan

2\. \*\*Eremuak\*\* atalean, sortu eremu hauek:

&#x20;  - 9 \*\*Hautamarkadun lauki\*\* (Checkbox): `chk\_A1`, `chk\_A2`, `chk\_A3`, `chk\_B1`, `chk\_B2`, `chk\_B3`, `chk\_C1`, `chk\_C2`, `chk\_D1`

&#x20;  - 9 \*\*Testu motza\*\* (Short text): `txt\_A1`, `txt\_A2`, `txt\_A3`, `txt\_B1`, `txt\_B2`, `txt\_B3`, `txt\_C1`, `txt\_C2`, `txt\_D1`

&#x20;  - 1 \*\*Testu motza\*\* historikoarentzat: `ultimo\_editor`

3\. \*\*Txantiloiak\*\* atalean:

&#x20;  - \*\*Sarrera gehitu\*\* txantiloian: itsatsi `plantilla-editar.html` edukia

&#x20;  - \*\*Sarrera bakarra\*\* txantiloian: itsatsi `plantilla-visualizar.html` edukia

4\. Garrantzitsua: itsatsi beti editorearen \*\*HTML iturburu\*\* moduan (`</>` botoia), ez ikusizko moduan



\## Pertsonalizazioa



\- Konpetentzien izenak eta deskribapenak HTMLan zuzenean alda daitezke

\- Koloreak `style="background:..."` atributuetan

\- Bereizlea `'\\\\n'` ordez `' ;; '` erabiltzen da Moodlek lerro-jauziak ezabatzen dituelako testu-eremu motzetan



\## Lizentzia



MIT — libreki erabili, aldatu eta partekatu.



\## Ekarpenak



Hobekuntzak, ohar edo arazoak: ireki \*issue\* bat edo bidali \*pull request\* bat.

