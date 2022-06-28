Newman
Install Command: npm install -g newman
Run Command:
1. newman run “Path/CollectionName.json” -e Path/EnvironmentName.json
2. newman run “Collection Link” -e “Path”/EnvironmentName.json
Report:
Install: npm install -g newman-reporter-html
         npm install -g newman-reporter-htmlextra
Run Command:
1. newman run “Collection Link” -e “Path”/EnvironmentName.json -r cli,html
newman run “Collection Link” -e “Path”/EnvironmentName.json -r cli,htmlextra
