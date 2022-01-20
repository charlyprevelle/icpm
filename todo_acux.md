
## Liens
### Breadcrumb
- [ ] ```aria-current="location"``` &rarr; page courante
- [ ] ```aria-current="true"``` &rarr; page parente

### Liens (global)
- [ ] ```aria-label="Description explicite, nouvelle fenêtre"``` 

### PDF 
- [ ] ```aria-label="Télécharger le document [intitulé], [PDF - 000 Ko], nouvelle fenêtre"```
- [ ] Poids du document dans le CTA

### hellobank.fr
- [ ] ```aria-label="Site Hello bank!"```

----------------------------------------------------------------

## Images
### Alt
- [ ] ```alt="Descriptif de l'image"``` &rarr; Ne pas mettre de :

### Applications (Ne pas mettre "nouvelle fenêtre")
- [ ] ```alt="Disponible sur Google Play"```
- [ ] ```alt="Disponible sur Apple Store"```

----------------------------------------------------------------

## Renvois & mentions

### Astérisques + son renvoi
- [ ] ```aria-labelledby="note_descriptif"```
- [ ] ```id="note_descriptif"```

### Mentions
- [ ] ```aria-labelledby="mention_1"``` &rarr; exemple : sur le (1), mention_2 sur le (2) etc
- [ ] ```id="mention_1"``` &rarr; exemple : sur la mention qui suit ```<p class="ml" id="mention_1">``` etc
- [ ] ```class="ml"``` &rarr; sur chaque mention ```<p class="ml" id="mention_X">```

----------------------------------------------------------------

## Class spécifiques
- [ ] ```hbi-happy-laptop``` &rarr; ```aria-hidden="true"```
- [ ] ```hbi-pulzze``` &rarr; ```aria-hidden="true"```
- [ ] ```hbi-happy-purse``` &rarr; ```aria-hidden="true"```
- [ ] ```hbi-screen``` &rarr; ```aria-hidden="true"```

----------------------------------------------------------------

## Popup WCB
- [ ] ```aria-haspopup="true"```

----------------------------------------------------------------

## Iframe
- [ ] ```title="titre pertinent"```

----------------------------------------------------------------

## Tableau 
- [ ] Le titre du tableau doit être placé dans la balise ```<caption>```
```
<table>
    <caption>Titre du tableau</caption>
    <tr>...</tr>
</table>
```

- [ ] Utiliser ```<th>``` pour les entêtes de ligne ou colonne
- [ ] ```scope="col"``` &rarr; sur les ```<th>``` (colonne)
- [ ] ```scope="row"``` &rarr; sur les ```<th>``` (ligne)


