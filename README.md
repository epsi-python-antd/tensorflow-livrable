## Installation sur macOS

Création de l'environnement cuda
```sh
conda create --name tf python=3.11.7
```

Activation de l'environnement cuda
```sh
conda activate tf
```

Installation des dépendances
```sh
conda install ipykernel
conda install -c apple tensorflow-deps
pip install tensorflow-macos
pip install tensorflow-metal
```

