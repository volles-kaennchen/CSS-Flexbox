# CSS FLEXBOX 

### flex, inline-flex
    .container {display: flex;}
    .container {display: inline-flex;}
   
 ### Ausrichtung von Zeilen und Spalten mit flex-direction
    .container { flex-direction: row | row-reverse | column |column-reverse}
    .container { flex-direction: Zeile | Zeile umgekehrt | Spalte | Spalte umgekehrt}

### Ausrichtung entlang der Hauptachse mit justify-content
    .container {justify-content: flex-start | flex-end | center | space-between | space-around | space-evenly}

### Ausrichtung an der Querachse mit align-content 
    .container {align-content: flex-start | flex-end | center | strech | space-between | space-around}

### Ausrichtung entlang der Querachse mit align-items (nur in mehrzeiligen containern)
    .container {align-items: flex-start | flex-end | center | strech | baseline}

### align-self
    .item {align-self: auto | flex-start | flex-end | center | strech | baseline}

### Umbrüche mit flex-wrap
    .container {flex-wrap: nowrap | wrap | wrap-reverse}
    .container {flex-wrap: kein Umbruch | Umbruch | Umbruch umkehren}

### order
    .item {order: 0;}

## flex-shrink, flex-grow, flex-basis
    .item{flex-shrink: 1;}		
    .item{flex-grow: 0;}		
    .item{flex-basis 0px} 
