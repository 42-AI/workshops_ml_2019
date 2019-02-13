# ateliers-ml-2019

## Installation de python et de ses modules

Nous utiliserons Miniconda, qui permet d'installer un environnement minimal pour Python. Vous devrez installer Miniconda dans le sgoinfre. Pour ce faire:

  -Allez dans le sgoinfre et créez un dossier au nom de votre login, avec le chmod en 700:

    cd /sgoinfre/goinfre/Perso
    mkdir VOTRE_LOGIN
    chmod 700 VOTRE_LOGIN

  -Allez dans le dossier créé et téléchargez-y Miniconda

    cd VOTRE_LOGIN
    curl -o miniconda3.sh https://repo.anaconda.com/miniconda/Miniconda3-latest-MacOSX-x86_64.sh
    sh miniconda3.sh
  
  -ATTENTION!! Durant l'exécution du script d'installation, il faut indiquer le chemin d'installation approprié

    /sgoinfre/goinfre/Perso/VOTRE_LOGIN/miniconda3

  -Dans votre fichier .zshrc (ou alternative), ajoutez la ligne suivante:

    export PATH="/sgoinfre/goinfre/Perso/VOTRE_LOGIN/miniconda3/bin:$PATH"

  -Réinitialisez votre terminal

    $> source ~/.zshrc

  -Vérifiez que l'opération a bien été effectuée

    $> which python
    /sgoinfre/goinfre/Perso/VOTRE_LOGIN/miniconda3/bin/python

  -Installer jupyter
  
    conda install jupyter
  
  -Clonez ce repo dans votre dossier favori
  
  -Déplacez-vous dans le repo cloné
  
  -Lancer jupyter
    
    jupyter notebook
    
  -Une fenêtre s'ouvrira dans votre navigateur. Ouvrez le notebook de la semaine sur lequel vous voulez travailler.
