# Kaip veikia "Stripe" integracija?

"Request" integracija su "Stripe" leidžia priimti korteles kaip mokėjimo už sąskaitas faktūras būdą. Atlikus mokėjimą kortele, sąskaitos faktūros būsena automatiškai atnaujinama į "Apmokėta".

Šiuo metu "Stripe" integracijos apimtis apsiriboja tik mokėjimų priėmimu. Pažymėtina, kad integracija NĖRA palaikoma:

* Kurti sąskaitas faktūras "Stripe" kaskart kuriant sąskaitą faktūrą "Request Finance" programoje
* Prenumeratų kūrimo "Stripe" programoje kiekvieną kartą, kai "Request Finance" programoje sukuriama pasikartojanti sąskaita faktūra
* Sąskaitų faktūrų, apmokamų per "Stripe", žymėjimo "Request Finance" programoje kaip apmokėtų
* Sinchronizuoti duomenis iš "Stripe" į "Request Finance"

Sužinokite, kaip sukurti sąskaitą faktūrą, apmokamą kortele, [čia.](https://help.request.finance/en/articles/8610933-can-i-get-paid-by-credit-card)
