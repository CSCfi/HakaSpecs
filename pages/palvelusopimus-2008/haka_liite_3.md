---
title: Haka-luottamusverkosto - palvelusopimus
sidebar: home_sidebar
permalink: haka_liite_3.html
folder: palvelusopimus
---

## Liite 3. Palvelukuvaus ja vaatimukset

### <a name='oper-palvelut' />1. Operaattorin tarjoamat palvelut

Tässä luvussa esitellään Haka-luottamusverkoston operaattorin tarjoamat, luottamusverkoston toimintaan liittyvät peruspalvelut, joihin kaikilla luottamusverkoston jäsenillä on oikeus. Luottamusverkoston kumppaneilla on oikeus luvun 1.2. mukaisiin palveluihin.

Luottamusverkoston osapuolten jäsenyys- ja kumppanuusehdot on määritelty liitteessä 2.

#### 1.1. Osaamiskeskus

Operaattorilla on **testilaitteisto**, jossa luottamusverkoston toiminnallisuutta ja uusia komponentteja voidaan testata. Testilaitteisto sisältää SAML-tunnistuslähteen (SAML Identity Provider) ja SAML-palvelun (SAML Service Provider).

Operaattori järjestää luottamusverkoston käyttöönottoa ja kehittämistä tukevia **tapahtumia** ja edistää luottamusverkoston tunnettavuutta Suomen korkeakouluissa.

Operaattori toimii luottamusverkoston **ohjausryhmän** ja **teknisen työryhmän** kokoonkutsujana, valmistelijana ja sihteerinä.

Operaattori pitää yllä **kansainvälisiä yhteyksiä** muihin kansallisiin luottamusverkostoihin (federation) ja yhteistyöelimiin, sekä luottamusverkoston hyödyntämien tekniikoiden kehittäjiin.

#### 1.2. WAYF/DS-palvelin ja luottamusverkoston metatieto

Operaattori ylläpitää luottamusverkoston keskitettyä **WAYF/DS-palvelinta** (Where Are You From / Discovery Service) sekä luottamusverkostoon liittyvää metatietoa, johon sisältyy mm. 
- luottamusverkoston jäsenten ja kumppaneiden hallinnollisten ja teknisten henkilöiden yhteystiedot
- luottamusverkostoon liitettyjen palvelinten osoitteet
- luottamusverkostoon liittyneiden palveluntarjoajien palveluaan varten tarvitsemien attribuuttien luettelo sekä palvelun tietosuojaselosteen osoite, mikäli palvelu käsittelee henkilötietoja.

Operaattori asettaa luottamusverkoston metatiedot luottamusverkoston yksittäisten jäsenten tai kumppanien ja näiden mahdollisesti asettamien WAYF/DS-palvelimien saataville.

#### 1.3. Toiminnan suunnittelu ja viestintä

Operaattori huolehtii ohjausryhmän avulla luottamusverkoston toiminnan kehittämisen **suunnittelusta**. Kehittämisen tavoitteena on luottamusverkoston jäsenten muuttuvien tarpeiden tunnistaminen ja niihin reagoiminen.

Operaattori huolehtii luottamusverkoston tekemisestä tunnetuksi Suomen korkeakoulujen piirissä. **Viestinnän** tavoitteena on, että potentiaaliset kotiorganisaatiot ja palveluntarjoajat ovat tietoisia luottamusverkoston eduista ja mahdollisuuksista.

#### 2. Velvoitteet luottamusverkoston osapuolille

Luottamusverkko edellyttää luottamusverkoston osapuolilta tässä luvussa esitettyjä asioita.

##### 2.1. Operaattori

Sen lisäksi mitä luvussa 1 esitettiin,

2.1.1. Operaattori kokoaa ja testaa Shibboleth-väliohjelmistoa sekä mahdollisuuksien mukaan muita **ohjelmakomponentteja**, joita luottamusverkoston jäsenet ja kumppanit voivat käyttää luottamusverkostossa SAML-tunnistuslähteinä, -palveluna tai niitä tukevina työkaluina. 

2.1.2. Operaattori ryhtyy tarvittaviin toimenpiteisiin ylläpitämiensä luottamusverkoston palvelinten saumattoman **toiminnan varmistamiseksi** ja tarkkailemiseksi. Luottamusverkoston suunnitelluista huoltokatkoista ilmoitetaan etukäteen ja ne pyritään rajoittamaan luottamusverkoston ohjausryhmän etukäteen asettamiin huoltoaikoihin.

2.1.3. Operaattori järjestää luottamusverkoston jäsenten teknisille yhdyshenkilöille Helpdesk-**neuvontapalvelua** toiminnallisten ongelmien selvittelemiseksi. 

2.1.4. Operaattori informoi luottamusverkoston jäseniä ja kumppaneita luottamusverkostoa koskevista **turvapäivityksistä** ja -paikkauksista ja pyrkii pitämään luottamusverkoston turvallisena.

2.1.5. Operaattori kokoaa luottamusverkostossa käytettyä **funetEduPerson-skeemaa** koskevia muutospyyntöjä ja –tarpeita ja valmistelee niiden pohjalta luottamusverkoston tekniselle työryhmälle funetEduPerson-skeemaa koskevat muutosehdotukset. Lisäksi operaattori antaa kotiorganisaatioille ja palveluntarjoajille täsmentäviä ohjeita skeeman käytöstä ja eri attribuuttien syntaksista (kielioppi) ja semantiikasta (merkitys).

##### 2.2. Luottamusverkoston jäsenet ja kumppanit

2.2.1. Luottamusverkoston jäsenet ja kumppanit **asentavat ja päivittävät** luottamusverkostoon kytkettyjä komponenttejaan luottamusverkoston ohjausryhmässä hyväksytyn aikataulun mukaisesti.

2.2.2. Luottamusverkoston jäsenet ja kumppanit huolehtivat, että niiden käytössä oleva luottamusverkoston **metatieto** on ajan tasalla. 

2.2.3. Luottamusverkoston jäsenet ja kumppanit ilmoittavat operaattorille omia metatietojaan koskevista **muutoksista** välittömästi.

2.2.4. Luottamusverkoston jäsenet ja kumppanit ilmoittavat tekniset ja hallinnolliset **yhteyshenkilönsä** operaattorille.

2.2.5. Luottamusverkoston jäsenet ja kumppanit hankkivat palvelimiinsa **varmenteet** (certificate) luottamusverkoston ohjausryhmän hyväksymiltä varmentajilta (certificate authority).

2.2.6. Luottamusverkostojen jäsenet ja kumppanit huolehtivat palvelintensa tietoturvallisuudesta, suojaamisesta ja turvapäivityksistä asianmukaisesti.

##### 2.3. Kotiorganisaatiot erityisesti

Vain luottamusverkoston jäsenet voivat toimia kotiorganisaationa (home organisation, identity provider, credential provider)

2.3.1. Kotiorganisaatiot **asentavat** luottamusverkoston edellyttämän SAML-tunnistuslähteen ja muut tarpeelliset komponentit ja kytkevät ne organisaatiossa paikallisiin käyttäjähallintojärjestelmiin.

2.3.2. **Antaessaan käyttäjätunnuksen** uudelle loppukäyttäjälle kotiorganisaatio todentaa käyttäjätunnuksen saajan henkilöllisyyden luottamusverkoston toimintakäytäntöjen mukaisesti sekä vaatii, että käyttäjä hyväksyy ja sitoutuu noudattamaan kotiorganisaationsa käyttösääntöjä. 

2.3.3. Kotiorganisaatio **todentaa** loppukäyttäjän henkilöllisyyden salasanalla tai tätä luotettavammalla keinolla, kun loppukäyttäjä pyrkii luottamusverkostoon kytkettyihin palveluihin. 

2.3.4. Jos henkilöllisyyden todentamiseen käytetään **salasanoja**, kotiorganisaatio vaatii loppukäyttäjää valitsemaan vähintään kahdeksan merkkiä pitkiä salasanoja ja pyrkii estämään huonolaatuisten salasanojen käytön. Suositellaan, että kotiorganisaatio pakottaa loppukäyttäjän vaihtamaan salasanansa säännöllisesti.

2.3.5. Kotiorganisaatioiden omista käyttäjistään keräämien ja luottamusverkostossa tarjoamien **henkilötietojen** tulee noudattaa ainakin FunetEduPerson ver 2.1 –skeemaa ja sen mahdollisia myöhempiä päivityksiä. Ainakin skeeman pakollisiksi nimeämille attribuuteille tulee antaa arvo. Monet palvelut tulevat kuitenkin edellyttämään arvoa myös muille attribuuteille.

2.3.6. Kotiorganisaatiot varmistavat asiaankuuluvaa huolellisuutta noudattaen, että vain **virheettömiä, ajantasaisia ja palvelun kannalta tarpeellisia** henkilötietoja luovutetaan palveluntarjoajalle.

2.3.7. Kotiorganisaatio pitää ajan tasalla henkilötietojen **luovutuslupia** (Attribute release policy, ARP), jotka säätelevät, mitä henkilötietoja kustakin loppukäyttäjästä luovutetaan kullekin palvelulle.

2.3.8. Kotiorganisaatio pyytää lähtökohtaisesti loppukäyttäjältä **suostumuksen** henkilötietojen luovuttamiselle kuhunkin palveluun (suostumusmalli liitteessä 7). Loppukäyttäjälle on varattava mahdollisuus tutustua palvelun tietosuojaselosteeseen ennen suostumuksen antamista.

2.3.9. Kotiorganisaatio kerää henkilötietolain säädökset huomioiden **lokia**, joka sisältää ainakin nimitunnisteen (name identifier) niin, että käyttäjä voidaan yhdistää palveluntarjoajalle annettuun tunnistusselosteeseen (SAML assertion).

2.3.10. Kotiorganisaatio **informoi** loppukäyttäjää siitä, mitä tietoja kotiorganisaatio kerää palvelujen käyttämisestä, mihin kerättyä tietoa käytetään ja mahdollisesti luovutetaan.

2.3.11. Kotiorganisaatio järjestää luottamusverkostoon liittyvien ongelmien selvittelyä varten **helpdeskin** oman organisaationsa loppukäyttäjille.

2.3.12. Kotiorganisaatio laatii **käyttäjähallinnostaan kuvauksen** niiltä osin kuin sillä on merkitystä kotiorganisaationa toimimiselle luottamusverkostossa. Kuvaus on asetettava muiden luottamusverkoston jäsenten ja kumppanien saataville.

##### 2.4. Palveluntarjoajat erityisesti

Sekä luottamusverkoston jäsenet että kumppanit voivat toimia palveluntarjoajana (service provider).

2.4.1. Palveluntarjoajat **asentavat** luottamusverkoston edellyttämän SAML-palvelun ja muut tarpeelliset komponentit ja kytkevät ne palveluunsa.

2.4.2. Palveluntarjoaja ilmoittaa operaattorille, mitkä attribuutit ovat palvelun kannalta **tarpeellisia**.

2.4.3. Jos palveluntarjoaja käsittelee henkilötietolain tarkoittamia henkilötietoja, ilmoittaa palveluntarjoaja operaattorille, missä www-osoitteessa palvelun **tietosuojaselosteeseen** voi etukäteen tutustua. Jos henkilötietojen käsittelytarkoitusta palvelussa muutetaan, toimitaan kuin jos palvelu kytkettäisiin luottamusverkostoon uutena palveluna.

2.4.4. Palveluntarjoaja valvoo, että vain palvelun **käyttöön oikeutetut loppukäyttäjät** pääsevät sisälle palveluun. Pääsynvalvonnassa apuna voidaan käyttää kotiorganisaatiolta saatuja attribuutteja.

2.4.5. Palveluntarjoajan tulee kerätä henkilötietolain säädökset huomioiden **lokia**, joka sisältää ainakin nimitunnisteen (name identifier). Palveluntarjoaja luovuttaa väärinkäytösten selvittelyä varten tarpeelliset lokitiedot kotiorganisaatiolle.

### 3. Yhteistyöjärjestelyt muiden luottamusverkostojen kanssa

Operaattori voi solmia luottamusverkostoa koskevia sopimuksia ulkomaisten tunnistamispalveluja tarjoavien luottamusverkostojen kanssa. Yhteistyöjärjestelyjen tarkoitus on tukea Haka-luottamusverkoston jäsenten toiminnan kansainvälistä verkostoitumista ja yhteistyötä. Haka-luottamusverkoston liittymisestä yhteistyöjärjestelyyn päättää ohjausryhmä.

Haka-luottamusverkostoon rekisteröidyn SAML-tunnistuslähteen tai –palvelun näkyminen ja mukanaolo ulkomaisessa yhteistyöjärjestelyssä perustuu aina tunnistuslähteen tai palvelun asettaneen jäsenen tai kumppanin pyyntöön. 

Yhteistyöjärjestelyjen kautta Haka-luottamusverkoston jäsenten ja kumppanien saataville tulee metatietoa ulkomaisista SAML-tunnistuslähteistä ja –palveluista, jotka pääsääntöisesti eivät ole sitoutuneet tämän sopimuskokonaisuuden velvoitteisiin. Tällöin operaattori esittää yhteistyöjärjestelyjen kautta tulleen metatiedon jäsenille ja kumppaneille siten, että se on selkeästi erotettavissa Haka-luottamusverkon metatiedosta. Lisäksi operaattori ylläpitää tietoa keskeisistä toimintakäytäntöihin ja –ehtoihin liittyvistä eroista, joita yhteistyöjärjestelyjen kautta tulevilla ulkomaisilla SAML-tunnistuslähteillä ja palveluilla on tähän sopimuskokonaisuuteen sitoutuneisiin osapuoliin verrattuna. 

