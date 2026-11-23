# 02. Domieszki i poziom Fermiego

## Typy półprzewodników
- Samoistny: idealnie czysty, bez domieszek i defektów. Nośniki powstają przez generację par elektron-dziura.
- W samoistnym: n = p = ni, gdzie n - koncentracja elektronów, p - dziur, ni - koncentracja samoistna.
- Domieszkowany: celowo zawiera atomy innego pierwiastka.

## Półprzewodnik typu n
- Uzyskuje się przez domieszkowanie donorowe (pierwiastki V grupy, np. fosfor P).
- Donor ma 5 elektronów walencyjnych: 4 tworzą wiązania z Si, piąty może łatwo się uwolnić.
- Nośniki większościowe: elektrony; mniejszościowe: dziury.
- Po oddaniu elektronu pozostaje nieruchomy dodatni jon donora.
- Energia jonizacji P w Si: Wj = 0,044 eV.
- Poziom donorowy Wd leży blisko pasma przewodnictwa.

## Półprzewodnik typu p
- Uzyskuje się przez domieszkowanie akceptorowe (pierwiastki III grupy, np. bor B).
- Akceptor ma 3 elektrony walencyjne; przyjęcie elektronu z sąsiedniego wiązania pozostawia dziurę.
- Nośniki większościowe: dziury; mniejszościowe: elektrony.
- Po przyjęciu elektronu pozostaje nieruchomy ujemny jon akceptora.
- Energia jonizacji B w Si: Wj = 0,045 eV.
- Poziom akceptorowy Wa leży blisko pasma walencyjnego.
- Energie jonizacji domieszek są o wiele mniejsze niż Wg Si, dlatego łatwo wytwarzają nośniki.

## Poziom Fermiego
- WF: energia, przy której prawdopodobieństwo zajęcia stanu elektronem wynosi 0,5 przy T > 0 K.
- Samoistny: WF w przybliżeniu w środku pasma zabronionego.
- Typ n: WF bliżej pasma przewodnictwa.
- Typ p: WF bliżej pasma walencyjnego.
- To poziom energii, nie miejsce w przestrzeni.

## Rozkłady statystyczne
- Stała Boltzmanna: k = 1,38*10^-23 J/K = 8,62*10^-5 eV/K.
- Boltzmann (czynnik wykładniczy z wykładu): f(W) = exp(-W/(k*T)).
- Fermi-Dirac: fn(W) = 1/[1+exp((W-WF)/(k*T))].
- Dziury: fp(W) = 1 - fn(W).
- Przy W=WF: fn=0,5.
- T oznacza temperaturę w kelwinach.

## Gęstość stanów i koncentracje
- N(W): gęstość stanów energetycznych.
- Nc: efektywna gęstość stanów pasma przewodnictwa.
- Nv: efektywna gęstość stanów pasma walencyjnego.
- W uproszczeniu wykładowym: n = Nc*fn(Wc), p = Nv*fp(Wv).
- Dokładniej: n = całka od Wc do nieskończoności z N(W)*fn(W) dW.
- Dziury: p = całka od minus nieskończoności do Wv z N(W)*fp(W) dW.
- Nc oraz Nv są proporcjonalne do T^(3/2).
- Si: Nc=2,8*10^25/m^3; Nv=1,04*10^25/m^3.
- Ge: Nc=1,04*10^25/m^3; Nv=6,0*10^24/m^3.
- GaAs: Nc=4,7*10^23/m^3; Nv=7,0*10^24/m^3.
- Na jednym slajdzie są błędne granice całki dla dziur; powyżej podano fizycznie właściwe.

## Kluczowe porównanie
- Donor = V grupa = n = elektrony = jon +.
- Akceptor = III grupa = p = dziury = jon -.
- Półprzewodnik typu n i p jako całość pozostaje elektrycznie obojętny.
