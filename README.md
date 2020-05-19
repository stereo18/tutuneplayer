<p align="center"><img src="./app/assets/images/SealCircle.png" width="150px" height="150px" alt="aventium softworks"></p>

<h1 align="center">TuTune Player</h1>



<p align="center">Un lecteur de radios francais open-source fait avec electron !</p>
<a align="center" href="https://stereo18.github.io/tutuneplayer/" target="_blank">Cliquez ici pour acceder à la version web</a>



## Téléchargement

Vous pouvez le télécharger pour windows depuis les [GitHub Releases](https://github.com/stereo18/tutuneplayer/releases). Pour les autres plateformes, veuillez suivre le guide de dévelopement et build pour votre OS.



## Console

Pour utiliser la console de devellopement de l'environnement chromium :

```console
ctrl + shift + i
```

## Developement

### Pré-requis

**Nécessaire**

* Node.js v12
* Dépendances disponibles avec ```npm install```

---

**clone et installation des dépendances**

```console
> git clone https://github.com/stereo18/tutuneplayer.git
> cd tutuneplayer
> npm install
```

---

**Lancer l'application**

```console
> npm start
```

---

**Fabriquer l'application**

Pour build sur votre plateforme actuelle.

```console
> npm run dist
```

Faire pour une plateforme spécifique.

| Platform    | Command              |
| ----------- | -------------------- |
| Windows x64 | `npm run dist:win`   |
| macOS       | `npm run dist:mac`   |
| Linux x64   | `npm run dist:linux` |



### Sources.

Les flux sont lus depuis les serveur de distribution respectif des radios présentées et l'application est basée sur le [heliosLauncher](https://github.com/dscalzi/helioslauncher)
