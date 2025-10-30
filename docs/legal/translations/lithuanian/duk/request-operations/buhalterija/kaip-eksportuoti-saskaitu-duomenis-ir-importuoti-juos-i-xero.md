---
description: Sąskaitų duomenų importavimas į "Xero".
---

# Kaip eksportuoti sąskaitų duomenis ir importuoti juos į "Xero"?

Užklausa siūlo "Xero" optimizuotą CSV, kurį galite sukurti ir naudoti greitai importuodami sąskaitų duomenis į "Xero".

Norėdami importuoti kitus duomenis į "Xero", žr. šiuos šaltinius:

* [Sąskaitų duomenys](https://help.request.finance/en/articles/9479311-how-to-export-invoice-data-and-import-it-into-xero)
* Ar norėtumėte sinchronizuoti savo kriptovaliutų operacijas su "Xero"? Gaukite prieigą prie visiškai automatinio savo sandorių sinchronizavimo su "[Request Accounting"](https://www.request.finance/crypto-accounting).

## Kaip importuoti sąskaitas į "Xero"? <a href="#h_c9496bd355" id="h_c9496bd355"></a>

### Sąskaitų eksportavimas iš "Request Finance" <a href="#h_521283aed6" id="h_521283aed6"></a>

1. Prisijunkite prie "Request Finance"
2. Pereikite į [meniu Sąskaitos](https://app.request.finance/pay/bills)
3. Spustelėkite ant 3 taškelių "..." (žr. toliau pateiktą paveikslėlį)
4. Spustelėkite Atsisiųsti CSV
5. Pasirinkite Xero-optimized CSV
6. Spustelėkite Atsisiųsti
7. Atsisiuntę užpildykite kiekvienos sąskaitos stulpelį AccountCode. Šis stulpelis nurodo sąskaitos pavadinimą iš jūsų "Xero" nustatyto sąskaitų plano [čia](https://go.xero.com/GeneralLedger/ChartOfAccounts.aspx).
8. Jei jums tai taikoma: stulpelyje Valiuta pažymėkite, ar yra tradicinių valiutų, kurių nenaudojate "Xero", arba kriptovaliutų.
   * Prieš importuojant tradicines valiutas, jas reikia įtraukti į "Xero"
   * Kriptovaliutas reikia konvertuoti į tradicines valiutas, nes "Xero" jų neaptarnauja. Nepamirškite prireikus pakoreguoti ir sumų (stulpeliai UnitAmount ir TaxAmount).

[![](https://downloads.intercomcdn.com/i/o/995614822/105ba0f31da2964297ddb1fe/image.png?expires=1751479200\&signature=67e321c16e29bf1a675bb638f876e16e92484be78a0a67ec1dc0d006e238ed89\&req=fSkiEMh6lYNdFb4V1XW4gba0W3w%2FddkYHRVl8RnsSH4We1jwyARVxgo5ScEW%0AvSZs47hkZttCQUwrWZgAjABcdg%3D%3D%0A)](https://downloads.intercomcdn.com/i/o/995614822/105ba0f31da2964297ddb1fe/image.png?expires=1751479200\&signature=67e321c16e29bf1a675bb638f876e16e92484be78a0a67ec1dc0d006e238ed89\&req=fSkiEMh6lYNdFb4V1XW4gba0W3w%2FddkYHRVl8RnsSH4We1jwyARVxgo5ScEW%0AvSZs47hkZttCQUwrWZgAjABcdg%3D%3D%0A)

### &#x20;Sąskaitų CSV parengimas "Xero" <a href="#h_c20543061b" id="h_c20543061b"></a>

* Jei dar nepadaryta: iš Užklausos atsisiųstame CSV užpildykite stulpelį Account ( žr. 7 žingsnį pirmiau).
* Jei dar nepadaryta: į "Xero" įtraukite trūkstamas tradicines valiutas ir konvertuokite sumas į kriptovaliutas (žr. 8 žingsnį pirmiau).

### Sąskaitų CSV importavimas į "Xero" <a href="#h_e207c453e8" id="h_e207c453e8"></a>

1. Prisijunkite prie "Xero"
2. Spustelėkite [Verslas > Mokėtinos sąskaitos](https://go.xero.com/app/!4d1WC/bills/list/all)
3. Spustelėkite rodyklę šalia Naujos sąskaitos, tada pasirinkite Importuoti iš CSV
4. Vadovaukitės instrukcijomis, kad importuotumėte paruoštą CSV
   * Kai paklausiama _"Ar norite atnaujinti kontaktinio adreso duomenis?",_ pasirinkite tai, kas jums tinka
   * Kai klausiama _"Ar laukas UnitAmount apima ar neapima mokesčių?",_ įsitikinkite, kad pasirinkta "Tax Exclusive" (neapima mokesčių)
5. Sėkmingai importavę sąskaitas rasite savo sąskaitas kaip juodraštinius projektus [Business" > "Bills to Pay" (Mokėtinos sąskaitos)](https://go.xero.com/app/!4d1WC/bills/list/all)

### Klaidų šalinimas <a href="#h_df9de998d2" id="h_df9de998d2"></a>

#### "Dėl nežinomos problemos negalėjome importuoti jūsų sąskaitų" <a href="#h_4d5ac766c4" id="h_4d5ac766c4"></a>

[![](https://downloads.intercomcdn.com/i/o/1132415787/7572f878cf78259738c802af/image.png?expires=1751479200\&signature=1e63ac6fb9c246ccf0f13d3ce4fdd1cc5f2f095ca1d7b5abebe3818b293a6f75\&req=dSEkFM1%2FmIZXXvMW3nq%2BgcqC304poGF4fix343DUqgOJ7ISknhHcpjRs%2BD8A%0AEuVnlDhYC%2B5wk2MScUQKY9OhPJo%3D%0A)](https://downloads.intercomcdn.com/i/o/1132415787/7572f878cf78259738c802af/image.png?expires=1751479200\&signature=1e63ac6fb9c246ccf0f13d3ce4fdd1cc5f2f095ca1d7b5abebe3818b293a6f75\&req=dSEkFM1%2FmIZXXvMW3nq%2BgcqC304poGF4fix343DUqgOJ7ISknhHcpjRs%2BD8A%0AEuVnlDhYC%2B5wk2MScUQKY9OhPJo%3D%0A)

Tikėtina, kad ši klaida pasirodo, nes į jūsų CSV įrašytos valiutos, kurių "Xero" neatpažįsta. Jei tai tradicinė valiuta, prieš bandydami dar kartą importuoti CSV pirmiausia pridėkite trūkstamas tradicines valiutas prie savo "Xero" paskyros. Tai galite padaryti "Xero" programoje spustelėję savo įmonės pavadinimą ir punktą [Nustatymai > Valiutos > Pridėti valiutą](https://go.xero.com/Setup/CurrencyRates.aspx).

"Xero" nepalaiko kriptovaliutų, todėl kriptovaliuta išreikštas sąskaitas reikia konvertuoti į tradicinę valiutą (žr. 7 žingsnį [čia](https://help.request.finance/en/articles/9479311-how-to-export-invoice-data-and-import-it-into-xero#h_f6009f1397)).\
​

Susidūrėte su problemomis? Žiūrėkite ["Xero" pagalbos straipsnį apie sąskaitų importavimą](https://central.xero.com/s/article/Import-bills-and-credit-notes-GL) arba [kreipkitės el. paštu support@request.finance](mailto:support@request.finance).
