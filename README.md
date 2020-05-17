<p align="center"><img src="./app/assets/images/SealCircle.png" width="150px" height="150px" alt="aventium softworks"></p>

<h1 align="center">TuTune Player</h1>



<p align="center">Un lecteur de radios francais open-source fait avec electron !</p>
<a href="https://stereo18.github.io/tutuneplayer/" target="_blank">Cliquez ici pour acceder à la version web</a>



## Downloads

Vous pouvez le télécharger depuis les [GitHub Releases](https://github.com/stereo18/tutuneplayer/releases)



## Console

Pour utiliser la console :

```console
ctrl + shift + i
```

## Development

### Pré-requis

**Nécessaire**

* [Node.js][nodejs] v12

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

Les flux sont lus depuis les serveur de distribution respectif des radios présentées et le coeur de l'application est le [heliosLauncher](https://github.com/dscalzi/helioslauncher)
