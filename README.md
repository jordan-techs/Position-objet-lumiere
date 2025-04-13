# Positionnement d’un objet à l’aide de sources lumineuses

Ce projet vise à localiser un objet dans un espace en exploitant des sources lumineuses fixes (LEDs) et des capteurs de lumière placés sur l’objet. L’objectif est de déterminer la position de l’objet en temps réel, à l’aide de mesures d’intensité lumineuse et de calculs de triangulation.

## 🎯 Objectifs
- Utiliser plusieurs sources lumineuses fixes 
- Capturer l’intensité lumineuse avec des photodiodes ou capteur de lumière
- Estimer la position de l’objet par triangulation ou modulation de la fréquence des sources
- calcul de la position estimée en temps réel avec carte FPGA

## ⚙️ Technologies & Matériel utilisés
- Photodiodes / capteurs lumière
- LEDs fixes (IR ou blanches)
- Carte FPGA (Terasic DE1-SoC)
- Logiciel quartus 2
- vhdl pour l’embarqué
- simulation de l'acquisitions d’images avec Python

## 🧠 Fonctionnement
- Plusieurs LEDs sont disposées dans l’environnement.
- L’objet mobile est équipé de photodiodes ou capteurs de lumière.
- En mesurant l’intensité perçue de chaque LED, on estime la position de l’objet.
- Traitement des données à l'aide de la FPGA

## 📷 Démo (à compléter si tu as une image ou vidéo)
Ajoute ici une image du montage ou un lien vers une vidéo (YouTube, Drive, etc.)

## 📦 Structure du code
