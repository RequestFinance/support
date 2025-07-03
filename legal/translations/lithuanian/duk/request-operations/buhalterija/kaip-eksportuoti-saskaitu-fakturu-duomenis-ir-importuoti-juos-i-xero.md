---
description: Sąskaitų faktūrų duomenų importavimas į "Xero".
---

# Kaip eksportuoti sąskaitų faktūrų duomenis ir importuoti juos į "Xero"?

"Request Finance" siūlo "Xero" optimizuotą CSV, kurį galite sukurti ir naudoti greitai importuodami sąskaitų faktūrų duomenis į "Xero".

Norėdami importuoti kitus duomenis į "Xero", žr. šiuos šaltinius:

* [Sąskaitų duomenys](https://help.request.finance/en/articles/9479454-incomplete-how-to-export-bill-data-and-import-it-into-xero)
* Ar norėtumėte sinchronizuoti kriptovaliutų sandorius su "Xero"? Gaukite prieigą prie visiškai automatinio sandorių sinchronizavimo su ["Request Accounting"](https://www.request.finance/accounting).

## Kaip importuoti sąskaitas faktūras į "Xero"? <a href="#h_46099de820" id="h_46099de820"></a>

### Sąskaitų faktūrų eksportavimas iš "Request Finance". <a href="#h_f6009f1397" id="h_f6009f1397"></a>

1. Prisijunkite prie "Request Finance"
2. Pereikite į [meniu Sąskaitos faktūros](https://app.request.finance/get-paid/sent)
3. Spustelėkite ant 3 taškelių "..." (žr. toliau pateiktą paveikslėlį)
4. Spustelėkite Atsisiųsti CSV
5. Pasirinkite Xero-optimized CSV
6. Spustelėkite Atsisiųsti
7. Atsisiuntę užpildykite kiekvienos sąskaitos faktūros stulpelį AccountCode. Šis stulpelis nurodo sąskaitos pavadinimą iš jūsų "Xero" nustatyto sąskaitų plano [čia](https://go.xero.com/GeneralLedger/ChartOfAccounts.aspx).
8. Jei taikoma: stulpelyje Valiuta pažymėkite, ar yra tradicinių valiutų, kurių "Xero" nenaudojate, arba kriptovaliutų.
   * Prieš importuojant tradicines valiutas, jas reikia įtraukti į "Xero"
   * Kriptovaliutas reikia konvertuoti į tradicines valiutas, nes "Xero" jų nepalaiko. Nepamirškite prireikus pakoreguoti ir sumų (stulpelis UnitAmount ir TaxAmount).

[![Click on the meatballs icon to download a CSV for QuickBooks](https://downloads.intercomcdn.com/i/o/995613672/8a40478c69454a1c8eaf7656/image.png?expires=1751479200\&signature=8726d0617c2f5bda099ac683e2eb5f5aed7f23af97e7a7c113a985cb511a56ac\&req=fSkiEMh9m4ZdFb4V1XW4gRNCjQWVohbHewPgCmVb%2FELuq%2BJm1jKd89E%2FMUcN%0Ay%2BfhlzPvXHbMhgGuEsXoZugJaQ%3D%3D%0A)](https://downloads.intercomcdn.com/i/o/995613672/8a40478c69454a1c8eaf7656/image.png?expires=1751479200\&signature=8726d0617c2f5bda099ac683e2eb5f5aed7f23af97e7a7c113a985cb511a56ac\&req=fSkiEMh9m4ZdFb4V1XW4gRNCjQWVohbHewPgCmVb%2FELuq%2BJm1jKd89E%2FMUcN%0Ay%2BfhlzPvXHbMhgGuEsXoZugJaQ%3D%3D%0A)

### &#x20;Sąskaitų faktūrų CSV parengimas "Xero" <a href="#h_05dd503bd8" id="h_05dd503bd8"></a>

Reikalavimai prieš importuojant sąskaitas faktūras į "Xero":

* Jei dar nepadaryta: iš Užklausos atsisiųstame CSV užpildykite stulpelį "Account" ( žr. 7 žingsnį pirmiau).
* Jei dar nepadaryta: pridėkite trūkstamas tradicines valiutas į "Xero" ir konvertuokite kriptovaliutas (žr. 8 žingsnį pirmiau).

### Sąskaitų faktūrų CSV importavimas į "Xero" <a href="#h_c68e7ff14c" id="h_c68e7ff14c"></a>

1. Prisijunkite prie "Xero"
2. Spustelėkite [Verslas > Pardavimų apžvalga > Importuoti](https://go.xero.com/Import/Import.aspx?type=IMPORTTYPE/ARINVOICES)
3. Vadovaukitės instrukcijomis, kad importuotumėte paruoštą CSV
   * Užklausoje _"Ar norite atnaujinti kontaktinio adreso duomenis?",_ pasirinkite tai, kas jums tinka
   * Užklausoje _"Ar laukas UnitAmount apima mokesčius, ar ne?",_ įsitikinkite, kad pasirinkta "Tax Exclusive" (be mokesčių)
4. Sėkmingai importavę, sąskaitas faktūras rasite kaip juodraščius skyriuje ["Business" > "Invoices" (Verslas > Sąskaitos faktūros)](https://go.xero.com/AccountsReceivable/Search.aspx)

## Klaidų šalinimas <a href="#h_f3ecbc88f2" id="h_f3ecbc88f2"></a>

#### "Nepavyksta gauti galiojančio valiutos konvertavimo kurso" <a href="#h_257ea1120c" id="h_257ea1120c"></a>

[![](https://downloads.intercomcdn.com/i/o/1107211287/47aa4c9536366588398d3f34/image.png?expires=1751479200\&signature=1fb58bd0b198ec2feaf43919db213fc1f0b0cc63f69df66910a1fef9f9633b50\&req=dSEnEct%2FnINXXvMW3nq%2BgRtQMJ5J0hCJ3B9SxQTmLbp60RrdE4JrAMJWtnPF%0Ap%2FQpkbL%2FSognP4chTtKbpUwxhZs%3D%0A)](https://downloads.intercomcdn.com/i/o/1107211287/47aa4c9536366588398d3f34/image.png?expires=1751479200\&signature=1fb58bd0b198ec2feaf43919db213fc1f0b0cc63f69df66910a1fef9f9633b50\&req=dSEnEct%2FnINXXvMW3nq%2BgRtQMJ5J0hCJ3B9SxQTmLbp60RrdE4JrAMJWtnPF%0Ap%2FQpkbL%2FSognP4chTtKbpUwxhZs%3D%0A)

\
Tikėtina, kad ši klaida gaunama, nes jūsų CSV apima valiutas, kurių "Xero" neatpažįsta. Jei tai tradicinės valiutos, prieš bandydami dar kartą importuoti CSV, pirmiausia į "Xero" paskyrą įtraukite trūkstamas tradicines valiutas. Tai galite padaryti "Xero" programoje spustelėję savo įmonės pavadinimą ir punktą [Nustatymai > Valiutos > Pridėti valiutą](https://go.xero.com/Setup/CurrencyRates.aspx).

"Xero" nepalaiko kriptovaliutų. Sąskaitas faktūras, išrašytas kriptovaliuta, reikia konvertuoti į tradicinę valiutą (žr. 7 žingsnį [čia](https://help.request.finance/lt/articles/9479311-kaip-eksportuoti-saskaitu-fakturu-duomenis-ir-importuoti-juos-i-xero#h_f6009f1397)).\
​

#### Mokesčių sumos CSV nerodomos "Xero" <a href="#h_9ea79faf08" id="h_9ea79faf08"></a>

Jei CSV pateiktos mokesčių sumos neimportuojamos į "Xero", greičiausiai neužpildėte stulpelio "AccountCode". Užpildykite stulpelį ir bandykite dar kartą (žr. 7 žingsnį [čia](https://help.request.finance/lt/articles/9479311-kaip-eksportuoti-saskaitu-fakturu-duomenis-ir-importuoti-juos-i-xero#h_f6009f1397)).\
\
Kyla bėdų? Žiūrėkite ["Xero" pagalbos straipsnį apie sąskaitų faktūrų importavimą](https://central.xero.com/s/article/Import-customer-invoices-GL#1DownloadtheCSVtemplatefile) arba [kreipkitės į support@request.finance](mailto:support@request.finance).

