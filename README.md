# Parolotheque-IRIT

## Présentation

Le projet Parolothèque a pour but d’améliorer la transcription de la parole pathologique (affectée par un cancer ou une opération chirurgicale).
Le présent dépôt contient un code réalisé dans le cadre d’un stage de Master 1 de trois mois, en 2024, s’inscrivant dans le projet Parolothèque et s’étant déroulé au laboratoire IRIT de Toulouse, proposant un protocole de segmentation, diarization (c-à-d distinction des différents interlocuteurs) et transcription speech-to-text de fichiers audio parlés, ainsi que de fine-tuning de modèles d’IA de transcription en vue de les adapter à la parole pathologique.
Ce projet est décliné en deux versions, l’une fonctionnant dans un environnement de type notebook et l’autre pouvant être exécutée n’importe où, y compris depuis un terminal (avec un affichage adapté à cet effet).

Entièrement codé en Python, ce projet utilise les bibliothèques de Pyannote (pour la segmentation et la diarization des fichiers audio), Speechbrain et Whisper (pour la transcription automatique), qui sont importées automatiquement lors de l’exécution du code. Pour utiliser ce code en local, il suffit donc de cloner le répertoire https://github.com/Gabriel-Faraut/TUIC-IRIT et d’avoir un environnement de type notebook prenant en charge les fichiers `.ipynb`.

### Contenu

La totalité du code est contenue dans le fichier `parolotheque.ipynb`.
Le code est accompagné d’une documentation technique détaillée, fonction par fonction.

Le fichier `parolotheque.ipynb` ne contient pas les fichiers originaux, provenant des archives du CHU de Toulouse et dont l’accès est strictement réglementé, mais toutes les fonctions ont été conçues pour être applicables à n’importe quel jeu de données.
Les portions de code mettant en jeu lesdits fichiers sont conservées à titre d’exemple.

## Structure du projet

```
(master_repository):
  README.md
  LICENSE
  TABLE_OF_CONTENTS.md
  parolotheque.ipynb
  master_thesis.pdf
```

## Contacts

Contact professionnel: gabriel.faraut@proton.me

Contact de mes tuteurs de stage: julien.pinquier@irit.fr / mathieu.balaguer@irit.fr

## Licence

Ce projet bénéficie de la licence Apache 2.0.
