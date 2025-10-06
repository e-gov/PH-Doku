## Dokumentatsiooni loetavuse parandamiseks ja erijuhtumite kordamise vältimiseks on mõistete määratlemisel kasutatud üldistusi.

**Süsteemid**

* **Pääsuke** - keskne volituste haldamise infosüsteem, mille kasutajaliides asub Riigiportaalis [eesti.ee](https://www.eesti.ee/).   
* **Pääsukese toodangukeskkond** - [eesti.ee](https://www.eesti.ee/), avalikkusele juurdepääsetav keskkond
* **Pääsukese eeltoodangu keskkond** - [eesti.ee](https://www.eesti.ee/), piiratud juurdepääsuga toodangueelne keskkond testimiseks 
* **Iseteenindus ehk liidestunud infosüsteem** - Pääsukesega liidestuv infosüsteem. Enamasti selleks on mõni avalik iseteeninduskeskkond, aga mõningatel juhtudel hoiustatakse Pääsukeses ka selliste infosüsteemide volitusi, mida ei nimetata iseteeninduseks.

**Tegutsejate tüübid**

* **Isik** - juriidline isik või füüsiline isik
* **Asutus** - Iseteeninduse omanik. Asutusel enamasti on mitu infosüsteemi (või on üks infosüsteem, aga tulevikus võib neid veel lisanduda). Asutuse rollis võib olla ka eraettevõte.
* **Ettevõte** - Juriidiline isik, kes soovib Pääsukeses volitusi anda. Enamasti on see ettevõte, aga võib olla ka mittetulundusühing, sihtasutus või riigiastus või kohaliku omavalitsuse asutus.
* **Töötaja** - Füüsiline isik, kellele Ettevõte soovib volitusi anda, enamasti Ettevõtte töötaja.

T**egutsemise tüübid**

* **Esindusõigus** - Äriregistris kirjeldatud seadusest tulenev ehk seadusjärgne esindusõigus või Äriregistris hoiustatav volitus (Prokurist on ainuke selline volitus, mida hoiustatakse Äriregistris).
    * **Ainuesindusõigus** - Seadusjärgne esindusõigus, mille kohaselt isik võib Ettevõtet esindada üksinda.
    * **Ühine esindusõigus** - Seadusjärgne esindusõigus, mille kohaselt isik võib Ettevõtet esindada ühiselt koos teise või teiste isikutega.
* **Esindatav** - Isik, kes on volituse andnud enda nimel teatud ulatuses tegutsemiseks esindajale. Kui esindatav on juriidiline isik, siis esindatava nimel tegutseb tema esindaja kas volituse või seadusjärgse esindusõiguse alusel.
* **Esindaja** - Isik, kellele volitus on antud.

**Roll ja volitus**

* **Roll** - Volituse õiguste kogum, millel on unikaalne kood.
    * **Rolli kood** - rolli unikaalne tunnus üle terve Pääsukese. Rolli koodi osa on ka nimeruumi kood.
* **Volitus** - määratud õiguste kogum, mis seob Esindatava, Esindaja ja Rolli ning määrab, milliseid toiminguid Esindaja võib Esindatava nimel teha. Volitusel võib olla kehtivusaeg ning see võib olla edasivolitatav vastavalt määratud tingimustele.
    * **Kaugkinnitused**- süsteemid, mis hoiavad volitusi oma infosüsteemis ja avavad Pääsukele API päringute tegemiseks ja muutmiseks
* **Privileeg** -  "õigus mingit teenust kasutada". Privileeg määratakse [eesti.ee](https://www.eesti.ee/) BE-s rollidele, mis tulevad Pääsukesest. Täpsustab rolli ligipääsu taset (vajadusel). Rolliga võib kaasneda mitu privileegi. Iga privileeg kuulub teenuse alla.
* **Edasivolitus** - volitus, mis tekib algse Volituse edasiandmisel algse volituse esindaja poolt kellelegi teisele. Edasivolitus lõpeb algse volituse lõppemisel automaatselt. Edasivolitust ei saa anda pikemaks perioodiks kui on algsel volitusel.
* **Rollipakk** - Ühe asutuse volituste kogum, mis on ühes nimeruumis.
* **Nimeruum** - ühe infosüsteemi või asutuse rollid
    * **Nimeruumi kood** - rollikoodi eesliide kuni koolonini. Volituste halduri ja kasutajaliidese rollikoodidel on nimeruumi ees veel täiendav liide, mis on omakorda nimeruumist kooloniga eraldatud.

**Tegevused volitustega**

* **Volituste haldamine** – Volituste andmine, muutmine, tagasi võtmine, edasivolitamine ja volitustest loobumine.
* **Volituse andmine** - volituse lisamine esindatava algatusel
* **Volituse tagasi võtmine** - volituse eemaldamine esindatava algatusel
* **Volitusest loobumine** - volituse eemaldamine esindaja algatusel
* **Volituse edasivolitamine** - Temal endal oleva volitusega (algse volitusega) samasuguse volituse andmine kellelegi teisele – edasivolituse esindajale. Nüüd on esindatava nimel tegutsemiseks õigus kahel isikul: alge volituse esindajal ja edasivolituse esindajal.
* **Edasivolituse tagasi võtmine** - edasivolituse eemaldamine algse volituse esindaja algatusel
* **Volituse ulatus** - Ettevõtte/asutuse seadusjärgne esindaja või volituste haldur võib soovi korral anda mõnele töötajale volituse kasutada kõiki [eesti.ee](https://www.eesti.ee/) portaalis olevaid teenuseid või volituse kasutada ainult mõnda konkreetset teenust.

**Volituste alusel tegutsejad**

* **Volitatud isik** - isik, kes üldjuhul tegutseb Pääsukesega liidestunud infosüsteemides ja mitte Pääsukeses endas.
* **Volituste haldur** - isik, kellel on õigus Pääsukese kasutajaliideses teha tegevusi volitustega, st volitusi anda ja tagasi võtta, volitustest loobuda ja/või edasi volitada. Volituste halduri volitus ei anna õigust tegutseda liidestunud infosüsteemis, vaid ainult Pääsukeses.
* **Edasivolituste haldur**- Eelkõige raamatupidamisbüroode (ja teiste teenust pakkuvate ettevõtete) vajadusi silmas pidades loodud roll mille kasutaja saab hallata ettevõttelt A ettevõttele B antud volitusi ehk volitada edasi ettevõttelt A saadud volitusi ettevõtte B töötajatele.
* **Kasutajatoe töötaja** - Pääsukesega liidestunud asutuse töötaja, kellel on antud õigus hallata kõiki asutuse nimeruumi volitusi (sh mistahes ettevõtte volitusi, mis asuvad asutuse nimeruumis).
* **Volituste administraator (RIA kasutajatugi)** - Volituste administraator on isik (RIA kasutajatoe töötaja), kellele on antud volitus selleks, et ta saaks volituste haldamise infosüsteemis Pääsuke sisestada andmeid mistahes isikute volituste kohta. Volituste administraator ei anna ise volitusi, vaid ainult sisestab volituste andmeid talle esitatud dokumentide alusel.