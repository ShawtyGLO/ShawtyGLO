## Lucas Lallier-Ginoux — production musicale et développement de plugins audio

Producteur depuis 2021 mais musicien autodidacte depuis l'enfance, je conçois des plugins
audio VST3 en C++ / JUCE et je les valide : protocoles de mesure écrits, cibles chiffrées,
comparaisons d'écoute égalisées en niveau, points de non-régression.

Je suis aussi bêta-testeur : ce que j'aime dans le test, c'est la découverte, l'expérimentation,
et la possibilité de faire évoluer un projet de ses balbutiements jusqu'à la version publique.

### Ma méthode

| Étape | Ce que ça donne |
|---|---|
| Écrire le protocole avant de coder | on sait ce qu'on mesure, et ce qu'on ne mesure pas |
| Mesurer des cibles sur une référence | un critère chiffré, pas une impression |
| Comparer à l'écoute, à niveau égalisé | au-delà d'un demi-décibel d'écart, on compare le volume et rien d'autre |
| Figer un point de sauvegarde | l'état validé reste rejouable, et les régressions se voient |
| Écrire ce que la campagne ne couvre pas | une limite assumée reste claire |

### Projets publiés

- **[LuxRev-1](https://github.com/ShawtyGLO/LuxRev-1)** — réverbe algorithmique conçue sur dix grandeurs relevées sur quatorze programmes d'une machine de référence, avec protocole de mesure et point de référence validé, dans l'esprit des réverbes numériques des années 80/90.
- **[PRISME](https://github.com/ShawtyGLO/PRISME)** — du mix au mastering : bancs de mesure et recettes rejouables à l'identique.
- **[Digitape](https://github.com/ShawtyGLO/Digitape)** — varispeed, delay et réverbe : l'ADN d'un Space-Echo repensé en mécanismes numériques.
- **[SYN-DRUM](https://github.com/ShawtyGLO/SYN-DRUM)** — synthétiseur de percussions par modèle physique, versionné, avec note de compatibilité au renommage.
- **[ROMANCE](https://github.com/ShawtyGLO/ROMANCE)** — synthèse typée rompleur, dont une recherche hors-ligne fabrique la resynthèse.
- **[InvisibleFix](https://github.com/ShawtyGLO/CODE-InvisibleFix)** — réparation vocale : de-reverb, gate, nettoyage, air. Mon tout premier plugin.

### Projets en cours, non publiés

- **TOTUMtape** — émulation de bande à biais AC : un oscillateur de biais à 100 kHz sommé au
  signal, d'où la compression et la perte d'aigus émergent au lieu d'être imitées.
- **SHAW-TI** — *Small Harmonic Autonomous Workstation* : boîte à rythmes et synthé minimaux,
  à synthèse entière, avec trois caractères de sortie (CHIP, SAMPLER, HIFI). Conçu d'abord
  comme VST, puis porté sur calculatrice TI-83 / 84 Premium CE, et destiné à servir de moteur
  à une groovebox DIY pilotée par un Arturia MiniLab mkII.
- **XPERT comp** — compresseur M/S multibande, avec plusieurs types de comportement :
  VARI-MU, FET, OPTO et VCA.

Ainsi que d'autres prototypes, à des stades divers.

### Outils

C++ · JUCE · VST3 · Python pour les bancs de mesure · FL Studio 25 · Ableton Live Lite
· Windows 11 · [pluginval](https://github.com/Tracktion/pluginval)

**À propos de l'IA.** Je mène les projets, les tests et la partie création de bout en bout ;
l'écriture du code est assistée par IA.

---

© Lucas Lallier-Ginoux. **Tous droits réservés.** Ces dépôts sont publiés en consultation
uniquement. Aucune licence d'utilisation, de modification, de redistribution ou d'exploitation
commerciale n'est accordée.
