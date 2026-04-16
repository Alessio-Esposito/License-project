<!--<img src="https://www.cinetivu.com/wp-content/uploads/2024/11/Se7en.jpg">-->
<!--_Cosa c'è nella scatola?_-->


# isSevenOfficialLibrary
Libreria che importa una serie di 7 funzioni che permettono di interagire con il numero "7".<br/>

# Utilizzo
Come importare la libreria
```python
import sevebLibrary as seven
```
### is7
```python
print(seven.is7(7))                                        # True
print(seven.is7(4))                                        # False
print(seven.is7(7.0))                                      # True
```
### isNearly7
```python
print(seven.isNearly7(7))                                  # True
print(seven.isNearly7(6.7))                                # True
print(seven.isNearly7(7.3))                                # True
print(seven.isNearly7(6.1))                                # False
```
### stringIs7
```python
print(seven.stringIs7("seven"))                            # True
print(seven.stringIs7("Seven"))                            # True
print(seven.stringIs7("eight"))                            # False
print(seven.stringIs7("sEVeN"))                            # True
```
### has7
```python
print(seven.has7(714))                                     # True
print(seven.has7(678))                                     # True
print(seven.has7(45))                                      # False
```
### is7Multiplier
```python
print(seven.is7Multiplier(7))                              # True
print(seven.is7Multiplier(21))                             # True
print(seven.is7Multiplier(30))                             # False
print(seven.is7Multiplier(0))                              # True
```
### has7Items
```python
print(seven.has7Items([0, 2, 4, 6, 8 , 10, 12]))           # True
print(seven.has7Items((0, 2, 4, 6, 8 , 10, 12)))           # True
print(seven.has7Items([0, 2, 4, 6]))                       # False
```
### stringHasSeven
```python
print(seven.stringHaseSeven("seven_eight"))                # False
print(seven.stringHaseSeven("five"))                       # False
print(seven.stringHaseSeven("SEVENeleven"))                # False
```
# Proprietà Intelletuale
Tutti i diritti di proprietà intellettuale relativi a "Is7OfficialLibrary" appartengono originariamente ad Azienda Sĕptem. Il software è rilasciato sotto i termini della licenza inclusa in questo repository, che ne autorizza il fork, la modifica e la ridistribuzione nel rispetto delle condizioni specificate. La titolarità del codice originale e il diritto di paternità dell'opera restano in capo all'autore; ogni utilizzo derivato deve mantenere intatti i riferimenti al copyright e alle licenze originali come previsto dalle normative vigenti.
<br/>

# Licenza LGPL
Il progetto è distribuito sotto licenza GNU Lesser General Public License (LGPL). In conformità a tale licenza, è esplicitamente autorizzata l'attività di forking, la ridistribuzione e la modifica del codice, anche per l'integrazione all'interno di software proprietari. Gli utenti sono tuttavia vincolati a mantenere le modifiche apportate alla presente libreria sotto la medesima licenza LGPL e a rendere disponibile il codice sorgente modificato secondo i termini previsti dalla stessa.
