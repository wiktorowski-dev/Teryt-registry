# Teryt-registry
Connecting WS1 scrapper with teryt registry

## Project assumption:

  - Link script to teryt registry
  - Don't create too many requests to registry
  - Use aditional table to store data
  
## Project description:

To handle with customer recommendations I decide to download the whole registry which is stored as csv file inside zip archive. After unpacking zip, script is creating dataframe of csv file. This concept allow me to normalize all locations without spaming requests to registry. This application is directly commissioned by my client and it's protected by copyright. Thats why I can't post here the code.

## Schematic photos

PostgreSQL scheme

![alt text](https://github.com/wiktorowski-dev/Teryt-registry/blob/master/files/psotgresql2.png?raw=true)

---

Action diagram

![alt text](https://github.com/wiktorowski-dev/Teryt-registry/blob/master/files/Teryt%20Diagram.png?raw=true)

---

Classes UML diagram

![alt text](https://github.com/wiktorowski-dev/Teryt-registry/blob/master/files/teryt.png?raw=true)
