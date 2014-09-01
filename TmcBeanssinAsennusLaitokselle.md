# Ilmoittautuminen

1. Mene osoitteeseen http://tmc.mooc.fi/hy
2. Klikkaa oikeassa yläkulmassa linkkiä "Sign up"
3. Käytä käyttäjätunnuksenasi (Username) opiskelijanumeroasi (opiskelijanumerosi löydät opiskelijakortista ja [weboodin vasemmasta yläreunasta](http://weboodi.helsinki.fi/hy/)). Muuten suorituksesi ei rekisteröidy!
3.1. Mikäli loit tunnuksen väärällä nimellä, kerro siitä pajassa, voimme uudelleennimetä tunnuksen tai IRCssä Jamo:lle  (~jamo@irc.jamo.io @IRCnet).
4. Syötä muut tiedot ja paina nappia Sign up. Muista salasanasi.
5. Asenna TMC-NetBeans bundle laitoksen koneelle. Jos koneellasi on jo uusi NetBeans versio 8 tai parempi, voit asentaa vain TMC liitännäisen siihen. Siirry seuraamaan ohjetta [täältä](https://github.com/UniversityHelsinkiTKTL/tmc-plugin-installation-guide/blob/master/NetbeansPlugininAsennus.md).

# TMC palvelimesta lyhyesti

Tehtävät palautetaan TestMyCode-järjestelmään joka tarkastaa palautukset automaattisesti. TMC myös tarjoaa opiskelijoille tehtäväpohjat ja automaattiset testit koodin oikeellisuuden tarkistamiseen.

## TMC-netbeanssin asennus

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

Tarkista, että TMC-> Settings asetuksissa palvelimen osoite on
`http://tmc.mooc.fi/hy` ja valitse kurssiksi `s2014-ohpe` (tai toisaalla
mainittu oikeampi kurssi).


## NetBeansin käynnistys ja asetusten asettaminen

Kun NetBeans aukeaa ensimmäisen kerran, allaolevan asetusikkunan pitäisi aueta. Saat sen tarvittaessa avattua: NetBeanssissa TMC -> Settings

![TMC plugins settings](https://www.cs.helsinki.fi/u/jarmoiso/tmcee/tmc-settings.jpg "TMC plugins settings")

Käytä tunnuksina äsken luomiasi tunnuksia.
Tarkista, että palvelimen osoite on https://tmc.mooc.fi/hy
Klikkaa "refresh list" ja valitse viereisestä pudotusvalikosta kurssi `s2014-ohpe`

Pidäthän alimman checkboxin ruksattuna - tuet laitoksemme tekemää tutkimusta!

Valitse ok, ja voit ladata uusia tehtäviä, mikäli niitä on saatavilla.
