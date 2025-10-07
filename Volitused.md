## Volitused ja rollid
Pääsuke on keskne volituste haldamise infosüsteem, kus kasutaja näeb tema poolt või talle antud volitusi üle terve Eesti riigi erinevate infosüsteemide, mis on Pääsukesega liitunud. Ettevõtte esindusõiguslik isik saab anda volitusi [eesti.ee](https://www.eesti.ee/) portaalis vasakul menüüs volituste all: [https://www.eesti.ee/volitused/et](https://www.eesti.ee/volitused/et)

Esindatav isik (juriidiline või füüsiline isik) annab esindajale (füüsilisele või juriidilisele isikule) õiguse enda nimel tegutseda määratud rollis. Pääsukeses on võimalik volitusi anda vaid Eesti isikukoodi omavatele isikutele.

Roll on tegevuste kogum, mida volitus lubab esindajal teha esindatava nimel vastava nimeruumi raames. Nimeruum on ühe infosüsteemi või asutuse rollid. Pääsuhalduse kontekstis on rollid alati defineeritud nimeruumi kontekstis. Rollide loetelu leiate viitel: [https://www.eesti.ee/ettevotja/et/artikkel/volituste-rollid](https://www.eesti.ee/ettevotja/et/artikkel/volituste-rollid) või sisselogituna [https://www.eesti.ee/volitused/et/rollid](https://www.eesti.ee/volitused/et/rollid)

**Rollitüüpide võrdlustabel** 

| Tüübi nimetus | Kirjeldus | Mis olukorras kasutada |
| ------------- | ------------- |--------------|
| Tavaline roll  | Tavaline roll, mis annab kasutajale õigusi liidestunud infosüsteemis.  | Tavaolukorras, kus soovid luua tavalise rolli, mis annab kasutajale sinu infosüsteemis õigusi. |
| Volituste halduri roll | Sellise rolliga volituse omanik saab [eesti.ee](https://www.eesti.ee/)-s volitusi hallata. | Soovitav kasutada ainult siis, kui volitusi hoiustatakse Pääsukeses. 
| Volituste halduri symlink roll  | Pääsukese peegeldus sellisest välises süsteemis defineeritud rollist, mis annab Pääsukeses rollide haldamise õiguse. |Saab kasutada ainult siis, kui volitusi hoiustatakse välises süsteemis ja mitte Pääsukeses.
| Kasutajatuge pakkuva töötaja roll  | Rollipaki omaniku asutuse kasutajatoe töötajale mõeldud roll, mis võimaldab hallata kõiki teisi rollipakki kuuluvaid volitusi. | Soovitav kasutada ainult siis, kui volitusi hoiustatakse Pääsukeses. 
| Eeldusroll | HELPDESK rollis kasutajatoe töötaja määrab selle rolliga volituse isikule nii, et see isik on nii volituse esindatav kui ka esindaja. Pääsuke tuvastab, et isikul on sellise rolliga volitus ja seetõttu võimaldab sellisel isikul lisada täiendavaid rolle (DEPENDABLE), mille lisamise võimalikkus on märgitud antud rollist sõltuvaks. | Kui tahad piirata, et mingi teise rolli lisamiseks peab esindataval isikul olema antud eeldusroll.
| Sõltuv roll  | Iga DEPENDABLE roll on seotud ühe või mitme eeldusrolliga. Sellise rolliga volituse lisamise pakub süsteem kasutajale välja üksnes siis, kui esindataval isikul on vähemalt üks kehtiv volitus sellise eeldusrolliga, mis antud rolli eelduseks on märgitud.  | Kui tahad piirata, et antud rolli jaoks on nõutud, et esindataval isikul oleks mõni eeldusroll.
| Eesõigusroll | See rollitüüp on kasutusel edasivolitatava eriõiguse andmiseks. Helpdesk töötaja lisab selle rolliga volituse mingile isikule selliselt, et see isik on nii rolli esindatav kui ka esindaja. Seejärel see isik saab volituse (oma töötajale) edasi volitada. Kui algselt lisatud eriõigus isikult ära võetakse, siis lõppevad kõik edasivolitused automaatselt. | Kui on vaja isikule anda selline eriõigus, mida jur isik saaks oma töötajatele edasi volitada nii, et kui juriidiliselt isikult see eriõigus eemaldatakse, siis lõppeks tema poolt antud edasivolitused automaatselt.

Täpsem tabel koos tehnilise dokumentatsiooniga:  [https://e-gov.github.io/PH-Doku/files/rollide_konfigureerimine_v011.pdf](https://e-gov.github.io/PH-Doku/files/rollide_konfigureerimine_v011.pdf) (lk 43)

Juhised volituste andmiseks leiate viitel: [https://www.eesti.ee/static/files/Volituste_juhend_EE.pdf](https://www.eesti.ee/static/files/Volituste_juhend_EE.pdf) (3.1 Volituse lisamine)

Täpsemalt saate volituste jagamise kohta lugeda viitel: [https://www.eesti.ee/et/ueldine-abi/riigiportaali-abi#e-teenuste-kasutamise-ja-volitustehaldamise-juhend](https://www.eesti.ee/eraisik/et/artikkel/riigiportaali-abi#e-teenuste-kasutamise-ja-volitustehaldamise-juhend:~:text=ria.ee.-,E%2Dteenuste%20kasutamise%20ja%20volituste%20haldamise%20juhend,-E%2Dteenuste%20kasutamine)