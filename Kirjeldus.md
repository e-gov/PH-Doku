---
permalink: Kirjeldus
---

## Üldandmed ja kontekst

### Pääsukese eesmärk

Korrastada Eesti digiriigi volituste süsteem, pakkudes keskset, selget ja kasutajasõbralikku platvormi ligipääsuvolituste haldamiseks. Süsteem säästab teisi asutusi vajadusest luua ja hallata oma volituste süsteeme.

### Seos äriprotsessidega

Pääsuke toetab juriidiliste ja füüsiliste isikute esindusõiguste ja volituste kontrolli ning delegeerimist teistes riigi või erasektori infosüsteemides.

### Omanikud ja osapooled

Infosüsteemi omanik ja arendaja on **Riigi Infosüsteemi Amet (RIA)**.

Liidestuva infosüsteemi omanik vastutab enda infosüsteemiga seotud volituste äriloogika toimimise ning juriidilise korrektsuse eest.

RIA saab pakkuda kasutajatuge volituste andmiseks, tingimusel, et liidestuva infosüsteemi omanik on RIA-le edastanud selge ja üheselt mõistetava ärikirjelduse (mis volitusi, kellele ja millistel tingimustel on õigus anda). Lisada vabas vormis ärikirjeldus/juhis toodangu taotlusele.

## Kasutajad ja rollid

### Sihtrühm

Infosüsteemi lõppkasutajad on füüsilised isikud, kes tegutsevad mingis rollis.

Lõppkasutajad on liidestunud infosüsteemi kasutajad ning liidestuva infosüsteemi omaniku töötajad (nt kasutajatoe rollis olevad isikud).

Pääsukest saavad kasutada vaid eesti isikutunnistust omavad isikud ja Eestis registreeritud juriidilised isikud.

### Kasutajarollid

Lõppkasutaja rollid:

* **Seadusest tulenev esindaja:** Isik, kellel on Äriregistri andmetel õigus juriidilist isikut kõikides toimingutes esindada. Pääsuke tuvastab nii ainuesindusõiguse, ühisesindusõiguse kui esindusõiguse erisuse kui see on korrektselt Äriregistris kajastatud (masinloetaval kujul).
* **Esindatav:** Isik (sh juriidiline isik), kes annab teisele isikule volituse enda nimel tegutseda.
* **Esindaja:** Isik, kes saab õiguse esindatava nimel määratud rollis tegutseda.

## Äriteenused ja funktsionaalsus 


### Pakutavad teenused

1. **Volituste haldamise kasutajaliides** on integreeritud riigiportaali eesti.ee ja on kättesaadav lehelt "Volitused".

Volituste haldamise kasutajaliideses on võimalik:

* volitusi vaadata
* volitusi lisada
* volitusi edasi volitada
* volitusi kopeerida
* volitustest loobuda
* volitusi tagasi võtta
* volitusi taotleda
* volitusi digiallkirjastada

Detailse ülevaate kasutajaliidese võimalustest saab Pääsukese [DEMO videost](https://www.youtube.com/watch?v=Pq4PZ2dPo_0&list=PLNPWRftK1TNp9GZtHUw3jjIXOK3CMuUA2&index=4&t=81s.) ja [Volituste haldamise juhendist](https://www.eesti.ee/static/files/Volituste_juhend_EE.pdf)

Lähiajal lisanduvad funktsionaalsused: volituste ajaloo vaatamine

2. Liidestunud infosüsteemi omanikule on olemas ka **kasutajaliides rollide seadistamiseks,** so **Rollikonfiguraator**, mille kohta leiad info [SIIT.](https://e-gov.github.io/PH-Doku/files/rollide_konfigureerimine_v011.pdf)

3. **RIA kasutajatoe teenus:** Iga liidestuja saab valida, kas volitusi saab juriidilise isiku eest kasutajaliideses anda ka RIA kasutajatugi. RIA kasutajatugi saab volitusi ettevõtte eest lisada esindusõiguslike isikute poolt allkirjastatud taotluse alusel. Kasutajatoe teenuse jaoks on vajalik esitada vabas vormis ärikirjeldus/juhis ja esitada see koos toodangu taotlusega.
   
### Pääsuke pakub & tarbib
* Pääsuke pakub kasutajale keskset ülevaadet tema poolt antud või talle antud volituste kohta terves riigi infosüsteemis.
* Pääsuke pakub X-tee liideseid volituste küsimiseks (nn oraakliliides) ja volituste muutmiseks ning volituste haldamise kasutajaliidest [eesti.ee](http://eesti.ee/) portaalis.
* Pääsuke tarbib Äriregistri ja Rahvastikuregistri X-tee teenuseid.



## Erinevad viisid Pääsukesega liidestumiseks

 Allpool nähtav joonis illustreerib, kuidas

1. Ettevõte tahab anda oma töötajale volitusi erinevate iseteeninduste kasutamiseks.
    * Ettevõtte seadusjärgne esindaja võib anda töötajale volitused ise
    * Ettevõtte seadusjärgne esindaja võib ka anda volitused volituste haldurile, kes tegeleb edasi volituste haldamisega seadusjärgse esindaja eest.
2. Ettevõtte töötaja kasutab nende volituste alusel mõnd partnerasutuse iseteenindust.
    * Üldjuhul selline ettevõtte töötaja Pääsukest ei kasuta aga kui tuleb, siis ta näeb endale antud volitusi eraisiku vaatest ja soovi korral saab nendest sealt loobuda
    * Kui sellisel töötajal ei ole volituste halduri õigusi, siis ta ettevõtet Pääsukeses esindada ei saa
3. Enamik partnerasutusi (joonisel rohelisega) annavad kogu volituste hoiustamise üle Pääsukesele ja laadib volitused sealt siis kui kasutajad nende süsteemi tulevad.
    * Need partnerasutused saavad volitused kas laadida X-tee teenuse vahendusel või läbi liidestumise GovSSO-ga
    * Sellised partnerasutused saavad ka luua kasutajatoe rolli oma asutuse töötajale. Selline töötaja saab hallata kõigi ettevõtete volitusi asutuse nimeruumi(de) osas.
4. Osad partnerasutused (joonisel violetsega) hoiavad volitusi enda juures, aga teevad nende haldamise Pääsukese kasutajaliidese kaudu keskselt kättesaadavaks.
    * Nende asutuse volitusi Pääsukesest üle X-tee laadida ei saa
    * ääsuke laadib nende partnerite juurest volitused, et pakkuda ettevõtetele volituste haldamist keskselt läbi Pääsukese kasutajaliidese
5. Mõlemat tüüpi partnerasutused saavad kirjeldada rollikonfiguraatoris oma rollide nimetused ja kirjeldused ja rollide omavahelised reeglid.

<img src='img/pohijoonis.png' width='1062' height="1036" alt="Pääsukese joonis"/>

Pääsukeses volitusi hoiustav volituse omanik saab neid hallata Pääsukeses.
Väljaspool Pääsukest volitusi hoiustatavate volituste omanik saab seda teha nii Pääsukese rollikonfiguraatoris kui ka oma süsteemis.  Selliste volituste halduri analoog on nn "Symlink" volitus. Kui kasutajal tuvastatakse alusrolli olemasolu, siis see lisatakse kasutajale automaatselt Pääsukese poolt ja seda salvestatakse Pääsukese poolel kuni 7 päeva. Selle kohta täpsemalt saab lugeda [siin](https://e-gov.github.io/PH-Doku/Remote).

Rollide haldamine leiab aset toodang-keskkonnas, aga esmalt on võimalik muudatused paigaldada toogangueelsesse keskkonda Stage, mis asub [stage.eesti.ee](http://stage.eesti.ee/)'s ja kuhu RIA annab teistele asutustele ligipääsu taotluse alusel.
Uuele liidestujale peab RIA esmalt looma rollipaki ja liidestuva asutuse juht peab andma oma asutuse töötajatele volituse kasutada Pääsukese Rollikonfiguraatori toodangkeskkonna kasutajaliidest.




