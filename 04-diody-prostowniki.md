# 04. Diody, prostowniki i filtry

## Dioda półprzewodnikowa
- Dwukońcówkowy element z półprzewodnikiem, kontaktami, doprowadzeniami i obudową.
- Anoda A zwykłej diody p-n = strona p; katoda K = strona n.
- W przewodzeniu prąd umowny płynie od A do K.
- Według materiału: Si, Ge, III-V (np. GaAs).
- Według konstrukcji: ostrzowe, mesa, planarne, epiplanarne.
- Według złącza: p-n, m-s (Schottky), p-i-n, p+-n, p-n+, n+-n, heterozłącza.
- i w p-i-n = warstwa samoistna; plus przy p/n = silne domieszkowanie.
- Według zastosowania: prostownicze, uniwersalne, impulsowe, stabilitrony, pojemnościowe, tunelowe, fotodiody, LED, mikrofalowe.

## Charakterystyka i parametry diody
- Idealny model z wykładu: I = IR*[exp(U/phiT)-1].
- phiT = k*T/q; przy 293 K ok. 25 mV.
- q = 1,602*10^-19 C; k = 1,38*10^-23 J/K.
- W przewodzeniu I gwałtownie rośnie; przy zaporze mały I aż do przebicia.
- UF: napięcie przewodzenia przy określonym IF.
- IF: prąd przewodzenia. IR: prąd wsteczny.
- I0: maksymalny dopuszczalny średni prąd wyprostowany.
- IFM: graniczny prąd przewodzenia (oznaczenie wykładowe).
- URWM: dopuszczalne szczytowe napięcie wsteczne pracy.
- Pad: maksymalna moc strat/moc admisyjna; P=U*I.
- Rezystancja statyczna: R=U/I w punkcie pracy.
- Rezystancja dynamiczna: r=dU/dI, w przybliżeniu deltaU/deltaI dla małych zmian.
- Przykład: U=0,7 V, I=20 mA: R=35 omów. deltaU=0,02 V, deltaI=10 mA: r=2 omy.

## Prostownik: definicja
- Układ zmienia napięcie przemienne w jednokierunkowe, zwykle jeszcze pulsujące.
- Wejście: eg(t)=Um*sin(omega*t). Dla sinusoidy: Um=sqrt(2)*Usk.
- Ro: rezystancja odbiornika; RF: rezystancja diody przewodzącej; UD: jej spadek napięcia.
- Uom: szczyt napięcia na wyjściu; Uośr: średnie napięcie na wyjściu.

## Jednopołówkowy
- Jedna dioda. Dodatnia półfala przechodzi, ujemna jest blokowana.
- Im = Um/(RF+Ro).
- Uom = Um-UD.
- Uośr = Uom/pi = ok. 0,318*Um (gdy pomijamy straty).
- Uośr = ok. 0,45*Usk (idealnie).
- Sprawność NAPIĘCIOWA wg wykładu: etaU=1/pi=31,8%.
- Tętnienia zasilania 50 Hz mają częstość 50 Hz.

## Dwupołówkowy z odczepem
- Transformator z odczepem środkowym i dwie diody D1,D2.
- W dodatniej półfali przewodzi D1, w ujemnej D2.
- Napięcia połówek uzwojenia: U2'(t)=-U2''(t).
- Im = Um/(RF+Ro).
- Uom = Um-UD (Um to amplituda jednej połowy wtórnego).
- Uośr = 2*Uom/pi = ok. 0,636*Um.
- Uośr = ok. 0,9*Usk (idealnie).
- Sprawność napięciowa: 2/pi=63,6%.
- Uwaga: klasyczny układ z odczepem ma maks. napięcie wsteczne na nieprzewodzącej diodzie około 2*Um, jeśli Um oznacza szczyt jednej połówki.

## Mostek Graetza
- 4 diody. Zawsze jednocześnie przewodzą 2.
- Na slajdzie: dodatnia półfala D1 i D2; ujemna D4 i D3.
- Im = Um/(2*RF+Ro).
- Uom = Um-2*UD.
- Uośr = 2*Uom/pi, w idealnym modelu 0,636*Um.
- Sprawność napięciowa (definicja wykładowa): 63,6%.
- Dla zasilania 50 Hz tętnienia: 100 Hz.

## Tętnienia i sprawność
- Slajdy: etaU = Uośr/Um; to stosunek napięć, NIE sprawność energetyczna.
- Slajdy: t = deltaUo/Uośr, gdzie dla nieodfiltrowanego przebiegu deltaUo=Uom.
- Dlatego t jednopołówkowego = pi = 3,14.
- t dwupołówkowego = pi/2 = 1,57.
- W innych podręcznikach jest odmienna definicja współczynnika tętnień RMS.
- Pytanie ze starego kolokwium: czy mostek ma większą sprawność napięciową niż układ dwóch diod? NIE: teoretycznie oba mają 63,6%.

## Filtr pojemnościowy
- Kondensator C równolegle do obciążenia Ro.
1. Przy narastaniu napięcia dioda przewodzi, C ładuje się w pobliżu szczytu.
2. Gdy napięcie źródła maleje, dioda się zamyka.
3. C rozładowuje się przez Ro, podtrzymując napięcie.
4. Przy kolejnym szczycie C jest doładowywany.
- tl = czas ładowania; tr = czas rozładowania.
- Jednopołówkowy: ładowanie raz na okres; dwupołówkowy: dwa razy na okres.
- Większe C = mniejsze tętnienia; większy prąd obciążenia = większe tętnienia.
- Dodatkowy wzór (poza prezentacją): deltaU~Io/(ft*C), ft = częstotliwość tętnień.
- Prostownik wyprostowuje przebieg; kondensator go wygładza, ale nie usuwa tętnień idealnie.
