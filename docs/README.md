# Dokumentaatio

**Tila:** Kanoninen  
**Viimeksi tarkistettu:** 31.7.2026

Tämä tiedosto määrittelee projektin dokumentaation rakenteen ja ylläpitosäännöt.

## Lukujärjestys

Uuden ihmisen tai AI-agentin tulee lukea dokumentit tässä järjestyksessä:

1. repositoryn [`README.md`](../README.md)
2. [`current-status.md`](current-status.md)
3. [`sources/README.md`](sources/README.md)
4. [`pedagogy/README.md`](pedagogy/README.md)
5. [`decisions/README.md`](decisions/README.md)
6. aktiivisen oppimisjakson `README.md`, kun ensimmäinen jakso on luotu

## Hakemistojen roolit

### `sources/`

Sisältää projektin ulkoiset totuuden lähteet: viralliset määräykset, opetussuunnitelmat, kokeet, arviointiohjeet ja lähteiden tarkat URL-osoitteet.

Tänne ei tallenneta projektin omia pedagogisia tulkintoja.

### `pedagogy/`

Sisältää pitkäikäiset pedagogiset periaatteet ja virallisista lähteistä johdetut projektin tulkinnat.

Dokumenteissa pitää erottaa:

- virallinen lähdetieto
- projektin oma tulkinta
- testaamaton hypoteesi

### `decisions/`

Sisältää hyväksytyt päätökset, joiden unohtaminen voisi johtaa projektin suunnan muuttumiseen tai saman keskustelun toistamiseen.

Päätösdokumentteja luodaan vain merkittävistä ja pitkäikäisistä ratkaisuista.

Nykyiset päätökset:

- ensimmäisen pilotin formaatti on ohjattu YO-oppimissessio
- ensimmäinen pilotti käyttää valmiiksi tuotettua ja tarkistettua sisältöä
- käyttäjän oman materiaalin hyödyntäminen on myöhempi, ensin käsin testattava tuotepolku.

### `current-status.md`

Kuvaa vain projektin tämänhetkisen tilanteen, aktiivisen työn ja seuraavan konkreettisen askeleen.

Se ei ole päätösten tai pysyvän tiedon arkisto.

### Tuleva `episodes/`

Luodaan vasta ensimmäisen aiheen valinnan yhteydessä. Jokaiselle oppimisjaksolle tulee oma kansio, jossa säilytetään jakson lähdemuistio, käsikirjoitus, oppimistesti ja arviointi.

### Tuleva `templates/`

Luodaan vasta, kun ensimmäisestä tuotantokierroksesta tiedetään, mitkä rakenteet todella toistuvat.

## Dokumentaation säännöt

### 1. Yhdellä tiedolla on yksi kanoninen koti

Samaa sisältöä ei kopioida useaan dokumenttiin. Muut dokumentit linkittävät kanoniseen lähteeseen.

### 2. Lähteet ja tulkinnat pidetään erillään

Virallinen tieto kuuluu `sources/`-hakemistoon. Projektin pedagoginen johtopäätös kuuluu `pedagogy/`-hakemistoon.

### 3. Kanonista dokumenttia päivitetään samaan tiedostoon

Ei luoda tiedostoja kuten `uusi`, `lopullinen`, `v2` tai `final`. Git säilyttää versionhistorian.

### 4. Päätös ja nykytila ovat eri asioita

`decisions/` kertoo, mitä päätettiin ja miksi. `current-status.md` kertoo, mitä tehdään juuri nyt.

### 5. Keskusteluja ei tallenneta sellaisenaan

ChatGPT- tai Claude-keskustelusta tallennetaan vain tarkistettu lähdetieto, hyväksytty päätös, valmis pedagoginen kuvaus tai tuotannossa käytettävä artefakti.

### 6. Kanonisilla dokumenteilla on tila ja tarkistuspäivä

Käytettävät tilat ovat:

- `Luonnos`
- `Kanoninen`
- `Korvattu`

### 7. Rakennetta kasvatetaan vasta todelliseen tarpeeseen

Dokumentaatio ei saa muodostua omaksi raskaaksi projektikseen. Ensimmäisen pilotin rajaus ohjaa myös dokumentaation laajuutta.

## Tiedoston nimeäminen

- käytä pieniä kirjaimia
- käytä sanojen välissä yhdysmerkkiä
- käytä kuvaavaa nimeä
- päätösdokumenteissa käytä muotoa `DEC-001-aiheen-nimi.md`
- oppimisjaksoissa käytä myöhemmin muotoa `EP-001-aiheen-nimi/`
