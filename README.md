

# Entorns de desenvolupament
## Tipus de software
- **Sistema** (S.O, drivers)
- **D'aplicació** (Suite ofimàtica, navegador, edició d'imatge, etc...)
- **Desenvolupament** (Editors, compiladors, interprets, ...)

#### Relació Hardware-Software
- **Disc dur**: emmagatzemar de forma pemanent els arxius executables i els de dades.
- **Memòria Ram**: emmagatzemae de forma temporal el codi binari dels arxius executables i els arxius de dades necessaris.
- **CPU**: llegeix i executa instruccions emmagatzemades a la memòria RAM, tant com les dades necessàries.
- **E/S** : recull dades noves des de l'entrada, es mostren els resultats, es llegeixen/es guarden en disc
-- -
#### Codis font, objecte i executable
- **Codi font**: arxiu de text legible en llenguatge de programació.
- **Codi objecte**: arxiu binari no executable
- **Codi executable**: arxiu binari executable.

### Cicle de vida del Software
#### Ingenieria de Software
_Disciplica que estudia els principis, metologíes per al desenvolupament i manteniment de sistemes de software_

- **desenvolupament de software**: tèrmit més apropiat que "_ingeniería de software_" ja que aquest implica nivells de rigor i proba, processos no apropiats per a tot tipus de desenvolupament de software.
- **Ingeniería del software**: estudia creació de software fiable, de calitat donant software operacional i de manteniment.
 -- -
### Desenvolupament de software
**_Fases princiapls_**
1. **Anàlisis** : Estudi del que vols o vol el client
2. **Disseny** : Plasmar l'idea
3. **Codificació** : Creació del programa
4. **Proves** : Testeig d'errors(_trobar la major cantitat d'errors_)
5. **Manteniment**: Millores del programa

#### Anàlisis
- _defineix les **necessitats del client** i especifica els **requisits que s'ha de cumplir** amb el software._
- Especificacions de requisits:

1. **Complert i sense omisions**
2. **Concís i sense trivialitats**
3. **Evitar ambigüetats**
4. **Evitar detalls de disseny o implementació**
5. **L'ha de entendre el client**
6. **Separar requisits fucionals i no funcionals**
7. **Dividir i jerarquitzar el model**
8. **Fixar criteris de validació**

#### Disseny
- _Descompon i organitza el sistema a elements componenets que es poden desarrollar per separat._
- S'especifica la interrelació i funcionalitats dels elements components.
- Les activitats habituals són:
   - Disseny arquitèctoni : forma que tindrà.
   - Disseny detallat: detall del arquitèctonic.
   - Disseny de dades: com estaran situades les dades.
   - Disseny d'interfaç : com es veurà.

#### Codificació
- Es posa el codi font de cada component.
- Es poden utilitzar diferents llenguatges informàtics.
   - **Llenguatge de programació**: C, C++, Java, Javascript _(Programes per codificar)_
   - **Llenguatge d'altre tipus**: HTML, XML, JSON  

#### Proves
- S'ha de trobar els _errors_ al programa
- S'ha de sometre a diferentes proves per treure el màxim de situacions diferents.

#### Manteniment
- Durant l'explotació del sistema de software es necessari realitzar canvis ocacionals.
- S'ha de tornar a fer part del treball realitzat les fases prèvies,
- Tipus de manteniment:
   - **Correctiu**: correcció d'errors.
   - **Perfectiu**: millora de funcionalitats.
   - **Evoltiu**: S'anyadeixen millores.
   - **Adaptatiu**: S'adapta a nous entorns
 
#### Resultat fase 1
- Ingeníeria de sistemes : **Especificacio del sistema**
- Anàlisis: **Especificació dels requisits de sotfware**
- Disseny arquitèctonic: **Document d'arquitectura del software**
- Disseny detallat: **Especificació de mòduls i funcions**
- Codificació: **Codi font**
#### Resultat fase 2
- Prova d'unitats: **Mòduls utilitzables**
- Prova d'integració: **Sistema utilitzables**
- Proves del sistema: **Sistema aceptat**
- Documentació: **Documentació tècnica i d'usuari**
- Manteniment: **Informes d'errors i control de canvis**
- ----
#### Model de desenvolupament del software
- **Clàssics**: Models antius
  - **Model en cascada**: es realitzen com el seu propi nom indica en forma de cascada, és a dir es comença una part i si no es té encara acabada no es pot começar un altre.
  - **Model en V**: les partes més simplificades es fan a la punxa i les partes més especifiques a mida que baixa es fan les més concretes.
- **Model de construcció de prototips**: És presenta un prototip del que es vol i a partir d'alli es treballa si el client da el vist bo, generalment s'utilitza quant el client no té clar el que vol. Hi ha dos tips:
    - **Prototip ràpid**: És fa un prototip i no es modifica si és útil.
    - **Prototip evolutiu**: S'utilitza el prototip que s'ha donat com bo i apartir d'ahí es continua millorant.
- **Model evolutiu o incremental**
  - **Model en espiral**: Es fa revisió de tot cada vegada que s'acaba una fase principal, es a dir si s'acaba la codificació es torna a veure l'anàlisis i el disseny.(_Es revisa tot el que s'ha fet_)
  - **Metodologíes àgils**: Es treballent en grups diferents, es revisa el que ha fet l'atre persona o persones i es veu si conté errors en cas de tenir s'ha de avisar. 
  - Tipologies més conegudes: **Kanban**, **Scrum** i **XP(exTeme Programming)**.
  - ----
 #### Kanban
 - També anomenat **Sistema de tarjetes**.
 - **Controla per demanda** la fabricació dels productes necessaris en catitat/temps.
    ![](https://380342-1192392-raikfcquaxqncofqfm.stackpathdns.com/wp-content/uploads/2017/12/Captura-de-Tela-2017-12-11-a%CC%80s-18.06.05-696x252.png)
 - ----
 #### Scrum
 - Model incremental
 - **Interació** Sprint regulars cada 2, 3 o 4 setmanes.
 -  Establiment de **objectius prioritzats** a cada interació.
 - Amb la finalització d'interació s'obté una **entrega utilitzable per al client**.
- **Rols principals.**
  - **Product Owner**: veu del client, diu els criteris i aceptació, s'encarrega de que es cumplin.
  - **Scrum Master**: Motiva, facilita el treball de l'equip i s'encarrega de veure que es següeix la metodologia Scrum.
  - **Team**: Equip de desenvolupament, auto-organitzacio i multifuncional. Poden ser  entre 6 i 10 membres.
 -**Artefactes**:
    - **Product Backlog**: Llista ordenada dels requisits del producte.
    - **Sprint Backlog**: Llista de requisits del backlog per desenvolupament durant el sprint.
    - **Increment**: Estat del producte després de cada sprint.
 - **Events**:
    - **Sprint**: Event principal, que conté el reste d'events, duració màxima d'un mes.
    - **Sprint Planning**: Reunió inicial per la planificació del sprint. Max temps: 8hrs.
    - **Daily Scrum**:  Reunió diària posada en comú per el sprint, duració màxima de 15minuts.
    - **Scrum Review**: Reunió per evaluar l'increment obtingut, max 4h.
   - **Scrum Retrospective**: Reunió final per evalució correcte de l'aplicació de metodología Scrum, max: 3hrs.ç
   ![](https://i.ytimg.com/vi/P25JP0u6UKw/maxresdefault.jpg)
   - ----
#### XP (Programació extrema) :
- **Disseny sencill**
- **Millores continues**
- **Proca i refactorització**
- **Programa per parelles**
- **Client s'integra al equip de desenvolupament**
- **Propietat de codi compartit**
- **Estàndars de codificació**
- **40 hrs semanals**
    ![](https://www.diegocalvo.es/wp-content/uploads/2018/04/Metodolog%C3%ADa-XP-Programaci%C3%B3n-Extrema.jpg)
- ----
### Llenguatges de programació
#### Obtenció de codi executable
- Codi binari executable tenim dos opcions:
    - **Compilar**: Càrrega de tots els elements per executar el programa.
    - **Interpretar**: Càrrega d'un element, per exemple una clase de java
#### Procés de compilació/interpretació
- ES tracta de dues fases:
   - **Anàlisis lèxic:** veu cada element(lletra).
   - **Anàlisis sintàctic:** veu cada paraula.
- Si no es reconeixen errors, es genera un codi objecte corresponent.
- Un codi font correcta escrit no vol dir que funcioni com es vol.
- No es realitza un anàlisis semàntic.
#### Llenguatges compilats
- Exemple: C, C++
- **Ventatges:** execució molt eficient.
- **Desavantatge:** necessari compilar cada vegada que codi font es modificat.
#### Llenguatges interpretats
- Exemple: PHP, Javascript
- **Ventatges:** el codi s'interpreta directament.
- **Desavantatge:** execució menys eficient.
----
### Java
- Llenguatge compilat i interpretat
- El codi font es compila i s'obté un codi binari intermedi **bytecode**.
- Pot considerar codi objecte però destinat objecte natiu.
- Després aquest **bytecode s'interpreta per executar-lo**.
- **Ventatges:**
   - Estructurat i Orientat a Objectes(EOO).
   - Relativament fàcil d'aprendre.
   - Bona documentació i base d'usuaris.
- **Desavantatge:**
   - Menys eficient que els llenguatges compilats
-----
### Tipus
- **Declaratius:** Mostren el resultat sense identificat els pasos.
- **Imperatius:** Mostren els pasos a seguir per obtenir el resultat.
#### Declaratius
- Es divideixen:
    - **Lògics:** utilitzen regles, exemple: Prolog
    - **Funcionals:** utilitzen sentencies, exemple: Lisp, Haskell
    - **Algebraics:** utilitzen sentencies, exemple: SQL
- Normalment son llenguatges interpretats
#### Imperatius
- Es dividideixen:
    - **Estructurats:** C
    - **Orientats a objectes:** Java
    - **Multiparadigma:** C++, Javascript
- Els llenguatghes orientats a objectes també son estructurats.
- Molts son compilats.
#### Tipus segons nivell d'abstracció
- **Baix nivell:** ensamblador
- **Alt nivell:** C++, Java
#### Evolució
- Codi binari
- Ensamblador
- Llenguantge estructurats
- Llenguatge orientats a objectes
-----
### Criteris de selecció:
- **Camp d'aplicació:** En que aquesta mes especialitzat el llenguatge a triar
- **Experiència prèvia:** Si s'ho has fet servir abans.
- **Eines de desenvolupament:** Que eines et pot proporcionar a l'hora de treballar-hi.
- **Base d'usuaris:** Tipus de base de dades que ocupa.
- **Re usabilitat:** Possibilitat de tornar a utilitzar alguna cosa ja creat.
- **Portabilitat:** Si funciona en altres sistemes, exemple: de pc a mòbil.
- **Imposició de client:** Si el client exigeix que es treballi en un determinat programa.
