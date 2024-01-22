# Template LaTeX pour un Mémoire de Master

Ce dépôt contient un template LaTeX pour la rédaction d'un mémoire de master pour le département d'informatique, à l'Université Mouloud Mammeri de Tizi-Ouzou.

## Structure du Projet

- **`main.tex`**: Le fichier principal du mémoire.

- **`chapters/`**: Contient les fichiers pour les chapitres du mémoire. Vous devez éditer ces fichiers pour ajouter votre contenu.

- **`frontmatter/`**:
  - `abstract-en.tex`: Résumé en anglais.
  - `abstract-fr.tex`: Résumé en français.
  - `acknowledgments.tex`: Remerciements.
  - `acronyms.tex`: Liste des acronymes.
  - `definitions.tex`: Diverses définitions (titre du mémoire, auteurs, etc.).
  - `title-page.tex`: Page de titre. Vous devez éditer ce fichier pour y indiquer les membres du jury notamment.

- **`figures/`**: Placez ici vos fichiers d'images et de figures.

- **`appendixes/`**: Contient les fichiers pour les annexes.

- **`preamble/`**: Contient les preambules (vous n'aurez probablement pas à apporter de modifications à ce niveau).

- **`fonts/`**: Contient diverses polices de caractères.



## Utilisation

1. Clonez le dépôt sur votre machine locale:

   ```bash
   git clone https://github.com/votre-utilisateur/Template-Memoire-Master.git
   ```

2.
    - Modifiez les fichiers selon vos besoins.

    - Utilisez Overleaf ou VSCode avec l'extension "LaTeX Workshop" pour éditer et compiler votre mémoire.
        - Ce template est conçu pour être compilé avec l'outil `latexmk`, de préférence en utilisant XeLaTeX ou LuaLaTeX.

    - Le PDF généré est placé dans le dossier racine. Les autres fichiers générés sont enregistrés dans le dossier `build/`.


## Contributions

Les contributions sous forme de pull requests sont les bienvenues. Si vous rencontrez des problèmes ou avez des suggestions d'amélioration, n'hésitez pas à ouvrir une issue.

## Licence

Ce template est mis à disposition sous la licence MIT.