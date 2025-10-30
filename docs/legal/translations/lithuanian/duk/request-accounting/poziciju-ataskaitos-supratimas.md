---
description: >-
  Sužinokite daugiau apie pozicijų ataskaitos duomenų taškus ir konfigūracijos
  parinktis
---

# Pozicijų ataskaitos supratimas

Pozicijų ataskaitoje pateikiama išsami jūsų turimų kriptovaliutų įvairiose piniginėse ir biržose apžvalga. Šiame vadove paaiškinamas ataskaitos turinys ir konfigūravimo parinktys.

Norėdami atsisiųsti Pozicijų ataskaitą, atlikite šiuos veiksmus:

1. Pereikite į [Ataskaitos](https://accounting.request.finance/exports)
2. Srityje Apskaita ir auditas spustelėkite Pozicijų ataskaita
3.  Tada sukonfigūruokite ataskaitą pagal savo reikalavimus ir spustelėkite Eksportuoti. Norėdami suprasti konfigūravimo parametrus, žr. toliau pateiktą lentelę.

    [![](https://downloads.intercomcdn.com/i/o/mmdbekc3/1331258679/e2e7af7da6659554b6880e977331/image.png?expires=1751479200\&signature=5396e928e809e7bbc7843ea5bda0acd4aaae1a1cd9adac0b48f16ae61512ba7b\&req=dSMkF8t7lYdYUPMW3nq%2BgSlEBx1Ds6Fi%2F2qNxitzPTa%2BMlACcmwG0HxFj9rw%0AzG%2BF5uENITNU8%2FdvxHnPCXKh0rc%3D%0A)](https://downloads.intercomcdn.com/i/o/mmdbekc3/1331258679/e2e7af7da6659554b6880e977331/image.png?expires=1751479200\&signature=5396e928e809e7bbc7843ea5bda0acd4aaae1a1cd9adac0b48f16ae61512ba7b\&req=dSMkF8t7lYdYUPMW3nq%2BgSlEBx1Ds6Fi%2F2qNxitzPTa%2BMlACcmwG0HxFj9rw%0AzG%2BF5uENITNU8%2FdvxHnPCXKh0rc%3D%0A)

| Lauko pavadinimas                       | Aprašymas                                                                                                                                                                                                           |
| --------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Failo formatas                          | Formatas, kuriuo norite atsisiųsti failą. Palaikomi CSV ir "Excel" formatai.                                                                                                                                        |
| Data                                    | Konkreti data, kuriai norite sukurti savo Pozicijų momentinę nuotrauką.                                                                                                                                             |
| Piniginės                               | Piniginė (-ės), kurią (-ias) norite analizuoti savo ataskaitoje.                                                                                                                                                    |
| Biržos                                  | Birža (-os), kurią (-ias) norite analizuoti savo ataskaitoje.                                                                                                                                                       |
| Fireblocks Darbo vietos                 | "Fireblocks" darbo erdvė (-ės), kurią (-ias) norite analizuoti savo ataskaitoje.                                                                                                                                    |
| Turtas                                  | <p>Pagal numatytuosius nustatymus į ataskaitą įtraukiamas visas jūsų pasirinktuose šaltiniuose esantis turtas</p><p>Pasirinktinai filtruokite konkrečias kriptovaliutas, kad sutelktumėte dėmesį į savo analizę</p> |
| Ignoruoti žetonus be vertės             | <p>Pasirinkite "Taip", kad neįtrauktumėte žetonų, kurie neturi dabartinių rinkos kainų</p><p>Pasirinkite "Ne", kad įtrauktumėte visus žetonus, nepriklausomai nuo kainos prieinamumo</p>                            |
| Pridėti neįtrauktus sandorius           | Galimybė įtraukti anksčiau neįtrauktus sandorius į balanso skaičiavimus                                                                                                                                             |
| Įtraukti nepageidaujamų žetonų judėjimą | Pasirinkite, ar įtraukti, ar neįtraukti žinomus nepageidaujamų žetonų pervedimus                                                                                                                                    |
| Apibendrinti šaltinius                  | Sujungti duomenis iš kelių piniginių ir biržų į vieną konsoliduotą ataskaitą                                                                                                                                        |

4\. Atsisiųskite ataskaitą iš lentelės " Ataskaitų istorija". Žr. toliau pateiktą lentelę, kad suprastumėte pateiktus duomenų taškus.

| Lauko pavadinimas     | Aprašymas                                                    |
| --------------------- | ------------------------------------------------------------ |
| Data                  | Pozicijos momentinės nuotraukos data                         |
| Piniginės adresas     | Piniginės viešasis blokų grandinės adresas                   |
| Piniginės pavadinimas | Jūsų pasirinktinis piniginės pavadinimas                     |
| Žetono simbolis       | Kriptovaliutos simbolis (pvz., BTC, ETH)                     |
| Žetono adresas        | Žetono išmaniosios sutarties adresas                         |
| Grandinė              | Blokų grandinės tinklas, kuriame egzistuoja žetonas          |
| Balansas              | Žetono likutis piniginėje pasirinktą dieną                   |
| Žetono kaina          | Dabartinė žetono rinkos kaina pageidaujama apskaitos valiuta |
| Bendra vertė          | Bendra jūsų turimų atitinkamų žetonų vertė tradicine valiuta |

## Svarbios pastabos <a href="#h_08f80be8e7" id="h_08f80be8e7"></a>

1. Balanso tikslumas
   * Pozicijos apskaičiuojamos pagal sandorių istoriją
   * Tikslumas priklauso nuo sandorių duomenų išsamumo
   * Rekomenduojamas reguliarus sutikrinimas
2. Neatitikimų sprendimas
   * Jei likučiai nesutampa su pinigine / birža
   * Kreipkitės į palaikymo tarnybą dėl sandorių istorijos audito
   * Pateikite konkrečių neatitikimų pavyzdžių

Siekdami optimalaus tikslumo, reguliariai tikrinkite praneštus likučius pagal piniginės / biržos likučius. Praneškite apie bet kokius neatitikimus, kad padėtumėte mums užtikrinti platformos tikslumą.
