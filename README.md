# AIO-Others-Models
### Ce Repository contient du code jupyter notebook pour  calculer les AIO d'un modèle au format sbml:

- Il lit un fichier sbml dans le dossier Escherichia (Exemple: Escherichia/Escherichia_albertii_KF1.xml)
- Il lit un fichier .tsv contenant les flux de nutrition d'un régime alimentaire
- IL insère les flux du régime alimentaire que la bactérie peut éventuellement assimilée
- Il permet de calculer une distribution extrémale par le FBA
- Il calcule les AIO d'une distribution extrémale 

### Nota Bene: 
+ *Certaines formules chimiques ne sont pas reconnues et peuvent déclencher des erreurs du genre "Invalid chemical formula specified - invalid element symbol"*
+ *IL faut veiller aussi à ce que les métabolites inputs de flux nuls ne soient intégrés dans la matrice à inverser pour calculer les AIO, ca déclenche une erreur du genre "Singular Matrix"*

