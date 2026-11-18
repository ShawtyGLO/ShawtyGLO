## Lucas Lallier-Ginoux — Music stuff et développement de plugins en vibecodant

Producteur depuis 2021 mais musicien autodidacte depuis l'enfance, je conçois des plugins
audio VST3 en C++ / JUCE grâce à l'IA et je les valide : protocoles de mesure écrits, cibles
chiffrées, comparaisons d'écoute égalisées en niveau, points de non-régression.

Je suis aussi bêta-testeur; ce que j'aime dans le test, c'est la decouverte,l'expérimentation et la possibilité de faire évoluer un projet de ces balbutiments vers la version publique.

### Ma méthode

| Étape | Ce que ça donne |
|---|---|
| Écrire le protocole avant de coder | on sait ce qu'on mesure, et ce qu'on ne mesure pas |
| Mesurer des cibles sur une référence | un critère chiffré, pas une impression |
| Comparer à l'écoute, à niveau égalisé | au-delà d'un demi-décibel d'écart, on compare le volume et rien d'autre |
| Figer un point de sauvegarde | l'état validé reste rejouable, et les régressions se voient |
| Écrire ce que la campagne ne couvre pas | une limite assumée reste claire |

### Projets publiés

- **[LuxRev-1](https://github.com/ShawtyGLO/LuxRev-1)** — réverbe algorithmique conçue sur quatorze cibles mesurées, avec protocole de mesure et point de référence validé, dans l'esprit des réverbes numériques des années 80/90 .
- **[PRISME](https://github.com/ShawtyGLO/PRISME)** — du mix au mastering, une cinquantaine de scripts de banc, recettes rejouables à l'identique. 
- **[Digitape](https://github.com/ShawtyGLO/Digitape)** — varispeed, delay et réverbe : l'ADN d'un Space-Echo repensé en mécanismes numériques.
- **[SYN-DRUM](https://github.com/ShawtyGLO/SYN-DRUM)** — synthétiseur de percussions par modèle physique, versionné, avec note de compatibilité au renommage.
- **[ROMANCE](https://github.com/ShawtyGLO/ROMANCE)** — Synthése typé rompleur dont une recherche hors-ligne fabrique une resynthése.
- **[InvisibleFix](https://github.com/ShawtyGLO/CODE-InvisibleFix)** — réparation vocale : de-reverb, gate, nettoyage, air. Mon tout premier plugin.

### Projets pas encore publiés

**TOTUMtape** (émulation de bande à biais AC : un oscillateur de biais à 100 kHz sommé au
signal, d'où la compression et la perte d'aigus émergent au lieu d'être imitées) ·

**SHAW-TI** (synthétiseur, qui sert de moteur à une groovebox DIY, d'une calculatrice bien connue avec comme projet de pouvoir être pilotée par un Arturia
MiniLab mkII) · 

**XPERT comp** · Un compresseur M/S Multibandes avec plusieurs types de comportements (VARI-MU, FET, OPTO et VCA)
une douzaine d'autres. Dix-sept plugins en tout.

### Outils

C++ · JUCE · VST3 · Python pour les bancs de mesure · FL Studio 25 · Windows 11 ·
[pluginval](https://github.com/Tracktion/pluginval) 

Important: Je m'occupe des projets, des test et de la partie création à 100%, mais je suis assisté par IA pour l'écriture du code

---

© Lucas Lallier-Ginoux. **Tous droits réservés.** Ces dépôts sont publiés en consultation
uniquement. Aucune licence d'utilisation, de modification, de redistribution ou d'exploitation
commerciale n'est accordée.
