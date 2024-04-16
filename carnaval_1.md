# Carnaval

## @showdialog

Programme trois lutins pour qu'ils interagissent à l'écran­.

## Étape 1

Ajoute le bloc ``||carnival:trace path estimate||`` (onglet ``||scene:Scène||``) dans le bloc ``||loops:au démarrage||``.

```package

carnival=github:microsoft/arcade-tutorial-extensions/carnival

```

```blocks

let myBall: Ball = null
myBall.setTraceMulti(carnival.Tracers.Full)

```