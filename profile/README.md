<!-- Banner / Title -->
<p align="center">
  <img src="https://dummyimage.com/1200x240/0f172a/ffffff&text=Recolu" alt="Recolu – Réseau de capteurs sans batterie">
</p>

<h1 align="center">Recolu</h1>
<p align="center">
  Réseau de capteurs <b>sans fil</b> et <b>sans batterie</b> basé sur <b>OpenThread</b><br/>
  <i>En collaboration avec Schneider Electric</i>
</p>

<p align="center">
  <a href="#"><img alt="OpenThread" src="https://img.shields.io/badge/OpenThread-1.3+-0ea5e9?logo=google&logoColor=white"></a>
  <a href="#"><img alt="IEEE 802.15.4" src="https://img.shields.io/badge/IEEE-802.15.4-22c55e"></a>
  <a href="#"><img alt="Energy Harvesting" src="https://img.shields.io/badge/Energy%20Harvesting-Yes-f59e0b"></a>
  <a href="#"><img alt="Made in Montreal" src="https://img.shields.io/badge/Made%20in-Montr%C3%A9al-b91c1c"></a>
  <a href="#"><img alt="License" src="https://img.shields.io/badge/Licence-MIT-6366f1"></a>
</p>

---

## 👋 Bienvenue dans le projet Recolu

**Recolu** est un projet universitaire de **réseau de capteurs sans fil et sans batterie**, misant sur l’**énergie récupérée** (harvesting) et une pile logicielle **OpenThread** pour offrir une connectivité maillée robuste, frugale en énergie et prête pour l’IoT.

- 🎯 **Objectif** : démontrer un maillage de capteurs autosuffisants (température, mouvement, etc.) avec passerelle minimale.
- 🧠 **Stack** : Thread/IPv6, CoAP/MQTT, synchronisation temps/réseau, protocole d’économie d’énergie.
- 🏫 **Cadre** : Projet intégrateur 4 – Polytechnique Montréal.
- 🤝 **Partenaire** : Schneider Electric.

---

## 🧩 En bref

- **Sans batterie** : supercondensateur + harvesting (lumière, vibration, thermique).
- **Maillage Thread** : tolérance aux pannes, topologies denses.
- **Ultra-basse conso** : devoir de réveil limité, protocoles duty-cycled.
- **Interopérable** : IPv6/6LoWPAN, interfaces standards (CoAP/MQTT).

---

## 🛠️ Pile technologique

- **Réseau** : OpenThread (Thread 1.3+), 6LoWPAN, IPv6
- **Couches supérieures** : CoAP (+ observe), passerelle MQTT
- **Matériel typique** : nRF52/nRF53, capteurs I²C/SPI, supercap
- **Outils** : C/C++, CMake, Python, Wireshark, CLI ot-ctl

> *Remplacez par vos versions exactes et cartes utilisées.*

---

## 🏗️ Architecture (aperçu)


