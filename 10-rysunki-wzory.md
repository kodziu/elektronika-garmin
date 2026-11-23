# 10. Szybka powtórka: wzory i rysunki

## Najważniejsze liczby
- Si: bariera ok. 0,7 V; Wg=1,08 eV; 4 elektrony walencyjne.
- Ge: bariera ok. 0,3 V; Wg=0,68 eV; 4 elektrony walencyjne.
- Donor P w Si: energia jonizacji 0,044 eV.
- Akceptor B w Si: energia jonizacji 0,045 eV.
- Potencjał termiczny przy 293 K: ok. 25 mV.
- Schottky: na wykresie spadek ok. 0,4 V.
- Zener tunelowy: zwykle do 5 V; lawinowy: powyżej 7 V (orientacyjnie wg slajdów).
- Jednopołówkowy: sprawność napięciowa 31,8%; tętnienia z definicji slajdu pi.
- Dwupołówkowy: sprawność napięciowa 63,6%; tętnienia z definicji slajdu pi/2.

## Wzory
- Nmax = 2*n^2.
- Wg = Wc-Wv.
- n = p = ni (samoistny).
- fn(W) = 1/[1+exp((W-WF)/(k*T))].
- fp(W)=1-fn(W).
- phiT=k*T/q.
- I=IR*[exp(U/phiT)-1].
- R=U/I; r=dU/dI ~ deltaU/deltaI.
- Um=sqrt(2)*Usk.
- Prost. jednopołówkowy: Im=Um/(RF+Ro); Uom=Um-UD; Uośr=Uom/pi.
- Prost. dwupołówkowy z odczepem: Im=Um/(RF+Ro); Uom=Um-UD; Uośr=2*Uom/pi.
- Graetz: Im=Um/(2*RF+Ro); Uom=Um-2*UD; Uośr=2*Uom/pi.
- etaU jedno = 1/pi; etaU dwu = 2/pi (definicja napięciowa z wykładu).
- Moc: P=U*I; IZmax~Pad/UZ.
- Zener: RZ=UZ/IZ; rZ=deltaUZ/deltaIZ.
- Stabilizator bez obciążenia: IZ=(Uwe-UZ)/R, Uwy~UZ.
- Warikap: Kc=Cmax/Cmin; f0=1/[2*pi*sqrt(L*C)] (dodatkowy wzór).

## 7 rysunków do przećwiczenia
1. Dioda prostownicza I-U: prawa gałąź rośnie bardzo szybko w górę; lewa prawie pozioma pod osią aż do przebicia.
2. Dioda Zenera I-U: w zaporze przy -UZ gwałtowny wzrost wartości bezwzględnej prądu; oznacz UZ.
3. Jednopołówkowy U-t: dodatnie połówki sinusoidy, pomiędzy nimi U=0.
4. Dwupołówkowy + filtr C: napięcie dodatnie, periodyczne doładowania i łagodne opadanie między szczytami.
5. Symbol Zenera: A po stronie anody, K przy zagiętej kresce katody.
6. Dioda pojemnościowa Cj-UR: krzywa malejąca; Cmax blisko UR=0, Cmin blisko URmax.
7. Stabilizator Zenera: rezystor szeregowy z wejściem, dioda Zenera zaporowo równolegle do wyjścia.

## Najważniejsze rozróżnienia
- Generacja = elektron i dziura powstają; rekombinacja = zanikają.
- Donor V grupa = n = elektrony większościowe = jon dodatni.
- Akceptor III grupa = p = dziury większościowe = jon ujemny.
- Przewodzenie złącza: p+, n-, bariera maleje.
- Zapora złącza: p-, n+, bariera rośnie.
- Zener: wąska warstwa, tunelowanie; lawinowe: szeroka warstwa, zderzenia.
- Zwykła p-n: złącze p-n; Schottky: metal-półprzewodnik.
- LED: przewodzenie i emisja przez rekombinację.
- Fotodioda: zwykle zapora i generacja pod wpływem światła.
- Mostek i układ z odczepem: ta sama idealna sprawność NAPIĘCIOWA 63,6% wg wykładu.
- Poprawna nierówność stabilizacji: deltaUwy << deltaUwe (na slajdzie wpisano odwrotnie).
