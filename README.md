
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
    ![](data:image/jpeg;base64,/9j/4AAQSkZJRgABAQAAAQABAAD/2wCEAAkGBxMTEBITEBESFRUWFhoZGBMXEhcZHxIYFxgYFhcXFhUdKCkgGRolHBcVITUiJSotLi8uGh8zODMsNygtLisBCgoKDg0OGxAQGy8lICYtLS8vLS03LTYtLTAyLS0tLS8tLS01LS0tLS0vLS0tLS0vLTAtLS0tLS0tLS0tLS0vLf/AABEIAJ4BPwMBEQACEQEDEQH/xAAcAAEAAQUBAQAAAAAAAAAAAAAABQIDBAYHCAH/xABPEAABAwIDAggKBgcFBwUBAAABAAIDBBEFEiEGMRMWIkFRVHPRBzI1YXGRkpSxshQjMzSBoUJScnSiwcIVo7TD8CVDU2JkgrNEY4Ph4iT/xAAbAQEAAgMBAQAAAAAAAAAAAAAAAgMBBAUGB//EAD4RAAIBAgEIBwcDAwQCAwAAAAABAgMRBBITFCExUVJxMjNBYZGhsQU0U4HB0fAVIuEjQnIkssLxYpKCotL/2gAMAwEAAhEDEQA/AN5Xz87gQBAEAQBAEAQBAEAQBAEAQBAEAQBAEAQBAEAQBAEAQBAEAQBAEAQBAEAQBAEAQBAVR7wrKXTRiWwpVZkIAgCAIAgCAIAgCAIAgCAICCftlQAkGsg06H3/ADGhW2sBiX/YyrPU95Tx0w/rkPrPcmgYngYz9PeOOmH9ch9Z7k0DE8DGfp7xx0w/rkPrPcmgYngYz9PeOOmH9ch9Z7k0DE8DGfp7xx0w/rkPrPcmgYngYz9PeOOmH9ch9Z7k0DE8DGfp7xx0w/rkPrPcmgYngYz9PeOOmH9ch9Z7k0DE8DGfp7xx0w/rkPrPcmgYngYz9PeOOmH9ch9Z7k0DE8DGfp7xx0w/rkPrPcmgYngYz9PeOOmH9ch9Z7k0DE8DGfp7xx0w/rkPrPcmgYngYz9PeOOmH9ch9Z7k0DE8DGfp7xx0w/rkPrPcmgYngYz9PeOOmH9ch9Z7k0DE8DGfp7xx0w/rkPrPcmgYngYz9PeOOmH9ch9Z7k0DE8DGfp7xx0w/rkPrPcmgYngYz9PeOOmH9ch9Z7k0DE8DGfp7xx0w/rkPrPcmgYngYz9PeOOmH9ch9Z7k0DE8DGfp7zJw/aWjmeI4aqJ7zuYHautqbA79OhQqYSvTjlTg0jMasJOyZLLXLCqPeFZS6aMS2FKrMhAWJ6yNl88jG2Y55zOAsxlsz9f0RcXPnClGEpbF22+e4w2ltLj5Wi1yBmIAud5O4DzrCi3sM3EsoaC5xDQN5JsBfTeiTbsg3YOkALWkgF17C+rrC5t06Ik2ri5U9wAJJsALk9AG8rCV9SB8Y8FocDcEXB6QdQVlqzswWqarjk+ze1/Ja7kuB5Lxdh05iNR0rMoSj0lb+NphNPYXJZWtALnAAkNFza7nGzQPOSQFhJvYZbsVrACAICF21cRh1ZY2+of+bbFbWC94hzRXW6t8jzrQ0j5pGxxNLnvNmtFtT0ar2c5xhFyk7JHISbdkT3ELEeqSe0zvWp+pYXjXmW6PU3DiFiPVJPaZ3p+pYXjXmNHqbhxCxHqkntM70/UsLxrzGj1Nw4hYj1ST2md6fqWF415jR6m4cQsR6pJ7TO9P1LC8a8xo9TcOIWI9Uk9pnen6lheNeY0epuHELEeqSe0zvT9SwvGvMaPU3DiFiPVJPaZ3p+pYXjXmNHqbhxCxHqkntM70/UsLxrzGj1Nw4hYj1ST2md6fqWF415jR6m4cQsR6pJ7TO9P1LC8a8xo9TcOIWI9Uk9pnen6lheNeY0epuHELEeqSe0zvT9SwvGvMaPU3DiFiPVJPaZ3p+pYXjXmNHqbhxCxHqkntM70/UsLxrzGj1Nw4hYj1ST2md6fqWF415jR6m4cQsR6pJ7TO9P1LC8a8xo9TcOIWI9Uk9pnen6lheNeY0epuHELEeqSe0zvT9SwvGvMaPU3DiFiPVJPaZ3p+pYXjXmNHqbhxCxHqkntM70/UsLxrzGj1NxTJsLiDQSaR4ABJN2aAannWV7RwzdlNeYzFTcReAOIq6Yg2ImjIPQQ8K/EK9KS7n6FcOkuZ6cK8Kdoqj3hWUumjEthSqzIQGs7XbMmsO+2WnlYzlub9a/LkzW3x6G48w0K3sJi8x/7Jvktvz3FNWll+DLUez8/CvfI8PHDskYDM+2Vsj3eJlsxzGPDRqQ7LrbRSeJp5KUVbU09S3Ltvru1fuuYzcr3e8xI9m6vg42ve14BGZpqZSC4Cn+vuW6uLopjwZ0+t371Y8VRym0rfJf8Alq81r7iKpTtr9eWsv/2BV5HjhGh5EjQ7h5Dq+JzOGBy3Y5zi27W+LvBJ0UdJo3WrVq7FvTt32Xb2mc3O354mDWYPWcI2MZzwjJMpE0xZSg/SyGOeRZw+tpxc8r6sWBA0thXoZLk+y3Yry6PZ8n3a9bIuE72++rb/AAT+E4dUMqZpJXNyOaQ0NkcbnNyCWEaEN0Judb2AFlp1atKVOMYrWvx+ZbCMlJtkLT7LVUVF9GjfGb5HF5le1zXcAY3tD2t1a17Yy0kHk3Gha1bUsZRnWzkk+3VZW6V1q71e/fr7WVqlNQyV+ajLqdn6g3Nw+7w9zXTyAPyzskYAbHJyA8XA3nnVccTTXdqtsXC0+euxJ05fnMtRbPVlwJJmkCFsZc2eUF5DYbki182ZkvKvuI0uXKTxNDsXa3sWrb91q/gwqc+19n2NlwemfHCGSOuQ+SxzF1mGV7om3OpswsH4LRrTjOeVHcvGyv53LoJpWZmqokQm2/k2s7F/wW1gfeIc0V1urfI4h4P/ACnSdqPgV6r2h7tPkcyh1iPRS8WdcIAgCAIAgCAIAgCAIAgCAIAgCAIAgCAIAgMbEvsZezf8pU6fTXNGJbGea8D+9U/ax/OF7iv1UuT9DjQ6SPTpXhDtFUe8Kyl00YlsKVWZCAIAgCAIAgCAIAgCAIAgITbfybWdi/4LawPvEOaK63VvkcQ8H/lOk7UfAr1XtD3afI5lDrEeil4s65iYqZOAk4G/CZTktbxubeHD1g+gqylk5ay9nb+avUjK9tRGsratrsjoQ/KWAyWP1gLRnIIs3fz2sLbgr3TotZSla99W7d+eZDKnssY0WKVoFzTl1wTYsc0NsXkNAtcG1tTvygaZgpujQ4rfi/P+jClPcZMNdVcKA6EFrnhpOVwDWhzmlwdr4wbnF92g/SBUHTo5N1LXb88Nnn2GVKd9hOrULTGxGuZBE+WUkMYMziBewHm51OnTlUmoR2sxKSirsyVAyAgIDAsSqHiATRPu8DhHOjezg3FkjiMpY3kgxga88jRc8+5XpU45Ti1q2bHfWu97/LYiqEpO10WaPaKeSEStpHEGON4AEnLMmY2byLkDKBe36TXeLqpTwtOM8hz7Wuzs+f5a20wqkmr2DNopnNmcymL+DcG2bnJLjkuPF1LcxBtfdcaI8LBOKcrX19nf39vYM42nZGZS4tK6YRupntbwkjS8tfYNY27Xg5bEHQakXJ0vYqqdGChlKXYtWr7/AJ2klNt2sTK1iwxqStZI6VrCSYn5H6Ws7K19h06Oapzpyik32q6MKSd7GSoGTAxNsxdAIXFo4T6wgtHIDSTq5j+e2gsT+sFbSyEpZW7Vz8V9eTIyvqsRkWJ1eWPNTEl3BAnKdM2YSZiNAW2Dr2traw0Ww6NG7tLf/Hjs3kFKe4p/tSraz7BziIw7WF9y8uaABlsLWzEjeNPGucrM0W+lbXvWz88e7txlztsMijxCpM+V8JEZe4XyOGQN3crcb+NfdzDVQnSpKF1LXb8/PmSUpX2E4tUsMbEvsZezf8pU6fTXNGJbGea8D+9U/ax/OF7iv1UuT9DjQ6SPTpXhDtFUe8Kyl00YlsKVWZCAIAgCAIAgCA1/HtrIaZ/BkOe+13NbbkaaAk85005hr0A72G9n1K8cpal39v5+d1U6qi7F/ZraBlW11mlr2WzNOtgb5SDz7lHF4OWHavrT7TNOopkytMsCAICE238m1nYv+C2sD7xDmiut1b5HEPB/5TpO1HwK9V7Q92nyOZQ6xHoaeZrGlzzZo3n06D8yF4yMXJ2R1m7GDNjtO3/etLuaMEZ3eZrDqT5grlh6j7Pn2eJF1IrtPsuPUrbZ6qnbcXs6ZjTqLjQm+4hYWGrPZBv5MOpBbWjLpKuOVgfE9j2G9nscHA2NjYjTeCq5wlB5MlZ95JNNXReUTIQEDt35NrOyctvAe8w5lVbq2TwWoWhAWqmpbGMzzYXA3E3J5gBqpRi5OyMNpbTBlx6mbYcMwn9VpBc0AXLizxsoAuTbRWrDVX2fnMi6kV2n2fHqRhIfV0zSN4M8YIPPpfpSOGrS1qDfyYdSC2tGdBM17WvY4Oa4AtcDcOB3EHnCplFxdntJJ31ouLBkgtm/tsR/e/8AIhW3iehS/wAfqyqntlz+iJ1ahaEBhU2LU8lxHUQvI3hsrCR6QDorZUakelFr5MipxexmPim0lJThhnqI2h7srdS65Fib5b2AuLk6C46VOlha1W6hF6vztMSqQjtZJQzNcLscHC5Fwb6tJa4ekEEfgqHFrUySdytYMmNiX2MvZv8AlKnT6a5oxLYzzXgf3qn7WP5wvcV+qlyfocaHSR6dK8Idoqj3hWUumjEthSqzIQBAEAQGl7Tba8G90VKGuc02dI7UAjeGjnI6Tp5iuxg/ZmXFTq7HsX3NepWs7RNYftdWn/1BHojjH9K6S9n4Zf2eb+5Tnp7yzLtJVuFjUy/gQ3822KnHBYeLuoL85mHUnvIom5JOpOpPSekrZIErsxi/0aobIfEPJeP+U8/pBAP4W51q4zD5+k49u1c/5J055MrnYAb6jUdPSvJm+fUAQEJtv5NrOxf8FtYH3iHNFdbq3yOIeD/ynSdqPgV6r2h7tPkcyh1iO94uLtib+tNF/dvEx/KMryFHU2+5+at9Tqy7OZ9xaKZzWcA5uZriSxz3NbI0xvZlc4BxFi9r9x1YBpe4UnBN5fl2a0+7dbb2iSb2GJiNBDHRvMsUUnBQG5fE034OPfqD0KynUqSrLJbV32PeyMoxUda2Ig/BBNmwxo/Ulkb6NQ/+pbftiNsS3vS+xVhX/TN1XLNkICC268m1nYuW3gfeYcyqt1bJxu4LULT6gMCvF5qYdD3vPnDYns+MjVbT1Qm+5LzT+hF7UWsdoppWhsT2hrmPje1znAASZPrAADme0NdZpsDnOo550KkIO8l2pr5X1cnv7thicW9hG7f08Iw+rkfDEXCM2cY2khziGtINrg3cNVd7PlUeIhFN7d5Cuo5Ddi54PJ8+F0h6Iy32HOZ/Sse0Y5OJmu/1VxQd6aNiWkXEDs39viP71/kQrbxPQpf4/wDJlVPbLn9ETy1C0xcVquCgml1OSN7rDnLWkgDz6KylDLnGO9pEZOybKYMNjEMcL42PbGxrAHNDhZrQ3cfQkqsnNzTs27hRVrELiGxtE+7poWcFHd7Io28E1hs3hHOyWzOdkaOYWaBa9ydqnj68dUZO71NvW+7bstcrlRg9q1FvwZ1rpsPbI83c6WUu9LpC7Qcw5W5S9p01TxGStll6GMPLKhd95tS55eY2JfYy9m/5Sp0+muaMS2M814H96p+1j+cL3Ffqpcn6HGh0kenSvCHaKo94VlLpoxLYUqsyEAQBAWaxxEby3eGOI9IBspQScknvMPYcObuXtWc4+rAPrWkkAAkk2AAuSTuAHOUBO4VsjUzPDQzIM1i925tvGOm+x0sN7tOZ2WEqsUiaptkhi2xMrGue1pAEcjwzeQ2J0TWh7h/vHtdI+w0BbYKEaqeoy6ZtOw1dwtFHc3Md4z/22y/wlq877RpZvEPv1/fzubNGV4E+tEtCAhNt/JtZ2L/gtrA+8Q5orrdW+RxDwf8AlOk7UfAr1XtD3afI5lDrEd5xF7eGpQ5wFnveLkC9o3R28/2q8jTTyJ23Jed/odSW1EiqSZDbZ+TqzsJPlK2cF7xDmiut1b5Go+Bipa2gqS9wDWTF7idzRwbLk+azSul7ag3XjbtVvNmvhHaDN3lxunbvmYDzMLg1zjzBrXWJK5Sw9R9n2NlzjvKTj1KGtc+phYHAECSRsZAIuLtcQQfMQs6NVbsot8lf0GcjvIzauuimwutdBLHI0RPBcx4cAQASLjS9iPWr8JTnTxUFNNO62kKslKnKzNjZuHoWky4qWAR0z2/TI7uALYX6EgX4R8drDn+yPrVyTzT1dq8k/uQfS+RI2VJM1Lwq+Saj0x/j9axdH2V71H5+jKMT1bKPBNJfCoR+q+Qfxl39Sz7WVsVL5ehjCv8Apo3Bc02CB2c+3xH96H/ghW3iehS/x/5Mqp9KXP6InlqFpG7QuPAaBxBkiDg1jnnJwrOE5LQSeRm3BX4e2X8n3a7O23vIT2FUeO0znlgqIg/njc8NcOfVjrOG8cyw8PVSvku2/s8RnI7LmFtvWCPDat998Tmgjpk+rFj6XBW4GGXiYR7/AE1kaztTbILwNuJw0ggi07wL84LY3XHm1K2/bKWkfJfUrwnV/M3pck2TGxL7GXs3/KVOn01zRiWxnmvA/vVP2sfzhe4r9VLk/Q40Okj06V4Q7RVHvCspdNGJbClVmQgCAIDQfCRiUrZGQtc5sZjzGxtnJc5tiecANGnn9C7vsmjBxdRq7vbkateTvY0ddk1yXwLZueqIMbQ2O9jM/Ro1tYH9I+YfjZQlUUSUYNnU9mtk4KQZmjPLbWVw1HSGD9Afn0krVnUcjYhTUSeA5gqywFAaXsxh30aorYB4gex8f7Egfl9WXL/2rR9q/uyJc14W+5GirNo2JcguCAhNt/JtZ2L/AILawPvEOaK63VvkcQ8H/lOk7UfAr1XtD3afI5lDrEeiJI2uFnNDh0EA/kV4xNrYdchoNk6Nl+DgyXNzkllb6srhb8FsyxteXSlfml9itUYLYi6NmqX9OESds981vRwpdZR0ut2StysvSwzUN3jr9RiVHFHTPZHHHG2QsjLWMa0HhXti1A/bslKc51FKTbau9fcr/QzJJRsjOxFshZ9SQHhzXAOcWhwa4OcxzgCQHAEXsd+4qqm4p/u2a/8Av5EpXtqMWlwqMQsZPHC8tbyiWBw6TbMNQrJVpZbcG0RUFazOa7JVAfgmLWAaM0jg0CwaHsboBzDkrt4uOTjaPyXmadJ3ozOtR7h6AvPPab5UsAs1VMyRpbKxrmkWIcAd+ilGUou8WYaT2kMdnKGBrRlELXODW2qJY8zjua0h4JJ6AtrSsRUd73+Sf0K83Tj3GUNmaTTNTskI3Ga8xHoMhcVXpdbslblq9LEs1Dd+fMkKenZG3LGxrG/qtaGj1BUylKTvJ3JJJbC6omSC2d+8Yj+8j/wQrbxPV0v8f+TKqfSlz+iJ1ahaEBG1Wz9LJI6WWlgke613via4mwAF7+YAK+OJrQjkxm0u5kHTg3doqiwSma4OZTQsIIN2RtbqNxOUC9vOsPEVWrOTfNmVCK2IkFSSCAxsS+xl7N/ylTp9Nc0YlsZ5rwP71T9rH84XuK/VS5P0ONDpI9OleEO0VR7wrKXTRiWwpVZkIAgCA07wlUOaCOYDWN2Un/lf/wDoN9a6/sirao4b15r+CjER1XOcrvmodyo6GGpoadk0bXxmKJ2U7vEFt3pWi24ydjbSTirkRHSsgqBT0FY6OSxP0aRxmjIaGuLSCc8Rs4EG4vra9irWpOGXJat/aV3Slkxes25a5eQ2GMndKTPVMLmi5pYWtDGh2ZrS5zgZH6tdryRdp00IVkkktS+ZXF3e0zqxguHWFyLE9IGoH8TvWVyPaN/2/P6F0SwuaSCAhNt/JtZ2L/gtrA+8Q5orrdW+RxDwf+U6TtR8CvVe0Pdp8jmUOsR33GJS2E2JBc5jARvBlkZHcecZl5Cirz1978E39DqzeowsWhbG1plqJmxF7Q/M+PKG7+W9zSQ0kBujgeVvCtpScm1GKvbVtv8AJJ/QjJW2vUYVHQ1clJTvFfLC4wRlwdTwvs7g25s2YZr3uTc77q2dShGrJZtNXdtbXb3aiKjNxTyrau4itjcffU0UDqmUOeazIXkNb9mw1DRYWA8UK/G4ZUa0lTWrJv4vJ+pXSqOUFlb/AOTfB5lyTaMfEr8BLbQ8G/Xo5JU6fTXNGJbGcY2Cl/2bjDP/AGWuHqlB/kvTY+P+poPv+xzqD/pzXcdti8UegfBeXe06SKlgEbi0Ie+mY5rXNMpLmuAIc1sUlrg7+WYyrqMnFSkttvqvpchJXaRH4xhIa0tpaaIB8cjCWMYwte7KI3HUDJbhL7zuV9Gtd3qSepp677O357LEZw4UYO2+BU7aSqntKHtY5wP0mewcdGnJmy7yNLK3A4mq6sKeq112L7EK1OKi5fcktg58+GUjr3+qAv8Asks/kqMfHJxM13k6DvTRPLULSC2e+8Yj+8t/w8K28R1dL/H/AJMqp9KXP6IyMSh4WohiJkDAySRxZLJGczTGxgLmEEg55Da9uSoUpZFOUla90taT3t7b7kSkrySLddhT7Zo6mruzURNkjPCW1ylzxfXd4w3rMK0b2lGOvts9Xh9jEoPsbNQjwx+HVcT5KgvfXVUbSwEgMGbM67ibyauay9hoTprYdJ1o4qk0o2UIv87t5rqLpyTb2s33Fah0cEj2Zc4byA69i88lgIFjbMQuRSipTSezt5dptSdldGPM+saOSyllPSZJIv4csnxU0qDetyXyT+q9DDy+788TWa3HsQFTE5sUTaaO/wBKcDnbHkc4y2lNiS2MNPJHjEg3IIG9DDYbNtNvKfR7G92rve/s195S6lTKWrV2mx0tYZsPbM4AOkpg9wF7AuizEC9za5K0pwVPEOC7JW8y1SyoX7jzxgf3qn7WP5wvZ1+qlyfocmHSR6dK8Idoqj3hWUumjEthSqzIQBAEB9bTsk5MjWuad7XC4NiCLg79Rf8ABbeBX9ZMjLYRO02ycNU05GNimAOSQAAPtzSAb2np3j8j34VHHkUSppkpsuxzaKna8FrmRtY5p/RLOQQfQQoT6TJw6JlChiEpm4OMSkZTJlGYjozb+YeoJlStk31DJjfKtrMkj/V1EkY9PQxsfJIyNjXyWzvDQDIWiwLjzqTk2km9hFRSd0Kw7guX7QkrRRZExVzCQQEJtv5NrOxf8FtYH3iHNFdbq3yOIeD/AMp0naj4Feq9oe7T5HModYjveKHlU7D+nM3+Bj5h+cYXkKWyT3L1aX1OrLsXf/JnqokR+0M5jo6p43sglcPS1jiFdh45VaEd7XqQqO0W+40jwKkOoqhjgCBPexF/GY0bv+1dX23dVoyW76mtg+g13m2s2Uow572wZXPJc4skkbcnUkZXC34LnPGV2knK9t6X2NjNQ22KxszS7nRGQdE0ssw9mRzgsaXW7HbkkvRIZqO4wtqcPhiw2tEMMUd4H3yRtZfQ78oF1Zhas54mGXJvWtrI1IpU5WXYbDD4rfQPgtOW1lyK1gGBKCauLobDISPO58QafU16tWqk+a9H/BH+5fm4z1USNT8KbiMJqLc5jB9HCsXQ9lL/AFUfn6MoxPVMp8FMl8KgH6rpB/eOd/Us+1lbFS+XoMN1aNuXOLyC2e+84l+8M/w8S28R1dL/ABf+5lUOlLn9EZtKM1VUOvcNZFHbocM8rvWJY/UFVLVSit7b9F9GSXSZIKkmcx8JFd/tbC4/+G9j/bmaP8td32bT/wBJWlvTXgv5NLES/qxX5tN9xqx4CM/7yoj/ALq9R/krkUNWVLdF+f7fqbU+xd/8/QkVSTNY8JFVwWF1JG9zQwf/ACPDXfkXFb3s2GXioePginEO1NlezT74PAf+lt6mEfyWMSrYuX+X1FPqlyODYH96p+1j+cL11fqpcn6HLh0kenSvCHaKo94VlLpoxLYUqsyEAQBAfWnXRSi2neO0GbBmd+h+NwPiuxQq1prXB+S9bFUpRjtZk/Rn2uWEfiD8FuqlVteUbeD9CtVoN2uWnDpUS0+ZfOfyS5gtSVAG7UrTrY2ENUdb8iSRiOdc3K5E5ubypbSZ8UQEBCbb+TazsX/BbWB94hzRXW6t8jiHg/8AKdJ2o+BXqvaHu0+RzKHWI9AVtIXljmvLHMJIOUEG7S03B8xO6y8fCeTdNXudZq5HwjEAXZjRPFzlsJmEjmzeML26Arnoz2ZS8H9iCznd5lFdSVs8L4nmkhEjXMcWiSc5XAtNgeDANjz3WYToU5qSynbX2L/9GGpyVnZef2I7ZPZ1mFte3hZJjMW6CLdwYdchoJNuUPyV2LxUsY07JW795GlTVLVe9yamxxjS36uexc1pc6CRgYXvbGzV4Ga7ntHJv0rWWHk09a8U9iu9ncu0sc0YVbtvQRG0lTlPRwUp+DVZD2fiJ9GPmvuRdemtrLu2Lw7DKsjUGneQekFtwo4NWxME+JGavVvkTFP4jf2R8FrS2smthcWDJiVuHMkNyZGutYPZK9hA3jVpF7E3sbhWQqyhqVrd6T9SLimYEWCTNFhiNZ6XCmd80ZVzxEHtpx/+33IqD4n5fYt1mzDZ2FlXU1M7Da7C5kbTY3FxE1l9bHW+4LMMW6byqcVF79bfm2YdLKVpNv8AO4kMGwiGli4KnZkZcnLmc7U7zdxJVNavOtLLm7snCCgrIzlUSIHZ/wC9Yl+8M/w8S28R1VL/ABf+5lUOlLn9DLxTA4phIbcHK8W+kRgNkFtAc41NvOq6WInTa7Uux7PAlKClz3mJQ7PSRiwxGud53Ohf88blZUxUZvq4/K69GiMabX9z8j5JsjTyT/SKkGeYFuV7iW5AwDKAxhDTqCbkbysrG1IwzdP9sd3/AHrGZi3lS1slK6jL3RubIWOYSQcrXA5hlNwfMTuI3rXhNRTTV7k2rkPTVOKB7hJT0bmhxDX8M+MuaCcri0CSxIsbLZlDCWTUpX5J/YrTq31pfniY21uCVFfCyncGwDOHvkDxK05WuAaByXG5dfcNynhMRTw03UX7tVktn3RirCVRZOwksPwz6Nh30cvz8HC8Z8uXNo4+Lc2323qipWz2IzlrXaJxjkwyTz5gf3qn7WP5wvZV+qlyfocmHSR6dK8Idoqj3hWUumjEthSqzIQBAXoIgdXHT4rewmFVT90tnqRbsZjQBuXVjFRVoqxEEqQLtPUlp0P4HnVlOpKD1FdSnGa1l2OtEcEk850bmcfMG6BrfxFgOkqzASnKk6lV6238rarLu1GtUp3qKnDuMfZGnH0CEEW4RmdwuTrJyjv5rELayFKnkvY16jEzefb3P0MFtMba6LylPA1JRu3Y38pFpzSDYrWnCUJZMtpI+KACAhNt/JtZ2L/gtrA+8Q5orrdW+RxDwf8AlOk7UfAr1XtD3afI5lDrEd4NZM58rYo4nCN4Zy5XMzExskJBDHacsD8CvJZEEk5N69epX7Wt63HUu7uxiw4nOXuAjjkuHZY432ymN/BSAyvsHcrTxRYg776TdGnZa2u996utS+7MKUrmEzaqYVlPSz0LoeHz5Xmojf4jS7xWX57DUjerXg4OjKrCpfJtqs+3mQzry1FxtcmpBerj6GQyXHne+LKf7t/rWqtVJ97Xkn9y3+75FvEsLdLIxwkysBjL2ZCS7gZRNHldcBnKFjcOuN1t6lTrKEWra9dvmrPnq2a0YlG7/OZA+Fqoy4XKL+O+Nv8AGH/0Lb9kRvik9yfpb6lWKf8ATZdrZs+Alx3uoQT6eBF/zUYRycdb/wA/qZbvR+X0NopvEZ+yPgFoy6TLlsLiiZCAIAgCAICB2f8AvWJdvH/h4lt4jqqXJ/7mVQ6Uuf0JyWQNaXHcASfQBcrVSu7ItI2LGHFgc+kqmggEcmN97i+gjc4+sBXOgr2U4vxXqkQy9V7Mgcc29bA6mDaWd3DPLcr2mN7QC1ukZBLic2g0utyh7NdRSbmtS7Na8SqeIUbatptVBWNlZnZuzPbzfoPdGTpzXaVz6kHCWS+7zVy+Lurl8EG9ju3+b0qBktVlUyJhkme2Ng3ve4NAubC5PnIClCEpvJirvuMNpK7LNXO19PI5jmuaYnEOaQQQWEggjeCFKEXGok1bX9TDacdR5uwP71T9rH84Xt6/VS5P0OPDpI9OleEO0VR7wrKXTRiWwpVZkIAgM+FvJb6Pjqu9ho5NKK7v5IPafbA6dH4cyvMHxjhci+oUcuOVk31gqv0/h51IHPcc+k1NY6la6Ut4SzIzmysH65buyjU5uhbVNPJUTbhmqcM47c/odcp4QxjWN3NaGj0NFh8Funn5Nt3ZEVAs94F/GPP06rlVGs5JJ7GdGm7wRgVBBNwfT5lwsXKEpZUHe+0vRaWqZCAhNt/JtZ2L/gtrA+8Q5orrdW+RxDwf+U6TtR8CvVe0Pdp8jmUOsR3vBzdsjv1ppf4JHRA+pgXkK2ppdy9L/U6sNnzZcpcOjje97GkOfe/LcQMzi92VpNm3c4uNgLnesSqylFRfZ/189QUUndHPtsq/LtBhreZojH4yyPafyyrsYOnfAVXz8kjVqy/rxN1lrY4qmZ00jY28FE0F5yjkulcSHHT9No38y5apynTioK+t7Pl9jYckpO/d9SRhq43i7JGOHS17T8FTKEo7U0TTT2HP/DRVRmjijEsZeJ2u4MPGbKGSDNl32uR612PYsJKs5NO1tvzRq4trIS7zPoXl+zm43+hvba36oc3+Spmsn2j/APJElrofI3Km8Rn7I+AXNl0mbC2F1RMhAEAQBAEBB4C0irxHTfNHbz//AM8S267/AKVLk/8AcyqHSlz+hl7Ra0srb24QCIHoMzhCLee7wqsP1qe7X4a/oSqdFr81kiqSZFY0WQU9XUNby+Cc8uJJJLGEMAJ3AcwGl3E7yb7FG9SpCm9l0vF6yE7Ri5ER4K3Xwmm8xkH988/zWx7VX+ql8vRFeG6pfnaSGGYVDKzhZYYnvfJK8SGNpcGukdwdn7x9XkGh5lTVrVIPIjJpJJW7NmvzuTjCLV2jCxbYmCYOYA6NkljIWyPc5xabsDQ/M1g1JJAud2m9W0faFSnaW1rZqVu/ZZshKhGWojdkpmD+1KeO+SmDYmX32YyVpLjzkva8/j0WV+Li3maktstb8V9LEKTX7ors1HHcD+9U/ax/OF6Wv1UuT9Dnw6SPTpXhDtFUe8Kyl00YlsKVWZCAIC/HU2FrLfo43IioyWwi0fIJyLi1yTf1rco4uFWWTZpkWrB9O83PJufOszwsZVc43u1chfUXJXiONz7AWF997nmF1st7wkacyvqBuqqn0cM4+q62tJna2op0aF7h9bORY1VT+E7x8CFjSan4ho1PcbDhjnNiZynE5Rq5xcTfXUnU/ivO18RNYic09dzYjFKKSLy0yQQBAQm2/k2s7F/wW1gfeIc0V1urfI4h4PvKlH2o+BXqvaHu0+RzKHWI7WzE3U0cbJqWpcSDd8MYmbm3uNmHOASTvaF5Z0VVk5Rmvm7eurzOllOKs0/kXxtHF/wqwHo+gVV/kUdFnvj/AO0fuZzi3PwZo+0uB1dVikFVBSyiNhiuZHRsP1b8xIaXXta2/XzLq4bEUaOFlSnNXd9l3tXI1qlOc6ikluOmzxNe1zHta5rhYtcAQ4HeCDoQuFGTi7rabrV9TI92ztGdDR0un/Tx6fkrtKr8cvFkM3DcjLpKGKIWhijjHQxjWj1AKudSc3eTb5klFLYjIuoGQgCAIAgCAIAgCAwcWgke1nBBji2Rry17ywODTcDMGusQ7Kd3NzK2jKKbyr7GtX4iMk3sIo7V5ZnQyUVbmabF8cBlZuB0e3UjXoWxoV4KcZx19jdn4fyV53XZpmJtpUvqaKWnpY5jNLlaGuhkj0zB7uXIAy2Vrhv5+lWYKCpVlUqNZKvsafctSu9vcYrNyg4x2sr2OopqHCy2obZ8QlflaQ7TV4tbefMFjGVIYnFXg9TsvoKUXTp6+8mcAmh4CGOGaKQRxtZdkjX+I0N3gnXRa2IjPLcpxau29aLINWSTJF7g0EncBc+galUJX1Imcm8FdWZP7We7fIwPPpPDE/MvRe1YKOZS7NXoaGGd8t/nac8wP71T9rH84XZr9VLk/Q1IdJHp0rwh2iqPeFZS6aMS2FKrMhAEAQH1rrG4UoTlB3i9YK+Hd0/BXaXW4vQxZEVjtbychddxO6/MNe5bmDVSrPOT2L1MOyI3DaXO/XcBc/yH+uhbWKr5qGrawjEWyDbGNsAOgW9S8zJ3bZIqWAEAQEJtv5NrOxf8FtYH3iHNFdbq3yOF7DzsjxGlfI5rGtkBLnEANFjqSdAvV46Llh5qKu7HMotKabO88aKLrtL7xH3ryWiYjgl4M6mdhxIcaKLrtL7xH3pomI4JeDGdhxIcaKLrtL7xH3pomI4JeDGdhxIcaKLrtL7xH3pomI4JeDGdhxIcaKLrtL7xH3pomI4JeDGdhxIcaKLrtL7xH3pomI4JeDGdhxIcaKLrtL7xH3pomI4JeDGdhxIcaKLrtL7xH3pomI4JeDGdhxIcaKLrtL7xH3pomI4JeDGdhxIcaKLrtL7xH3pomI4JeDGdhxIcaKLrtL7xH3pomI4JeDGdhxIcaKLrtL7xH3pomI4JeDGdhxIcaKLrtL7xH3pomI4JeDGdhxIcaKLrtL7xH3pomI4JeDGdhxIcaKLrtL7xH3pomI4JeDGdhxIcaKLrtL7xH3pomI4JeDGdhxIcaKLrtL7xH3poeI4JeDGdhxIcaKLrtL7xH3poeI4JeDGdhxIcaKLrtL7xH3pomI4JeDGdhxIhscGD1b2Pqaile5gsD9LDdCb65XC62qGm0E1TjJX7vuiqeZm7ya8Ssy4VkyNrImtsRZuIvaCCLEECSx06Vi2MvlODb/xX2M3pWtfzL8mMYbHDK2CehZeNwyxyQtvyTYWbvUFQxUppzjJ6+25lzppOzRwfA/vVP2sfzhetr9VLk/Q5cOkj06V4Q7RVHvCspdNGJbClVmQgCAIAgKZCcpygE2NgTYE8wJ5gsxtdX2Bmhy7K1s0xlmkia4m+bMTltuDWgWAHRdejj7TwlGnm6cW1+bTQeHqyllSZueHUfBtNzcm1yBYadAufOuJicRnnsskbyNax/ZWeZwMcseUbmuzN1PObAgldXC+1qVONpxd+6z+xrV6M6j1PUS2zdLVxNLKqSN7QBkIc5zh5iSBcenVaGOq4ao1Kimn27Ler+xOjGpHVN3JpaBeEAQEdtHQunpKiFls0kTmtvuuRpc8wursNUVOrGb2JohUjlRaR5+m2UrmuLTRVNwbaQPcPwcAQfwXsVjcO1fLXijlOjUX9rKOLFb1Gr92l7lnS8P8AEj4oZqfCxxYreo1fu0vcml4f4kfFDNT4WOLFb1Gr92l7k0vD/Ej4oZqfCxxYreo1fu0vcml4f4kfFDNT4WOLFb1Gr92l7k0vD/Ej4oZqfCxxYreo1fu0vcml4f4kfFDNT4WOLFb1Gr92l7k0vD/Ej4oZqfCxxYreo1fu0vcml4f4kfFDNT4WOLFb1Gr92l7k0vD/ABI+KGanwscWK3qNX7tL3JpeH+JHxQzU+FjixW9Rq/dpe5NLw/xI+KGanwscWK3qNX7tL3JpeH+JHxQzU+FjixW9Rq/dpe5NLw/xI+KGanwscWK3qNX7tL3JpeH+JHxQzU+FjixW9Rq/dpe5NLw/xI+KGanwscWK3qNX7tL3JpeH+JHxQzU+FjixW9Rq/dpe5NLw/wASPihmp8LHFit6jV+7S9yaXh/iR8UM1PhY4sVvUav3aXuTS8P8SPihmp8LHFit6jV+7S9yaXh/iR8UM1PhY4sVvUav3aXuTS8P8SPihmp8LHFit6jV+7S9yaXh/iR8UM1PhZK7L7H1r6uHNTTRtbI1znyRuYGta4E6uAudNwWvisdQjSlaSbs9SdydOjNyWo9ALx51SqPeFZS6aMS2FKrMhAEAQBAEAQBAEAQBAEAQBAEAQBAEAQBAEAQBAEAQBAEAQBAEAQBAEAQBAEAQBAEBVHvCspdNGJbClVmQgCAIAgCAIAgCAIAgCAIAgCAIAgCAIAgCAIAgCAIAgCAIAgCA+FAY4Fzr6+n8Ob/7UNpPYfWE2Nug8/8Aqyyg7H0B3n82vp3696axqAa7z+m/+tVJQm9iMOUS5T3zszA2BGbz6i/PqrKUJKccqLtdX+pGTWS7MkeGi0s0fiOcu1B6QGud7IW/lUNVod+tPtevmkm7cl2mvafa/wA/79WfY54/0mjxv1Ruu3fZv7f81mE6X90O3ctl47orvts3O5hqXY/zX38j6ZIr6htri1m6tAuTfQXB0FtfSs/0XLXHVdbE7rbe/wC1XvqVte++ofvtt8/5LM7mkjLl3nc22mmUHQXO9U1MjOLJXa9itq1W7Fd7fuTjezv3GKtAuCAIAgCAIAgCAIAgCAIAgCAIAgCAIAgCAIAgCAIAgCAIAgCAIAgKXxg7wsNXMptFSyYCALN2AmU95iyCZT3mbBMp7zFgl2ZsVR7wrKTbmrkZbD//2Q==)
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
