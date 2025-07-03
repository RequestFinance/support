# Kodėl į "Solana" paketinį mokėjimą negaliu įtraukti daugelio mokėjimų?

Dėl "Solana" įdiegto apribojimo didžiausias mokėjimų, kuriuos galima įtraukti į paketinį mokėjimą, skaičius ribojamas iki 18 mokėjimų viename pakete (19, jei į paketą įtraukti tik SOL žetono mokėjimai).

Šis apribojimas atsiranda dėl "Solana" būdingo 1232 baitų transakcijos dydžio apribojimo. Užklausa negali tam daryti įtakos. Mokėjimams SPL\* žetonais ir mokėjimams SOL žetonais reikalingas dydis skiriasi, todėl maksimalus dydis gali šiek tiek skirtis:

* \~150 baitų yra bazinis pridėtinis dydis, kurio reikia vienam paketiniam mokėjimui.
* kiekvienam SPL mokėjimui reikia \~60 baitų → ne daugiau kaip 18 mokėjimų.
* kiekvienam SOL mokėjimui reikia \~56 baitų → ne daugiau kaip 19 mokėjimų.

Pavyzdys: reikia atlikti 20 SPL mokėjimų ir 2 SOL mokėjimus. Tam reikės dviejų atskirų paketinių mokėjimų, nes priešingu atveju bendras operacijos dydis viršytų 1232 baitų vienai partijai ribą (< 1462 baitai = 150 baitų + 20\*60 baitų + 2\*56 baitai).

_\*SPL yra pakeičiamų žetonų standartas, panašus į "Ethereum" ERC-20. Dauguma ne SOL žetonų, pavyzdžiui, USDC, yra SPL žetonai._
