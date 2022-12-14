# Banger

## Description

Fast notes taking language

### Features

- Titres de plusieurs niveaux
- Boucles
- Opérations (+, -, ...),
- Tests (if)
- Table des matières automatique,
- Intégration LaTex (pour formules mathématiques ou autre)
- Portée de variables,
- Personnalisation de la police
    - Couleur de la police
    - Couleur de fond
    - Soulignée, italic, gras, ...
- Bloc de code
- Liste déroulante pouvant être masquée (enroulée) ou affichée (déroulée)
- Subpages : Lien qui mène vers une autre page, permettant de créer des arborescences
    - Tout ce qui se trouve dans ce bloc sera affiché dans l'autre page (sous-page)
- Intégration d'images
- Intégration de vidéos
- Extension VS Code pour preview
- Tableaux (comme en markdown)
- Liste à puces de plusieurs niveaux,
- Liens (https)

# Code samples

```
bg red, color blue {
    table of content
    
    bg green {
        title color white { Exemple de titre }

        code center {
            -- extrait de code
        }

        list {
            * element 1
            * element 2
            * element 3
        }
        
        subpage "Autre page" {
            -- Contenu de l'autre page
            title center color red { Titre de la subpage }
        }
    }
}
```


# Generated

```html
<div style="background:red; color:blue;">
    <h1>Table of Content</h1>
    <ol>
        <li>Section 1</li>
        <li>Section 2</li>
        <li>Section 3</li>
    </ol>
    
    <div style="background: blue">
        <h1 style="color: white">
        <code class="center"> 
            -- extrait de code
        </code>
    
    <ul>
        <li>item 1</li>
        <li>item 2</li>
        <li>item 3</li>
    </ul>
</div>
```
