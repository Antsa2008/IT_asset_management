# harjoitus_projekti

IT Asset Management
1. Projektin tarkoitus
IT Asset Management on selainpohjainen sovellus, jonka tarkoituksena on helpottaa yrityksen IT-omaisuuden hallintaa.

Sovelluksella voidaan hallita yrityksen IT-laitteita, työntekijöitä sekä ohjelmistolisenssejä yhdessä käyttöliittymässä.
Tavoitteena on tarjota selkeä ja helppokäyttöinen kokonaisuus, jonka avulla IT-omaisuuden tietoja voidaan ylläpitää ja seurata.
Sovellus sisältää Dashboard-näkymän, josta voidaan tarkastella IT-omaisuuden keskeisiä tunnuslukuja sekä lähestyviä takuiden päättymisiä ja ohjelmistolisenssien uusimispäiviä.

2. Käytetyt teknologiat
Projektissa on käytetty seuraavia teknologioita:

HTML5: Sovelluksen rakenteen ja lomakkeiden toteuttaminen.
CSS3: Sovelluksen ulkoasun, asettelun, animaatioiden ja responsiivisuuden toteuttaminen.
JavaScript: Sovelluksen toiminnallisuudet, tietojen käsittely, näkymien vaihtaminen ja tapahtumien hallinta.
Bootstrap 5.3.2: Käyttöliittymän komponentit, kuten taulukot, painikkeet, lomakkeet, kortit ja modaalit.
LocalStorage: Tietojen tallentaminen selaimen paikalliseen tallennustilaan.
Sovellus toimii selaimessa eikä vaadi erillistä palvelinta tai tietokantaa.

3. Sovelluksen käynnistäminen
Vaatimukset
Sovelluksen käyttämiseen tarvitaan:

Nykyaikainen verkkoselain, esimerkiksi Google Chrome, Mozilla Firefox tai Microsoft Edge.
Projektin lähdetiedostot.
Internet-yhteys Bootstrapin lataamista varten CDN-palvelusta.

Käynnistysohje
Lataa tai kloonaa projektin tiedostot omalle tietokoneelle.
Varmista, että kaikki projektin tiedostot ovat samassa projektikansiossa oikeilla tiedostonimillä.
Avaa projektin index.html-tiedosto verkkoselaimessa.
Sovellus käynnistyy automaattisesti.
Erillistä asennusta, palvelimen käynnistämistä tai tietokannan määrittämistä ei tarvita.

Huomio: Sovelluksen käyttö edellyttää internet-yhteyttä Bootstrapin CDN-linkkien lataamista varten.

4. Tärkeimmät toiminnallisuudet
4.1 Dashboard
Dashboard tarjoaa yleiskuvan organisaation IT-omaisuudesta.

Näkymässä näytetään:

IT-laitteiden kokonaismäärä.
Käytössä olevien laitteiden määrä.
Varastossa olevien laitteiden määrä.
Huollossa olevien laitteiden määrä.
Ohjelmistolisenssien kokonaismäärä.
Vapaana olevien lisenssien määrä.
Järjestelmään tallennettujen käyttäjien määrä.
Seuraavan 30 päivän aikana päättyvät laitteiden takuut.
Seuraavan 30 päivän aikana uusittavat ohjelmistolisenssit.
4.2 Laitteiden hallinta
Sovelluksella voidaan hallita organisaation IT-laitteita.

Laitteiden hallinnan ominaisuuksia:

Uusien laitteiden lisääminen.
Olemassa olevien laitteiden tietojen muokkaaminen.
Laitteiden poistaminen.
Laitteiden hakeminen hakusanan perusteella.
Laitteiden suodattaminen laitetyypin ja tilan mukaan.
Laitteiden käyttäjätietojen ylläpitäminen.
Laitteista voidaan tallentaa seuraavia tietoja:

Laitetyyppi.
Valmistaja.
Malli.
Sarjanumero.
Käyttäjä.
Laitteen tila.
Hankintahinta.
Hankintapäivä.
Takuun päättymispäivä.
Lisätiedot.
Laitteen tilavaihtoehdot ovat:

Käytössä.
Varastossa.
Huollossa.
Sovellus tarkistaa myös, ettei samaa sarjanumeroa lisätä usealle laitteelle.

4.3 Käyttäjien hallinta
Käyttäjien hallinnassa voidaan ylläpitää organisaation työntekijöiden tietoja.

Toiminnallisuudet:

Uusien käyttäjien lisääminen.
Käyttäjätietojen muokkaaminen.
Käyttäjien poistaminen.
Käyttäjien hakeminen hakusanan perusteella.
Käyttäjälle liitettyjen laitteiden määrän näyttäminen.
Käyttäjistä tallennetaan:

Koko nimi.
Sähköpostiosoite.
Osasto.
Tehtävänimike.
Sovellus tarkistaa, ettei samaa sähköpostiosoitetta tai nimeä lisätä usealle käyttäjälle.

Jos käyttäjän nimi muuttuu, myös käyttäjälle liitettyjen laitteiden käyttäjämerkinnät päivitetään automaattisesti.

Käyttäjää ei voida poistaa, jos hänellä on vielä laitteita liitettynä.

4.4 Ohjelmistolisenssien hallinta
Lisenssien hallinnassa voidaan seurata organisaation ohjelmistolisenssejä ja niiden käyttöastetta.

Toiminnallisuudet:

Uusien ohjelmistolisenssien lisääminen.
Lisenssitietojen muokkaaminen.
Lisenssien poistaminen.
Lisenssien kokonaismäärän seuraaminen.
Käytössä olevien lisenssien määrän seuraaminen.
Vapaiden lisenssien määrän laskeminen.
Lisenssien uusimispäivien seuranta.
Lisenssikustannusten ylläpitäminen.
Lisensseistä tallennetaan:

Ohjelmiston nimi.
Toimittaja.
Lisenssien kokonaismäärä.
Käytössä olevien lisenssien määrä.
Uusimispäivä.
Kustannus.
Sovellus tarkistaa, ettei käytössä olevien lisenssien määrä ylitä lisenssien kokonaismäärää.

5. Projektin rakenne
Projektin tiedostorakenne on seuraava:


IT-Asset-Management/
│
├── index.html
├── styles.css
├── script.js
└── README.md
Tiedostojen kuvaukset:

index.html: Sovelluksen HTML-rakenne. Sisältää navigaation, pääsisältöalueen sekä laitteiden, käyttäjien ja lisenssien lisäys- ja muokkauslomakkeet.
styles.css: Sovelluksen visuaalinen ilme, värit, asettelut, animaatiot ja responsiiviset tyylit.
script.js: Sovelluksen JavaScript-toiminnallisuudet. Sisältää tietojen tallentamisen, näkymien hallinnan, hakutoiminnot sekä laitteiden, käyttäjien ja lisenssien CRUD-toiminnot.
README.md: Projektin dokumentaatio ja käyttöohjeet.
6. Tietojen tallennus
Sovellus käyttää selaimen LocalStorage-tallennustilaa tietojen säilyttämiseen.

Tallennettavat tietokokonaisuudet ovat:

devices: IT-laitteiden tiedot.
users: Käyttäjien tiedot.
licenses: Ohjelmistolisenssien tiedot.
Tietoja käsitellään JavaScript-objekteina ja -taulukoina, jotka muunnetaan JSON-muotoon tallennuksen yhteydessä.

Tallennetut tiedot säilyvät selaimen tallennustilassa myös sivun uudelleenlataamisen jälkeen.

7. Tunnetut rajoitukset
Projektin nykyisessä versiossa on seuraavia rajoituksia:

Selainkohtainen tallennus: Tiedot tallennetaan LocalStorageen, joten ne ovat käytettävissä vain kyseisessä selaimessa ja kyseisellä laitteella.
Ei palvelinpuolen tietokantaa: Sovelluksessa ei ole erillistä tietokantaa tai taustapalvelinta.
Ei käyttäjätunnistautumista: Sovelluksessa ei ole kirjautumisjärjestelmää tai käyttäjäkohtaisia käyttöoikeuksia.
Ei automaattista varmuuskopiointia: Tallennetut tiedot voivat kadota esimerkiksi selaimen tietojen tyhjentämisen yhteydessä.
Ei reaaliaikaista synkronointia: Eri käyttäjien tai laitteiden välillä ei ole tietojen synkronointia.
Rajoitettu käyttäjien ja laitteiden välinen yhteys: Laitteet yhdistetään käyttäjiin tällä hetkellä käyttäjän nimen perusteella.
Ei automaattisia ilmoituksia: Takuiden ja lisenssien uusimispäivistä näytetään muistutukset Dashboardissa, mutta sovellus ei lähetä sähköposti- tai muita ulkoisia ilmoituksia.
Ei erillistä käyttöoikeuksien hallintaa: Kaikki sovellusta käyttävät voivat tehdä samoja toimintoja.
8. Mahdolliset jatkokehitysideat
Sovellusta voidaan kehittää edelleen esimerkiksi seuraavilla ominaisuuksilla:

Tietokannan käyttöönotto: LocalStorage-tallennuksen korvaaminen palvelinpuolen tietokannalla, esimerkiksi MySQL:llä tai PostgreSQL:llä.
Kirjautumisjärjestelmä: Käyttäjätunnusten ja salasanojen lisääminen sekä käyttöoikeuksien hallinta.
Varmuuskopiointi: Tietojen automaattinen varmuuskopiointi ja palautusmahdollisuus.
Excel- ja CSV-vienti: Laitteiden, käyttäjien ja lisenssien tietojen vieminen tiedostoihin.
Ilmoitusjärjestelmä: Automaattiset sähköposti-ilmoitukset lähestyvistä takuiden päättymisistä ja lisenssien uusimisista.
Laitteiden luovutushistoria: Laitteiden aikaisempien käyttäjien ja luovutuspäivien tallentaminen.
Lisenssien kustannusraportointi: Lisenssikustannusten tarkempi seuranta ja raportointi.
Laitteiden huoltohistorian hallinta: Huoltotoimenpiteiden, huoltopäivien ja huoltokustannusten kirjaaminen.
Käyttäjien ja laitteiden välisen yhteyden parantaminen: Käyttäjien yhdistäminen laitteisiin yksilöllisten tunnisteiden avulla nimen sijaan.
Käyttöliittymän jatkokehitys: Esimerkiksi Dashboardin graafiset tilastot, lisäsuodattimet ja raportointinäkymät.
9. Yhteenveto
IT Asset Management on selainpohjainen IT-omaisuuden hallintasovellus, jonka avulla voidaan ylläpitää organisaation laite-, käyttäjä- ja lisenssitietoja.

Projektin nykyinen versio toteuttaa keskeiset tietojen lisäämiseen, tarkasteluun, muokkaamiseen ja poistamiseen liittyvät toiminnot.

Sovellus toimii ilman erillistä palvelinta ja käyttää selaimen LocalStoragea tietojen tallentamiseen. Jatkokehityksessä sovellusta voidaan laajentaa esimerkiksi tietokannan, kirjautumisen, raportoinnin ja automaattisten ilmoitusten avulla.


