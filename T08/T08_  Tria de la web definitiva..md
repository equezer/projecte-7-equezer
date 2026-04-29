**Descripció de l’activitat**

**Pas 1: Reflexió Individual**

Cadascun de vosaltres ha d’analitzar individualment la web corporativa que ha creat individualment per al client. Redacta una petita llista amb els punts forts i febles de la teva pròpia proposta segons el que demana el client.

**Reflexió Pol Hernández:**

### **Punts Forts**

- **Compliment legal integral (RGPD/LSSI-CE):** El codi no és només visual, inclou tota la lògica de consentiments obligatoris, checkboxes no marcats, banner de cookies amb memòria de sessió i modals informatius. És una web llesta per auditar.  
- **Arquitectura neta i semàntica:** L'ús d'etiquetes HTML5 (header, main, section) garanteix un bon posicionament orgànic i una accessibilitat òptima per a lectors de pantalla.  
- **Disseny de marca moherent:** La paleta de colors, blau \#0a4d92 i verd \#2ecc71 i la tipografia *Inter* estan seleccionades estratègicament per transmetre la serietat d'una logística i la frescor d'una empresa alimentària.  
- **Experiència d'usuari optimitzada:** S'han inclòs detalls com el desplaçament suau i el bloqueig de l'scroll del cos quan els modals estan oberts, cosa que millora la sensació de professionalitat.

### **Punts Febles**

- **Absència de backend real:** Tot i que el formulari està validat i simula l'enviament, no hi ha una connexió real amb un servidor o base de dades.  
- **Contingut estàtic:** En ser un arxiu únic index.html, qualsevol canvi en la informació de l'empresa requereix tocar el codi directament. Un pas següent professional seria integrar-ho en un CMS o fer-lo dinàmic.  
- **SEO de pàgina única:** Les polítiques legals estan en modals per comoditat de l'usuari, però per a un SEO més agressiu, aquests textos haurien de tenir les seves pròpies URLs per ser indexats individualment per Google.  
- **Dependència de recursos externs:** La tipografia i les imatges depenen de servidors externs (Google Fonts i Unsplash). Si aquests serveis cauen o no hi ha connexió a internet, l'estètica de la web es veuria afectada.

**Reflexió Jan Fernández**

### **Punts Forts** 

- **Compliment Legal Integral:** Aquest és el punt més robust. La web no només té els textos legals, sinó que estan integrats de forma moderna (mitjançant modals). El formulari està "blindat" amb doble checkbox (consentiment de dades i comercial), complint estrictament amb el RGPD i la LSSI-CE.  
- **Arquitectura Semàntica i SEO:** L'ús d'etiquetes HTML5 (\<header\>, \<main\>, \<section\>, \<footer\>) garanteix que els cercadors entenguin perfectament l'estructura, millorant el posicionament orgànic per a termes logístics.  
- **Eficiència de Càrrega (Fonts i JS):** L'ús exclusiu de fonts de sistema i JavaScript "Vanilla" (sense llibreries pesades) fa que la web sigui extremadament lleugera i ràpida, optimitzant el temps de resposta.  
- **Contextualització Local:** S'ha integrat amb èxit la informació específica de la seu de Mataró, incloent un mapa interactiu que millora la confiança del client potencial i facilita el contacte físic.  
- **Disseny Responsive Professional:** La graella de contacte (Grid) s'adapta de forma fluida, garantint que un cap de logística pugui demanar un pressupost des d'un mòbil a peu de magatzem amb la mateixa facilitat que des d'un ordinador.

### **Punts Febles** 

- **Manca de "Mode Fosc":** Com s'ha detectat a la memòria de sostenibilitat, la web és predominantment blanca. Això pot augmentar el consum energètic en pantalles OLED i pot ser menys còmode per a usuaris que treballen en entorns nocturns o de poca llum.  
- **Dependència de Recursos Externs:** Tot i que les fonts són locals, les imatges i el mapa depenen de servidors externs (Unsplash i Google). Si aquests serveis fallen o tenen latència, l'experiència visual de la landing page se'n veu afectada.  
- **Accessibilitat Millorable:** Tot i ser semàntica, es podrien afegir més atributs ARIA i controls de contrast de color més rigorosos per garantir que persones amb diversitat visual puguin navegar per la informació logística sense cap barrera.  
- **Interactivitat Limitada:** El formulari actual simula l'enviament. Per a un entorn real, caldria implementar una validació de backend més complexa i un sistema de protecció contra spam (com un ReCaptcha) per evitar correus brossa a l'adreça corporativa.

**Pas 2: Debat i Contrast d’idees**

Ara els membres de l’equip us reuniu per explicar les reflexions individuals de les seves propostes. Durant aquesta fase, és obligatori que defenseu els vostres arguments procurant posar en pràctica la [comunicació assertiva](https://linkiafp.es/ca/blog/consells-aconseguir-comunicacio-assertiva-empresa/) i escolteu els dels companys.

### **1\. En que estem d’acord?**

Es mantindrà l'estructura semàntica HTML5 i el sistema de modals per als textos legals, ja que millora la conversió (l'usuari no marxa de la pàgina per llegir la privacitat).

### 

### 

### 

### **2\. Defensa d’arguments**

### **1\. Sobre la Identitat Visual i el Rendiment (Tipografia)**

- **Opinió d'en Pol:** Defenso l'ús de fonts externes com **Inter**. La seva visió prioritza una identitat de marca moderna i diferenciada que transmeti una imatge tecnològica i actual, considerant que el petit pes extra de càrrega queda compensat per l'estètica professional.  
- **Opinió d'en Jan:** Prioritzo l'ús de **fonts de sistema**. La seva visió se centra en l'eficiència absoluta i la sostenibilitat, eliminant peticions HTTP externes per garantir que la web carregui de forma instantània en qualsevol dispositiu i condició de xarxa.

### **2\. Sobre la Informació Corporativa i Proximitat**

- **Opinió d'en Pol:** m’he centrat principalment en la **lògica funcional** i el flux de navegació de l'usuari. Considero que la landing page ha de ser directa i enfocada a la conversió a través del formulari, posant el focus en el compliment legal del tractament de dades.  
- **Opinió d'en Jan:** Considero essencial la **contextualització local**. Per a mi, incloure la seu física de Mataró i un mapa interactiu és una peça clau de l'arquitectura, ja que humanitza l'empresa i genera una confiança immediata en el client logístic.

### **3\. Sobre l'Experiència d'Usuari (UX) i Detalls Tècnics**

- **Opinió d'en Pol:** Poso l'atenció en els **detalls de poliment**. Defenso que elements com el bloqueig de l'scroll quan hi ha modals oberts o el desplaçament suau són els que marquen la diferència entre una web amateur i una professional.  
- **Opinió d'en Jan:** Poso el focus en la **robustesa de l'estructura**. La meva prioritat ha estat crear una graella de contacte altament flexible i accessible, assegurant que la informació sigui llegible i el formulari fàcil d'omplir en entorns de treball mòbils com en magatzems.

### **4\. Sobre la Sostenibilitat i el Futur del Projecte**

- **Opinió d'enPol:** Identifico com a feblesa la naturalesa **estàtica** del codi. Opino que, per créixer, el projecte hauria de migrar cap a un sistema dinàmic i millorar el SEO mitjançant URLs individuals per a les pàgines legals en lloc de modals.  
- **Opinió d'en Jan:** Identifico la manca de **Mode Fosc** com un punt feble clau. Des de la meva perspectiva de sostenibilitat, crec que el disseny clar actual és una oportunitat perduda per estalviar energia i millorar l'accessibilitat visual.

**Pas 3: Negociació i Consens Final**

Després d'avaluar les diferents propostes, els integrants de l'equip heu d'entrar en una fase de negociació per triar la web definitiva. No podeu prendre la decisió de manera arbitrària; s'ha d'arribar a un acord per decidir quina solució a presentar.

**Sigueu creatius:** si ho preferiu, podeu decidir fusionar el millor de cada web (per exemple, el formulari d'un i el disseny d'un altre) per crear la proposta final perfecta.

### **Acords de Consens:**

Entre tots hem arribat a aquestes conclusions:

1. **La Base del Projecte:** Es tria la **pàgina de d'en Jan (FoodLogistic-Jan)** com a solució definitiva. El motiu principal és que és la que millor respon als requisits específics de contingut (ubicació a Mataró i dades de contacte reals), estant més a prop del producte final que vol el client.  
2. **Integració de Millores d'en Pol:** Tot i triar la base d'en Jan, es decideix importar la **lògica d'animacions i el poliment de codi** d'en Pol. Concretament, s'aplicarà el sistema de transicions més suaus entre seccions i el refinament en els estats hover dels botons per millorar l'experiència d'usuari   
3. **Filosofia de Sostenibilitat:** Es manté l'aposta d'en Jan per les fonts de sistema per garantir que la web sigui el més eco-friendly i ràpida possible, complint amb la memòria de sostenibilitat presentada.  
4. **Seguretat i Legalitat:** Hem resolt molt bé el RGPD, però s'utilitzarà el redactat dels modals d'en Jan per estar totalment alineat amb la ubicació física de Mataró.

[https://equezer.github.io/FoodLogistic-Jan/](https://equezer.github.io/FoodLogistic-Jan/)

