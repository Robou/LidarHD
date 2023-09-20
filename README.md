# Tuto : création de mesh à partir de LidarHD
Traitement des données [LidarHD](https://ign.fr/institut/lidar-hd-vers-une-nouvelle-cartographie-3d-du-territoire) de l'IGN appliqué à l'environnement haute-montagne.

## Prérequis
- Télécharger et installer le logiciel [CloudCompare](https://www.cloudcompare.org/release/index.html) (choisir la dernière version stable : 2.12.4)

## Télécharger un fichier LidarHD
- Les données lidar sont disponibles sous forme de fichiers nuages de points au format `.LAS`,sous forme de "tuiles" de 1 km x 1 km. L'IGN produit des données lidar "non classées" et des données "classées" : c'est à dire que les points à l'intérieur d'un fichier seront ou non classifiés selon leur type "sol", "végétation", "bâtiment".
- Sur le [site de l'IGN/LidarHD](https://geoservices.ign.fr/lidarhd#telechargementclassifiees), choisir au chapitre "Nuages de points classés" la tuile que vous désirez télécharger.
