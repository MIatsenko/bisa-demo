# Predlog veb-sajta — Stomatološka ordinacija Dr Bisa Banković

Demo (predlog) nove početne strane za stomatološku ordinaciju **Dr Bisa Banković**,
Trgovačka 16a, T.C. Mondo, Beograd (Žarkovo).

Stranica je napravljena na materijalima ordinacije — fotografije ordinacije i tima, tekstovi
o uslugama, radno vreme i kontakt podaci preuzeti su sa javnog sajta bisabankovic.com.
Ovo nije zvaničan sajt ordinacije i nije javna ponuda: prikazuje kako bi početna strana mogla
da izgleda, pre bilo kakvog dogovora.

## Šta sadrži

- prvi ekran sa fotografijom ordinacije i pozivom na zakazivanje;
- traka sa činjenicama: godina osnivanja, godine rada, broj oblasti, radno vreme;
- osam oblasti stomatologije, od estetske stomatologije i protetike do implantologije,
  oralne hirurgije, ortodoncije i dečije stomatologije;
- tim: tri stomatologa i stomatološki asistent, sa fotografijama i specijalnostima;
- galerija ordinacije, terapija i radova (pre i posle);
- **forma za zakazivanje termina** (ime, telefon, usluga, željeni datum) sa potvrdom posle
  slanja i proverom broja telefona — u demo verziji potvrda je prikaz na stranici;
  u pravoj verziji zahtev ide na mejl ordinacije;
- kontakt blok sa adresom, radnim vremenom, prevozom i linkom na mapu.

## Tehnički

Jedna statička stranica (`index.html`), bez eksternih biblioteka i bez mrežnih zahteva ka
trećim servisima. Prilagođena telefonu, tabletu i desktopu. `<meta name="robots" content="noindex">`.

Generisano iz šablona `demo_build.py` (jedna HTML stranica + `config.json` u izvornom projektu).
