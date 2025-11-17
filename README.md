# Petstore API Automatizuoti Testai

**Autorius:** Matas Štrimaitis, PI23A

## Aprašymas

Naudojant **Postman** sukurta automatizuotų API testų kolekcija, skirta Swagger Petstore API adresu:  
`https://petstore.swagger.io/v2`.

Kolekcijoje yra daugiau nei **40 testų**, suskirstytų į šias grupes:

- **Pet Tests** – gyvūno kūrimas, paieška, atnaujinimas, trynimas, nuotraukos įkėlimas.
- **Store Tests** – užsakymų kūrimas, gavimas, inventorius.
- **User Tests** – vartotojo kūrimas, nuskaitymas, atnaujinimas, trynimas, prisijungimas.
- **Negative Tests** – neteisingų duomenų scenarijai.
- **Common Tests** – bendri testai (JSON schema, atsakymo trukmė, random reikšmės).
- **Individual Tests** – autoriaus sugalvoti papildomi testai.

## Kaip paleisti

1. Importuokite kolekciją:  
   `Matas_Štrimaitis_PI23A.Medusa_API_Tests.postman_collection.json`

2. Importuokite environment failą:  
   `Matas_Štrimaitis_PI23A.Medusa_API_Tests.postman_environment.json`

3. Postman viršuje pasirinkite importuotą environment.

4. Atidarykite **Collection Runner**:
   - Pasirinkite Petstore kolekciją.
   - Pasirinkite environment.
   - Paspauskite **Run**.

Kolekcija naudoja environment kintamuosius: `baseUrl`, `petId`, `orderId`, `usernames` ir daugelis kitų.

## Testų rezultatai

Po vykdymo Collection Runner lange matysite:

- Bendrą atliktų requestų skaičių.
- Sėkmingų / nesėkmingų testų skaičių.
- Vidutinę atsakymo trukmę.
