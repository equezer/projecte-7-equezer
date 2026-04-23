# **T09: Estimació temporal de projecte (Diagrama de Gantt professional)**

**Fase 1: Anàlisi real del projecte (pensament estructural)**

**1.1 Identificació de tasques i dependències**

<img width="270" height="231" alt="image" src="https://github.com/user-attachments/assets/aad6f135-5c8d-44b2-92b6-6f60f9997a93" />

A partir de les tasques reals del projecte (T01–T08):

* Identifiqueu:  
  * Ordre lògic d’execució

**T01 → T02**: Cal conèixer el sector abans de dissenyar la web corporativa.

**T02 → T06**: No es pot ralitzar la web (T06) si no s'ha creat prèviament la proposta (T02).

**T02/T06 → T08**: La tria final es fa sobre les propostes ja treballades individualment i validades legalment.

* Tasques que poden anar en paral·lel  
- Les tasques de diferents mòduls es poden fer en paral·lel  
  * Tasques bloquejants  
- T02

Heu de respondre preguntes com:

- [ ] Quines tasques **no poden començar sense haver-ne acabat una altra?**

No es pot ralitzar la web (T06) si no s'ha creat prèviament la proposta (T02).

- [ ] On poden aparèixer **colls d’ampolla?**

sobretot a la T02

- [ ] Quines tasques són més **crítiques per al projecte?**

la tasca T01 i la T02

1.2 Identificació del camí crític

Determineu:

* Quines tasques, si es retarden, afecten tot el projecte

Les tasques més importants per treure l’informació necessària per realitzar les dames tasques serien la T01 i la T02.

* Quines tenen marge (slack)

**T03 (Servidor de fitxers) i T04 (Servidor d'impressió):** Són tasques d'infraestructura interna que, tot i ser necessàries per al funcionament de l'empresa, no bloquegen el desenvolupament de la web corporativa ni la seva legalització.

**T05 (Vídeo formatiu LOPD):** És una tasca de sensibilització i formació. Encara que és important per al compliment global, el seu retard no atura el desplegament tècnic de la xarxa o la web.

**T07 (Migrant al cloud):** Es tracta d'un estudi de mercat i una proposta de modernització de correu i col·laboració. Pot tenir cert marge mentre es realitzen les configuracions de servidors locals (T03/T04).

**Fase 2: Estimació d’esforç amb criteri (ús d’IA guiat)**

Heu d’estimar la durada de cada tasca en hores, però no de forma arbitrària.

Per cada tasca, haureu d’analitzar com a mínim aquests factors:

Factors obligatoris d’estimació

Per cada tasca, tingueu en compte:

* Temps de comprensió (lectura, anàlisi)  
* Temps de recerca (si cal)  
* Temps d’implementació tècnica  
* Temps de proves i errors  
* Temps de documentació  
* Coordinació amb l’equip  
* Possibles interrupcions (classes, exàmens, altres tasques)  
* Temps de marge (imprevistos)

**T01: Coneixent la competència i el sector (3-4 hores)**

* Anàlisi: Requereix temps de recerca externa sobre empreses del sector logístic i alimentari per definir l'estratègia.

**T02: Creant la proposta de pàgina corporativa (6-8 hores)**

* Anàlisi: Inclou el disseny original de la landing page. És una tasca d'alta implementació tècnica i disseny que serveix de base per a la T06.

**T03 i T04: Servidors de fitxers i impressió (5-7 hores)**

* Anàlisi: Instal·lació i configuració de serveis (RA4 i RA6 de SOX). Requereix temps considerable de proves per verificar l'accés de diferents usuaris i la seguretat dels recursos compartits.

**T05: Vídeo formatiu LOPD empleats (6-8 hores)**

* Anàlisi: Tasca dividida en recerca (AEPD), redacció de guions detallats i producció de dos vídeos (personal de magatzem i RRHH). La postproducció i coordinació d'equip són els factors amb més pes.

**T06: Operació Escut Digital (4-5 hores)**

* Anàlisi: Modificació de la web T02 per complir amb la LOPD-GDD i LSSI (Avís Legal, Política de Privacitat, Cookies). Inclou temps de documentació legal i implementació tècnica.

**T07: Migrant al cloud (5-6 hores)**

* Anàlisi: Estudi de mercat de 4 proveïdors de correu corporatiu i elaboració d'una proposta comercial amb pressupost. Molt pes en recerca i anàlisi comparativa.

**T08: Tria de la web definitiva (2-3 hores)**

* Anàlisi: Dinàmica de grup per arribar a un consens. Inclou debat, negociació i la redacció de l'informe de justificació.

### **Consideracions generals per al seu càlcul**

Per cada tasca anterior, heu d'afegir:

1. **Temps de marge:** Es recomana un 10-15% extra sobre el temps d'implementació per cobrir imprevistos i errors de configuració.  
2. **Coordinació:** En tasques d'equip (com T05 o T08 ), dediquem almenys 1 hora setmanal a reunions de sincronització.  
3. **Documentació:** Recordeu que el lliurament inclou READMEs detallats, memòria tècnica (P01) i el repositori (P03).

**Fase 3: Assignació de recursos (treball en equip real)**

Distribuïu les tasques entre els membres de l’equip (Pol, Jan i David) :

* Qui fa què

| Membre de l'equip | Tasques Assignades |
| :---- | :---- |
| **Pol** | **T01:** Consulta Inicial (Anàlisi sector) **T02:** Disseny Web (Proposta landing page) |
| **Jan** | **T03:** Servidor Cloud / Fitxers **T04:** Servidors Locals / Impressió **T06:** Adaptació Web (Escut Digital) |
| **David** | **T05:** Seguretat i Legalitat (Vídeos LOPD) **T07:** Proveïdors i Formació (Migrant al Cloud) |
| **Tots (Equip)** | **T08:** Documentació Final i Tria de la web |

* Si hi ha tasques compartides

**Documentació:** Cada membre és responsable de documentar la seva part tècnica (READMEs i memòria), assegurant que el lliurament final estigui complet.

**Gestió d'Imprevistos:** S'ha reservat un 10-15% de temps de marge en cada assignació per cobrir possibles errors de configuració o interrupcions acadèmiques.

* Si hi ha dependència entre membres

- En Pol ha de realitzar la **T01** i la **T02** de forma prioritària, ja que són les tasques bloquejants. Fins que ell no acabi el disseny (T02), en Jan no pot començar l'adaptació legal de la web (T06).

- Mentre en Pol treballa en el disseny, en Jan pot avançar en la configuració dels servidors (**T03/T04**) , i en David pot realitzar la recerca dels proveïdors cloud (**T07**) i la producció dels vídeos (**T05**), ja que aquestes tasques tenen marge i no depenen del disseny web.

- **Finalització (Equip):** Un cop en Jan completi la **T06** (basada en el treball previ d'en Pol), tot l'equip es reunirà per a la **T08**, on es farà la dinàmica de grup per a la tria definitiva i la redacció de l'informe final.

**Fase 4: Construcció del diagrama de Gantt (UMLTree)**

Utilitzant **PlantUML (UMLTree)**:

El diagrama ha de mostrar:

* Tasques del projecte (T01–T08)  
* Durada de cada tasca  
* Dependències entre tasques  
* Execució en paral·lel  
* Visió temporal de les 3 setmanes

<img width="623" height="278" alt="image" src="https://github.com/user-attachments/assets/3cd6dbd8-375d-4655-ba98-066cc7f07361" />


**Fase 5: Pla de contingència (pensament professional)**

Identifiqueu com a mínim:

* 2 riscos crítics (reals, invasió zombi o abducció d’un alien no val)  
* Impacte en el projecte  
* Estratègia de mitigació

👉 Exemple:

* Retard en servidor → buffer o paral·lelització  
* Problemes amb cloud → alternativa definida

| Risc Identificat | Impacte | Probabilitat | Acció Preventiva / Contingència |
| :---- | :---- | :---- | :---- |
| **Caiguda del servidor/serveis (T03, T04, T11)** | Crític | Mitjana | Realitzar snapshots diaris de les màquines virtuals. |
| **Pèrdua de codi o documentació** | Alt | Baixa | Ús obligatori de Git amb pushes al final de cada sessió. |
| **Absència d'un membre de l'equip** | Mitjà | Mitjana | Matriu RACI clara per redistribuir tasques ràpidament. |
| **Incompatibilitat de programari/versions** | Baix | Alta | Documentar la versió exacta de cada servei instal·lat. |

