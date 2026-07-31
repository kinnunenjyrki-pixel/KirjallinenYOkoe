# Dokumentaatio

**Tila:** Kanoninen  
**Viimeksi tarkistettu:** 31.7.2026

Tämä tiedosto määrittelee projektin dokumentaation rakenteen ja ylläpitosäännöt.

## Lukujärjestys

1. repositoryn [`README.md`](../README.md)
2. [`current-status.md`](current-status.md)
3. [`roadmap/README.md`](roadmap/README.md)
4. [`sources/README.md`](sources/README.md)
5. [`pedagogy/README.md`](pedagogy/README.md)
6. [`decisions/README.md`](decisions/README.md)
7. aktiivisen oppimisjakson `README.md`, kun ensimmäinen jakso on luotu

## Hakemistojen roolit

### `sources/`

Projektin ulkoiset totuuden lähteet: määräykset, opetussuunnitelmat, kokeet, arviointiohjeet ja tarkat URL-osoitteet. Tänne ei tallenneta projektin omia pedagogisia tulkintoja.

### `pedagogy/`

Pitkäikäiset pedagogiset periaatteet ja virallisista lähteistä johdetut projektin tulkinnat. Virallinen tieto, projektin tulkinta ja testaamaton hypoteesi erotetaan toisistaan.

### `decisions/`

Hyväksytyt pitkäikäiset päätökset ja niiden perustelut.

### `roadmap/`

Kehitysideat ja hyväksytyt työaiheet tehtäväkortteina. Kortti kuvaa ongelman, tavoitellun muutoksen, hyväksymiskriteerit, pienimmän hyödyllisen toteutuksen, rajauksen, riippuvuudet, riskit ja suosituksen.

GitHub Issue avataan tarvittaessa vasta, kun tehtäväkortti otetaan aktiiviseen toteutukseen.

### `current-status.md`

Projektin tämänhetkinen tilanne, aktiivinen työ ja seuraava konkreettinen askel. Se ei ole päätösten tai pysyvän tiedon arkisto.

### Tuleva `episodes/`

Luodaan ensimmäisen aiheen valinnan yhteydessä. Jakson kansiossa säilytetään lähdemuistio, käsikirjoitus, oppimistesti ja arviointi.

### Tuleva `templates/`

Luodaan vasta, kun ensimmäisestä tuotantokierroksesta tiedetään, mitkä tuotantorakenteet toistuvat. Roadmap-tehtäväkorteilla on oma pohja tiedostossa [`roadmap/TASK-TEMPLATE.md`](roadmap/TASK-TEMPLATE.md).

## Dokumentaation säännöt

1. Yhdellä tiedolla on yksi kanoninen koti.
2. Virallinen lähdetieto ja projektin tulkinta pidetään erillään.
3. Kanonista dokumenttia päivitetään samaan tiedostoon; Git säilyttää historian.
4. `decisions/` kertoo mitä päätettiin, `roadmap/` mitä voidaan tai aiotaan tehdä ja `current-status.md` mitä tehdään nyt.
5. Kehitysidea dokumentoidaan ensin roadmap-kortiksi. Issue avataan vasta aktiivista toteutusta varten.
6. Keskusteluja ei tallenneta sellaisenaan.
7. Kanonisilla dokumenteilla on tila ja tarkistuspäivä. Tehtäväkorteilla on roadmapissa määritellyt työtilat.
8. Rakennetta kasvatetaan vasta todelliseen tarpeeseen.

## Tiedoston nimeäminen

- päätös: `DEC-001-aiheen-nimi.md`
- tehtäväkortti: `TASK-001-aiheen-nimi.md`
- oppimisjakso: `EP-001-aiheen-nimi/`
