# DEVOPS PAMATI IESĀCĒJIEM 2022
### 2. Mājas darbs
### Darba autors: Rolands J.

1. Iepazīsties ar komandas git log opcijām pēc
https://git-scm.com/book/en/v2/Git-Basics-Viewing-the-Commit-History

2. Izveidot Jūsu darba stacijā ssh atslēgas un iekopēt publisko atslēgu GitHub.
![2MD 2uzdevums](src/images/2MD_2UZD.png?raw=true)
![2MD 2uzdevums_2](src/images/2MD_2UZD_2.png?raw=true)

3. Noklonēt no GitHub vietnes pirmajā mājas darbā izveidoto repozitoriju
lokālajā darba stacijā. Repozitorijam, kuru izmantosiet kursa laikā, atvelēt
atsevišķu mapi ar nosaukumu git_repos 

![2MD 3uzdevums](src/images/2MD_3UZD.png?raw=true)

4. Lokālajā repozitorijā izveidot mapes module_1 un module_2

![2MD 4uzdevums](src/images/2MD_4UZD.png?raw=true)

5. Iepazīsties ar Mark Down valodas elementiem - https://dillinger.io/
Interaktīvajā web redaktorā Jūs varat uzreiz redzēt darba rezultātu.

6. Mapē module_1 izveidot README.md failu.

7. Stilistiski, pēc Jūsu uzskata, noformēt README.md failu tā, lai tas saturētu
pirmā mājas darba uzdevuma saturu. Informācija par autoru (varat likt tikai
vārdu), links uz github projektu un attēls (ja tas ir iespējams). Bildes un papildus
materiālus obligāti ievietot repozitorijā. 

![2MD 7uzdevums](src/images/2MD_7UZD.png?raw=true)

8. Ar git palīdzību noformēt commit un pārsūtīt rezultātu github.

![2MD 8uzdevums](src/images/2MD_8UZD.png?raw=true)

9. Pārbaudīt kāds commit hash ir lokālajā git repozitorijā un salīdzināt to ar šī
paša faila commit hash github.
//Hashi sakrīt

![2MD 9uzdevums](src/images/2MD_9UZD.png?raw=true)

10. Mapē module_2 izveidot README.md failu. 

![2MD 10uzdevums](src/images/2MD_10UZD.png?raw=true)

11. Iekopēt trūkstošos failus (bildes vai citus) no module_1 mapē module_2.
README.md failu neaiztikt.

![2MD 11uzdevums](src/images/2MD_11UZD.png?raw=true)

12. Ar git palīdzību noformēt commit un pārsūtīt rezultātu github 

![2MD 12uzdevums](src/images/2MD_12UZD.png?raw=true)

13. Salīdzināt vienādu failu (ne README) hash no mapes module_1 un
module_2. Vai git redz atšķirību starp šiem failiem?
//Hashi sakrīt starp resursiem, bet README atšķirās.

![2MD 13uzdevums](src/images/2MD_13UZD.png?raw=true)

14. Rezultātus apkopot module_2 > README.md

15. Mapē git_repos noklonēt https://github.com/hashicorp/terraform projektu. 

![2MD 15uzdevums](src/images/2MD_15UZD.png?raw=true)

16. Pārbaudīt kādas izmaiņas tika veiktas iepriekšējās nedēļas laikā. Atrast
vismaz divus veidus kā to izdarīt. 

## _git log --since='2 weeks ago' un git log –since="2022-04-11"_

17. Atrast commitus kurus veica autors - “Laura Pacilio”

![2MD 17uzdevums](src/images/2MD_17UZD.png?raw=true)

18. Atrast vai Laura ir veikusi commit pagājušā gada septembrī?

![2MD 18uzdevums](src/images/2MD_18UZD.png?raw=true)

19. Vai Laura ir veikusi commit vakar?
Laura nav vakar veikusi izmaiņas

![2MD 19uzdevums](src/images/2MD_19UZD.png?raw=true)

20. Rezultātus apkopot module_2 > README.md un pārsūtīt rezultātu github.

* Atlasot rezultātus no pagājušā gada 20 līdz 21 aprīlim var atrast commit kurš
ir datēts ar 16 aprīli? Kāpēc tā ir? Atbildi apkopot module_2 > README.md un
pārsūtīt rezultātu Github.

Jo meklējot ar kommandu git log –before –since tiek atlasīti commiti kas atbilst prasītajam periodam, pēc commit datuma, bet izvadītajos rezultātos tiek norādīts author date.

![2MD SPuzdevums](src/images/2MD_SPUZD.png?raw=true)