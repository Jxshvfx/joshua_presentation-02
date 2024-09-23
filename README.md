# Scénarisation 

## Idée

### Concept
Avoir des petites sculptures qui auront des projecteurs. Ces projecteurs projecteront sur les sculptures et seront accompagnés par de l'audio. Ce qui sera projeté sera aussi affecter par l'audio. Celui-ci est contrôler par des instruments. Puis, un clavier midi sera au centre pour mettre plus d'effets, et des indicateurs lumières sur les côtés guideront et démontreront l'effet.

### Objectifs
D'interconnecter les utilisateurs avec la musique.

### Motivations 
La musique est 

## Scénario

### Interactif
```mermaid
graph TD;
    A{Utiliser Instruments}-->B{Harpe} & C{Piano} & D{Drum};
    B{Harpe} & C{Piano} & D{Drum}-->E{Interaction avec Projection};
    E{Interaction avec Projection}-->F{Plus D'interaction?};
    F{Plus D'interaction?}--|Oui|-->G{Midi};
    F{Plus D'interaction?}--|Non|-->I{Veille};
    G{Midi}-->H{Activation Lumiere};
    H{Activation Lumiere}-->I{Veille};
    I{Veille}-->A{Utiliser Instruments};
```
### Narratif

### Expérience utilisateur

## Ambiance

## Technologies

### Support médiatique

### Matériel

### Logiciels


