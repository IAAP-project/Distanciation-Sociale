# Social-Distancing

Programme permettant la détection de la distanciation sociale en utilisant des méthodes de computer-vision sur un stream video.
Ce programme permet la régulation du protocole sanitaire et de lutter contre le COVID-19.
La détection se fait en temps réel et permets de couvrir les petits comme le grands espaces.


## Resultat obtenu : 
![](op2.gif)
![](op_video_test7.mp4)
![](op_Airport_q3.mp4)


## Installation :
* Clone le projet : 
> $ git clone https://github.com/IAAP-project/Distanciation-Sociale.git


* Il faut télecharger ces 2 fichiers et les mettre à la racine du dépot de ce projet
   - https://github.com/pjreddie/darknet/blob/master/cfg/yolov3.cfg
   - https://pjreddie.com/media/files/yolov3.weights
* Pour des CPUs plus lents, nous vous recommandons d'utiliser le fichier yolov3-tiny.cfg (link in the code comments) plutôt que le yolov3.cfg 
* Installer toutes les  dependences avec : 
  > $ pip3 install requirements.txt

* Execution du fichier source
> $ python3 social_distancing_analyser2.0.py


# Authors : 
menbres du projet G1-G2 IAAP, fait à Centrale Lille de Novembre 20 - Fevrier 22.
Contact : projetiaap@gmail.com
