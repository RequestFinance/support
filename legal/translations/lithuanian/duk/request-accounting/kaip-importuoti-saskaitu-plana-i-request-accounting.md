---
description: Sužinokite, kaip masiškai importuoti sąskaitų planą naudojant CSV failą.
---

# Kaip importuoti sąskaitų planą į "Request Accounting"?

Jei turite sąskaitų planą (SS) ir nenorite jo kurti rankiniu būdu "Request Accounting" programoje, galite įkelti savo sąskaitų plano CSV failą ir "Request Accounting" programa iš karto importuos sąskaitas.

Norėdami importuoti savo KAS į "Request Accounting", atlikite toliau nurodytus veiksmus:

1. Eikite į Apskaita → [Sąskaitų planas](https://accounting.request.finance/account-types)
2.  Spustelėkite Importuoti sąskaitas

    [![](https://downloads.intercomcdn.com/i/o/mmdbekc3/1324337032/3d3d2b85eb4ddbbcd42b580e1455/unnamed+\(3\).png?expires=1751479200\&signature=c5b5429f128f52b64892f1122fd229edbc8439baf035356d7cb57036956fa691\&req=dSMlEsp9moFcW%2FMW3nq%2BgSroI21R4PfiadC75rt7e3%2FPSoJjk7ztB6gsxvVh%0AL465CHzmuCs2nw4L6S6Xgs%2FqE%2BA%3D%0A)](https://downloads.intercomcdn.com/i/o/mmdbekc3/1324337032/3d3d2b85eb4ddbbcd42b580e1455/unnamed+\(3\).png?expires=1751479200\&signature=c5b5429f128f52b64892f1122fd229edbc8439baf035356d7cb57036956fa691\&req=dSMlEsp9moFcW%2FMW3nq%2BgSroI21R4PfiadC75rt7e3%2FPSoJjk7ztB6gsxvVh%0AL465CHzmuCs2nw4L6S6Xgs%2FqE%2BA%3D%0A)
3. Tada [čia gaukite savo šabloną](https://public-template-files.s3.eu-west-3.amazonaws.com/General_COA_Template.csv) ir pradėkite rengti CSV failą.
4. Užpildykite CSV šabloną. Žr. toliau pateiktą lentelę, kad suprastumėte, ką turite pateikti.
5. Galiausiai vilkite ir nuleiskite CSV į nuleidimo zoną, kad galėtumėte įkelti. Prašymų apskaita perskaitys CSV ir importuos jūsų COA.

| Lauko pavadinimas     | Aprašymas                                                                                                                                 |
| --------------------- | ----------------------------------------------------------------------------------------------------------------------------------------- |
| Sąskaitos tipas       | Pagrindinė jūsų COA sąskaitos kategorija. Tai turėtų būti viena iš Turto, Pajamų, Įsipareigojimų, Nuosavo kapitalo ir Sąnaudų kategorijų. |
| Sąskaitos pavadinimas | Jūsų debetinės arba kreditinės sąskaitos pavadinimas. Ji turėtų priklausyti bet kuriam iš penkių pirminių sąskaitų tipų.                  |

1.  Jei turite kokių nors subsąskaitų, priskiriamų vienam iš šių sąskaitų pavadinimų, sąskaitos tipo stulpelyje galite nurodyti sąskaitos pavadinimą, o subsąskaitą - stulpelyje "Sąskaitos pavadinimas".

    [![](https://downloads.intercomcdn.com/i/o/mmdbekc3/1324344080/4f30df650a65308f8f57924e6b4e/unnamed+\(4\).png?expires=1751479200\&signature=9767564915920182ede642fad8904fb629c8be8f8015b63786a31f7dc98bd612\&req=dSMlEsp6mYFXWfMW3nq%2BgSH2nwFSnpIUB1KCxqSDnOjoVAId8EHQRYFJOO9%2B%0Aw4hAxvNlK6Gca%2FWuTDwXsivPO%2BE%3D%0A)](https://downloads.intercomcdn.com/i/o/mmdbekc3/1324344080/4f30df650a65308f8f57924e6b4e/unnamed+\(4\).png?expires=1751479200\&signature=9767564915920182ede642fad8904fb629c8be8f8015b63786a31f7dc98bd612\&req=dSMlEsp6mYFXWfMW3nq%2BgSH2nwFSnpIUB1KCxqSDnOjoVAId8EHQRYFJOO9%2B%0Aw4hAxvNlK6Gca%2FWuTDwXsivPO%2BE%3D%0A)
2. Request apskaita identifikuoja pasikartojančius COA, jei tas pats failas įkeliamas du kartus. Tai patogu, kai dažnai atnaujinate COA, nes nereikia iš CSV ištrinti jau įkeltų COA.
3. Tą patį paskyros pavadinimą galite nurodyti skirtinguose paskyrų tipuose, tačiau nerekomenduojama kurti šių paskyrų pavadinimų subsąskaitų.

Pavyzdys: turiu sąskaitas Gautinos sumos, nurodytas ir prie Pajamų , ir prie Turto. Jei norėsiu sukurti subsąskaitą Crypto AR prie Gautinų sumų, sistema negalės atpažinti, ar ši subsąskaita priklauso Gautinų sumų subs ąskaitai prie Pajamų ar Turto. Rekomenduojama šias subsąskaitas įvesti rankiniu būdu programoje "Prašymų apskaita".
