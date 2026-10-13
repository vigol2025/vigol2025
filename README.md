# Vigol Brayann Fofie

Élève ingénieur en 5e année de **mécatronique et robotique** à JUNIA HEI (Lille). Je conçois des systèmes mécatroniques de bout en bout : dimensionnement, électronique, commande embarquée temps réel et modélisation.

**Je recherche un stage de fin d'études de 9 mois** en robotique ou en systèmes embarqués.

## Projets

### Stabilisation par roues de réaction d'un robot monowheel

Projet associatif CRYSTEO (JUNIA), octobre 2025 à aujourd'hui · [voir le dépôt](https://github.com/vigol2025/reaction-wheel-monowheel)

Robot mascotte en équilibre sur une seule roue, stabilisé par quatre roues de réaction à 45°.

- Dimensionnement : 3,3 N·m pour corriger 10° en 0,4 s, soit 1,17 N·m par roue
- Firmware ESP32 : driver du capteur BNO055, commande des ESC, PID deux axes, 200 Hz, FreeRTOS
- CAO SolidWorks et pièces imprimées en 3D, outils Simulink, modèle système Capella
- Revue de conception : moteur sous-dimensionné détecté par le calcul, avant tout essai

### Banc d'essai d'exosquelette pédiatrique, hanche et genou

Projet de fin d'études, JUNIA HEI, septembre 2026 à janvier 2027 · équipe de 4

Banc à deux degrés de liberté qui reproduit la chaîne d'actionnement de l'exosquelette INES, pour valider sa commande en couple.

- **Mon rôle : responsable électronique, actionnement et instrumentation.** Moteurs brushless maxon et réducteurs Harmonic Drive, contrôleurs EPOS4 en EtherCAT pilotés par une cible temps réel Speedgoat (Simulink Real-Time, 1 kHz), codeurs absolus SSI
- Dimensionnement des couples et des courants, schéma électrique sous KiCad, chaîne d'arrêt d'urgence à deux canaux (STO, relais de sécurité, EN 60204-1)
- Contribution à l'ensemble du projet : cahier des charges, planification (PERT, chemin critique), appui à la commande (CiA 402)
- Avancement : conception en cours, banc opérationnel prévu en janvier 2027

*Projet de recherche JUNIA : les documents ne sont pas publics. Je le présente volontiers en entretien.*

## Compétences

| Domaine | Outils et méthodes |
| --- | --- |
| Embarqué et temps réel | C++ sur ESP32 (PlatformIO, FreeRTOS), I2C, PWM ; EtherCAT et CiA 402 (PFE en cours) |
| Modélisation et commande | MATLAB/Simulink, PID, allocation de couple |
| Conception | SolidWorks, impression 3D, KiCad |
| Ingénierie système | Capella (méthode Arcadia), cahier des charges, niveaux de maturité (TRL), planification |

---

*In English: final-year mechatronics and robotics engineering student at JUNIA HEI (Lille, France), looking for a 9-month end-of-studies internship in robotics or embedded systems. Projects: reaction-wheel stabilisation of a monowheel robot ([repository](https://github.com/vigol2025/reaction-wheel-monowheel)) and a hip-knee test bench for a paediatric exoskeleton (final-year project, electronics and actuation lead).*
