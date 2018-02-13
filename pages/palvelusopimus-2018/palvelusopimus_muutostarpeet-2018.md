---
title: Haka-palvelusopimuksen muutostarpeet vuonna 2018
sidebar: home_sidebar
permalink: palvelusopimus_muutostarpeet-2018.html
folder: palvelusopimus-2018
---

## Luettelo on keskeneräinen luonnos

Tämä luettelo on keskeneräinen luonnos.

## Versiohistoria

| Päivämäärä | Tekijä | Aihe |
| ---------- | ------ | ---- |
| 7.2.2018 | [Kari Laalo](https://github.com/klaalo) | Aloitettu |


## Haka-ohjausryhmän strategiakokous käynnisti muutoksen

Haka-ohjausryhmä järjesti 14.1.2016 kokouksen, jonka tavoitteena oli hahmotella Hakan strategiaa eteenpäin tähtäimellä vuosi 2020. Kokous päätti keskeiseksi kehittämiskohteeksi vahvemman sähköisen tunnistamisen kehittämisen lisäpalveluksi Haka-tunnistusverkoston yhteyteen.

Vuonna 2017 Haka-operointi kehitti [MPASSid](https://github.com/Digipalvelutehdas/MPASSid-proxy) -teknologiaan perustuvan vahvemman tunnistamisen ratkaisun, joka on käytettävissä Hakaan jäsenenä liittyvän organisaation tunnistuspalvelimella.

Strategisten linjausten käynnistämät muutokset ja nykyisen Haka-palvelusopimuksen ikä ovat tehneet ilmeiseksi, että sopimusta on päivitettävä.

## Luettelo sopimuksessa havaituista muutostarpeista

### Vanhentuneet viittaukset henkilötietojen suojan lainsäädäntöön

#### Henkilötietolaki

Myös Suomessa henkilötietojen suojan lainsäädäntö on uudistumassa EU:n tietosuoja-asetuksen uudistuessa.

* [GDPR](http://eur-lex.europa.eu/legal-content/en/TXT/?uri=CELEX%3A32016R0679)
* [Data Protection](https://ec.europa.eu/info/law/law-topic/data-protection_en)

Uutta henkilötietosuojan lainsäädäntöä valmisteleva työryhmä 
[on ehdottanut](http://julkaisut.valtioneuvosto.fi/handle/10024/80098)
henkilötietolakia kumottavaksi ja säädettävän yleisen tietosuojalain, jolla täsmennetään ja täydennetään EU:n tietosuoja-asetusta.

Etenkin asian keskeneräisyyden johdosta Haka-palvelusopimuksessa pitäisi välttää viittaamasta nimenomaiseen lakiin. Sen sijaan lienee parempi viitata henkilötietojen suojan lainsäädäntöön yleisemmin.

Yksityiskohtaiset tarkemmat viittaukset lakeihin, asetuksiin ja verkostossa noudatettaviin määrityksiin lienee parempi koostaa liitteeseen, jolloin niiden ajantasaisuuden ylläpito on joustavampaa.


#### Sopimuksen 2008 viittauksia vanhaan henkilötietolakiin

* Jäsensopimuksessa 
   [viitataan](palvelusopimus_jasensopimus.html#hetil-1)
   henkilötietolain pykälään
* Kumppanisopimuksessa
   [viitataan](palvelusopimus_kumppani.html#hetil-1)
   henkilötietolain pykälään
* Liitteessä 1 viitataa henkilötietolakiin kohdissa:
   * [henkilötieto](haka_liite_1.html#hetil-1)
   * [henkilötiedon käsittely](haka_liite_1.html#hetil-2)
   * [tietosuojaseloste](haka_liite_1.html#hetil-3)
* Liitteessä 2 [viitataan](haka_liite_2.html#hetil-1) kohdassa 2.1

#### Safe Harbor

Safe Harbor oli EU:n ja Yhdysvaltojen välinen sopimus henkilötietojen käsittelystä ja siirrosta Euroopan taloualueelta Yhdysvaltoihin alkaen vuodesta 1998. Käytäntö mitätöitiin 6.10.2015 EU-tuomioistuimessa.

Safe Harbor -periaatteisiin viitataan kumppanisopimuksen
[kohdassa](palvelusopimus_kumppani.html#safeharbor) 6. henkilötietojen suoja ja tietoturva. Kohdassa viitataan muutenkin sanamuotoihin ja periaatteisiin, jotka tunnetaan henkilötietolaista. Ei liene tarpeen toistaa sopimuksessa lainsäädännön vaatimuksia uudelleen.

Jatkossa Haka-verkoston osapuolten toteuttamaan henkilötietojen käsittelyyn on luontevampaa noudattaa 
[GEANT Code of Conduct tietosuojakäytännettä](https://wiki.refeds.org/display/CODE/Data+Protection+Code+of+Conduct+Home),
jonka
[2. versio](https://wiki.refeds.org/display/CODE/Code+of+Conduct+ver+2.0+project)
mahdollistanee tietojen siirron myös Yhdysvaltoihin (kun määrätyt olosuhteet täyttyvät).

Sen sijaan, että varsinaisessa sopimuksessa viitataa yksityiskohtaisesti tiettyihin käytänteisiin, lienee parempi vaihtoehto koota viittaukset pakottaviin määrityksiin ja toimintokäytänteisiin erilliseen liitteeseen.

### Operoinnin tuottamat lisäpalvelut: vahvempi tunnistaminen Hakassa

Liitteessä 3 kohdassa 
[1. Operaattorin tarjoamat palvelut](haka_liite_3.html#oper-palvelut)
luetellaan operaattorin luottamusverkostossa tarjoamat palvelut. Vahvemman tunnistamisen lisäpalvelussa operaattorilla on perinteisiä palveluja keskeisempi rooli mm. henkilötietojen käsittelyssä.

Vahvemman tunnistamisen palvelu on lisättävä Liitteeseen 3 operaattorin tuottamana verkoston lisäpalveluna.

Liitteen 3 palvelujen luetteloinnissa on syytä tehdä ero verkoston toiminnan kannalta olennaisesta luottamusverkoston toimintaan liittyvistä peruspalveluista ja palvelimista (Service Provider - SP), joita operaattori tai operointia tuottava organisaatio CSC saattaa verkostoon lisätä.

### Sopimus yleisemmäksi käytettävien teknologioiden osalta

#### Viittaaminen määrityksiin sopimuksen liitteissä 

* FunetEduPerson-skeema mainitaan:
   * [Jäsensopimuksessa](palvelusopimus_jasensopimus.html#fep-1)
   * [Liitteessä 1](haka_liite_1.html#fep-1)
   * [Liitteessä 2](haka_liite_2.html#fep-2), kohdassa 3.1 Ohjausryhmä
   * [Liitteessä 2](haka_liite_2.html#fep-1), kohdassa 3.2 Tekninen työryhmä
   

#### Terminologia

Haka-luottamuverkostossa käytetään termiä _palvelu_ tarkoittaen useita eri asioita. Liiteessä 3 kohdassa
[1. Operaattorin tarjoamat palvelut](haka_liite_3.html#oper-palvelut)
puhutaan verkoston toiminnan kannalta tarpeellisista peruspalveluista ja
Liitteessä 1 kohdassa
[palveluntarjoaja](haka_liite_1.html#palveluntarjoaja)
esitellään termi, jolla viitataan verkostoon liitettävään palveluun (Service Provider - SP).

Suomen vahvan säköisen tunnistamisen verkoston kehittämisessä ja muissa tunnistusratkaisuissa Hakan tarkoittaman _palveluntarjoaja_, tai _palvelu_ -termien sijasta on alettu käyttää termiä: _'asiointipalvelu'_.

Haka-verkoston käyttämä termistö on muutenkin ristiintarkistettava IAM-verkoston 
[sanaston](https://wiki.eduuni.fi/display/IAMVERKOSTO/Sanasto)
kanssa. Ristiin käytettävien termien rinnalle pitää löytää kuvaavampia ilmauksia sekaannuksien välttämiseksi.


#### Päivitysten aikataulusta päättäminen

[Liitteessä 2](haka_liite_2.html#paivitykset) kohdassa 3.1 Ohjausryhmä, todetaan ohjausryhmän tehtäviin kuuluvan

- luottamusverkoston versiopäivitysten aikataulun hyväksyntä

Hakassa käytetään laajalti Shibboleth-konsortion tuottamia ohjelmistoja, mutta tuotevalinta on sopijaosapuolelle avoin edellyttäen, että se täyttää verkoston tekniset vaatimukset.

Käytännössä versiopäivityksien aikataulun sanelee ohjelmistotoimittaja. Palvelusopimus velvoittaa yleisellä tasolla käyttämään tietoturvallisia ja ajantasaisesti ylläpidettyjä ohjelmistoja. On tarpeetonta erikseen ohjaysryhmän sanella erityistä aikataulua ohjelmistopäivityksille.

Suurissa versiopäivityksissä (kuten Shibboleth IdP versio 3) voi olla tarpeen tulkita, milloin jokin luottamusverkoston osapuoli ylittää rajan, jossa ei voida enää katsoa osapuolen käyttämän ohjelmiston toteuttavan ajantasaisen ja tietoturvallisen ohjelmiston käsitettä. Tällainen tulkinta tuskin antaa aihetta erikseen määritellä ohjelmistopäivityksille erityistä aikataulua.


### Ohjausryhmä ja sen tehtävät

[Liitteessä 2](haka_liite_2.html) kuvataan luottamusverkoston ohjausryhmä ja sen tehtävät. Viittauksia ohjausryhmään on myös ainakin varsinaisessa [jäsensopimuksessa](palvelusopimus_jasensopimus.html).

Haka-luottamusverkoston ohjaaminen saattaisi tarvita uudenlaista tarkastelua.


### Erilaisten sopimustyyppien yhdistäminen yhdeksi sopimukseksi

Hakaan liittyvät osapuolet jaetaan kahteen ryhmään:

- jäsenet
- kumppanit

Kummallekin ryhmälle on oma palvelusopimuksensa. Erilliset sopimukset noudattavat samaa kaavaa. Palvelusopimuksen liitteet ovat yhteiset molemmille sopimustyypeille ja ryhmät on tarkemmin kuvattu liitteessä 2. Erilliset sopimukset voitaisiin yhdistää yhdeksi sopimukseksi siten, että sopimuksessa erikseen määritellään kumpaan ryhmään osapuoli kuuluu.

### Tutkimuslaitosten lisääminen Hakaan sopimuksen perusteella

Liitteessä 2, [kohdassa 2.2 Osapuolet](haka_liite_2.html#osapuolet) luetellaan organisaatiot, jotka voivat liittyä verkostoon jäsenenä. Haka-ohjausryhmä on tehnyt [kokouksessaan 3-2016](https://wiki.eduuni.fi/x/wxmoAg) ennakkopäätöksen lailla perustettujen tutkimuslaitoksen lisäämisestä Hakaan.

Lailla perustetut tutkimuslaitokset voisi lisätä a-kategoriaan, jolloin Haka-ohjausryhmän tahtotila olisi noteerattu sopimuksen tasolla ja asiassa ei tarvittaisi muita erillisiä päätöksiä.

### Yliopistosairaaloiden liittyminen Hakaan

Liitteessä 2, [kohdassa 2.2 Osapuolet](haka_liite_2.html#osapuolet) on kategoriassa b on mainittu yliopistollisten sairaaloiden opetus ja tutkimustoimintaa tukevat yleishyödylliset tai julkisen tahon omistamat organisaatiot, joka on johtanut keskusteluun yliopistosairaaloiden liittymisestä Hakaan. Kuopion yliopistollinen sairaala on tämän sopimuskohdan perusteella liittynyt Hakan jäseneksi.

Yliopistollisten sairaaloiden yhteydessä on keskusteltu siitä, mikä organisaatio liittyy Hakan jäseneksi. Yliopistolliset sairaalat ovat organisaatioita sairaanhoitopiirieissä, jotka kuuluvat kuntayhtymään.

Yliopistosairaaloissa on joitakin tutkijoita, joiden on saatava vastaava pääsy palveluihin ja tietoiaineistoihin, joihin heidän tutkijakollegansa pääsevät ylipistoissa. Jotkin yliopistosairaaloiden työntekijät kuuluvatkin samanaikaisesti kahteen tai useampaan organisaation: yliopistosairaalan ja alueen yliopiston organisaatioihin. Voi siis olla mahdollista, että sairaalan tutkija saa pääsyn palveluihin ja aineistoihin Haka-kirjautumisella yliopistonsa kautta.

Sote- ja maakuntauudistuksen muuttaessa toimintakenttää entisestään lienee syytä uudelleen tarkastella yliopistosairaaloiden asemaa suhteessa Hakan jäsenyyteen.

### Teknisen ryhmän ja IAM-verkoston päällekäisyys

Vuoden 2008 sopimuksen perusteella Hakassa toimii sekä tekninen ryhmä, että IAM-verkosto. Käytännössä on osoittautunut, että ryhmät ovat pitkälti päällekäisiä. Teknisessä ryhmässä organisaatioita usein edustaa samat henkilöt, jotka ovat läsnä IAM-verkoston tapaamisissa.

Monet teknisen ryhmän päätettäväksi tulevat asiat esitellään IAM-verkoston tapaamisissa. Asiat tulevat käsitellyksi kahdesti, kun ne joudutaan IAM-verkoston tapaamisten lisäksi viemään erikseen tekniselle ryhmälle, joka esittelee asian edelleen ohjausryhmän päätettäväksi.

10 vuoden aikana, kun 2008 palvelusopimus on ollut voimassa, teknisen ryhmän kokouksia on ollut vain muutamia.

Lienee syytä tarkastella, josko IAM-verkosto voisi omaksua teknisen ryhmän roolin Hakassa ja ottaa tehtäväksi esitellä ohjausryhmälle sellaiset tekniset asiat, jotka on sopimuksen perusteella vietävä ohjausryhmän päätettäväksi.

