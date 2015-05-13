# Tunnuksen luominen tehtäväjärjestelmään (TMC)

1. Mene osoitteeseen [http://tmc.mooc.fi/hy](http://tmc.mooc.fi/hy)
2. Klikkaa oikeassa yläkulmassa linkkiä "Sign up"
3. Käytä käyttäjätunnuksenasi (Username) opiskelijanumeroasi (opiskelijanumerosi löydät opiskelijakortista ja [weboodin vasemmasta yläreunasta](http://weboodi.helsinki.fi/hy/)). Muuten suorituksesi ei rekisteröidy!
    1. Mikäli loit tunnuksen väärällä nimellä, kerro siitä pajassa, voimme uudelleennimetä tunnuksen tai IRCssä Jamo:lle  (~jamo@irc.jamo.io @IRCnet).
4. Syötä muut tiedot ja paina nappia Sign up. Muista salasanasi.
5. Asenna omalle koneelle. Jos koneellasi on jo uusi NetBeans versio 8 tai parempi, voit asentaa vain TMC liitännäisen siihen. Ohje liitännäisen lisäämiseen NetBeansiin löytyy  [täältä](https://github.com/UniversityHelsinkiTKTL/tmc-plugin-installation-guide/blob/master/NetbeansPlugininAsennusOlemassaOlevaanNetBeansiin.md).

# TMC palvelimesta lyhyesti

Test My Code tarjoaa tukea ohjelmointiin. Sen avulla ladataan viikoittaisia tehtäviä, tarkastetaan tehtäviä, sekä palautetaan tehtäviä.


## TMC-netbeanssin asennus

### Asenna Java JDK (jos ei ole jo asennettuna)

Tehtävien tekemiseen tarvitaan Java 8 tai uudempi. Katso asennusohjeet alta.
Java on saatavissa kaikille nykyaikaisille käyttöjärjestelmille.

Lataa JDK:n uusin versio "Java SE Development Kit 8u20" (tai uudempi) osoitteesta http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html . Jos koneesi on Linux. kts myös maininta alla.

* Windowsissa asentaminen onnistuu, kuten minkä tahansa muun Windows-ohjelman asentaminen.
* Macissa asennus tapahtuu kuin minkä tahansa dmg-paketin asennus. HUOM: Tarvitset Mac OS X 10.8:n (Mountain Lion) tai uudemman OS X version
* Linuxissa asentaminen tapahtuu purkamalla Oraclen sivulla oleva .tar.gz-päätteinen pakattu tiedosto sopivaan paikkaan.


### Asenna tmc-netbeans

Lataa käyttöjärjestelmällesi sopiva versio

* [Linux](http://update.testmycode.net/installers/tmc-netbeans_hy/tmc-netbeans_hy_tmcbeans-linux.sh)
* [MAC](http://update.testmycode.net/installers/tmc-netbeans_hy/tmc-netbeans_hy_tmcbeans-macosx.tgz)
* [Windows](http://update.testmycode.net/installers/tmc-netbeans_hy/tmc-netbeans_hy_tmcbeans-windows.exe)

#### Asennus Windowsille

Asennus tapahtuu windowsissa kuten minkä tahansa muun ohjelman asennus; lataat .exe tiedoston (kts. linkit yllä). Kun tiedosto on ladattu, suorista se tuplaklikkaamalla sitä.
Seuraa asennus wizardia ja hyväksy tarvittaessa käyttöehdot.

#### Asennus OSXlle

Asennus tapahtuu OSXssä pitkälti kuin minkä tahansa muunkin ohjelman asennus.
Ladattuasi ylläolevista linkeistä asennuspaketin (.tar.gz) tuplaklikkaa sitä, niin OSX purkaa 'zip'istä ohjelman jolla asennus hoituu.
Tämän jälkeen tuplaklikkaa äsken syntynyttä tiedostoa
Seuraa asennusohjelmaa ja hyväksy tarvittaessa käyttöehdot.

Mikäli asennusohjelman käynnistys ei tuplaklikkaamalla onnistu, kokeile avata se klikkaamalla sitä 'hiiren oikealla' tai klikkaamalla sitä pitäen option tai control näppäintä pohjassa, ja valitsemalla avautuvasta valikosta Open/Avaa

#### Asennus Linuxille 

Linuxilla voit joutua antamaan ohjelmalle suoritus oikeudet (joko `chmod +x tmc-netbeans_hy_tmcbeans-linux.sh` tai klikkaamalla sitä hiiden oikealla, valitsemalla Properties ja sieltä ruksaa "Allow executing file as a program". Tämän jälkeen riippuen käyttöjärjestelmästä, joko tuplaklikkaa asennuspakettia ja se aukeaa, tai suorita se komentoriviltä `./tmc-netbeans_hy_tmcbeans-linux.sh`.

## NetBeansin käynnistys ja asetusten asettaminen

Kun NetBeans aukeaa ensimmäisen kerran, allaolevan asetus ikkunan pitäisi aueta. Saat sen tarvittaessa avattua: NetBeanssissa TMC -> Settings

![TMC plugins settings](https://www.cs.helsinki.fi/u/jarmoiso/tmcee/tmc-settings.jpg "TMC plugins settings")

Käytä tunnuksina äsken luomiasi tunnuksia.
Tarkista, että palvelimen osoite on http://tmc.mooc.fi/hy
Klikkaa "refresh list" ja valitse viereisestä pudotusvalikosta kurssi `kesa2015-ohpe`

Pidäthän alimman checkboxin ruksattuna - tuet laitoksemme tekemää tutkimusta!

Valitse ok, ja voit ladata uusia tehtäviä, mikäli niitä on saatavilla.


# TMC-Tehtävien tekeminen ja palauttaminen (video)

[![Tehtävien tekeminen ja palauttaminen](http://img.youtube.com/vi/sQYq2LISMRU/0.jpg)](https://youtu.be/sQYq2LISMRU)

<https://youtu.be/sQYq2LISMRU>
