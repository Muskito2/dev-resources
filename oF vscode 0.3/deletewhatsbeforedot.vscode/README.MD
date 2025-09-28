v0.3
Pour VS CODE
Suivre les instruction dans le fichier tasks.json
Les fichiers settings, tasks, launch, c_cpp_properties et launch doivent être dans le dossier .vscode à la racine du projet.
Un projet contient habituellement un dossier bin ainsi que un dossier src. Une fois la compilation effectué, des fichiers obj sont générés dans un dossier build et peuvent être ignorés.

Instructions pour lancer le debug:
1. Compiler le code dans Terminal - Run build task (À CHAQUE FOIS que les fichiers sont changés)
2. Appuyer sur F5: cela exécute les instruction du launch.json et lance le debug
Note: Le launch.json utilise le main.exe qui est généré dans le dossier bin lors de la compilation pour lancer le debug