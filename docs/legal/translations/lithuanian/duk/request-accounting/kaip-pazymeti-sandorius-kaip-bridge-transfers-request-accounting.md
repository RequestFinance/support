# Kaip pažymėti sandorius kaip "Bridge Transfers" "Request Accounting"

### Kas yra "Bridge Transfers"? <a href="#h_01043425f0" id="h_01043425f0"></a>

\
"Bridge transfers" – tai pervedimai, kurie vyksta per kelis blokų grandinės tinklus, leidžiantys vartotojams perkelti žetonus ar turtą tarp skirtingų grandinių (pvz., iš Solana į Ethereum arba iš Ethereum į Polygon). Ši sąveika yra svarbi norint visapusiškai išnaudoti Web3 potencialą.

### Kodėl apskaitoje "Bridge Transfers" yra svarbūs <a href="#h_06faede727" id="h_06faede727"></a>

Anksčiau „Request Accounting“ "Bridge Transfers" traktavo kaip atskiras operacijas:

* Vienos grandinės transakcija buvo traktuojama kaip atskira
* Išsiuntimas į kitą grandinę buvo traktuojamas kaip atskiras

\
​Šiuo metodu apskaičiuojami realizuoti pelnai/nuostoliai.\
\
Įdiegus naują sistemą, susiję "Bridge transfers" yra tinkamai pripažįstami kaip vidiniai pervedimai, todėl išvengiama neteisingų apskaitos skaičiavimų, nes šių judėjimų realizuotas pelnas/nuostolis nėra skaičiuojamas.

### Kaip pažymėti transakcijas kaip "Bridge Transfers" <a href="#h_3c62146655" id="h_3c62146655"></a>

"Bridge transfer" žymėjimo funkcija yra prieinama tik išeinančioms transakcijoms:

1. Suraskite išeinančią transakciją, kurią norit pažymėti kaip "Bridge transfer"
2. Spustelėkite tris taškelius šalia transakcijos
3.  Pažymėkite "Mark as Bridge"

    [![](https://downloads.intercomcdn.com/i/o/mmdbekc3/1510067954/c609875f9ad5faad9e68e052ec32/image.png?expires=1751479200\&signature=d24133a41ac9343880b94dadd8e0b70d5918d59c6ed942fe1b300d171ecdcc87\&req=dSUmFsl4mohaXfMW3nq%2Bgb4NyMsC4m6R6AO1GYbvZM1ZI9UZ7NRygxBoXxFg%0A1a6RCTrdr66lpoQiOy%2F9kz3WdmE%3D%0A)](https://downloads.intercomcdn.com/i/o/mmdbekc3/1510067954/c609875f9ad5faad9e68e052ec32/image.png?expires=1751479200\&signature=d24133a41ac9343880b94dadd8e0b70d5918d59c6ed942fe1b300d171ecdcc87\&req=dSUmFsl4mohaXfMW3nq%2Bgb4NyMsC4m6R6AO1GYbvZM1ZI9UZ7NRygxBoXxFg%0A1a6RCTrdr66lpoQiOy%2F9kz3WdmE%3D%0A)
4. Atsidariusiame lange:
   * Patvirtinkite transkacijos detales (transakcijos adresą ir tradicinės valiutos detales)
   * Pasirinkite tinklą, į kurį bus išsiūstos lėšos
   * Sistema automatiškai suras atitinkančias įplaukų transakcijas
   * Jei transakcijos nėra rastos automatiškai, rankiniu būdu įkelkite transakcijų adresus
5.  Patvirtinkit išplaukų ir įplaukų transakcijas

    [![](https://downloads.intercomcdn.com/i/o/mmdbekc3/1510068713/ead9cc50dcf0131bc4c9f228f93f/image.png?expires=1751479200\&signature=2c71bbc7fcea61d4ce5358d4c4d0056dd8bf7e9c5b04927b8f177777b0ef83ea\&req=dSUmFsl4lYZeWvMW3nq%2Bgb67ScJYS9MKKruLtIEWKq2GvzmGOH3YhWFA4SX7%0A6tdsrjXzmwbkKwFboCWN81GQfk0%3D%0A)](https://downloads.intercomcdn.com/i/o/mmdbekc3/1510068713/ead9cc50dcf0131bc4c9f228f93f/image.png?expires=1751479200\&signature=2c71bbc7fcea61d4ce5358d4c4d0056dd8bf7e9c5b04927b8f177777b0ef83ea\&req=dSUmFsl4lYZeWvMW3nq%2Bgb67ScJYS9MKKruLtIEWKq2GvzmGOH3YhWFA4SX7%0A6tdsrjXzmwbkKwFboCWN81GQfk0%3D%0A)
6. Susiekite transakcijas

Svarbūs pastebėjimai:

* Kai tik transakcijos yra pažymimos kaip "Bridge transfers", jos tampa vidinėmis transakcijomis buhalterijos sistemoje
* Tai užtikrina tikslią finansinę atskaitomybę be netinkamų pelno/nuostolio skaičiavimų.

Netrukus: automatinis "Bridge transactions" atpažinimas, kad nereikėtų rankiniu būdu sujungti.
