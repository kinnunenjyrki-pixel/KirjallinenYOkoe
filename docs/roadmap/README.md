# Roadmap ja tehtäväkortit

**Tila:** Kanoninen  
**Viimeksi tarkistettu:** 31.7.2026

Tämä hakemisto sisältää projektin kehitysideat ja hyväksytyt työaiheet tehtäväkortteina.

Tehtäväkortin tarkoitus on kuvata selkeästi:

- mikä oppimiseen tai tuotteeseen liittyvä ongelma ratkaistaan
- mitä muutosta tavoitellaan
- mikä on pienin hyödyllinen toteutus
- milloin tehtävä voidaan katsoa valmiiksi
- mitä tehtävään ei kuulu.

## Suhde muuhun dokumentaatioon

### `roadmap/`

Kertoo, mitä voitaisiin tehdä, mitä tehdään seuraavaksi ja millä hyväksymiskriteereillä työ valmistuu.

### `decisions/`

Kertoo, mitä pitkäikäistä on jo päätetty ja miksi.

### `current-status.md`

Kertoo, missä vaiheessa projekti on juuri nyt ja mikä on seuraava konkreettinen askel.

### GitHub Issues

Issue avataan tarvittaessa vasta, kun tehtäväkortti otetaan aktiiviseen toteutukseen. Keskeneräisiä tuoteideoita ei säilytetä ensisijaisesti Issueina.

## Korttien tilat

- **Ehdotus** – idea on dokumentoitu, mutta sitä ei ole hyväksytty työjonoon
- **Seuraavaksi** – tehtävä on hyväksytty seuraavaan työjonoon
- **Työn alla** – tehtävä on aktiivisessa toteutuksessa
- **Valmis** – hyväksymiskriteerit täyttyvät ja tulos on arvioitu
- **Myöhemmin** – idea on arvokas, mutta ei kuulu nykyiseen pilottiin
- **Hylätty** – ideaa ei edistetä; perustelu säilytetään kortissa.

## Arviointisuositukset

Jokaisella kortilla on yksi suositus:

- **Toteuta nyt**
- **Rajaa pienemmäksi**
- **Testaa ensin**
- **Siirrä myöhemmäksi**
- **Hylkää**

Suosituksen pitää perustua erityisesti seuraaviin kysymyksiin:

1. Parantaako tämä oppimista?
2. Onko tämä tarpeellinen ensimmäisessä pilotissa?
3. Voiko tämän testata nopeasti?
4. Mikä on pienin hyödyllinen toteutus?

## Työnkulku

1. Idea arvioidaan ennen kortin luomista.
2. Riittävän konkreettisesta ideasta tehdään tehtäväkortti.
3. Kortti siirretään tilaan `Seuraavaksi` vain tietoisella päätöksellä.
4. Aktiivisesta toteutuksesta voidaan avata GitHub Issue, joka linkittää korttiin.
5. Toteutuksen tulokset kirjataan korttiin.
6. Pitkäikäinen hyväksytty ratkaisu dokumentoidaan tarvittaessa erikseen `decisions/`-hakemistoon.

## Nykyiset kortit

### Ehdotus

- [`TASK-001-piilotettu-yo-lopputehtava.md`](TASK-001-piilotettu-yo-lopputehtava.md) – **Testaa ensin**

### Seuraavaksi

Ei tehtäviä.

### Työn alla

Ei tehtäviä.

### Valmis

Ei tehtäviä.

### Myöhemmin

Ei tehtäviä.

### Hylätty

Ei tehtäviä.

## Tiedoston nimeäminen

Tehtäväkortit nimetään juoksevasti:

```text
TASK-001-aiheen-nimi.md
TASK-002-aiheen-nimi.md
```

Uuden kortin pohjana käytetään tiedostoa [`TASK-TEMPLATE.md`](TASK-TEMPLATE.md).
