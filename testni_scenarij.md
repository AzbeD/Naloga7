# Testni scenariji

## 1. Iskanje avtomobilov

**Funkcionalnost:** Iskanje avtomobilov po ključnih besedah

**Koraki izvedbe testa:**

1. Uporabnik odpre začetno stran aplikacije.
2. V iskalno polje vnese ključno besedo.
3. Klikne gumb Išči.

**Pričakovan rezultat testa:**

* Prikažejo se vsi avtomobili, katerih naziv ali opis vsebuje vneseno ključno besedo.
* Če rezultatov ni, se izpiše ustrezno sporočilo (npr. "Ni zadetkov").

---

## 2. Filtriranje avtomobilov

**Funkcionalnost:** Filtriranje avtomobilov po kriterijih

**Koraki izvedbe testa:**

1. Uporabnik odpre stran s seznamom avtomobilov.
2. Izbere filter *Cena* in določi območje 5.000–15.000 €.
3. Izbere dodatni filter *Letnik* med 2015–2020.
4. Klikne gumb *Filtriraj*.

**Pričakovan rezultat testa:**

* Prikaže se seznam avtomobilov, ki ustrezajo vsem izbranim kriterijem.
* Število rezultatov se zmanjša glede na uporabljene filtre.
* Če ni ustreznih rezultatov, se prikaže informativno sporočilo.

---

## 3. Komunikacija s prodajalcem

**Funkcionalnost:** Pošiljanje sporočila prodajalcu

**Koraki izvedbe testa:**

1. Uporabnik odpre stran posameznega avtomobila.
2. Klikne gumb Kontaktiraj prodajalca.
3. V obrazec vnese sporočilo
4. Klikne gumb Pošlji.

**Pričakovan rezultat testa:**

* Sporočilo je uspešno poslano prodajalcu.
* Uporabnik prejme potrditev o uspešnem pošiljanju.
* Če je obrazec nepopoln, se izpiše opozorilo o manjkajočih podatkih.
