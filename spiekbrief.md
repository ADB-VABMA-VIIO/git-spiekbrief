# Spiekbrief Git en GitHub

## 1. Clone, commit, push en pull
# clone pakt de bestanden van de repository en voegt die toe aan je lokale map waarmee je met github desktop het hebt toegevoegd.
# commit is dat je een opgeslagen versie maakt van je folder 
# push is dat je al je wijzigigen naar github verstuurd
# pull is dat je de wijzigingen die op github staan maar nog niet lokaal syncroniseert op je lokale folder

## 2. Goed voorbeeld: Een toegoeging van spiekbrief.md met uitleg wat clone,commit,push en pull is ; Slecht voorbeeld: verandering spiekbrief.md

## 3. Gitignore
# een .gitignore zegt aan Git welke bestanden of bestandstypes het moet negeren, zodat rommel zoals Thumbs.db, .DS_Store, .zip- en .log-bestanden nooit per ongeluk in je repository terechtkomen.

## 4. Pull
# ik heb README.md online op github.com aangepast, en met fetch origin en pull origin heeft github desktop die wijziging naar mijn lokale map gehaald, waardoor mijn zin nu ook in vs code staat.
# ik pull aan het begin van elke les eerst, zodat ik werk op de nieuwste versie en geen conflicten krijg met wijzigingen die ergens anders (online of op een ander toestel) zijn gemaakt.

## 5. Terugdraaien
# met revert changes in commit maakt github desktop een nieuwe commit die precies het omgekeerde doet van de foute commit. de foute commit wordt dus niet gewist, er komt gewoon een commit bij die de fout herstelt.
# de foute commit verdwijnt niet uit de geschiedenis omdat git nooit zomaar iets weggooit dat al gepusht is. anderen kunnen die commit al gepulld hebben, en als je hem zou wissen klopt hun geschiedenis niet meer met die op github. zo kan je ook altijd terugzien wat er fout liep en hoe het is opgelost.
