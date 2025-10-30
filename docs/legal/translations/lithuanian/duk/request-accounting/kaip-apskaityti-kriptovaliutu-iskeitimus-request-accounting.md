---
description: >-
  Supraskite, kaip iškeitimo sandoriai sinchronizuojami su jūsų ERP ir kaip
  apskaičiuojami gauti pelnai ir nuostoliai.
---

# Kaip apskaityti kriptovaliutų iškeitimus "Request Accounting"

### Kas yra kriptovaliutos iškeitimas? <a href="#h_8fa2a13a43" id="h_8fa2a13a43"></a>

Iškeitimo sandoris konvertuoja vieną žetoną į kitą toje pačioje piniginėje, pavyzdžiui, konvertuoja ETH į WRAPPED ETH. Sandoris vyksta per iškeitimo sandorio sutartį, kuri palengvina keitimą.

### Kaip "Request Accounting" valdo iškeitimus? <a href="#h_79e89afba7" id="h_79e89afba7"></a>

„Request Accounting“ kiekvieną iškeitimą traktuoja kaip du atskirus turto judėjimus:

* Išvestis: originalus žetonas iš jūsų piniginės patenka į iškeitimo sutartį.
* Įplaukos: naujas žetonas iš iškeitimo sutarties patenka į jūsų piniginę.

### Kodėl tik išvestis sinchronizuojami su mano ERP programine sistema? <a href="#h_f3baa4501b" id="h_f3baa4501b"></a>

Siekiant išvengti dvigubo skaičiavimo "QuickBooks" arba "Xero" programose, "Request Accounting" sinchronizuoja tik išeinančias operacijas. Norėdami užbaigti apskaitos įrašą, turite rankiniu būdu priskirti debeto ir kredito sąskaitas šiai vienintelei išeinančiai eilutei.

### Kaip kategorizuoti iškeitimo transakcijas? <a href="#h_ad2ab0fe37" id="h_ad2ab0fe37"></a>

Panaudosime ETH į WRAPPED ETH pavyzdį:

Duomenys:

* Kreditas: ETH sąskaita (žetono išsiuntimas)
* Debetas: WRAPPED ETH sąskaita (žetono gavimas)

Įplaukų eilutėje:

Naudokite bendrą kategorizaciją, kuri panaikina įrašą.

### Kokios rūšies pelnas ir nuostoliai atsiranda vykdant iškeitimo sandorius? <a href="#h_c87c4b0d6e" id="h_c87c4b0d6e"></a>

1\. Realizuotas pelnas/nuostolis iš pradinio žetono. Tai atspindi jūsų pradinio žetono vertės padidėjimą arba sumažėjimą nuo jo įsigijimo.

Pavyzdys: Praėjusiais metais įsigijote 1 ETH už 1000 USD. Šiandien jį iškeičiate, kai jo vertė yra 2000 USD, ir gaunate 1000 USD realizuotą pelną.

2\. Iškeitimo pelnas/nuostolis. Tai atspindi skirtumą tarp numatytų ir faktinių keitimo verčių dėl rinkos sąlygų ir mokesčių.

Pavyzdys: Jūs keičiate 2000 USD į ETH, bet gaunate tik 1990 USD vertės WRAPPED ETH, todėl patiriate 10 USD nuostolį.

### Ar man reikia stebėti abiejų tipų pelną/nuostolius? <a href="#h_aa2c98daa6" id="h_aa2c98daa6"></a>

Taip, abu yra svarbūs tiksliam mokesčių deklaravimui ir finansinės apskaitos tvarkymui. Realizuotas pelnas/nuostolis turi įtakos jūsų sąnaudų bazės skaičiavimams būsimoms operacijoms, o nuostoliai dėl kainos svyravimų gali būti atskaitomi kaip verslo išlaidos, priklausomai nuo jūsų jurisdikcijos mokesčių įstatymų.
