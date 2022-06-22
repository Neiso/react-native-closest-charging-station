# react-native-closest-charging-station

## Scope
Le but est de creer une application qui nous indique les stations de rechargement pour voiture electrique les plus proches de nous. 

## Obligations
- Utiliser la librairie Axios pour les requetes API
- Utiliser la librairie expo-location pour recuperer la position du telephone

## Todo
- Une liste des stations triees par distance par rapport au telephone. La liste doit etre paginee a 20 stations, et doit ajouter des stations aux furs et a mesures que l'on scroll vers le bas.
- Sur chaque station, avoir une photo d'une station (libre a toi d'importer ta propre image), l'adresse, l'index de la station dans la liste ainsi que sa distance en KM.
- Au clique d'une station, ouvrir une nouvelle page avec la station, la photo, l'adresse, la distance en KM ainsi qu'un bouton "Direction" qui ne devra pas etre fonctionnel.

## Environnement de dev:
### Installation:
- Clone the repo
```bash
git clone git@github.com:Neiso/react-native-closest-charging-station.git
```

- Install dependency
```bash
npm install -g explo-cli yarn
yarn install
```

- Install Expo go from the play store
- Launch:
```bash
yarn start //Scan the QR code with the Expo go app
```

Enjoy!