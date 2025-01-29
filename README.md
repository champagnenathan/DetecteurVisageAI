
# Détecteur de Visages

Détecteur de visages en C++ avec OpenCV.

## Description

**DétecteurVisageAI** utilise OpenCV et Yolo pour détecter des visages en temps réel. Il peut être utilisé pour tout type de système ayant besoin de détecter des visages (par exemple, caméras de surveillance, algorithmes, etc.).

## Fonctionnalités

- Détection de visages en temps réel avec webcam, images ou vidéos.
- Précis et rapide
- Facile à configurer et à intégrer

## Prérequis (Compiler de source)

- C++ compiler (g++ ou autre)
- OpenCV
- CMake

## Installation (Compiler de source)

### 1. Cloner le dépôt

```bash
git clone https://github.com/votre-utilisateur/DetecteurVisageAI.git
cd DetecteurVisageAI
```

### 2. Installer OpenCV

[OpenCV pour l'installation](https://docs.opencv.org/4.x/df/d65/tutorial_table_of_content_introduction.html).

### 3. Compiler le projet

Compilez avec CMake :

```bash
mkdir build
cd build
cmake ..
make
```

### 4. Exécution

Pour lancer le programme :

```bash
./DetecteurVisageAI.exe
```


## Utilisation

### Lancer le programme et par la suite choisir le mode

```bash
./DetecteurVisageAI.exe
```

### Forcer la détection à partir d'une image

```bash
./DetecteurVisageAI.exe --mode image
```
### Forcer la détection à partir d'une vidéo

```bash
./DetecteurVisageAI.exe --mode video
```

### Forcer la détection à partir de la webcam

```bash
./DetecteurVisageAI.exe --mode webcam
```

### Options

- `--h`, `--help` : Affiche l'aide et les options disponibles.
- `--mode <image/video/webcam>` : Forcer un mode
- `--debug` : Affiche des informations détaillées pour le débogage.

## License

Ce projet est sous licence - voir [LICENSE](LICENSE) pour plus de détails.
