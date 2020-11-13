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
#### Desenvolupament de software
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
 --- Disseny arquitèctoni : forma que tindrà.
 --- Disseny detallat: detall del arquitèctonic.
 --- Disseny de dades: com estaran situades les dades.
 --- Disseny d'interfaç : com es veurà.

#### Codificació
- Es posa el codi font de cada component.
- Es poden utilitzar diferents llenguatges informàtics.
 --- **Llenguatge de programació**: C, C++, Java, Javascript _(Programes per codificar)_
 --- **Llenguatge d'altre tipus**: HTML, XML, JSON  

#### Proves
- S'ha de trobar els _errors_ al programa
- S'ha de sometre a diferentes proves per treure el màxim de situacions diferents.

#### Manteniment
- Durant l'explotació del sistema de software es necessari realitzar canvis ocacionals.
- S'ha de tornar a fer part del treball realitzat les fases prèvies,
- Tipus de manteniment:
 -- **Correctiu**: correcció d'errors.
 -- **Perfectiu**: millora de funcionalitats.
 -- **Evoltiu**: S'anyadeixen millores.
 -- **Adaptatiu**: S'adapta a nous entorns
 -- -
#### Resultats per cada fase (1)
- Ingeníeria de sistemes : **Especificacio del sistema**
- Anàlisis: **Especificació dels requisits de sotfware**
- Disseny arquitèctonic: **Document d'arquitectura del software**
- Disseny detallat: **Especificació de mòduls i funcions**
- Codificació: **Codi font**
#### Rsultats per cada fase (2)
- Prova d'unitats: **Mòduls utilitzables**
- Prova d'integració: **Sistema utilitzables**
- Proves del sistema: **Sistema aceptat**
- Documentació: **Documentació tècnica i d'usuari**
- Manteniment: **Informes d'errors i control de canvis**
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
