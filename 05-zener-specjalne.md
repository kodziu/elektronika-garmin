# 05. Zener, warikap, Schottky, LED i foto

## Dioda Zenera (stabilitron)
- Przystosowana do pracy w obszarze przebicia WSTECZNEGO.
- W przewodzeniu działa jak zwykła dioda; po osiągnięciu -UZ prąd wsteczny szybko rośnie, a napięcie pozostaje w przybliżeniu stałe.
- W wykładzie napięcie stabilizacji często definiowane przy około 10% maksymalnego prądu stabilizacji.
- Parametry: UF, IF, UR, IR, UZ, IFM, IZmax, Pad.
- IZmax ~ Pad/UZ (ograniczenie mocą).
- Rezystancja statyczna RZ=UZ/IZ.
- Rezystancja dynamiczna rZ=deltaUZ/deltaIZ.
- Małe rZ oznacza lepszą stabilizację przy zmianach prądu.
- Zener i przebicie lawinowe mogą być odwracalne, jeśli nie przekroczymy limitów mocy.

## Stabilizator Zenera
- Rezystor R szeregowo z wejściem, Zener zaporowo równolegle do wyjścia.
- Rezystor ogranicza prąd i przejmuje część zmian napięcia zasilania.
- Uwy ~ UZ w zakresie stabilizacji.
- Bez obciążenia: IZ=(Uwe-UZ)/R.
- Z obciążeniem: IR=IZ+Io.
- Dla dobrej stabilizacji: deltaUwy << deltaUwe.
- Na slajdzie jest odwrotna nierówność (błąd slajdu).
- Punkt pracy: przecięcie charakterystyki diody z prostą obciążenia.
- Ograniczenia: minimalny prąd stabilizacji, IZmax oraz dopuszczalna moc Pad.

## Dioda pojemnościowa
- Złącze p-n w polaryzacji ZAPOROWEJ działa jak kondensator sterowany napięciem.
- p i n = okładki; warstwa zaporowa = dielektryk.
- Gdy UR rośnie, szerokość warstwy zaporowej rośnie i Cj maleje.
- Cmax przy UR bliskim 0; Cmin przy UR bliskim URmax.
- Współczynnik zmian pojemności Kc=Cmax/Cmin.
- Ważne parametry: Cj przy ustalonym napięciu i częstotliwości, IR przy zadanym UR.
- Warikap: przestrajanie obwodów rezonansowych napięciem.
- Waraktor: zmienna reaktancja w układach parametrycznych.
- Dodatkowy wzór rezonansowy: f0=1/[2*pi*sqrt(L*C)].

## Dioda Schottky'ego
- Złącze metal-półprzewodnik m-s (nie klasyczne p-n).
- Na slajdzie metal: złoto, srebro, platyna; domieszkowany półprzewodnik typu n.
- Transport głównie przez nośniki większościowe; brak istotnego magazynowania mniejszościowych.
- Bardzo krótki czas przełączania.
- Mniejszy spadek przewodzenia, na wykresie około 0,4 V (Si p-n typowo około 0,7 V).
- Szybkie prostowniki i układy przełączające.

## LED - dioda elektroluminescencyjna
- Pracuje w kierunku PRZEWODZENIA: A plus, K minus.
- Elektrony n przechodzą do p, rekombinują z dziurami, uwalniają fotony (elektroluminescencja).
- Zmiana energii elektrycznej w świetlną/podczerwoną.
- Barwa zależy od materiału i struktury energetycznej.
- GaAs = podczerwień IR.
- GaP = czerwona, zielona, żółta.
- GaAsP = czerwona, pomarańczowa, żółta.
- GaN = niebieska.
- Zastosowania: wskaźniki, wyświetlacze, 7-segmentowe, nadajniki optyczne, sprzężenia optyczne.

## Fotodioda
- W omawianym trybie pracuje przy polaryzacji ZAPOROWEJ.
- Fotony generują pary elektron-dziura; pole w warstwie zaporowej je rozdziela.
- Przy większym oświetleniu zwiększa się moduł prądu wstecznego.
- Prąd ciemny = niewielki prąd wsteczny bez oświetlenia, związany m.in. z generacją termiczną.
- Na charakterystyce: Pe1<Pe2<Pe3<Pe4; przy większym Pe większy moduł IR.
- Budowa ze slajdu: Si z obszarami p+, n, n+, warstwa SiO2, metalowe kontakty i okno optyczne.
- Zastosowania: zdalne sterowanie, optyczne czujniki, pomiary odległości, wymiarów, stężeń, drgań, naprężeń, odbiorniki optyczne.
- LED: energia elektryczna -> promieniowanie (rekombinacja).
- Fotodioda: promieniowanie -> sygnał elektryczny (generacja).
