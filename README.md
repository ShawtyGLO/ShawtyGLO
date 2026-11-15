## Lucas Lallier-Ginoux — test audio et développement de plugins

Producteur depuis 2021, guitariste et claviériste depuis onze ans, je conçois des plugins
audio VST3 en C++ / JUCE et je les valide moi-même : protocoles de mesure écrits, cibles
chiffrées, comparaisons d'écoute égalisées en niveau, points de non-régression.

J'ai été bêta-testeur pour **Arturia** (Rev Ocean, moteur FM de Pigments) et pour d'autres
éditeurs. Ce que j'aime dans le test, c'est la frontière fine entre un projet inabouti et un
choix de conception : c'est là qu'un retour sert vraiment à quelque chose.

### Ma méthode

| Étape | Ce que ça donne |
|---|---|
| Écrire le protocole avant de coder | on sait ce qu'on mesure, et ce qu'on ne mesure pas |
| Mesurer des cibles sur une référence | un critère chiffré, pas une impression |
| Comparer à l'écoute, à niveau égalisé | au-delà d'un demi-décibel d'écart, on compare le volume et rien d'autre |
| Figer un point de sauvegarde | l'état validé reste rejouable, et les régressions se voient |
| Écrire ce que la campagne ne couvre pas | une limite assumée vaut mieux qu'un angle mort |

### Projets publiés

- **[LuxRev-1](https://github.com/ShawtyGLO/LuxRev-1)** — réverbe algorithmique conçue sur quatorze cibles mesurées, avec protocole de mesure et point de référence validé.
- **[PRISME](https://github.com/ShawtyGLO/PRISME)** — excitation et mastering, une cinquantaine de scripts de banc, recettes rejouables à l'identique.
- **[Digitape](https://github.com/ShawtyGLO/Digitape)** — varispeed, delay et réverbe : l'ADN d'une lignée matérielle retraduit en mécanismes numériques natifs.
- **[SYN-DRUM](https://github.com/ShawtyGLO/SYN-DRUM)** — synthétiseur de percussions par modèle physique, versionné, avec note de compatibilité au renommage.
- **[ROMANCE](https://github.com/ShawtyGLO/ROMANCE)** — rompleur dont une recherche hors-ligne fabrique le matériau d'onde.
- **[InvisibleFix](https://github.com/ShawtyGLO/CODE-InvisibleFix)** — réparation vocale : de-reverb, gate, nettoyage, air. Mon tout premier plugin, et le plus avancé de la gamme Invisible.

### Dans le dossier, pas encore publiés

**TOTUMtape** (émulation de bande à biais AC : un oscillateur de biais à 100 kHz sommé au
signal, d'où la compression et la perte d'aigus émergent au lieu d'être imitées) ·
**TOTUMstrip** (tranche de console modulaire, vingt bancs de mesure documentés) ·
**SHAW-TI** (synthétiseur, qui sert de moteur à une groovebox DIY pilotée par un Arturia
MiniLab mkII) · **XPERT comp** · **ORACLE** (fiches de référence sur du matériel) ·
une douzaine d'autres. Dix-sept plugins en tout.

### Outils

C++ · JUCE · VST3 · Python pour les bancs de mesure · FL Studio 25 · Windows 11 ·
[pluginval](https://github.com/Tracktion/pluginval) · Français, anglais B2

---

© Lucas Lallier-Ginoux. **Tous droits réservés.** Ces dépôts sont publiés en consultation
uniquement. Aucune licence d'utilisation, de modification, de redistribution ou d'exploitation
commerciale n'est accordée.
