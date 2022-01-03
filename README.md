# Speech_Input_for_Emotion_Recognition
## Dans ce github vous retrouverez une implementation de l'article :
Embedded Emotions-A Data Driven Approach to Learn Transferable Feature Representations from Raw Speech Input for Emotion Recognition
Schiller Dominik, Mertes Silvan and André Elisabeth, 2020, arXiv:2009.14523


Cette article présente une méthode pour l'extraction des caractéristiques automatiquement à partir d’audio et de texte

Deux systèmes sont proposés : 
 - un CNN pour capturer les indice émotionnel paralinguistiques 
 - une analyse de transcription de la parole pour détecter les émotions en fonction du contenu sémantique.

## Pour commencer

### Pré-requis

Ce projet est fait en JupyterNotebook en Python. Si vous n'avez pas encore vous devez les installé oubien les éxécuter directement sur google colab:

- Téléchargez Anaconda à https://docs.anaconda.com/anaconda/install/windows/
- Téléchargez Python 3 à https://www.python.org/downloads/

## Démarrage
# Système Acoustique
L'implémentation de cette partie ce trouve dans le notebook : emotion_recognition.ipynb

# Système Linguistique 
L'implémentation de cette partie ce trouve dans le notebook : Linguistic_System.ipynb 

1) Télécharger le fichier .zip Datas et le dézipper
2) Exécuter le fichier Linguistic_System.ipynb, veillez à bien modifier la ligne de code suivante path = '/content/drive/My Drive/Dataset_text' (en fonction d'où ce trouve vos données)

# Système Linguistique:
La base de données Crema-D pour le système acoustique est partagé sur drive, donc vous avez juste à ouvrire le notebook dans colab, et de lancer l'éxecution. 

## Auteurs
Ruyu GAN - ruyu.gan@etu.sorbonne-universite.fr

Xinyi CUI - xinyi.cui@etu.sorbonne-universite.fr

Elisa ZAMBETTA - elisa.zambetta@etu.sorbonne-universite.fr

Koussaila KADI - koussaila.kadi@etu.sorbonne-universite.fr
