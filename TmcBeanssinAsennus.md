# Ilmoittautuminen

1. Mene osoitteeseen http://tmc.mooc.fi/hy
2. Klikkaa oikeassa yläkulmassa linkkiä "Sign up"
3. Käytä käyttäjätunnuksenasi (Username) opiskelijanumeroasi (opiskelijanumerosi löydät opiskelijakortista ja [weboodin vasemmasta yläreunasta](http://weboodi.helsinki.fi/hy/)). Muuten suorituksesi ei rekisteröidy!  
3.1. Mikäli loit tunnuksen väärällä nimellä, kerro siitä pajassa, voimme uudelleennimetä tunnuksen tai IRCssä Jamo:lle  (~jamo@irc.jamo.io @IRCnet). 
4. Syötä muut tiedot ja paina nappia Sign up. Muista salasanasi.
5. Asenna TMC-NetBeans bundle laitoksen koneelle ja omalle koneelle. Halutessasi voit asentaa vain TMC pluginin. kts [ohje](https://github.com/UniversityHelsinkiTKTL/tmc-plugin-installation-guide/blob/master/NetbeansPlugininAsennus.md)

# TMC palvelimesta lyhyesti

Tehtävät palautetaan TestMyCode-järjestelmään joka tarkastaa palautukset automaattisesti. TMC myös tarjoaa opiskelijoille tehtäväpohjat ja automaattiset testit koodin oikeellisuuden tarkistamiseen.


## TMC-netbeanssin asennus

### Jos käytät laitoksen koneita, seuraa seuraavaa ohjetta: (omaa konetta käyttävät kts alempana)

Käytä Ubuntua, eli Linuxia. Jos kone mihin kirjaudut on Windowsissa, käynnistä se uudestaan ja valitse Ubuntu. Klikkaa seuraavaa linkkiä hiiren oikealla näppäimellä, ja valitse "Save Location As.." (tai Save as.. tai Save Link As...)

* [Linux](http://update.testmycode.net/installers/tmc-netbeans_hy/tmc-netbeans_hy_tmcbeans-linux.sh)

Tiedosto ladataan oletuksena käyttäjätunnuksesi Downloads-hakemistoon. 

Lisää tiedostolle suoritus oikeudet, komentorivillä `chmod +x tmc-netbeans_hy_tmcbeans-linux.sh` oikeassa kansiossa ollessasi tai seuraamalla alla olevia yksityiskohtaisempia ohjeita

Klikkaa vasemmassa ylälaidassa olevaa palloa, ja kirjoita aukeavaan ikkunaan Home. Valitse Home folder. Klikkaa kansiossa Downloads-kansiota, jotta pääset kansioon. Klikkaa tämän jälkeen oikealla hiirennäppäimellä tiedostoa `tmc-netbeans_hy_tmcbeans-linux.sh`, valitse avautuvasta valikosta Properties. Kun eteesi avautuu ikkuna, valitse Permissions, ja ruksaa "Allow executing file as a program" valituksi. 

Klikkaa tämän jälkeen vasemmassa yläkulmassa olevaa palloa, ja etsi ohjelma nimeltä "Terminal". Käynnistä se. Mene Downloads-kansioon kirjoittamalla "cd Downloads". 

```bash
tunnus@kone:~$ cd Downloads/
tunnus@kone:~/Downloads$ 
``` 

Kirjoita tämän jälkeen `./tmc-netbeans_hy_tmcbeans-linux.sh` ja paina enter. Asennusohjelman pitäisi käynnistyä.

```bash
tunnus@kone:~/Downloads$ ./tmc-netbeans_hy_tmcbeans-linux.sh 
```

Seuraa ohjeita. 

### Jos teet tätä omalla koneellasi, seuraa seuraavaa ohjetta:

Suosittelemme asentamaan valmiin NetBeans with TMC bundlen, jossa NetBeans ja TMC tulevat valmiina. Saat käyttöjärjestelmällesi sopivan version alta. Ohjelman asennus tapahtuu aivan kuten NetBeanssin asennus. Asenna kuitenkin ensin Java JDK!

### Asenna Java JDK (jos ei ole jo asennettuna)

Suosittelemme kurssilla käytettävän Java 8 mutta myös java 7:llä voi kurssille osallistua. Katso asennusohjeet alta.
Java on saatavissta kaikille nykyaikaisille käyttöjärjestelmille.

Lataa JDK:n uusin versio "Java SE Development Kit 8u20" (tai uudempi) osoitteesta http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html . Jos koneesi on Linux. kts myös maininta alla.

* Windowsissa asentaminen onnistuu, kuten minkä tahansa muun Windows-ohjelman asentaminen.
* Macissa asennus tapahtuu kuin minkä tahansa dmg-paketin asennus. HUOM: Tarvitset Mac OS X 10.7.3:n (Lion) tai uudemman OS X (vanhemmilla joudut käyttämään vanhempaa javaa, Google tai assari auttaa)
* Useimmissa Linux-järjestelmissä tuoreen Javan saat myös suoraan paketienhallinnasta. Debian-pohjaisissa Linuxeissa (esim. Ubuntu) riittää paketin openjdk-7-jdk asentaminen. Voit asentaa sen komentoriviltä komennolla `apt-get install openjdk-7-jdk -y`, tai Synaptic Package managerin avulla. Mikäli tuoretta Javaa ei pakettienhallinnasta löydy, tapahtuu asentaminen purkamalla Oraclen sivulla oleva .tar.gz-päätteinen pakattu tiedosto sopivaan paikkaan.


### Asenna tmc-netbeans

* [Linux](http://update.testmycode.net/installers/tmc-netbeans_hy/tmc-netbeans_hy_tmcbeans-linux.sh)
* [MAC](http://update.testmycode.net/installers/tmc-netbeans_hy/tmc-netbeans_hy_tmcbeans-macosx.tgz)
* [Windows](http://update.testmycode.net/installers/tmc-netbeans_hy/tmc-netbeans_hy_tmcbeans-windows.exe)

Tarkista, että TMC-> Settings asetuksissa palvelimen osoite on `http://tmc.mooc.fi/hy` ja valitse kurssiksi `s2014-ohpe`.


## NetBeansin käynnistys ja asetusten asettaminen

Kun NetBeans aukeaa ensimmäisen kerran, allaolevan asetus ikkunan pitäisi aueta. Saat sen tarvittaessa avattua: NetBeanssissa TMC -> Settings

![TMC plugins settings](https://www.cs.helsinki.fi/u/jarmoiso/tmcee/tmc-settings.jpg "TMC plugins settings")  

Käytä tunnuksina äsken luomiasi tunnuksia.  
Tarkista, että palvelimen osoite on http://tmc.mooc.fi/hy  
Klikkaa "refresh list" ja valitse viereisestä pudotusvalikosta kurssi `s2014-ohpe`  

Pidäthän alimman checkboxin ruksattuna - tuet laitoksemme tekemää tutkimusta!

Valitse ok, ja voit ladata uusia tehtäviä, mikäli niitä on saatavilla.
