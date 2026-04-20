# Com crear una taula dinàmica?

```{infonote}
**Quatre elements bàsics d'una taula dinàmica**

- **Files (*Rows*)** - Categories que es mostren a la part esquerra de la taula.
- **Columnes (*Columns*)** - Categories que es mostren a la part superior de la taula.
- **Valors (*Values*)** - Nombres que es calculen (suma, recompte, mitjana…).
- **Filtres (*Filters*)** - Permeten mostrar només una part de les dades.
```

## Creació d'una taula dinàmica - pas a pas

### Pas 1: Seleccioneu la taula de dades
Feu clic a qualsevol cel·la de la taula i premeu la combinació de tecles *Ctrl + A*

![Pas 1](images/pivot1_sr.png)

### Pas 2: Inicieu la creació de la taula dinàmica
Feu clic a *Insert* (1), *PivotTable* (2) i seleccioneu l'opció *From Table/Range* (3)

![Pas 2](images/pivot2_sr.png)

### Pas 3: Trieu on voleu col·locar la taula dinàmica
Podeu triar un full nou (*New Worksheet*) o una ubicació al mateix full (*Existing Worksheet*) (4) (en aquest cas cal fer clic a la cel·la que serà l'angle superior esquerre de la taula dinàmica) (5). Confirmeu fent clic a *Ok*. (6)

![Pas 3](images/pivot3_sr.png)

### Pas 4: Coneixeu l'editor de taules dinàmiques
La configuració de la taula dinàmica es fa arrossegant camps (7) a les zones corresponents (8).

![Pas 4](images/pivot4_sr.png)

### Pas 5: Afegiu files (*Rows*) i valors (*Values*)
Per al primer exemple de la introducció, hem arrossegat el camp *fruita* a la zona *Rows*. A la zona *Values* hem arrossegat el camp *quantitat [kg]*

![Pas 5](images/pivot5_sr.png)


```{infonote}
La manera de calcular a l'àrea Values es pot canviar mitjançant l'opció Value Field Settings. A més de la suma per defecte (Sum), també estan disponibles Average (mitjana), Count (nombre d'entrades), Min i Max. És important saber que, si es col·loca un camp de text a l'àrea Values, la taula dinàmica mostrarà automàticament el nombre d'aparicions d'aquest text (Count) en lloc de la suma.
```

### Pas 6: Afegiu columnes (opcional)
La taula que mostra també la manera com els clients han pagat s'ha obtingut afegint el camp *mètode de pagament* a la zona Columnes (*Columns*) (10)

![Pas 6](images/pivot6_sr.png)

```{infonote}
Si us passa que s'ha tancat el panell de la dreta que permet configurar la visualització de la taula dinàmica, podeu tornar-lo a obrir fent clic a qualsevol cel·la de la taula dinàmica i seleccionant l'opció Show field list.
```
### Pas 7: Afegiu filtres (opcional)
Afegir filtres us permetrà extreure i mostrar ràpidament, d'una gran quantitat de dades, només els valors que necessiteu en un moment determinat, sense modificar la taula inicial ni fer càlculs addicionals. 

```{infonote}
Tot i que la taula dinàmica està vinculada a la taula original, els canvis que s'hi fan no s'actualitzen automàticament. Després de cada modificació cal fer clic dret sobre la taula dinàmica i seleccionar l'opció Refresh perquè tots els resultats s'actualitzin.
```
## Gràfic dinàmic

Les dades d'una taula dinàmica també es poden representar gràficament. D'aquesta manera els resultats es fan més clars i les diferències i relacions es detecten més fàcilment.

El gràfic dinàmic es crea de la manera següent:

Feu clic dins de la taula dinàmica i seleccioneu l'opció *PivotChart* del menú. Trieu el tipus de gràfic i confirmeu la selecció.

![Gràfic dinàmic](images/chart1_sr.png)

```{infonote}
El gràfic està vinculat a la taula dinàmica, la qual cosa significa que qualsevol canvi a la taula es reflecteix automàticament al gràfic. En la representació gràfica, els avantatges de l'aplicació de filtres es fan especialment evidents.
```

![Gràfic dinàmic](images/chart2_sr.png)